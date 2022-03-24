# Semantic HTML

In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

Semantic HTML is a way of writing code to be easier to read and more accessible to search engines. And also for humans. Instead of constantly inventing new ways to describe what role elements have, you can use agreed on terms instead.

For example, which of the following elements is a button?

```html
<div class="button">Click me</div>
<p class="button">Click me</p>
<a href="#" class="button">Click me</a>
<button class="button">Click me</button>
```

How do you know? One could assume that the class name "button" will describe it to machines and humans. Sure, a human can understand it, but screen readers generally do not read class names.

Semantic HTML standardizes HTML language, so there is nothing left to interpretation. From the implementation of HTML5, there are around 100 semantic elements. Web applications have become increasingly more prominent and complex over the years, so it is necessary to realize the importance of structuring content in an organized and easy-to-understand manner.

## Why should one care about semantic HTML?

Semantic HTML is understandable for humans and machines, and therefore it will increase your page:

- Accessibility
- Findability
- Readability

**Accessibility**

When a screen reader or any assistive device scans a web page, it gets information about the Document Object Model (DOM) or the HTML structure of the page. Semantic HTML will describe what elements are used on the webpage, and the screen reader can interpret content more accurately. Note: A screen reader will read no styles or JavaScript.

**Findability**

With semantic HTML, you can increase your page SEO score, as search crawler knows part of the page they are crawling. Search engines emphasise keywords inside headings, links, etc., than keywords included in non-semantic <div>s, etc.

A Search Crawler is an Internet bot that browses through internet, downloads and indexes content. It is widely used to learn each webpage on the web to retrieve information. It is sometimes called a spider bot or spider.

**Readability**

Writing semantic HTML makes your code easier to understand, making the source code more readable for other developers.
They are machine and human-readable.

## HTML elements

### Everyday use

`<html>`
`<head>`
`<title>`
`<body>`
`<header>`
`<main>`
`<footer>`
`<nav>`
`<section>`
`<article>`
`<ul>`
`<li>`
`<button>`

### Text elements

`<a href="...">`
`<h1>, <h2>, <h3>, <h4>, <h5>, <h6>`
`<p>`
`<em>`
`<strong>`
`<small>`
`<address>`

### Media

`<img scr="..." alt="...">`
`<figure>`
`<figcaption>`
`<picture>`
`<video>`
`<audio>`
`<source>`

### Data

`<time>`
`<data>`
`<meter>`
`<progress>`

### Meaningless tags

`<div>`
`<span>`

### Avoid these

`<br>`
`<hr>`
`<i>`
`<b>`
`<u>`

## HTML best practices

- Use only one `<h1>` element for one code sheet
- Do not skip heading levels in HTML
- Use the figure element to add captions to your images in HTML
- Do not use divs to create headers and footers – use semantic elements instead
- Avoid using `<b>` and `<i>` to bold and italicize texts on a web page
- Don't place block-level elements within inline elements
- Elements like `<div>` and `<span>` are for layout only.

## Code validation

To check if your code is correctly written, you can use HTML and CSS validators. Code validation is beneficial when you are a beginner, as you can learn a lot from the validation process to get to know rules in HTML and CSS.

HTML code in all web applications should comply with the standards and recommendations set by the World Wide Web Consortium (W3C) for the web.

### Why you should validate your code?

- Validation can be used as a debugging tool
- Validation can be a great learning tool
- Validation prove your ability to write correct code
- Validation makes maintenance easier
- Good code is a sign of professionalism

### Tools for validation

[Validator.nu](https://validator.nu/): A new-school validator that validates HTML5, ARIA, SVG 1.1 and MathML 2.0: it goes through the entire document pointing out places where your markup doesn’t follow that doctype correctly (ie where there are errors). This is the one we recommend if you are using the HTML5 doctype, like we do throughout most of this course.

[The W3C MarkUp Validator](https://validator.w3.org/)
: This looks at the (X)HTML doctype you are using for the document you give it to check, and then checks your markup accordingly. This is the one we recommend if you are using an HTML4 or XHTML1.x doctype. It does validate HTML5, but validator.nu is arguably more up to date.

[The W3C Link Checker](https://validator.w3.org/checklink)
: This looks through a document you give it to check, and tests all the links inside that document to make sure they are not broken (ie the `<href>` values point to resources that don’t exist).

[The W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
: As you’ve probably guessed, this will go through a CSS (or HTML/CSS) document and check that the CSS follows the CSS specs properly.

## Tools for better HTML in VSc

**Built in:**

- Emmet
- Auto Rename Tag (Settings -> Linked Editing)

**Extensions**

- Prettier
- HTML End Matching Tag
- Highlight Matching Tag
