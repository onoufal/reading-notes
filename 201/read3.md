# Chapter 3: Lists.
___
* **Ordered lists.**
### - Use numbers
```html
<ol>
  <li>Item1</li>
  <li>Item2</li>
  <li>Item3</li>
</ol>
```
* **Unordered lists.**
### - Use bullets
```html
<ul>
  <li>Item</li>
  <li>Item</li>
  <li>Item</li>
</ul>
```
* **Defention lists.**
### - Define terminology
```html
<dl>
  <dt>term</dt>
  <dd>defention</dd>
</dl>
```
* **Nested list**
```html
<ul>
  <li>Item A</li>
  <li>Item B</li>
    <ul>
      <li>Item a</li>
      <li>Item b</li>
      <li>Item c</li>
    </ul>
  <li>Item C</li>
</ul>
```
___
___

# Chapter 13: Boxes
* **CSS trearts every element like it lives in its own box.** 

* **Box Dimentions** (**Width & Height**):
```css
p {
height: 300px;
width: 300px; }
```
* **min & max width:**
 >**min-width** property specifies
the smallest size a box can be
displayed at when the browser
window is narrow.

 >max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.
```css
p { 
min-width: 450px;
max-width: 650px; }
```

* **min & max height:**
> limit the height
```css
p {
min-height: 400px;
min-width: 400px; }
```

* **overflow:**
> The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself.

```css
p {
overflow: hidden; } /* hides any
extra content that does not fit in
the box. */

p {
overflow: scroll; } /*adds a scrollbar to
the box so that users can scroll
to see the missing content. */
```
* >The **border**
separates the edge of one box
from another.

* >**Margins** sit outside the edge
of the border. You can set the
*width* of a margin to create a
**gap between the borders of two
adjacent boxes.**
* >**Padding** is the space between
the border of a box and any
content contained within it.

* **border-width:**
```css
p. {
border-width: 2px;}
p. {
border-width: thick;} /* thin, medium or thick */
p. {
border-width: 1px 4px 12px 4px;} /* clockwise order: top, right,
bottom, left. */

/* control the individual
size of borders */
border-top-width
border-right-width
border-bottom-width
border-left-width
```
* **Border style:**
```css
p. {border-style: solid;} /* a single solid line */
p. {border-style: dotted;} /* a series of square dots */
p. {border-style: dashed;} /* a series of short lines*/
p. {border-style: double;} /* two solid lines */
p. {border-style: groove;} /* appears to be carved
into the page */
p. {border-style: ridge;} /* appears to stick out from
the page */
p. {border-style: inset;} /* appears embedded into
the page */
p. {border-style: outset;} /* looks like it is coming
out of the screen */
p. {border-style: none;} /* no border is
shown */
```

* **Border Color:**
```css
p {
border-color: #0088dd;
}

p {
  border-color: darkcyan deeppink darkcyan deeppink;
} /* The values here appear in
clockwise order: top, right,
bottom, left. */
```

* **Short hand border:**
> The border property allows you
to specify the **width**, **style** and
**color** of a border in one property
(and the values should be coded
in that specific order).

```css
p {
width: 250px;
border: 3px dotted #0088dd;}
```
* **Centering Content:**
```css
body {
text-align: center;} /* center, left, right*/
p {
```

* **Changing inline/block:**
1. **inline:**
> This causes a block-level
element to act like an inline
element.
2. **block:**
>This causes an inline element to
act like a block-level element.
3. **inline-block:**
> This causes a block-level
element to flow like an inline
element, **while retaining other
features of a block-level element.**
4. **none:**
> hides an element from the
page.
___
___
<br>

# Chapter 2: Basic JavaScript Instructions:
___
<br>

# Intro: 

> ## A **script** is a series of instructions that a computer can follow one-by-one.
> ## Each individual instruction or step is known as a statement.
> ## Statements should end with a semicolon.
<br>

> ## The curly braces indicate the start and end
> ## of a code block. (Each code block could contain
> ## many more statements.)
<br>

> ## A script will have to temporarily
> ## store the bits of information it
> ## needs to do its job. It can store this
> ## data in variables.
<br>

# Data Types:
1. Number
```javascript
let x = 76;
```
2. String
```javascript
let x = 'Osama';
```
3. Boolean
```javascript
let x = true;
```

## Variables Decalre, Assign and Re-ssign
___
___
<br>

# Chapter 4: Loops:

> if else statement allows
to provide two sets of code:
> 1. one set if the condition
evaluates to true
> 2. another set if the condition is
false

> A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.

> If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error.

> JavaScript can convert data
types behind the scenes to
complete an operation. This is
known as type coercion. For
example, a string 'l ' could be
converted to a number 1 in the
following expression:(' 1' > 0).
As a result, the above expression
would evaluate to true.

> Falsy values are treated as if they
are fa 1 se. The table to the left
shows a hi ghScore variable with
a series of va lues, all of which
are falsy.

> Truthy values are treated as if
they are true. Almost everything
that is not in the falsy table can
be treated as if it were true.