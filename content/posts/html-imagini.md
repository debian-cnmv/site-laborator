---
title: "HTML - Imagini "
date: "2026-03-14"
tags:
- html
---

### Imagini

O imagine se introduce într-un document html folosind elementul `img`.

#### Atributele de bază

- `src` care precizează calea către fișierul imagine;
- `alt` care permite specificarea unui text alternativ pentru imagine.
- `width` pentru stabilirea *lățimii* imaginii (în pixeli sau procentual);
- `height` pentru stabilirea *înălțimii* imaginii (în pixeli sau procentual).

#### Exemplu

Următoarea secvență încarcă în browser o imagine aflată pe internet (Wikipedia)
utilizând și alte atribute *deprecated* pentru stabilirea unei borduri și pentru
spațiere pe orizontală și veritcală:

```html
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/960px-Tux.svg.png"
		border='5'
		height='50%'
		hspace='10'
		vspace='10'
>
```

Elementele sau atributele *deprecated* au fost eliminate din standardele `HTML` fiind înlocuite
de `CSS`.

O listă a lor poate fi consultată [aici](https://www.tutorialspoint.com/html/html_deprecated_tags.htm).

