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