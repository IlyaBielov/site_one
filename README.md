# Asphalt 9: Legends — fan site

A small static fan site about the racing game **Asphalt 9: Legends**, built as practice for an
HTML5 & CSS3 course. Two pages, plain HTML and CSS, no build step and no JavaScript.

## Pages

| Page | File | What's on it |
|------|------|--------------|
| Home | [`index.html`](index.html) | Hero image and a short intro to the game |
| About | [`html/about.html`](html/about.html) | Gameplay, development and release history |

## Run it

Open `index.html` in a browser — that's it. Or serve the folder locally:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Structure

```
.
├── index.html          # Home page
├── html/
│   └── about.html      # About page
├── css/
│   └── style.css       # Shared styles for both pages
└── images/
    ├── logo.png
    └── main-content-image.jpg
```

## What it practices

- Semantic HTML5 layout: `header`, `nav`, `main`, `article`, `footer`
- A navigation menu built from a list, with flexbox and an active-page state
- A fixed-width centred layout (755 px max) that shrinks to fit phone screens
- One shared stylesheet with BEM-style class names (`menu__item`, `menu__link--active`)

## Credits

- The About page text is adapted from
  [Wikipedia — Asphalt 9: Legends](https://en.wikipedia.org/wiki/Asphalt_9:_Legends), licensed under
  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- *Asphalt*, the logo, the game screenshots and the car shown are trademarks and property of
  Gameloft and their respective owners. This is a non-commercial learning project, not affiliated
  with Gameloft.

Made by [Ilya Bielov](https://www.facebook.com/MrBiela).
