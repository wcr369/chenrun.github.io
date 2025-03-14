---
post
---

# Learning HTML

## Introduction
HTML (HyperText Markup Language) is the standard language for creating web pages. It describes the structure of a webpage using markup.

## Basic Structure
```html
<!DOCTYPE html>  //所有的HTML文档必须以此开头
<html>  //开始
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>  //结束
```

## Common Tags
- `<h1>` to `<h6>`: Headings
- `<p>`: Paragraph
- `<a>`: Anchor (link)
- `<img>`: Image
- `<ul>`, `<ol>`, `<li>`: Lists
- `<div>`: Division or section
- `<span>`: Inline section

## Example
```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first webpage.</p>
    <a href="https://www.example.com">Visit Example</a>
    <img src="image.jpg" alt="Example Image">
</body>
</html>
```

## 一些心得

1. 如果你想在 HTML 里让文本换行，但不想用 <p>（因为段落之间间距太大），可以使用以下方法：

    ```<p>这是一行文本。<br>这是一行换行后的文本。</p>```

## Resources
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
