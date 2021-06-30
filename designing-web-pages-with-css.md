[< Back](https://paulmichaelarmstrong.github.io/reading-notes/)

# Designing Web Pages With CSS
Cascading Style Sheets – better known as CSS – is what creates the visual looks of a webpage. If HTML is the structure of the house, CSS is the paint, carpets, finishes, furniture, and art. CSS lets you tell a browser how it should render an HTML file so you can control how fonts, colors, layout, and even animation is displayed to a user. 

A CSS rule is going to be made up of the HTML selector that is being rendered and then the styling **declaration** you wish to apply to a **property** with a **value**:

```
h1 {
    font-size: 6em;
}
```

In this example, `h1` is the declaration, `font-size` is the property, and `5em` is the value. The declaration sits outside the curly braces, and the property and value are nested inside.

## Adding CSS To Your Web Pages
CSS can be added three different ways: externally, internally, and inline. External style sheets impact the look and feel of the entire website, so setting `h1` to `font-size: 6em` on your external style sheet means that every single instance of an `h1` on your web page will render in 6em if you connect the page in the `<head>` by adding  `<link rel="stylesheet" href="mystyle.css">` after the expernal style sheet link. Internal style sheets are used when you want a single page to have specific styling; you to this by adding a `<style>` element in the `<head>`. Lastly, you can use inline CSS to apply styling to a single element by applying `style=""` after the HTML tag.


***

**Sources:**
- [MDN Web Docs - What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [W3 Shools - How To Add CSS](https://www.w3schools.com/css/css_howto.asp)
- [W3 Schools - CSS Color Property](https://www.w3schools.com/cssref/pr_text_color.asp)
- [MDN Web Docs - CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [Meyer Web - CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

[< Back](https://paulmichaelarmstrong.github.io/reading-notes/)