# HW10


```markdown
# HTML and CSS Code Explanation

This repository contains two HTML files and their corresponding CSS styles. Below is a breakdown of the code and its functionality.

## File 1: `index.html`

### HTML Structure
- The first HTML file is a simple webpage with a title, a paragraph, and a link.
- It uses an external stylesheet (`style.css`) for styling.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HW-9</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1 class="title">Iste odit similique sit</h1>
    <p class="text">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Obcaecati
      commodi,
      <span>veritatis nihil alias iste</span> odit similique sit eius optio
      veniam, impedit cumque fuga facere labore quo id necessitatibus quaerat
      rerum.
    </p>
    <a href="style.css" class="link">Читати далі...</a>
  </body>
</html>
```

### CSS Styling (`style.css`)
- **`span`**: Applies a line-through text decoration to the content inside `<span>` tags.
- **`.text`**: Adds a 100px indent to the first line of the paragraph and sets the line height to 1.7.
- **`.link`**: Adds a red text shadow to the link.

```css
span {
    text-decoration: line-through;
}

.text {
    text-indent: 100px;
    line-height: 1.7;
}

.link {
    text-shadow: 2px 2px 4px red;
}
```

---

## File 2: `index2.html`

### HTML Structure
- The second HTML file is a blog post layout with a title and two paragraphs.
- It uses an external stylesheet (`style2.css`) for styling and imports the "Unna" font from Google Fonts.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link
      href="https://fonts.googleapis.com/css2?family=Unna:ital,wght@0,400;0,700;1,400;1,700&display=swap"
      rel="stylesheet"
    />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <article class="post">
      <h1 class="post-title">Lorem ipsum dolor sit amet</h1>
      <p class="post-text">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Obcaecati
        commodi, veritatis nihil alias iste odit similique sit eius optio
        veniam, impedit cumque fuga facere labore quo id necessitatibus quaerat
        rerum.
      </p>

      <p class="post-text">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Obcaecati
        commodi, veritatis nihil alias iste odit similique sit eius optio
        veniam, impedit cumque fuga facere labore quo id necessitatibus quaerat
        rerum.
      </p>
    </article>
  </body>
</html>
```

### CSS Styling (`style2.css`)
- **`.post-title`**: Centers the title text.
- **`.post-text`**: Applies the "Unna" font, sets the font size to 20px, changes the text color to orange (`#F67103`), and makes the text bold.
- **`.post-text:first-of-type`**: Aligns the first paragraph to the right and preserves whitespace.
- **`.post-text:last-of-type`**: Justifies the text of the last paragraph and prevents word breaks.

```css
.post-title {
    text-align: center;
}

.post-text {
    font-family: 'Unna', serif;
    font-size: 20px;
    color: #F67103;
    font-weight: bold;
}

.post-text:first-of-type {
    text-align: right;
    white-space: pre-wrap;
}

.post-text:last-of-type {
    text-align: justify;
    word-break: keep-all;
}
```

---

## How to Use
1. Clone this repository.
2. Open the `index.html` or `index2.html` file in your browser to view the webpages.
3. Modify the HTML or CSS files as needed for your project.

## Dependencies
- Google Fonts: The "Unna" font is imported from Google Fonts for use in `index2.html`.

---

Feel free to explore and customize the code!

