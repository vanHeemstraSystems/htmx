# 200 - Quick Start

```
  <script src="https://unpkg.com/htmx.org@2.0.4"></script>
  <!-- have a button POST a click via AJAX -->
  <button hx-post="/clicked" hx-swap="outerHTML">
    Click Me
  </button>
```

The ```hx-post``` and ```hx-swap``` attributes on this button tell htmx:

> “When a user clicks on this button, issue an AJAX request to /clicked, and replace the entire button with the HTML response”

htmx is the successor to [intercooler.js](http://intercoolerjs.org/)

Read the [docs introduction](https://htmx.org/docs/#introduction) for a more in-depth… introduction.

Note that htmx 2.x has dropped IE support. If you require IE support you can use the [1.x](https://v1.htmx.org/) code-line, which will be supported in perpetuity.
