# HTML-cheatsheet
### Basic HTML 5 Tags and how to use it.

### Basic HTML 5 Structure
```html
<!DOCTYPE html>
  <html>
    <head>
      #This contain title tags, meta-tags, inline-style, css-link, favicon.
    </head>
    <body>
      #This contain body elements and will be display on your browser windows
    </body>
  </html>
```

### Starter code for html template
```html
<!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta name="description" content="description of this page">
      <meta name="keywords" content="keywords">
      <meta name="author" content="name">
      <link href="style.css" rel="stylesheet" type="text/css">
      <style>
      </style>
    </head>
    <body>
    </body>
</html>
```
Tag | Description
------------ | -------------
title | Show page title in tab of browser
meta charset | Specifies the character encoding for the HTML document
meta description | Use to describe your webpage
meta keywords | Define keywords for search engines
meta author | Define the author of the page
link | Use to link html with css
style | Use css inside html (internal-css)

### Heading
```
<body>
  <h1>This is H1 tag</h1>
  <h2>This is H2 tag</h2>
  <h3>This is H3 tag</h3>
  <h4>This is H4 tag</h4>
  <h5>This is H5 tag</h5>
  <h6>This is H6 tag</h6>
</body>
```
This is the output:
# This is H1 tag
## This is H2 tag
### This is H3 tag
#### This is H4 tag
##### This is H5 tag
###### This is H6 tag

### Paragraph + br tag
```
<body>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
     ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in     
     reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.<br>Excepteur sint occaecat cupidatat non proident,
     sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</body>
```
This is the output:

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad 
minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in 
reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
Tag | Description
------------ | -------------
<p></p> | To defines a paragraph
<br> | To add brakeline / move text to new line.

### Text Formatting
```
<body>
  This is sample of <strong>text</strong>.
  <br />
  This is sample of <em>text</em>.
  <br />
  This is sample of <mark>text</mark>.
  <br />
  This is sample of <ins>text</ins>.
  <br />
  This is sample of <del>text</del>.
  <br />
  This is sample of <sup>text</sup>.
  <br />
  This is sample of <sub>text</sub>.
</body>
```
This is the output:
<p align="center">
  <img width="300" height="300" src="https://github.com/WiLLiaM-noD/HTML-cheatsheet/blob/master/Screenshot_1.png">
</p>
![Text Formatting output](https://github.com/WiLLiaM-noD/HTML-cheatsheet/blob/master/Screenshot_1.png)
