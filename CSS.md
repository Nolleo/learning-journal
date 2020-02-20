[Home](README.md) 
1. Other Notes
	1. [Markdown](markdown.md)
	1. [Text Editor](TEXTEDITOR.md)
	1. [Terminal](TERMINAL.md)
	1. [Git Guide - (_made in VS Code_)](VScode.md)
	1. [HTML](HTML.md)
	1. [CSS](CDD.md)
	1. [Git Guide - (1st VS made notes)](GitGuide-VS.md)
	1. [How Computers Work](how_computers_work.md)
	1. [JaveScript Notes](JavaScript.md)
	1. [JavaScript Programming](JavaScript-Programming.md)
	
# CSS

## Cascading Style Sheets
- top to bottom 
- CLASS - multiple tags - .name
- ID - one tag - #name

### How it works
- Lives in the head as either:
    - a href to another doc - named either "CSS" or "style"
    - or an included rule in the HEAD.
- Elements
    - Block level - appear to start on new line
    ```
    <h1>-<h6>, <p> and <div>
    ```
    - Inline - flow within text, not on a new line
    ```
    <b>, <i>,<img>, <em> and <span>
    ```
    - Boxes
        - Width
        - Height
        - Borders
            - color
            - width
            - style
        - background
            - color
            - images
        - position in the browser window
    - Text
        - typeface
        - size 
        - color
        - italic, bold, upercase, lowercase, etc.
    - Specific
        - lists
        - tables
        - forms


### Rules

- CSS associates rules with HTML elements. Made of __RULE SETS__:
    - selector (front)
        - indicate which element applied.
        - same rule can apply to more than one element - spearate with commas.
    - delcaration (within "{" and "}")
        - indicate how elements in selector should be styled.
        - split into 
            - property - before ":"
            - value - "space and before ";"
            - multiple selector elements effected are listed with commas
            - multiple delcarations separated by semi-colon.
EXAMPLE:
```
<!DOCTYPE html>
<html>
<head>
<title>Introducing CSS</title>
<link href="css/example.css" type="text/css"
rel="stylesheet" />
</head>
<body>
<h1>From Garden to Plate</h1>
<p>A <i>potager</i> is a French term for an
ornamental vegetable or kitchen garden ... </p>
<h2>What to Plant</h2>
<p>Plants are chosen as much for their functionality
as for their color and form ... </p>
</body>
</html>


body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}
```

### Related to HTML

Verify on multiple browser tools:
- BrowserCam.com
- BrowserLab.Adobe.com
- BrowserShots.org
- CrossBrowserTesting.com

Browser Bug tools:
- PositionIsEverything.net
- QuirksMode.org

### COLOR
__Value options__
- RGB - numerical values per red, green, blue
- HEX - hexidecimal conversions of the RGB values
- Names - limited (147) color names
- HSLA
    - Hue - 0-360
    - Saturation - 0-100
    - Lightness - 0-100
    - Alpha (opacity) 0-1.0

__Opacity__
Values between 0.0 - 1.0 - representing percentage
