syntex for box shadow:
box-shadow: offsetX offsetY blurRadius spreadRadius color;

<!--  -->

The "border-radius" property accepts up to four values to round the top-left, top-right, bottom-right, and bottom-left corners.

<!--  -->

"clear" property set to "right". This will clear the "float" property, pushing the divider and any following content down below the float text.

<!--  -->

The "text-indent" property specifies the indentation of the first line in a text-block. (indentation = space before the first line, like paragraph style.)
eg.: text-indent: 100px; `it can be px, cm or %. & also accept negative values.`
`       This example demonstrates different text-indents. Try changing the text-indent by clicking on one of the line-height properties on the left, and see the result in this DIV element.`

<!--  -->

The clip CSS property defines a visible portion of an element. The clip property applies only to absolutely positioned elements — that is, elements with position:absolute or position:fixed. it allows you to clipping an element to a basic shape (circle, ellipse, polygon, or inset).
`clip: auto|shape|initial|inherit;`
`JavaScript syntax: object.style.clip="rect(0px,50px,50px,0px)"`

<!--  -->

The <kbd> element defines keyboard input.
The <samp> element defines sample output from a computer program.
The <code> element defines a piece of computer code.
The <var> element defines a variable in programming or in a mathematical expression.
The <pre> element defines preformatted text.

<!--  -->

The `loading` attribute on an `img` element can be set to `lazy` to tell the browser not to fetch the image resource until it is needed (as in, when the user scrolls the image into view). As an additional benefit, lazy loaded elements will not load until the non-lazy elements are loaded - this means users with slow internet connections can view the content of your page without having to wait for the images to load.

<!--  -->

If you wanted to add more social icons, but keep them on the same row, you would need to update grid-template-columns to create additional columns. As an alternative, you can use the `grid-auto-flow` property. `grid-auto-flow` uses an auto-placement algorithm to adjust the grid layout.
` grid-auto-flow: column`/`row;`

The dense value allows the algorithm to backtrack and fill holes in the grid with smaller items, which can result in items appearing out of order.

You can override this with the `grid-auto-columns` property.
`grid-template-columns: repeat(5, 1fr);`
`grid-auto-flow: column;`
`grid-auto-columns: 1fr;`

<!--  -->

`gap` property: If given one value, it sets the column-gap and row-gap both to that value. If given `two values`, it sets the `row-gap to the first value` and the `column-gap to the second`.

<!--  -->

The `place-items` property can be used to set the `align-items` and `justify-items` values at the same time. The place-items property takes `one` or `two values`. If two values are provided, the `first value  for the align-items` property and the `second value for the justify-items` property.

<!--  -->

`animation property :`
div {
animation-name: example;
animation-duration: 5s;
animation-timing-function: linear;
animation-delay: 2s;
animation-iteration-count: infinite;
animation-direction: alternate;
}
`shorthand:`
div {
animation: example 5s linear 2s infinite alternate;
}

<!--  -->

`common colors:`
:root {
--blue: #007bff;
--indigo: #6610f2;
--purple: #6f42c1;
--pink: #e83e8c;
--red: #dc3545;
--orange: #fd7e14;
--yellow: #ffc107;
--green: #28a745;
--teal: #20c997;
--cyan: #17a2b8;
--white: #fff;
--gray: #6c757d;
--gray-dark: #343a40;
--primary: #007bff;
--secondary: #6c757d;
--success: #28a745;
--info: #17a2b8;
--warning: #ffc107;
--danger: #dc3545;
--light: #f8f9fa;
--dark: #343a40;
}

<!--  -->
