# css
CSS on steroids

styles.css
```css
body {
  margin: 0;
}

body h1 {
  content: 'Hello';
}

body my-component[onclick=alert('Hello')] {
  content: var(--clickCount);
}

body canvas {
  camera: gyro;
  data: 'https://sketchfab.com/api/v1/models/suzanne.obj'
}
```

### `css styles.css` => index.html
- CSS file is left as it is
- You can edit it in the dev tools of your browser
- Style changes will appear live
- Structural changes require you to start a watcher to see them live
- Changes to index.html from outside will update your CSS (two-way reaction)
- Take the CSS with you, HTML not needed

Lifecycle, events and states (:hover etc).

You have components and components pass down properties and emit events.

- Tree Navigation (Selectors)
  - Element
  - id
  - class
  - attribute
  - state
  - pseudo class
  - descendent
  - direct child
  - :root
- Variables (Custom Properties)
  - --my-variable
  - var(--my-variable)
- Units
  - px
  - em
  - lh
  - vh
  - %
- Files
  - @import
- Responsiveness (Media Queries)
  - @media
- JS
  - document.styleSheets.item(i).rules.item(j).styleSheet
  - element.style
  - pointer-events
  - touch-action
- Geometry (box-sizing)
  - margin
  - border
  - padding
  - width
  - height
  - border-radius
- Position (position)
  - left
  - right
  - top
  - bottom
  - z-index
- Layout (display)
  - align-items
  - justify-content
  - flex-direction
- Color
  - background
  - color
  - border-color
  - box-shadow
- Graphics
  - Gradients
  - filter
  - transform
  - perspective
  - SVG
- Animation
  - transition
  - animation
  - @keyframes
- Scrolling (overflow)
  - scroll-behavior
  - scroll-snap
  - scroll-margin
  - scroll-padding
  - background-attachment
- Typography
  - font-family
  - font-variant
  - font-weight
  - font-size
  - letter-spacing
  - line-height
  - word-break
  - word-spacing
  - white-space
  - text-align
  - text-decoration
  - text-indent
  - text-overflow
  - text-shadow
  - text-transform
  - cursor
  - caret-shape
  - caret-color
