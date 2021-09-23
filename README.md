# css
CSS on steroids

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

css.compile() => index.html

Lifecycle, events and states (:hover etc).

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
  - document.styleSheets.item(i).rules.item(i).styleSheet
  - element.style
  - pointer-events
- Geometry (box-sizing)
  - margin
  - border
  - padding
  - width
  - height
- Position (position)
  - left
  - right
  - top
  - bottom
- Color
  - background
  - color
  - border-color
  - box-shadow
- Graphics
  - filter
  - transform
  - SVG
  - Gradients
- Animation
  - animation
  - transition
- Layout (display)
  - align-items
  - justify-content
  - flex-direction
- Scrolling (overflow)
  - scroll-behavior
  - scroll-snap
  - scroll-margin
  - scroll-padding
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
