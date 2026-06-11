# CSS Basics
If an element has two or more conflicting CSS rules, the website will determine the style rule by the specificity of the selector used in the rule set. Since an id selector affects only 1 element and a class selector affects more than one element, this means that a rule in an id selector rule set would trump the rule in a class selector. So in short, `id > class > type > universal`.

There are many rules in distinguishing between the specificity of a rule. In fact, developers have created a formula in order to calculate specificity to help browsers determine which rule sets to apply when there are conflicts. You can read about [CSS specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity) on the MDN Docs website.

In some cases, a particular element may have multiple rule sets that can apply. Let's take a look at an example. For this example, let's assume that we have an HTML `p` element with an id name of `attribution`.

```css
p {
    font-size: 12px;
    color: black;
}

#attribution {
    font-size: 9px;
}
```

In this example, the attribution `p` element will have adopt the following properties:

- `font-size: 9px;`
- `color: black;`
  - Property: A property is the type of style on an HTML element. This includes color, positioning, font, border, etc. Check out MDN Docs for a full list of CSS properties.
  - Value: This is the exact style you want to implement on your website. In the example above, we want to use the color `navy` in the `body` of our website.
  - **Note:** Each property has its own set of valid values. For example, The `color` property can take values by name (`blue`, `green`, etc), Hex format (`#FFFFFF`), or RGB colors (`rgb(255,255,255)`).
- `:`: The colon symbol is used to separate the property and value.
- `;`: The semicolon symbol is used to end a declaration or rule.

There are many great reference materials to read about different CSS properties and values. We highly recommend checking out [CSS Reference's free visual guide to CSS](https://cssreference.io/).

## CSS Selectors

Let’s take a step back and review different CSS selectors and their associated syntax. For this we will focus on the basic selectors, but we highly recommend you check out MDN Docs for a [full list of CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors).
