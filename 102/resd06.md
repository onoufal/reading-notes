# CSS
* Styling html pages and make them more attractive.
* We can apply rules to html elements with css about how they should be displayed.
* A rules contain **selector** and a **declaration**.

```css
p {
  font-family: Arial;
}
```

* Declaration contains a **property** and a **value**.

```css
h1, h2, h3 {
  font-family: Arial;
  color: yellow;
}

```

*External CSS:
```html
<link href="css/styles.css" type="text/css" rel="stylesheet>
```

## CSS Selectors:
* Target rules to specific elements.
1. Univeral Selector
```css
* {

}
```

1. Type Selector:
```css
h1, h2, h3 {

}
```
1. Class Selector:
```css
.note {

}

p.note {

}
```

1. ID Selector:
```css
#introduction {

}
```

1. Child Selector: 
```css
li>a {

}
```

1. Descendant Selector:
```css
p a {

}
```

## Rules priority:
1. Last
1. Specifity 
1. Important:
  ```css
  p b {
    color: blue !important;
  }
  ```










