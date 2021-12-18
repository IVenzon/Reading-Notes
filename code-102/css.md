# CSS:

CSS (which stands for Cascading Style Sheets) is a language that allows us to specify how our webpage is presented, from the style, layout, colors, etc. It works alongside a structured document, such as an HTML file, and converts its contents into a more visually apealling and usable form.

## Syntax:

CSS is a rule-based language, which means that we are assigning styles (the rules) to certain groups or certain elements in our page. Each rule opens with a selector, which chooses which HTML element we want to style. For instance, if I wanted to change the look of my header, I would use the CSS selector 'h1'.

We then enclose all of our declarations inside of a set of curly brackets {}. These declarations have a property and a value, and depending on which ones you utilize you can change how your element looks. Some examples include 'color', 'font-family', and 'font-size'.

## How to Add CSS:

There are three main ways you can add CSS to your HTML file.

1. External CSS
2. Internal CSS
3. Inline CSS

External CSS means we are linking a .css file to our .html file in the \<head> section of our HTML document. Using an external stle sheet is extremely helpful, as we only need to change one file in order to style our webpage. Note that the .css file must not contain any HTML tags.

Internal CSS means that we define our styles within the \<style> element, which itself is inside the \<head> element. Using internal CSS may be handy if we only need to style a few elements of our page, or if a single HTML page has a unique style.

Inline CSS means that we define our styles within the attributes of our element. While this can be useful if we only need to apply styling to a single element, using inline CSS takes away the many advantages of having a style sheet, as it mixes your content with your presentation. Use this with caution, and sparingly if you must!

## Multiple Style Sheets and Cascading Order:

If multiple style sheets contain different styles for the same element, then whatever style is defined last is what will be implemented. For example, if my external style sheet makes my header blue, but my internal CSS defines my header as orange, if I define my internal CSS **after** linking my external style sheet, then my header will be orange on my webpage.

When there is more than one style specified for an HTML element, the style that takes priority is chosen based on the cascading order, with #1 having the highest priority:

1. Inline CSS
2. External and internal style sheets
3. Browser Default

This means that inline CSS has the highest priority, and will override any external/internal styles you define, as well as the browser default.

## The Color Property:

The 'color' property in CSS sets the text color of your element. Note that this only text color, not the background. Make sure to choose a suitable background color (with 'background-color') such that your text is easy to read.

There are many ways to define what color you want your text to be. Here are some examples.

- The HTML color name (if it has one):

> h1 {color: Tomato;}

- The color's HEX value:

> h1 {color: #ff6347;}

- The color's RGB value:

> h1 {color: rgb(255, 99, 71);}

- The color's HSL value:

> h1 {color: hsl(9, 100%, 64%);}