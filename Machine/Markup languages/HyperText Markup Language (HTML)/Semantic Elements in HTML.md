
## Overview

- **Definition**: Semantic elements clearly describe their meaning in a human- and machine-readable way.
- **Purpose**: They provide information about the type of content they contain, enhancing accessibility and improving SEO.
- **Examples**: `<article>`, `<section>`, `<nav>`, `<header>`, `<footer>`

## Semantic vs Non-Semantic Elements

- **Semantic Elements**: `<form>`, `<table>`, `<article>`...
    - Clearly define their content.
- **Non-Semantic Elements**: `<div>`, `<span>`...
    - Do not define what type of content they contain.

## Semantic Elements

### `<header>`

- **Purpose**: Represents introductory content, typically a group of introductory or navigational aids.
- **Example Usage**:
    
```html
<header>   
	<h1>Page Title</h1>   
	<nav>...</nav> 
</header>
```

### `<nav>`

- **Purpose**: Used for navigation links.
- **Example Usage**:
    
```html
<nav>   
	<ul>     
		<li><a href="/">Home</a></li>     
		<li><a href="/about">About</a></li>
	</ul> 
</nav>
```

### `<article>`

- **Purpose**: Contains content that is independently distributable or reusable, e.g., in syndication.
- **Example Usage**:
    
```html
<article>   
	<h2>Article Title</h2>   
	<p>Article content...</p> 
</article>
```

### `<section>`

- **Purpose**: Represents a standalone section of content.
- **Example Usage**:
    
```html
<section>   
	<h2>Section Heading</h2>   
	<p>Content...</p> 
</section>
```

### `<footer>`

- **Purpose**: Represents the footer of a document or section, typically containing authorship, copyright information, etc.
- **Example Usage**:
    
```html
<footer>   
	<p>Copyright © 2024</p> 
</footer>
```

## Accessibility Benefits

- **Navigation**: Screen readers can use semantic elements to navigate and interpret content.
- **SEO**: Search engines use semantic markup to understand and rank pages better.

## Resources

- https://developer.mozilla.org/en-US/docs/Glossary/Semantics
- https://www.semrush.com/blog/semantic-html5-guide/
- https://www.w3schools.com/html/html5_semantic_elements.asp