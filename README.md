# Blog | Núcleo de Tecnologia

## Como rodar o projeto localmente

`yarn install`

`yarn dev`

## Como criar uma build de produção

`yarn build`

## Customização

`data/site.json`

### Homepage

`src/index.md`.

```
---
layout: home
title: 'Eleventy Duo'
---

Contents
```

### About page

`src/sobre.md`.

```
---
title: About Aidan Charles Powell
layout: about.njk
name: Aidan Charles Powell
image: '/images/me.jpeg'
---

Contents
```

### Blog posts

`src/posts`

```
---
title: Even yet another post with rich media
date: '2020-12-24'
tags: [demo-content, media]
decription: The last person we talked to said this would be ready action item, and what do you feel you would bring to the table if you were hired for this position bells and whistles. #optional
---

Contents
```

### Generic pages

```
---
layout: base
permalink: /generic-page
title: Generic page
---

Contents
```

## Stack

- Eleventy Duo (https://github.com/yinkakun/eleventy-duo)
- Eleventy for site generation (obviously)
- Webpack for asset bundling
- PostCSS for CSS processing
- Autoprefixer for vendor prefixing CSS
- PostCSS Preset Env for transpiling css
- PurgeCSS for unused CSS removal
- CSSNano for CSS minification

## License

This project is licensed under the MIT License.

Isn't Jamstack beautiful?
