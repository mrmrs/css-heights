# css-heights

Functional CSS for heights

## Filesize

| File | Size |
|------|------|
| `dist/heights.css` | 258 bytes |
| `dist/heights.min.css` | 190 bytes (96 Gzipped) |

## Install

```sh
npm install css-heights
```

## Usage

### Import

```css
@import "css-heights";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-heights/dist/heights.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-heights/dist/heights.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ht-auto` | `height: auto;` |
| `.ht-auto-ns` | `height: auto;` |
| `.ht-auto-m` | `height: auto;` |
| `.ht-auto-l` | `height: auto;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ht-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/heights.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/heights.css` — formatted
- `dist/heights.min.css` — minified

## License

MIT
