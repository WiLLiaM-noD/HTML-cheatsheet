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
p | To defines a paragraph
br | To add brakeline / move text to new line.

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
  <img width="200" height="170" src="https://github.com/WiLLiaM-noD/HTML-cheatsheet/blob/master/Screenshot_1.png">
</p>

### HTML Links
```
<body>
  <a href="https://www.w3schools.com/html/" target="_blank">Visit our HTML tutorial</a>
</body>
```
Output:

<a href="https://www.w3schools.com/html/" target="_blank">Visit our HTML tutorial</a>

You can add some attribute to a tag
Attribute | Description
------------ | -------------
target | specifies where to open the linked document.
title | attribute specifies extra information about an element.

### Images
```
<body>
  <img src="https://images.unsplash.com/photo-1531804055935-76f44d7c3621ixlib=rb1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEyMDd9"
   alt="pic"
   width="200"
   height="300"/>
</body>
```
This is the output:
<p align="center">
  <img width="200" height="300" src="https://github.com/WiLLiaM-noD/HTML-cheatsheet/blob/master/Screenshot_2.png">
</p>

### Lists
```
<body>
  <p>Unordered</p>
  <ul>
    <li>Banana</li>
    <li>Orange</li>
    <li>Manggo</li>
  </ul>
  <p>Ordered</p>
  <ol>
    <li>HTML 5</li>
    <li>CSS</li>
    <li>Javascript</li>
  </ol>
</body>
```
The output will look like this

Unordered
* Banana
* ORange
* Manggo

Ordered
1. HTML 5
2. CSS
3. Javascript

Tag | Description
------------ | -------------
ul | display an unordered list 
ol | display an ordered list 
li | define each element inside unordered or ordered list

### Tables
```
<body>
    <table>
      <tr>
        <th>name</th>
        <th>address</th>
        <th>phone number</th>
      </tr>
      <tr>
        <td>John Doe</td>
        <td>London</td>
        <td>9210404120</td>
      </tr>
      <tr>
        <td>Sally John</td>
        <td>Brighton</td>
        <td>2319092844</td>
      </tr>
    </table>
  </body>
```
Output:

<p align="center">
  <img width="200" height="300" src="https://github.com/WiLLiaM-noD/HTML-cheatsheet/blob/master/Screenshot_3.png">
</p>
