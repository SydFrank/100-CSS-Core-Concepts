# 1. Types of CSS (Cascading Style Sheets)

## 1.1 Inline CSS

> Inline CSS is applied directly to a specific HTML element by using the **style** attribute.

```css
<h1 style="color: blue; font-size: 20px;">This is a heading</h1>

```

## 1.2 Internal CSS

> Internal CSS is written within a **<** **style** **>** tag inside the **<** **head** **>** section of an HTML element.

```css
<head>
  <style>
    h1 {
      color: blue;
      font-size: 20px;
    }
  </style>
</head>

```

## 1.3 External CSS

> External CSS is written is a separate **.css** file and linked to an HTML document by using the **<** **link** **>** tag.

```css
<head>
  <link rel="stylesheet" href="styles.css">
</head>

```

```css
/* styles.css */
h1 {
  color: blue;
  font-size: 20px;
}

```

## 1.4 Best Practices

1. Use External CSS whenever possible for scalability and maintainability.
2. Reserve Inline CSS for quick tests or unique exceptions.
3. Use Internal CSS for small projects or when external styles are not feasible.

