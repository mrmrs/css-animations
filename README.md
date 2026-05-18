# css-animations

Functional CSS for animations

## Filesize

| File | Size |
|------|------|
| `dist/animations.css` | 1041 bytes |
| `dist/animations.min.css` | 811 bytes (179 Gzipped) |

## Install

```sh
npm install css-animations
```

## Usage

### Import

```css
@import "css-animations";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animations/dist/animations.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animations/dist/animations.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-dir-norm` | `animation-direction: normal;` |
| `.a-dir-rev` | `animation-direction: reverse;` |
| `.a-dir-alt` | `animation-direction: alternate;` |
| `.a-dir-alt-rev` | `animation-direction: alternate-reverse;` |
| `.a-dir-norm-s` | `animation-direction: normal;` |
| `.a-dir-rev-s` | `animation-direction: reverse;` |
| `.a-dir-alt-s` | `animation-direction: alternate;` |
| `.a-dir-alt-rev-s` | `animation-direction: alternate-reverse;` |
| `.a-dir-norm-m` | `animation-direction: normal;` |
| `.a-dir-rev-m` | `animation-direction: reverse;` |
| `.a-dir-alt-m` | `animation-direction: alternate;` |
| `.a-dir-alt-rev-m` | `animation-direction: alternate-reverse;` |
| `.a-dir-norm-l` | `animation-direction: normal;` |
| `.a-dir-rev-l` | `animation-direction: reverse;` |
| `.a-dir-alt-l` | `animation-direction: alternate;` |
| `.a-dir-alt-rev-l` | `animation-direction: alternate-reverse;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-dir-norm-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animations.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animations.css` — formatted
- `dist/animations.min.css` — minified

## License

MIT
