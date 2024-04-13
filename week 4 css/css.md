# What is cascading
## it is the order that rules are applied
## Notes on css
* CSS Basics: CSS (Cascading Style Sheets) is used to style web content, controlling things like color, layout, and decoration. It's not a programming or markup language but a style sheet language.
* What is CSS? CSS is used to selectively style HTML elements. For instance, p { color: red; } selects paragraphs and sets their color to red.
* Applying CSS: Save CSS code in a file (e.g., style.css) and link it to your HTML document using <link href="styles/style.css" rel="stylesheet" /> in the <head> section.
### Anatomy of a CSS Ruleset:
* Selector: HTML element name at the start of a ruleset, defining the elements to be styled. 
 *Declaration: Single rule like color: red;, specifying the property to be styled.
* Properties: Ways to style an HTML element.
* Property Value: Appearance chosen for a given property.
### Syntax Notes:
* Each ruleset is wrapped in curly braces {}.
* Colon : separates property from its value.
* Semicolon ; separates declarations.
* Modifying Multiple Properties: Multiple property values in one ruleset are separated by semicolons, like color: red; width: 500px;.
* Selecting Multiple Elements: You can select and style multiple elements with a single ruleset by separating multiple selectors with commas, like p, li, h1 { color: red; }.
* Different Types of Selectors: There are various types of selectors apart from element selectors, allowing more specific selections.
* DRY = don't repete yourself. Helps keep code clean.

# CSS Box Model Quick Notes

## What is the Box Model?
- The CSS box model is a fundamental concept in web design.
- It describes how elements on a webpage are rendered in terms of boxes or rectangles.
- Each box consists of content, padding, border, and margin.

## Components of the Box Model
1. **Content:** 
   - The actual content of the element, such as text, images, or other media.
2. **Padding:** 
   - The space between the content and the border.
   - It's transparent by default and can be styled with background colors or images.
3. **Border:** 
   - A line that goes around the padding and content.
   - It can have different styles, colors, and widths.
4. **Margin:** 
   - The space between the border and neighboring elements.
   - It creates space between elements on the webpage.

## Visual Representation
- Imagine each HTML element as a rectangular box.
- The width and height of the box are determined by the content width and height, padding, border, and margin.
- The total width of an element is calculated as follows: 
  `Width = content width + padding + border + margin`
- Similarly, the total height of an element is calculated in a similar way.

## Box Model in CSS
- You can adjust the size of an element by setting its width and height properties.
- You can control the padding, border, and margin using corresponding CSS properties (e.g., `padding`, `border`, `margin`).
- The box model properties can be set individually for each side of the box (e.g., `padding-top`, `border-left`, `margin-right`).

## Importance
- Understanding the box model is crucial for designing and laying out web pages.
- It helps in creating visually appealing and well-organized layouts.
- Mastering the box model allows for precise control over spacing, alignment, and overall appearance of elements on a webpage.
