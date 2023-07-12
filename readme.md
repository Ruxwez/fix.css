# fix.css

fix.css allows us to set default styles for our web pages.

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
