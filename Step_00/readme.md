# How CSS Works

CSS works by selecting HTML elements and applying styles to them
It uses selectors to target elements and declarations to specify the styles

## CSS can be added to HTML documents in three ways: inline, internal, and external.

### Inline CSS

Inline styles are added directly to HTML elements using the style attribute. For example

```bash
<p style="color: red;">This is a red paragraph.</p>
```

### Internal CSS

Internal styles are defined within the HTML document using the style element in the document head For example:

```bash
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
<body>
  <p>This is a blue paragraph.</p>
</body>

```

### External CSS

External styles are placed in separate CSS files with a .css extension and linked to the HTML document using the link element in the head For example:

```bash
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <p>This is a styled paragraph.</p>
</body>


```
