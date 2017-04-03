# Prism

The default theme for highlighter [Prism](http://prismjs.com)

## html

```html
<html>
  <head>
    <title>Prism</title>
  </head>
  <body>
    <a href="https://github.com/mobi-css/mobi-plugin-prism">GitHub</a>
  </body>
</html>
```

## js

```js
const Prism = require('prismjs');

// The code snippet you want to highlight, as a string
var code = "var data = 1;";

// Returns a highlighted HTML string
var html = Prism.highlight(code, Prism.languages.javascript);
```

## css

```css
.highlight-css {
  background: #f2f2f2;
}
```
