 # html-learning
A repository that houses my HTML studies.

## What is HTML?
HTML stands for HyperText Markup Language. It's used to structure and display content on the web. It consists of elements (tags) that define different parts of a webpage.

## HTML Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title> <!-- Page Title -->
  </head>
  <body>
    <h1>Welcome to My Website!</h1> <!-- Main heading -->
    <p>This is a paragraph.</p> <!-- Paragraph -->
  </body>
</html>
```

## The output of the example
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title> <!-- Page Title -->
  </head>
  <body>
    <h1>Welcome to My Website!</h1> <!-- Main heading -->
    <p>This is a paragraph.</p> <!-- Paragraph -->
  </body>
</html>

### Tags and Elements
Tags are enclosed in < > brackets, e.g., <p>.
Most tags come in pairs: an opening <tag> and a closing </tag>.
Self-closing tags: <img />, <br />, <hr />.

## Common HTML Elements

### 1 Headings
Used for titles. There are six levels, <h1> to <h6>, with <h1> being the largest.

```html
<h1>Main Title</h1>
<h2>Subheading</h2>
```
### 2 Paragraphs
```html
Copy code
<p>This is a paragraph.</p>
```
### 3 Links
Create hyperlinks with the <a> tag.

```html
Copy code
<a href="https://example.com">Visit Example</a>
```

### 4 Imagens
Embed images using the <img> tag.

```html
<img src="image.jpg" alt="Description of the image" />
```
### 5 Lists
Ordered List (Numbered)
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```
Unordered List (Bullets)
```html
<ul>
  <li>First item</li>
  <li>Second item</li>
</ul>
```
### 6 Tables
```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```
## Attributes
### Add information to elements

- **href**: URL of the link
- **target**: "_blank": Opens the link in a new tab

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```
## Forms
Used for user input
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <button type="submit">Submit</button>
</form>
```

## Semantic Tags
For better structure:
- **header**: Top section or navigation
- **nav**: Navigation links
- **section**: Groups content
- **article**: Standalone content
- **footer**: Bottom section

## Styling and Scripts
- **Inline CSS**
```html
<p style="color: blue;">This is a blue paragraph.</p>
```

- **External CSS**
```html
<link rel="stylesheet" href="styles.css" />
```

- **JavaScript**
```html
<script>
  alert("Hello, world!");
</script>
```


<script>
  alert("Hello, world!");
</script>
