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
