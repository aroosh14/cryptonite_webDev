# HTML Boilerplate

HTML documents have a standard structure, often referred to as a "boilerplate," which forms the foundation of every webpage. This guide will take you through the essential components of an HTML boilerplate and show you how they fit together.

### Lesson Overview

In this section, you'll learn the following:

- How to write the basic boilerplate for an HTML document.
- How to open an HTML file in your browser.

## Creating an HTML File

To start, you'll need to create an HTML file to work with. First, create a new folder on your computer and name it `html-boilerplate`. Inside that folder, create a new file and name it `index.html`.

The `.html` extension is what lets the computer know that the file contains HTML code. Naming this file `index.html` is crucial because most web servers look for a file called `index.html` by default when loading a site.

## The DOCTYPE Declaration

Every HTML document begins with a `DOCTYPE` declaration, which tells the browser which version of HTML to use. For HTML5 (the latest version), the declaration looks like this:

```html
<!DOCTYPE html>
```

Older versions of HTML have more complex declarations, but we’ll always use this simplified version for HTML5.

## The `<html>` Element

Following the `DOCTYPE`, the next element we add is the `<html>` element. This is the root element for the entire HTML document, meaning that all other elements will be placed inside it.

```html
<!DOCTYPE html>
<html lang="en">
</html>
```

Notice the `lang="en"` attribute here. This specifies the language of the content within the HTML document, which helps improve accessibility for users, especially for assistive technologies like screen readers.

## The `<head>` Element

Next, we include the `<head>` element. This section is where important meta-information about the page is placed, such as character encoding, title, and other metadata. It doesn't contain visible content for users.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>
</html>
```

### Meta Element

The `<meta charset="UTF-8">` tag specifies the character encoding for the document, ensuring that special characters and symbols from various languages display correctly.

### Title Element

The `<title>` element sets the title of the webpage, which appears on the browser tab. For example, if you look at the tab of your browser now, you'll see the title of this page.

```html
<title>My First Webpage</title>
```

## The `<body>` Element

Finally, the content displayed on the webpage goes inside the `<body>` element. This is where all your text, images, lists, links, and other content will be placed. 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>
  <body>
  </body>
</html>
```

## Viewing Your HTML File in the Browser

Once your `index.html` file is complete, you can view it in a browser. There are several ways to do this:

1. Drag and drop the HTML file into your browser’s address bar.
2. Find the file in your file system and double-click it, which will open it in your default browser.
3. Use the terminal:
   - **Ubuntu:** `google-chrome index.html`
   - **macOS:** `open ./index.html`
   - **Windows (WSL):** `explorer.exe index.html` (opens the file in the default browser).

At this point, you won't see anything in the browser because the `<body>` is still empty.

## Adding Content to the `<body>`

Let’s add a heading to the `<body>` element, save the file, and reload it in your browser.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

Now, when you refresh the page, you should see the heading “Hello, World!” displayed.
