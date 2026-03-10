# Html 1

## 1. What is HTML?

**HTML** stands for **HyperText Markup Language**.

![image.png](image.png)

It is a **markup language** used to create the **structure of web pages**.

A website is usually built using three main technologies:

- **HTML** → Structure of the page (content)
- **CSS** → Design and layout (colors, fonts, positioning)
- **JavaScript** → Interactivity and behavior

HTML is considered the **foundation of every website**.

---

# 2. History of HTML

HTML has evolved over time. Some important versions are:

- HTML 1.0
- HTML 2.0
- HTML 3.2
- HTML 4.01
- **HTML5** (the modern standard used today)

Today HTML is maintained as a **living standard**, meaning it continues to evolve without strict version numbers.

---

# 3. What Does HTML Do?

HTML is responsible for:

- Organizing content on a web page
- Defining headings, paragraphs, images, links, and other elements
- Structuring information so browsers can display it correctly

A website is usually made of **multiple web pages** connected together using **links**.

Example structure of a website:

```
Page + Page + Page + Page + ...
        ↓
     Website
```

---

# 4. Important Characteristics of HTML

### HTML is a markup language

It uses **tags** to mark and organize content.

### HTML is simple to write

It uses clear and readable syntax.

### HTML is not a programming language

It **does not perform calculations or logic**.

It only **describes the structure of content**.

---

# 5. Main Components of HTML

HTML consists of four main concepts:

- **Tags**
- **Elements**
- **Attributes**
- **Symbols**

---

# 6. HTML Tags

Tags are **special keywords enclosed in angle brackets**.

Example:

```
<p>
<h1>
<div>
```

Tags tell the browser **how to interpret the content**.

Most tags come in pairs:

```
<tag> content </tag>
```

Example:

```
<p>This is a paragraph</p>
```

Some tags are **self-closing**, such as:

```
<br>
<hr>
```

---

# 7. HTML Elements

An **HTML element** consists of:

- Opening tag
- Content
- Closing tag

Example:

```
<p>This is a paragraph</p>
```

Structure:

```
Opening tag + Content + Closing tag
```

Example with heading:

```
<h1>Welcome</h1>
```

---

# 8. HTML Attributes

Attributes provide **additional information about an element**.

They are written **inside the opening tag**.

Example:

```
<img src="image.jpg" alt="Example image">
```

Here:

- `src` → specifies the image source
- `alt` → alternative text for the image

General format:

```
<tag attribute="value">
```

Example:

```
<a href="https://example.com">Visit</a>
```

---

# 9. HTML Symbols

HTML includes special characters called **symbols**.

These are used when a character has a **special meaning in HTML**.

Examples:

| Symbol | Meaning |
| --- | --- |
| `<` | less than |
| `>` | greater than |
| `&` | ampersand |

Sometimes special codes are used to display them correctly in HTML.

---

# 10. Basic HTML Document Structure

Every HTML page follows a basic structure.

Example:

```html
<html>

<head>
    <title>My Page</title>
</head>

<body>
    Content of the page
</body>

</html>
```

Explanation:

| Tag | Role |
| --- | --- |
| `<html>` | Root of the document |
| `<head>` | Contains metadata (title, links, etc.) |
| `<body>` | Contains visible content |

---