### Report: Links and Images in HTML

---

### 1. **Creating Links**

#### **Anchor Elements (`<a>`)**
Links in HTML are created using the anchor element `<a>`. This tag wraps the text or element that will act as a clickable link. For example:

```html
<a href="https://www.example.com">Visit Example</a>
```

In this case, the text "Visit Example" becomes a clickable link that leads to the specified website.

#### **Key Attributes for Anchor Elements**
- **`href`**: Defines the URL or path the link points to.
- **`target`**: Specifies where to open the link. For example, `_blank` opens it in a new tab:
    ```html
    <a href="https://www.example.com" target="_blank">Open in new tab</a>
    ```
- **`rel`**: When using `target="_blank"`, it's good practice to include `rel="noopener noreferrer"` to improve security by preventing malicious activities like phishing.

---

### 2. **Types of Links**

#### **Absolute Links**
Absolute links direct users to an external page by using the full URL, including the protocol (`https://`), domain name, and path.

Example:
```html
<a href="https://www.theodinproject.com">The Odin Project</a>
```

#### **Relative Links**
Relative links point to other pages within the same website. These links only use the file path relative to the current page, without specifying the domain name.

Example:
```html
<a href="about.html">About Us</a>
```

If the file is in a different directory, the path must reflect this. For example:
```html
<a href="pages/about.html">About Us</a>
```

---

### 3. **Embedding Images in HTML**

#### **Image Elements (`<img>`)**
Images are added to web pages using the `<img>` tag. This is a self-closing or void element, meaning it doesn’t require a closing tag. 

Example:
```html
<img src="https://www.example.com/image.jpg" alt="A description of the image">
```

#### **Attributes of the `<img>` Element**
- **`src`**: Specifies the image file's URL or path. It can be an absolute URL or a relative file path.
- **`alt`**: Provides alternative text describing the image. This text is displayed if the image fails to load and is used by screen readers to aid visually impaired users.

#### **Using Relative Paths for Images**
For images stored locally, a relative path should be used. The path depends on the image's location relative to the HTML file.

Example:
```html
<img src="./images/photo.jpg" alt="Description of the image">
```

In this case, the image is in the `images` directory, located in the same folder as the HTML file.

---

### 4. **Navigating Directories**
When organizing web files, images and HTML files are often in different directories. To access an image from another directory, use `../` to move up one level in the folder structure.

Example:
```html
<img src="../images/photo.jpg" alt="Description of the image">
```

This code moves up one directory to access the `images` folder and displays the image `photo.jpg`.

---

### 5. **Sizing Images**
While not required, it's a good idea to specify an image's `width` and `height` to help the browser lay out the page correctly.

Example:
```html
<img src="image.jpg" alt="Image description" width="300" height="200">
```

This ensures that the image takes up a defined space on the page and prevents content from shifting as the image loads.

---
