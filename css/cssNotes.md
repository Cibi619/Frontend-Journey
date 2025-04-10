# CSS TOPICS
## Introduction to CSS
CSS is a stylesheet language used to control the layout and appearance of the web page.

Block Level Elements - Takes up entire line (width) of the page. Eg: `<p>, <h1, h2>, <div> etc`.

Inline Elements - Takes up only the space needed (width) of the content. Eg. `<span>, <a>, <img> etc`.

CSS Properties - 3 major types.

1. Content - CSS changes inside the box (text). Eg: `color, font-size, font-family etc`.
2. Box - CSS changes to the box itself. Eg: `width, height, border, padding etc`.
3. Layout - CSS changes to the layout of the box. Eg: `position, float, flex, grid`.

CSS Rules - Grouping of one or more CSS properties which are to be applied to one or more HTML elements. Eg: `h1 { color: blue; }`.

CSS Declaration - Combination of a CSS property and its value. Eg: `color: blue;`.

## CSS TEXT
### Text Styling
Styling focused on text, spacing of text, size changes for text, color and style guide.

Some examples - `text-transform: uppercase; `, `text-align: center;`, `font-size: 20px;`

### Text Spacing
Spacing between lines of text, spacing of text within a line, spacing between words.

Some examples - `line-height: 1.5;`, `letter-spacing: 2px;`, `text-align: center`

`text-align` property only works for block elements as inline elements cannot move as there is no space.

### CSS Color
Color of text, background color, color of borders.

Some examples - ` color: blue;`, `background-color: red;`, `border-color: green;`. Can have Hex or RGB values (commonly used)

Have few color palettes with tints and shades of the color (usually primary and secondary palette)

## CSS Selectors
CSS selectors are used to select the HTML elements you want to apply CSS styles to.

Some types of Selectors: Basic selectors ( tag, id, class), Combinators (descendant, child, adjacent sibling), Pseudo-classes (link, hover, active), Pseudo-elements (first letter, first line, before, after)

Styles declared later takes priority over the styles declared earlier.

Stylesheets also follow the same pattern.

### Class and ID Selectors
Class selectors are used to select elements with a specific class. Eg: `.class-name { color: blue; }`

ID selectors are used to select elements with a specific id. Eg: `#id-name { color : blue; }`

### Pseudo-classes
Pseudo-classes are used to select elements based on their state. Eg: `:hover { color: blue; }`. Other examples are `:link`, `:visited`, `:active`

Good practice is to style the pseudo-classes for the anchor tags, not the anchor tag itself. Eg. `a { color: blue; }` - not a good practice.

### Combinator Selectors
Combinator selectors are used to select elements based on their relationship with other elements. Eg: `h1 > p { color: blue; }` - selects all p elements that are direct children of h1 elements.

### Specificity
Determines the priority of a CSS rule when multiple rules apply to the same element. Eg. ` h1 { color: blue; }` has lower specificity than `.heading { color: blue; }`.

### CSS Inheritance
CSS inheritance is the process by which the styles of a parent element are applied to its child elements. Eg: Styles applied to parent div class containing h1 and p elements will be applied to h1 and p elements as well.

It is mainly the text properties that are inherited from parent to child.


