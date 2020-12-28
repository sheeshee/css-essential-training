# Images

## Absolute paths

* Don't _hotlink_ (using paths to resources on someone else's page)
* https://picum.photos for placeholders!

# CSS specifications and the W3C

* World Wide Web Consortium
* Responsible for establishing conventions and guidelines in
  specifications
* Use the "Recommended" standards
* MDN CSS developer's guide

# Syntax and terminology

* https://codeguide.co for style guide

# Color Property

* basic color keywords
  * look at w3C documentation
  * https://colours.neilorangpeel.com
* hex
* rgb function
  * values or percent
  * rgba() adds opacitiy with alpha channel

* hsl
  * Hue (angle in colour wheel relative to red)
  * Saturation (percentage, 0% is shade of grey)
  * Lightness (Black to White)
  * https://css-tricks.com

* https://coolers.co

# CSS Selectors

* type selectors
  * e.g. just name of element
  
* universal selector
  * just a "*" selects all elements

* class selector
  * begins with leading period ".myclass"
  * to apply styles only when two specific classes are present
    write the selectors with no space between the class names,
    e.g.: ".first.second"

* ID selectors
  * can only be used once per page

* In page linking
  * e.g. "#mylink {...}" corresponds to "<a href="#mylink">"

* Document Object Model

  * Descendant Selectors

* Grouping Selectors
  * seperate elements with a comma
  * or "element.classname"

# Inheritance
  * All children have parent properties
  * Some properties are not inheritable

# Specificity
  * When conflicting style declarations, resolve by priority (low to high)
    1. universal
    2. type
    3. class
    4. id
  * Specificity calculation
    * https://specificity.keegan.st
  * Cascade rule, two declarations of same value, the one lower
    down takes precedence
  * important keyword can help but considered bad practice
    e.g. "font-size: 12px!important;"

# Pseudo-classes

* e.g. .button:hover {}
# Font

* Use Google Fonts

# Text Decoration

* `text-align`
* `line-height`: same as font, no space. smaller, lines overlap
  more, then bigger gap in lines
  * Can also use relative e.g. % or a decimal
* 

# Float

* originally to mimick print
* The "clearfix" Hack

# Positioned

* static: not positioned
* relative: relative to current position
* absolute: relative to containing element
* fixed: relative to the viewport
* sticky: relative to containing element and viewport
  * still in draft phase


* All but static need position properties

## z-index

* The stacking context
* default is order in which they appear in the document (after=ontop_)
  * followed by float
  * followed by inline
  * followed by position documents


# Grid and Flexbox

Flexbox: usually one-dimensional: either x or y

Grid: newer, two-dimensional

# Flexbox

* `display: flex;` or `display: flex-inline;`
* height of each flex items adjusts to be length of longest flex item
* `flex-direction` wither `row`, `column`, `row-reverse` or `column-reverse`
* `flex-wrap: nowrap` or `wrap` or `wrap-reverse`
* `flex-basis`, `flex-grow`, `flex-shrink`

Align items for vertical alignment!
Also justify-content

## CSS Grid

* `display: grid` or `inline-grid`
* numerical index, 0-indexed
* grid cell, grid track, gutters (`gap`), 

* explicit grid
  * `fr` fraction unit
* or implicit grid

* supported in all modern browsers

explicit or implicit grid

implicit grid with `grid-auto-columns(or rows)`

# Advanced Selectors

* Child Combinator
* Descendent Combinator
* Sibling Combinator

* pseudo-class selectors:
  * first or last
  * first-of-type (last)
  * first-of-child (last)
