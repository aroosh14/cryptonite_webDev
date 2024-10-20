# Paragraphs

If you directly insert text into the body without wrapping it in a tag, the browser will display it in a single line, rather than as a distinct paragraph.

To format text as a paragraph, use the `<p>` tag, like this:

```html
<p>Hello World</p>
```

# Headings

HTML provides six levels of headings, from `<h1>` to `<h6>`, where `<h1>` represents the largest and most important heading, and `<h6>` is the smallest.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

# Text Formatting

## Bold Text
To make text bold, use the `<strong>` tag.

```html
<strong>This text will be bold.</strong>
```

## Italics
For italicized or emphasized text, the `<em>` tag is used.

```html
<em>This text will be italicized.</em>
```

# Nesting Elements and Indentation

When one element is placed inside another, it forms a "parent-child" relationship. The outer element is the parent, and the inner one is the child.

### Example:

```html
<html>
  <head></head>
  <body>
    <p>This is a nested paragraph.</p>
  </body>
</html>
```

In this example, the `<body>` is the parent, and the `<p>` element is the child.

# Comments

Comments are a way to leave notes in your HTML code, which won’t be visible on the webpage. They are useful for making your code more understandable to others (or yourself in the future).

```html
<!-- This is a comment in HTML -->
```

# Lists

HTML supports two main types of lists: ordered and unordered.

### Unordered List
An unordered list is used when the order of items isn’t important. It’s created using the `<ul>` tag, with each list item wrapped in `<li>`.

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

### Ordered List
When the order matters, such as for step-by-step instructions, use an ordered list. This is created with the `<ol>` tag, and each item is also wrapped in `<li>`.

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

# Code Example

Here’s an example of a simple HTML structure incorporating headings, paragraphs, lists, and formatting:

```html
<html>
  <head>
    <title>Sample Page</title>
  </head>
  <body>
    <!-- Main Title -->
    <h1>Welcome to the Demo</h1>

    <!-- Subheading -->
    <h2>Overview</h2>

    <!-- Paragraph with italics and bold text -->
    <p><em>Welcome</em> to our sample HTML document. Here is some <strong>important</strong> text for you.</p>

    <!-- A list of items -->
    <ul>
      <li>First item in unordered list</li>
      <li>Second item in unordered list</li>
      <li>Third item in unordered list</li>
    </ul>

    <!-- An ordered list -->
    <ol>
      <li>First ordered item</li>
      <li>Second ordered item</li>
      <li>Third ordered item</li>
    </ol>
  </body>
</html>
```

--- 
