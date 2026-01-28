## Is HTML and HTML5 different?

HTML (HyperText Markup Language) is the standard markup language used to create web pages, and HTML5 is the latest major version of HTML with many new features and improvements. HTML5 keeps the same basic idea of elements, tags, and attributes but adds better structure, multimedia support, and modern APIs for web applications. Older HTML versions mainly created static pages, while HTML5 helps build more dynamic, interactive, and mobile‑friendly websites.  

## HTML vs HTML5 points:

- HTML is the general language name; HTML5 is the current version of that language.  
- HTML5 has a simpler doctype: `<!DOCTYPE html>` compared to the long, complex doctypes in older HTML versions.  
- HTML needed plugins like Flash for audio and video, but HTML5 has built‑in `<audio>` and `<video>` tags.  
- HTML5 adds semantic tags like `<header>`, `<footer>`, `<nav>`, `<article>`, and `<section>` to give clearer structure and better accessibility.  
- HTML stored data mostly with cookies, but HTML5 adds web storage and other client‑side storage options like local storage and application cache.  
- HTML5 supports modern APIs like Canvas, Geolocation, Web Storage, and Web Workers for richer web apps.  

## HTML / HTML5 core concepts:

### 1. Basic structure

- Every HTML5 page starts with `<!DOCTYPE html>`, then `<html>`, `<head>`, and `<body>` tags.  
- The `<head>` usually contains metadata, title, links to CSS, and scripts; the `<body>` contains all visible page content.  

### 2. Elements, tags, and attributes

- **Elements** are the building blocks of the page, defined by tags like `<h1>`, `<p>`, `<a>`, `<img>`, `<ul>`, `<li>`, etc.  
- **Attributes** give extra information to elements, such as `id`, `class`, `href`, `src`, `alt`, `title`, and so on.  
- Most elements have an opening tag, content, and a closing tag, for example `<p>...</p>`.  

### 3. Text, headings, and lists

- Headings: `<h1>` to `<h6>` indicate titles and subtitles on a page.  
- Paragraphs: `<p>` elements for normal text content.  
- Lists: `<ul>` (unordered), `<ol>` (ordered), and `<li>` (list items) for bullet or numbered lists.  

### 4. Links and images

- Links are created with the `<a>` tag using the `href` attribute to point to another page or resource.  
- Images use the `<img>` tag with attributes like `src` for the image URL and `alt` for alternative text.  

### 5. Semantic HTML5 elements

- Semantic tags describe the meaning of the content: examples are `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.  
- These elements improve SEO and accessibility because browsers and screen readers understand the page structure more clearly.  

### 6. Forms and input types

- HTML5 forms use `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>`, etc.  
- HTML5 introduced new input types like `email`, `url`, `number`, `date`, `range`, and built‑in validation features, which reduce extra JavaScript for simple checks.  

### 7. Multimedia support

- HTML5 adds the `<audio>` and `<video>` elements for playing sound and video directly in the browser without external plugins.  
- It also supports `<track>` for subtitles and captions inside media elements.  

### 8. Graphics: Canvas and SVG

- The `<canvas>` element allows drawing graphics, animations, and games with JavaScript.  
- SVG (Scalable Vector Graphics) can be embedded inline in HTML5 for sharp, scalable icons and shapes like circles, rectangles, and paths.  

### 9. Storage and offline features

- HTML5 provides Web Storage (localStorage and sessionStorage) for storing key–value data in the browser with more space than cookies.  
- It also supports offline capabilities and application caching through related APIs, which help web apps work even without internet for some features.  
