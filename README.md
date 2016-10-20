# minimal.css

An opinionated, inheritance focused alternative to CSS resets

[**Demo** (lukebrooker.com/minimal.css)](http://lukebrooker.com/minimal.css)

## Why Use This?

When creating web applications with a component based approach, it's rare that you want to keep default browser styles on many elements.

Rather than having to create reset styles for each component, the approach of minimal.css is to have a predictable starting point with minimal per component resets. It also allows elements in an application to be used more semantically. For example, a button element can be used in the correct context even if you want it to look like a link, as by default most elements only have the styles set on the root, nothing else.

The other aim of minimal of minimal.css is to take advantage of inheritance as much as possible. For example, if you declare a font-family or color on the root of your document, it will be inherited by every single element by default. With this expectation, your component styles become even simpler and flexible. You can add just a `border: 2px solid` to a `<button>` and it will use the root color for the text and border.

## Goals

- A predictable base for elements in application development
- Allow for easy semantic use of HTML tags without worrying about reseting styling
- Components require as little additional CSS as possible (Especially useful when taking an "atomic" approach to CSS)
- Components are adaptive to their context when required (inheritance)

## Comparisons

[**Check out the Demo**](http://lukebrooker.com/minimal.css) that includes comparisons with other popular resets.

## To Do

- [ ] Ensure input fields with placeholders keep a consistent height across browsers

## Acknowledgements

Many of the browser normalizations are taken from the excellent [normalize.css](https://github.com/necolas/normalize.css/) & [sanitize.css](https://github.com/jonathantneal/sanitize.css)
