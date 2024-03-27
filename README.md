This is my personal website. Everything is basically from the [Particle Jekyll Theme](https://github.com/nrandecker/particle).

- The things (text and images and such) are all in _includes/
- The styles are in src/styles/

## Adding a New Section

Add the section in `_layouts/default.html`

Add the html file to `_includes/`

Add a link in `_includes/header.html`

Add the scss to `src/styles/`

Add the scss in `src/styles/main.scss`

## Commands

Run `sass src/styles/main.scss assets/css/main.css` to produce the .css

Run `set JEKYLL_ENV=production | jekyll build` to produce the _site

Run `uglifyjs src/js/app.js -o assets/js/main.js` to minify JS

Run `jekyll serve` to serve

## Icons

Devicons are [here](https://devicon.dev/).

Font Awsome is [here](https://fontawesome.com/v4/icons/).
