# CSS

- CSS stands for Cascading Style Sheets.
- Cascading means an algorithm or a process, CSS deciding which CSS rule sets will be applied when multiple CSS rule sets target the same element.
- Stylesheet is just a sheet which is used for styling the webpage.
- The current version of CSS language is CSS3.
- CSS language is not only used for styling the HTML files, CSS can also style XML and XHTML files.

## CSS Coding can be done in 3 ways

1. Inline CSS Coding
2. Internal CSS Coding
3. External CSS Coding

---

# CSS Coding Ways

HTML code will be written by using boilerplate. Likewise, CSS coding will be written in 3 ways.

## 1. Inline CSS Coding

The process of writing the CSS code within the same line by using the `style` attribute is known as Inline CSS Coding.

### Limitations

- When multiple elements need the same CSS changes, the developer has to repeat the style codes in each and every line of HTML code.
- When 100 style changes are given inside the same line, the HTML line will become lengthy and the HTML file will become clumsy.

---

To overcome the above limitations, we go for Internal CSS Coding.

## 2. Internal CSS Coding

The process of writing the CSS code within the `<head>` tag using the `<style>` tag by defining CSS rule sets is known as Internal CSS Coding.

### Limitations

1. When we create a big application using Internal CSS, the developer cannot dynamically work with HTML and CSS because of plenty of codes.

2. When a developer wants to work with multiple webpages having the same layout and same design, if Internal CSS is used, the developer has to repeat the CSS codes within every HTML file.

To overcome the above two limitations, we go for External CSS Coding.

> **Note:** Either repetition happens on the same HTML line or repetition happens in HTML files, we go for External CSS Coding.

---

## 3. External CSS Coding

The process of writing the CSS code inside a new CSS file is known as External CSS Coding.

- The external CSS file should contain CSS rule sets.
- It should be created with the `.css` extension.
- To link an external CSS file with an HTML file, we use the `<link>` tag.

The `<link>` tag contains two attributes:

1. `rel`
2. `href`

### rel Attribute

- `rel` stands for relationship.
- We have to pass the relationship between the HTML file and the external file.
- If the external file is a CSS file, we pass `stylesheet`.
- If the external file is an image file that we want to apply as favicon, we pass `icon`.

### href Attribute

- `href` stands for Hypertext Reference.
- We have to pass the relative file path of the external file.
