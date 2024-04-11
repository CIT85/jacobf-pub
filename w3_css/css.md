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