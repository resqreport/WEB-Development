**HTML Cheatsheet** with the **most commonly used tags** and their explanations.  

---

## **📌 Basic Structure Tags**
| **Tag**  | **Description** |
|----------|---------------|
| `<!DOCTYPE html>` | Declares the document as HTML5. |
| `<html>` | The root of an HTML document. |
| `<head>` | Contains metadata (title, links, styles, scripts). |
| `<meta charset="UTF-8">` | Defines the character set (supports special characters). |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Makes the website responsive on mobile. |
| `<title>` | Sets the page title (shown in the browser tab). |
| `<body>` | Contains all visible content. |

---

## **📌 Text Formatting & Headings**
| **Tag** | **Description** |
|---------|---------------|
| `<h1> ... <h6>` | Headings (h1 is the largest, h6 is the smallest). |
| `<p>` | Defines a paragraph. |
| `<br>` | Line break (moves text to the next line). |
| `<hr>` | Horizontal line (divider). |
| `<b>` | **Bold text** (without meaning). |
| `<strong>` | **Important text (bold)**. |
| `<i>` | *Italic text* (without meaning). |
| `<em>` | *Emphasized text (italic)*. |
| `<u>` | Underlined text. |
| `<mark>` | Highlights text. |
| `<small>` | Displays smaller text. |
| `<del>` | ~Strikethrough text~. |

---

## **📌 Links & Navigation**
| **Tag** | **Description** |
|---------|---------------|
| `<a href="URL">` | Creates a hyperlink. |
| `target="_blank"` | Opens a link in a new tab. |
| `<nav>` | Defines a navigation section (for menus). |

---

## **📌 Lists (Ordered & Unordered)**
| **Tag** | **Description** |
|---------|---------------|
| `<ul>` | Creates an **unordered** list (bullets). |
| `<ol>` | Creates an **ordered** list (numbers). |
| `<li>` | Defines a **list item** inside `<ul>` or `<ol>`. |
| `<dl>` | Creates a **description list**. |
| `<dt>` | Defines a **term** in a description list. |
| `<dd>` | Defines the **description** of a term. |

**Example:**  
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

<ol>
    <li>First step</li>
    <li>Second step</li>
</ol>
```

---

## **📌 Images & Media**
| **Tag** | **Description** |
|---------|---------------|
| `<img src="image.jpg" alt="Description">` | Displays an image. |
| `alt="text"` | Alternative text (used if the image doesn’t load). |
| `width="100"` `height="100"` | Sets the size of an image. |
| `<figure>` | Groups an image and caption together. |
| `<figcaption>` | Defines a caption for an image. |
| `<audio controls>` | Adds an audio player. |
| `<video controls>` | Adds a video player. |

**Example:**  
```html
<img src="photo.jpg" alt="A beautiful sunset" width="300">
```

---

## **📌 Tables**
| **Tag** | **Description** |
|---------|---------------|
| `<table>` | Creates a table. |
| `<tr>` | Defines a row in a table. |
| `<th>` | Defines a **header** cell (bold & centered). |
| `<td>` | Defines a **regular** cell. |
| `<thead>` `<tbody>` `<tfoot>` | Groups different parts of a table. |
| `colspan="2"` | Merges two columns. |
| `rowspan="2"` | Merges two rows. |

**Example:**  
```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
    </tr>
</table>
```

---

## **📌 Forms & Inputs**
| **Tag** | **Description** |
|---------|---------------|
| `<form>` | Creates a form for user input. |
| `<input type="text">` | Single-line text input. |
| `<input type="password">` | Password field. |
| `<input type="email">` | Email input. |
| `<input type="checkbox">` | Checkbox selection. |
| `<input type="radio">` | Radio button. |
| `<input type="submit">` | Submit button. |
| `<textarea>` | Multi-line text input. |
| `<label>` | Label for form elements. |
| `<select>` | Dropdown selection. |
| `<option>` | Options inside `<select>`. |

**Example:**  
```html
<form>
    <label for="name">Name:</label>
    <input type="text" id="name">
    
    <input type="submit" value="Send">
</form>
```

---

## **📌 Semantic HTML (For Better Structure)**
| **Tag** | **Description** |
|---------|---------------|
| `<header>` | Defines a page header. |
| `<footer>` | Defines a page footer. |
| `<section>` | Defines a section of content. |
| `<article>` | Represents a standalone article. |
| `<aside>` | Sidebar content. |
| `<main>` | The main content of a page. |
| `<div>` | Generic container (used for layout). |
| `<span>` | Inline container for styling small parts of text. |

**Example:**  
```html
<header>
    <h1>My Website</h1>
</header>
<main>
    <section>
        <h2>About Me</h2>
        <p>Welcome to my page!</p>
    </section>
</main>
<footer>
    <p>© 2024 My Website</p>
</footer>
```

---

## **📌 Miscellaneous Tags**
| **Tag** | **Description** |
|---------|---------------|
| `<iframe src="URL">` | Embeds another website inside your page. |
| `<script>` | Inserts JavaScript. |
| `<noscript>` | Alternative content if JavaScript is disabled. |
| `<link>` | Links external CSS files. |
| `<style>` | Embeds CSS styles. |
| `<button>` | Creates a clickable button. |
| `<progress>` | Displays a progress bar. |
| `<meter>` | Displays a measurement. |

**Example:**  
```html
<button onclick="alert('Hello!')">Click Me</button>
```

---

### **🎯 Quick Tips**
✔️ Always close tags: `<div></div>`  
✔️ Use `alt` for images for accessibility.  
✔️ Use **semantic tags** (`<header>`, `<footer>`, `<section>`) for better SEO.  
✔️ Always test your HTML in multiple browsers.  

---

### **🚀 Next Steps**
1. **Save this cheatsheet** for reference.  
2. Try using these tags in your HTML file.

