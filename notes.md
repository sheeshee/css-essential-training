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
