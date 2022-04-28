# HTML 5 Concepts

---

## HTML `meta` Tag

<br>
The `meta` tag defines metadata about an HTML document. Metadata is data (information) about data.
`meta` tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
Metadata will not be displayed on the page, but is machine parsable.
Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

Conditional comments

1. Conditional comments are conditional statements to hide or provide HTML source code from Internet Explorer.

2. There are two types of conditional comments - downlevel-hidden - which is used to hide HTML source and downlevel-revealed which is used to reveal HTML source code in Internet Explorer.

Syntax of Conditional comments

Type Syntax
downlevel-hidden <!-[if expression]> HTML Code<![endif]-->
downlevel-revealed <![if expression]> HTML Code <![endif]>

HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.
The form element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

The `input` Element

The HTML `input` element is the most used form element.

An `input` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

Type Description <br>
`input type="text"` Displays a single-line text input field <br>
`input type="radio"` Displays a radio button (for selecting one of many choices)<br>
`input type="checkbox"` Displays a checkbox (for selecting zero or more of many choices)<br>
`input type="submit"` Displays a submit button (for submitting the form)<br>
`input type="button"` Displays a clickable button<br>

The `label` Element: <br>
The `label` tag defines a label for many form elements.<br>

The `label` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.<br>

The `label` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `label` element, it toggles the radio button/checkbox.<br>

The for attribute of the `label` tag should be equal to the id attribute of the `input` element to bind them together.<br>

The Submit Button
The `input type="submit"` defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's action attribute.

`iframe`: The Inline Frame element: <br>
The HTML `iframe` tag specifies an inline frame. An inline frame is used to embed another document within the current HTML document.<br>
The `iframe` HTML element represents a nested browsing context, embedding another HTML page into the current one.<br>

## What is <strong>Specificity</strong>?

Specificity is the means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied.
If there are two or more CSS rules that point to the same element, the selector with the highest specificity value will "win", and its style declaration will be applied to that HTML element.

### <strong>Selector Types</strong>

The following list of selector types increases by specificity:

<strong>Type selectors</strong> (e.g., h1) and pseudo-elements (e.g., `::before`). <br>
<strong>
Class selectors (e.g., `.example`), attributes selectors (e.g., `[type="radio"]`) and pseudo-classes (e.g., `:hover`). <br>
ID selectors
</strong> (e.g., `#example`). <br>

# Advanced CSS3

Introduction to the CSS basic box model

When laying out a document, the browser's rendering engine represents each element as a rectangular box according to the standard CSS basic box model. CSS determines the size, position, and properties (color, background, border size, etc.) of these boxes.

Every box is composed of four parts (or areas), defined by their respective edges: the content edge, padding edge, border edge, and margin edge.

## Content area

The content area, bounded by the content edge, contains the "real" content of the element, such as text, an image, or a video player. Its dimensions are the content width (or content-box width) and the content height (or content-box height). It often has a background color or background image.

If the box-sizing property is set to content-box (default) and if the element is a block element, the content area's size can be explicitly defined with the width, min-width, max-width, height, min-height, and max-height properties.

## Padding area

The padding area, bounded by the padding edge, extends the content area to include the element's padding. Its dimensions are the padding-box width and the padding-box height.

The thickness of the padding is determined by the padding-top, padding-right, padding-bottom, padding-left, and shorthand padding properties.

## Border area

The border area, bounded by the border edge, extends the padding area to include the element's borders. Its dimensions are the border-box width and the border-box height.

The thickness of the borders are determined by the border-width and shorthand border properties. If the box-sizing property is set to border-box, the border area's size can be explicitly defined with the width, min-width, max-width, height, min-height, and max-height properties. When there is a background (background-color or background-image) set on a box, it extends to the outer edge of the border (i.e. extends underneath the border in z-ordering). This default behavior can be altered with the background-clip css property.

## Margin area

The margin area, bounded by the margin edge, extends the border area to include an empty area used to separate the element from its neighbors. Its dimensions are the margin-box width and the margin-box height.

The size of the margin area is determined by the margin-top, margin-right, margin-bottom, margin-left, and shorthand margin properties. When margin collapsing occurs, the margin area is not clearly defined since margins are shared between boxes.<br><br>

## <strong>CSS calc function</strong>

The calc() CSS function lets you perform calculations when specifying CSS property values. It can be used anywhere a length, frequency, angle, time, percentage, number, or integer is allowed.

Syntax
/_ property: calc(expression) _/
width: calc(100% - 80px);

The calc() function takes a single expression as its parameter, with the expression's result used as the value. The expression can be any simple expression combining the following operators, using standard operator precedence rules:

- Addition.

- Subtraction.

- Multiplication. At least one of the arguments must be a number.

- Division. The right-hand side must be a number.<br><br>
