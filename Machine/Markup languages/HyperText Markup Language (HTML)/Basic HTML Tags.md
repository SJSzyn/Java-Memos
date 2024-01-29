## Overview

- **Purpose**: HTML tags are the building blocks of HTML pages. They define and structure the content on web pages.
- **Usage**: Each HTML document starts with a `<!DOCTYPE html>` declaration, followed by a structured hierarchy of tags.
## Essential HTML Tags

### `<!DOCTYPE html>`

- **Purpose**: Declares the document type and HTML version.
- **Example**:
    
```html
<!DOCTYPE html>
```
### `<html>`

- **Purpose**: The root element that encloses all the content on the web page.
- **Example**:
    
```html
<html> 
	<!-- Content goes here --> 
</html>
```
### `<head>`

- **Purpose**: Contains meta-information about the HTML document like title, scripts, styles, etc.
- **Example**:
    
```html
<head>   
	<title>Page Title</title> 
</head>
```
### `<title>`

- **Purpose**: Specifies the title of the web page (shown in the browser's title bar or in the page's tab).
- **Example**:
    
```html
<title>My First HTML Page</title>
```
### `<body>`

- **Purpose**: Contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.
- **Example**:
    
```html
<body> 
	<!-- Page content --> 
</body>
```
### `<h1>` to `<h6>`

- **Purpose**: Header tags used to define headings, with `<h1>` being the most important and `<h6>` the least.
- **Example**:
    
```html
<h1>Main Title</h1> 
<h2>Subheading</h2>
```
### `<p>`

- **Purpose**: Defines a paragraph.
- **Example**:
    
```html
<p>This is a paragraph of text.</p>
```
### `<a>`

- **Purpose**: Defines a hyperlink, which is used to link from one page to another.
- **Attributes**: `href` (URL of the link), `target` (specifies where to open the linked document).
- **Example**:
    
```html
<a href="https://example.com">Visit Example.com</a>
```
### `<img>`

- **Purpose**: Embeds an image in an HTML page.
- **Attributes**: `src` (source of the image), `alt` (alternative text for the image).
- **Example**:
    
```html
<img src="image.jpg" alt="Descriptive text">
```
### `<ul>`, `<ol>`, `<li>`

- **Purpose**: `<ul>` creates an unordered list, `<ol>` creates an ordered list, and `<li>` defines a list item.
- **Example**:
    
```html
<ul>   
	<li>Item 1</li>   
	<li>Item 2</li> 
</ul>
```
### `<div>`

- **Purpose**: A container used to group together and style sections of the document with CSS.
- **Example**:
    
```html
<div>   
	<!-- Content --> 
</div>
```
### `<span>`

- **Purpose**: Used to group inline-elements in a document.
- **Example**:
    
```html
<span>Text</span>
```
### `<br>`

- **Purpose**: Inserts a line break.
- **Example**:
    
```html
<p>Hello,<br>World!</p>
```
### `<hr>`

- **Purpose**: Defines a thematic break in an HTML page (e.g., a shift of topic).
- **Example**:
    
```html
<hr>
```
## Resources