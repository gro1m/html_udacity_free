# html_udacity_free

Google Chrome > More Tools > Developer Tools

Browser builds tree-like structure (branch like structure with opening and closing tag)

HTML - HyperText Markup Language - the standard markup language used to create web pages.

CSS - Cascading Style Sheets - style sheet language used for describing the look and formatting of a document written in a markup language.

DOM - Document Object Model - a cross-platform and language-independent convention for representing and interacting with objects in HTML (and other markup languages). The nodes of every document are organized in a tree structure, called the DOM tree.

HTML basic word is tag and browser turns it into a tree using DOM.

Basic HTML structure:
```html
<tag>
  content
<\tag>
```
Each tag has a type (paragraph, image, etc.) and can have attributes (e.g.) class) with values

To define the style you use CSS.
Also circle is a rectangular box, defined via border radius in CSS file.

For boxes: use <div>-tag.

HTML elements reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_sectioning
HTML5: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines#The_HTML5_outline_algorithm
CSS reference: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
normalize CSS across different browsers: http://necolas.github.io/normalize.css/

Box-sizing:
```
* {
   outline: 1px solid red !important;
}

* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
} 
```

Flex box:
```

.app {
    display: -webkit-flex;
    display: flex;
}
```

Adding images:
```
<img src="images/app.png" alt="This is a screenshot">
```

Code, Test and Refine:
1. Look for natural boxes
2. Look for repeated styles and semantic elements.
3. Write your HTML.
4. Apply styles (from BIGGEST to smallest)
5. Fix things (different browsers, etc.)

Developer Tools: you can resize stuff change elements, etc. and by refreshing the page, it is back to the original layout.

W3C CSS Validation Service:
verify html: http://validator.w3.org/#validate_by_input
verify css: http://jigsaw.w3.org/css-validator/#validate_by_input

Responsive design principles: different devices use different resolution of screen in pixels.
adaptive design: adapt to how website is used - thumbs on tablets and phones instead of a mouse.
start in top left, left-to-right, then top-to-bottom -> grid-based layout.

Frameworks: collections of CSS classes that make page layout easier to implement

