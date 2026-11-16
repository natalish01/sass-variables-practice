# Sass Variables Practice

A small practical task for learning **Sass/SCSS variables**. The page is a simple card with a heading, a paragraph and a button, styled only with SCSS variables. No nesting and no Tailwind.

## Features

- Colors, font and border radius are stored in one place (`_variables.scss`)
- Card is centered on the screen with Flexbox
- Button has a smooth hover effect (color change and slight scale)

## Live
(https://natalish01.github.io/sass-variables-practice/)
## Project Structure

```
sass-variables-practice/
├── index.html
├── scss/
│   ├── _variables.scss
│   └── style.scss
└── css/
    └── style.css
```

## SCSS Variables

| Variable | Purpose |
| --- | --- |
| `$primary-color` | Heading color |
| `$accent-color` | Button color |
| `$hover-color` | Button hover color |
| `$bg-color` | Page background |
| `$text-color` | Text color |
| `$font-main` | Main font |
| `$border-radius` | Rounded corners |

## Technologies

- HTML5
- CSS3
- Sass/SCSS
