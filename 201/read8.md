# Layout
## Controling the position of elements
### Building blocks
* Each HTML element as if it is in its
own box. This box will either be a **block-level**
box or an **inline** box.
* We can control how much space each box takes up by setting the width of the boxes.
* To _separate_ boxes, you can use
**borders**, **margins**, **padding**, and **background colors**.

1. Block-level elements
start on a new line
Examples include:
`<h1> <p> <ul> <li>`

2. Inline elements
flow in between
surrounding text
Examples include:
`<img> <b> <i>`

### Containing Elements:
> If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
* Group a number of elements together inside a `<div>, <section>, <article>, <aside>, <header>, <main>, <footer>`
(or other block-level) element.

### positioning schemes:
1. **Normal flow**: Block element - new line, next item lower.
2. **Relative positioning**:shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements.
3. **Absolute positioning**: positions the element
in relation to its _containing_
element.
 a. **Fixed positioning**: positions the element in relation to the _browser window_, they do not move when the user scrolls up or down the page. <br>
 b. **Floating Elements**: allows you to take that element _out of normal flow_ and position it to the far left or right of a containing box. The floated element becomes

 * When you move any element from normal flow, boxes can overlap. **The z-index property allows you to control which box appears on top.**












