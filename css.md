# What is CSS?
- CSS = cascading style sheets
- HTML code will look sipmle based on the browser's default display settings
- a document is a text file that contains markup language (content)
- presenting a document (i.e. web browser) determines how viewers will see the documents displayed
## CSS Syntax
- CSS is rule based
    - you call out groups and apply your chosen styles using rules
- starts with a selector (what do you want to change)
- then curly braces "{}"
    - inside are declarations that have a property and value, separated by a colon
        - there should not be a space between the property and value
## CSS Modules
- code written should be digestable across browsers
# How To Add CSS
- three different ways:
    1. external CSS
        - add a CSS file and link it in your HTML file
    2. internal CSS
        - added via a style element inside the head section
    3. inline CSS
        - added via a style attribute within the HTML
- the most recent (last) selector and style will be used (if an element has properties defined twice, it will follow the last one)
## Cascading Order
- ordered by the following priority:
    1. inline style (inside an HTML element)
    2. external and internal style sheets (in the head section)
    3. browser default
# CSS Color Property
- can choose color 
- initial will reset to default value
- inherit will pull color from parent element
- can set color using the following values:
    - HEX (#)
    - RGB (rgb)
    - RGBA (rgba)
    - HSL (hsl)
    - HSLA (hsla)