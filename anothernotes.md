# 📘 Notes of HTML — With Tags, Elements, and Attributes

## 🧠 What is HTML?

**HTML** stands for **HyperText Markup Language**.  
It acts as the **skeleton of any website**.  

Just like a skeleton gives shape to the human body, **HTML gives structure to a webpage**.  
With the help of **tags**, **elements**, and **attributes**, we can design and organize web content to make it more **user-friendly**.

---

## 🔖 Key Concepts

### 🏷️ What is a Tag?
A **tag** is a special keyword that tells the browser **how to display** content on a webpage.  
Example:
```html
<p>This is a paragraph.</p>
```

### 🧩 What is an Element?
An **element** is the **combination of a tag and its content**.  
Example:
```html
<h1>Welcome</h1>
```
Here, `<h1>` and `</h1>` are tags, and together with "Welcome", they form an element.

### ⚙️ What is an Attribute?
**Attributes** provide **additional information** about an HTML element.  
They are always written **inside the opening tag**.  
Example:
```html
<img src="photo.jpg" alt="Wedding Hall Image">
```

### 🧱 What is a Semantic Tag?
**Semantic tags** are tags that have **clear meaning** both to the developer and the browser.  
Examples: `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>` etc.

---

## 🧾 HTML Boilerplate

Below is a basic HTML structure (boilerplate):

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Website Title</title>
</head>
<body>
  <h1>Welcome to My Website!</h1>
  <p>This is my first web page.</p>
</body>
</html>
```

### 📄 Explanation
- **<!DOCTYPE html>** → Defines the document type as HTML5.  
- **<html lang="en">** → Specifies the language of the document (English).  
- **<head>** → Contains metadata, title, and linked files.  
- **<meta charset="UTF-8">** → Defines character encoding (UTF-8 supports most characters and symbols).  
- **<meta name="viewport">** → Ensures the page fits properly on all screen sizes.  
- **<title>** → Sets the title shown in the browser tab.  
- **<body>** → Contains all visible content of the webpage.

---

## 🏗️ Commonly Used HTML Tags

| Tag | Description | Example |
|-----|--------------|----------|
| `<h1>`–`<h6>` | Headings (h1 = most important, h6 = least) | `<h1>Welcome</h1>` |
| `<p>` | Paragraph | `<p>This is a paragraph.</p>` |
| `<br>` | Line break | `<br>` |
| `<pre>` | Preformatted text (keeps spaces & newlines) | `<pre>This is pre text</pre>` |
| `<b>` | Bold text (styling only) | `<b>Bold</b>` |
| `<i>` | Italic text | `<i>Italic</i>` |
| `<strong>` | Important text (semantic) | `<strong>Important!</strong>` |
| `<mark>` | Highlight text | `<mark>Highlighted</mark>` |
| `<small>` | Small text | `<small>Note</small>` |
| `<del>` | Deleted text (strike-through) | `<del>₹1000</del>` |
| `<sup>` | Superscript (power) | `x<sup>2</sup>` |
| `<sub>` | Subscript (base) | `H<sub>2</sub>O` |
| `<a href="">` | Hyperlink | `<a href="https://example.com">Visit</a>` |
| `<img src="" alt="">` | Image | `<img src="image.jpg" alt="Hall Image">` |
| `<link rel="stylesheet" href="">` | Links CSS file | `<link rel="stylesheet" href="style.css">` |
| `<ol>` | Ordered list | `<ol><li>Item</li></ol>` |
| `<ul>` | Unordered list | `<ul><li>Item</li></ul>` |
| `<table>` | Table container | `<table>...</table>` |
| `<tr>` | Table row | `<tr>...</tr>` |
| `<th>` | Table header | `<th>Heading</th>` |
| `<td>` | Table data | `<td>Data</td>` |
| `<form>` | Creates a form | `<form action="">...</form>` |
| `<button>` | Clickable button | `<button>Submit</button>` |
| `<iframe>` | Embed video or another page | `<iframe src="video.html"></iframe>` |
| `<span>` | Inline text styling | `<span style="color:red;">Red Text</span>` |
| `<!-- comment -->` | Developer comments | `<!-- This is a comment -->` |

---

## 🧍 Example: Simple Marriage Hall Webpage

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rajhutsutra Palace</title>
</head>
<body>
  <h1>Welcome to Rajhutsutra Palace</h1>
  <p>We provide luxury wedding hall facilities with decoration, catering, and more!</p>

  <img src="hall.jpg" alt="Wedding Hall Image" width="400">

  <h2>Facilities:</h2>
  <ul>
    <li>AC Banquet Hall</li>
    <li>Parking Facility</li>
    <li>Catering Services</li>
    <li>Photography & Decoration</li>
  </ul>

  <h2>Contact Us</h2>
  <p>Email: info@rajhutsutrapalace.com</p>
  <p>Phone: +91 9876543210</p>

  <iframe src="https://www.google.com/maps" frameborder="0"></iframe>
</body>
</html>
```

---

## 💡 Summary

| Concept | Description |
|----------|--------------|
| **HTML** | Structure of a webpage |
| **Tag** | Tells browser how to display content |
| **Element** | Tag + Content |
| **Attribute** | Extra information in tags |
| **Semantic Tag** | Tags with meaningful names (header, footer, nav, etc.) |

---

✅ **Tip:** Always use proper indentation and closing tags to avoid webpage errors.