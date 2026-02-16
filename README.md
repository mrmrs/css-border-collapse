# css-border-collapse

Functional CSS for border-collapse

## Filesize

| File | Size |
|------|------|
| `dist/border-collapse.css` | 825 bytes |
| `dist/border-collapse.min.css` | 649 bytes (156 Gzipped) |

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
| `.border-collapse` | `border-collapse: collapse;` |
| `.border-separate` | `border-collapse: separate;` |
| `.border-collapse-inherit` | `border-collapse: inherit;` |
| `.border-collapse-s` | `border-collapse: collapse;` |
| `.border-separate-s` | `border-collapse: separate;` |
| `.border-collapse-inherit-s` | `border-collapse: inherit;` |
| `.border-collapse-m` | `border-collapse: collapse;` |
| `.border-separate-m` | `border-collapse: separate;` |
| `.border-collapse-inherit-m` | `border-collapse: inherit;` |
| `.border-collapse-l` | `border-collapse: collapse;` |
| `.border-separate-l` | `border-collapse: separate;` |
| `.border-collapse-inherit-l` | `border-collapse: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.border-collapse-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/border-collapse.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/border-collapse.css` — formatted
- `dist/border-collapse.min.css` — minified

## License

MIT
