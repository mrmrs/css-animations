# css-animations

Functional CSS for animations

## Filesize

| File | Size |
|------|------|
| `dist/animations.css` | 1225 bytes |
| `dist/animations.min.css` | 995 bytes (183 Gzipped) |

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
| `.a-direction-normal` | `animation-direction: normal;` |
| `.a-direction-reverse` | `animation-direction: reverse;` |
| `.a-direction-alternate` | `animation-direction: alternate;` |
| `.a-direction-alternate-reverse` | `animation-direction: alternate-reverse;` |
| `.a-direction-normal-s` | `animation-direction: normal;` |
| `.a-direction-reverse-s` | `animation-direction: reverse;` |
| `.a-direction-alternate-s` | `animation-direction: alternate;` |
| `.a-direction-alternate-reverse-s` | `animation-direction: alternate-reverse;` |
| `.a-direction-normal-m` | `animation-direction: normal;` |
| `.a-direction-reverse-m` | `animation-direction: reverse;` |
| `.a-direction-alternate-m` | `animation-direction: alternate;` |
| `.a-direction-alternate-reverse-m` | `animation-direction: alternate-reverse;` |
| `.a-direction-normal-l` | `animation-direction: normal;` |
| `.a-direction-reverse-l` | `animation-direction: reverse;` |
| `.a-direction-alternate-l` | `animation-direction: alternate;` |
| `.a-direction-alternate-reverse-l` | `animation-direction: alternate-reverse;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-direction-normal-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animations.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animations.css` — formatted
- `dist/animations.min.css` — minified

## License

MIT
