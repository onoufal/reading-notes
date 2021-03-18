# SMACSS and Responsive Web Design.

## Responsive web design components:
1. flexible layouts.
2. media queries.
3. flexible media.

### Flexible layouts:
> is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width.

> **Flexible grids** are built using **relative length units**, most commonly _percentages_ or _em_ units. 

#### The formula:
The relative width of the target element equal the target width of an element  divided by the width of it’s parent element.

`target ÷ context = result`

### Media Queries:
> Provide the ability to specify **different** styles for individual browser and device circumstances, _the width of the viewport_ or _device orientation_ for example.

#### Initializing Media Queries:
1. Using the `@media` rule inside of an existing style sheet, importing a new style sheet using the `@import` rule.
2.  Linking to a separate style sheet from within the HTML document.


#### Logical Operators in Media Queries:
1. and ===>
`@media all and (min-width: 800px) and (max-width: 1024px) {...}`
2. not ===>
`@media not screen and (color) {...}`
3. only ===> `@media only screen and (orientation: portrait) {...}`


#### Media Features in Media Queries:

1. Height & Width Media Features
`@media all and (min-width: 320px) and (max-width: 780px) {...}`

2. Orientation Media Feature
`@media all and (orientation: landscape) {...}`

3. Aspect Ratio Media Features
`@media all and (min-device-aspect-ratio: 16/9) {...}`

4. Resolution Media Feature
`@media print and (min-resolution: 300dpi) {...}`

## Floats:

* Floats can be used to create entire web layouts.

* Floats usefull when change size of wraped content, as it reflows and not cover a fixed area.

* Element can be cleared to ensure it stays beneath both floated columns.

* If parent element has nothing than floated elemets it will has no height thus it collapse, We fix it by clearing the float after the floated elements in the container but before the close of the container.