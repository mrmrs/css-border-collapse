# css-border-collapse

Functional CSS for border-collapse

## Filesize

| File | Size |
|------|------|
| `dist/border-collapse.css` | 717 bytes |
| `dist/border-collapse.min.css` | 541 bytes (154 Gzipped) |

## Install

```sh
npm install css-border-collapse
```

## Usage

### Import

```css
@import "css-border-collapse";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-border-collapse/dist/border-collapse.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-border-collapse/dist/border-collapse.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.bc-collapse` | `border-collapse: collapse;` |
| `.bc-separate` | `border-collapse: separate;` |
| `.bc-i` | `border-collapse: inherit;` |
| `.bc-collapse-s` | `border-collapse: collapse;` |
| `.bc-separate-s` | `border-collapse: separate;` |
| `.bc-i-s` | `border-collapse: inherit;` |
| `.bc-collapse-m` | `border-collapse: collapse;` |
| `.bc-separate-m` | `border-collapse: separate;` |
| `.bc-i-m` | `border-collapse: inherit;` |
| `.bc-collapse-l` | `border-collapse: collapse;` |
| `.bc-separate-l` | `border-collapse: separate;` |
| `.bc-i-l` | `border-collapse: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.bc-collapse-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/border-collapse.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/border-collapse.css` — formatted
- `dist/border-collapse.min.css` — minified

## License

MIT
