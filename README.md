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

# 2. Selectors

## 2.1 Universal Selector

> Selects all elements on the page

```css
* {
  margin: 0;
  padding: 0;
}
```

## 2.2 Type Selector (Element Selector)

> Selects all elements of a specific type (HTML tag)

```css
h1 {
  color: blue;
}
```

## 2.3 Class Selector

> Selects elements based on the value of their **class **attribute

```css
<div class="box">Content</div>
```

```css
.box {
  border: 1px solid black;
}
```

## 2.4 ID Selector

> Selects an element based on its **id** attribute

```css
<div id="unique">Content</div>
```

```css
#unique {
  background-color: yellow;
}
```

## 2.5 Attribute Selector

> Selects elements based on their attributes.

```css
/* Select elements with a "type" attribute */
[type] {
  border: 1px solid black;
}

/* Select elements with a specific "type" value */
[type="text"] {
  background-color: lightgray;
}

/* Select elements whose "type" value contains "pass" */
[type*="pass"] {
  color: red;
}

/* Select elements whose "type" value starts with "sub" */
[type^="sub"] {
  font-weight: bold;
}

/* Select elements whose "type" value ends with "name" */
[type$="name"] {
  text-decoration: underline;
}

```

## 2.6 Group Selector (,)

## 2.7 Descendant Selector ( )

## 2.8 Child Selector (>)

## 2.9 Sibling Selectors

## 2.10 Pseudo-Classes

## 2.11 Pseudo-Elements



## 2.12 Specificity

1. Inline Styles
2. #ID selectors
3. .class, ::pseudo-class and [attribute] selectors
4. <Tag> and ::pseudo-element selectors



# Font Family

