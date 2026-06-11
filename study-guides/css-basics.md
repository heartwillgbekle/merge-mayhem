# CSS Basics
In order to style the element on a page, CSS uses rule sets that contain specific properties and their values to apply to the elements. Let's take a look at the syntax of a rule set and explore deeper into its meaning.


## CSS Syntax

![CSS Syntax](https://user-images.githubusercontent.com/6511/163082188-24304dfc-0ff0-468b-a6c0-330348d0765a.png)

**Source**: [Anything.codes](http://anything.codes/gdi-intro-html-css/class2.html#/)

- `{}`: In CSS we use the curly brackets `{}` to define a rule set. All rules or declarations must be included inside the brackets.
- Selector: A selector is used to identify the element the CSS rule will be applied to. In the example above, we use an element selector to apply rules to the entire body element. Basic selectors can select all elements, elements by type, class, and id, or by attribute.
- Declaration: Each property and value pair is considered a declaration or rule.


| Selector | Description | Syntax |
|----------|-------------|--------|
| [Universal Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) | This selector uses the `*` symbol to apply styling rules to all elements on the website. | `* { property: value; }` |
| [Type Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) | This selector uses the name of an HTML element to apply styling rules to a specific type of elements | `element { property: value; }` |
| [Class Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | This selector uses the `.` symbol followed by the class name (as identified by the attributes of some elements in the HTML document) to apply styling rules to all elements with the same class name. | `.className { property: value; }` |
| [Id Selector](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) | This selector uses the `#` symbol followed by the id name to apply styling rules to a single element. | `#idName { property: value; }` |
