# fix.css

This npm style package provides a basic set of CSS rules to enhance the appearance and behavior of HTML elements on a website. The included rules address the box-sizing model, maximum width for images, 3D transformation of specific elements, and adjustmen

## NPM 
```
npm install --save fix.css
```

## What does it do?
- Sets the "border-box" box model for all HTML elements.
- Makes all elements and pseudo-elements inherit the box model of the parent element.
- Limits the width of all images to 100% of their container.
- Applies a 3D transformation to improve the performance of animations and transitions in: `section, main, header, footer`.
- Remove outline on links when receiving focus.
- Disables the ability to drag images inside links in WebKit based browsers.
