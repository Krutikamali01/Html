# 🌐 HTML Beginner Roadmap – by @KrutikaCodes

Welcome to your beginner-friendly **HTML Roadmap**! This guide will help you go from zero to confidently building webpages using HTML.

---

## 📖 Table of Contents
1. [Stage 1: HTML Basics](#stage-1-html-basics)
2. [Stage 2: Layout & Structure](#stage-2-layout--structure)
3. [Stage 3: Forms & Inputs](#stage-3-forms--inputs)
4. [Stage 4: Intro to CSS Styling](#stage-4-intro-to-css-styling)
5. [Mini Projects](#mini-projects)
6. [Resources](#resources)

---

## ⚐️ Stage 1: HTML Basics
📚 Learn:
- What is HTML?
- HTML, or Hypertext Markup Language, is the standard language used to create and design web pages.It provides the structure and layout of a webpage by using a system of tags and attributes to define elements such as headings, paragraphs, images, links, and more.By arranging these elements in a hierarchical structure, designers can create visually appealing and well-organized web pages.
- HTML document structure
- Basic tags: `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`, `<a>`, `<img>`

🛠️ Practice:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Hello World</title>
</head>
<body>
  <h1>Hello, world!</h1>
  <p>This is your first HTML page.</p>
</body>
</html>
```
🔗 Try it live on [CodePen](https://codepen.io) or [GitHub Pages](https://github.com/Krutikamali01)

---

## 🧱 Stage 2: Layout & Structure
📚 Learn:
- Semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Lists: `<ul>`, `<ol>`, `<li>`
- Grouping content with `<div>` and `<span>`

🛠️ Practice:
```html
<!DOCTYPE html>
<html>
<body>
  <header>
    <h1>My Blog</h1>
  </header>
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>
  <main>
    <section>
      <h2>Welcome!</h2>
      <p>This is a simple layout using semantic tags.</p>
    </section>
  </main>
  <footer>
    <p>© 2025 KrutikaCodes</p>
  </footer>
</body>
</html>
```
---

## 📝 Stage 3: Tables,Forms & Inputs
📚 Learn:
- `<form>`, `<input>`, `<label>`, `<button>`.`<table>`,`<tr>`,`<td>`,`<th>`
- Types of inputs: `text`, `email`, `password`, `radio`, `checkbox`

🛠️ Practice:
Tables
```html
<!DOCTYPE html>
<html>
<body>
 <table border="1">
        <tr>
           
            <th colspan="4">Channels</th>
        </tr>
        <tr>
            <th>CN</th>
            <th>nick</th>
            <th>disney</th>
            <th>disneyXD</th>
         </tr>
         <tr>
            <td>tom&jerry</td>
            <td>yes</td>
            <td>no</td>
            <td>no</td>
         </tr>
         <tr>
            <td>no</td>
            <td>power rangers</td>
            <td>no</td>
            <td>no</td>
         </tr>
         <tr>
            <td>no</td>
            <td>no</td>
            <td>Ducktales</td>
            <td>no</td>
         </tr>
         <tr>
            <td>no</td>
            <td>no</td>
            <td>no</td>
            <td>Spiderman</td>
         </tr>
    </table>
</body>
</html>
```
Forms
```html
<!DOCTYPE html>
<html>
<body>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>

    <label for="message">Message:</label><br>
    <textarea id="message" name="message"></textarea><br><br>

    <button type="submit">Send</button>
  </form>
</body>
</html>
```
---

## 🎨 Stage 4: Intro to CSS Styling
📚 Learn:
- Link CSS to HTML using `<link>`
- Styling tags: color, font, padding, margin, borders

🛠️ Practice:
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fdf6f0;
      color: #333;
    }
    h1 {
      color: #ff8ba7;
    }
  </style>
</head>
<body>
  <h1>About Me</h1>
  <p>Hello! I'm learning HTML and CSS.</p>
</body>
</html>
```

---

## ✨ Mini Projects can be made 
- Personal Portfolio Page
- Recipe Page
- Blog Post Page
- To-do List (HTML Only)

---

## 📚 Resources
- [W3Schools](https://w3schools.com)
- [FreeCodeCamp](https://www.freecodecamp.org/learn/)

---
⭐ Star this repo if it helps you & share with your coding buddies!
