# CSS Notes

## Box Shadow Property

### What is `box-shadow`?
- `box-shadow` is a CSS property.
- It is used to:
  - Apply a shadow to an element.
  - Create a Z-axis (depth) effect.
  - Make an element glow.

### Syntax

#### Outside Shadow
```css
box-shadow: horizontal-offset vertical-offset blur-radius spread-radius color;
```

Example:
```css
box-shadow: 5px 5px 10px 2px black;
```

#### Inside Shadow
```css
box-shadow: inset horizontal-offset vertical-offset blur-radius spread-radius color;
```

Example:
```css
box-shadow: inset 2px 2px 8px gray;
```

### Properties

| Property | Description |
|----------|-------------|
| Horizontal Offset | Moves the shadow on the X-axis. |
| Vertical Offset | Moves the shadow on the Y-axis. |
| Blur Radius | Controls the blur of the shadow. |
| Spread Radius | Controls the size of the shadow. |
| Color | Specifies the shadow color. |
| `inset` | Creates the shadow inside the element. |

---

# Font Properties

## 1. `font-size`

Used to control the size of text.

```css
font-size: 75px;
```

---

## 2. `font-weight`

Used to make text bold or lighter.

```css
font-weight: bold;
font-weight: bolder;
font-weight: normal;
```

---

## 3. `font-style`

Used to make text italic.

```css
font-style: italic;
font-style: normal;
```

---

## 4. `font-variant`

Used to convert text into small capital letters.

```css
font-variant: small-caps;
font-variant: normal;
```

---

# Text Properties

## 1. `text-align`

Used to align text.

```css
text-align: left;
text-align: center;
text-align: right;
```

---

## 2. `text-decoration`

A shorthand property used to decorate text.

### Individual Properties

### `text-decoration-line`

Defines the decoration line.

```css
text-decoration-line: underline;
text-decoration-line: overline;
text-decoration-line: line-through;
```

---

### `text-decoration-thickness`

Controls the thickness of the decoration line.

```css
text-decoration-thickness: 3px;
```

---

### `text-decoration-style`

Defines the style of the decoration line.

```css
text-decoration-style: solid;
text-decoration-style: dotted;
text-decoration-style: dashed;
text-decoration-style: double;
text-decoration-style: wavy;
```

---

### `text-decoration-color`

Sets the color of the decoration line.

```css
text-decoration-color: red;
```

---

### Shorthand

```css
text-decoration: underline 3px solid blue;
```

---

## 3. `text-underline-offset`

Creates space between the text and underline.

```css
text-underline-offset: 5px;
```

---

## 4. `text-transform`

Changes the letter casing.

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

---

## 5. `text-shadow`

Adds a shadow to text.

**Note:** Text shadow can only be applied outside the text.

### Syntax

```css
text-shadow: horizontal-offset vertical-offset blur-radius color;
```

Example:

```css
text-shadow: 2px 3px 0px black;
```

---

## 6. `text-indent`

Adds indentation to the first line of a paragraph.

```css
text-indent: 50px;
```

---

## 7. `letter-spacing`

Creates spacing between letters.

```css
letter-spacing: 3px;
```

---

## 8. `word-spacing`

Creates spacing between words.

```css
word-spacing: 10px;
```

---

## 9. `line-height`

Controls spacing between lines.

```css
line-height: 1.8;
```

---

# Font Family

The `font-family` property is used to specify the font of text.

Fonts can be added in three ways:

1. Using the `font-family` property
2. Using Google Fonts
3. Using downloaded font files

---

## 1. Using `font-family`

```css
font-family: Arial, sans-serif;
```

---

## 2. Google Fonts

Google Fonts can be added in two ways.

### Method 1: Using `<link>`

Copy the `<link>` tag from Google Fonts and paste it inside the `<head>` section.

```html
<link href="https://fonts.googleapis.com/..." rel="stylesheet">
```

---

### Method 2: Using `@import`

Paste the import statement at the top of your CSS file.

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
```

---

## 3. Using Downloaded Fonts

Fonts can also be downloaded from websites like:

- Google Fonts
- Befonts.com

### Supported Formats

- `.otf` (OpenType Font)
- `.ttf` (TrueType Font)

### Steps

1. Download the font.
2. Extract the ZIP file.
3. Copy the required font file.
4. Paste it inside your project's `assets/fonts/` folder.

Example:

```
project/
│
├── assets/
│   └── fonts/
│       ├── ProductSans-Regular.ttf
│       ├── ProductSans-Bold.ttf
│       └── NeueMachina-Regular.otf
```

---

## Using `@font-face`

Use `@font-face` to load local fonts.

```css
@font-face {
    font-family: "ProductSans";
    src: url("./assets/fonts/ProductSans-Regular.ttf");
}

body {
    font-family: "ProductSans";
}
```

---

# Summary

## Box Shadow
- Outside shadow
- Inside shadow (`inset`)
- Creates depth and glow effects

## Font Properties
- `font-size`
- `font-weight`
- `font-style`
- `font-variant`

## Text Properties
- `text-align`
- `text-decoration`
- `text-underline-offset`
- `text-transform`
- `text-shadow`
- `text-indent`
- `letter-spacing`
- `word-spacing`
- `line-height`

## Font Family
- Default fonts
- Google Fonts
- Downloaded fonts
- `@font-face`

---
