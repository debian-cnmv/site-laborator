---
title: "HTML - Structura unui document și a unui site"
date: "2026-03-11"
tags:
- html
---

### Structura

Un document `HTML`(**H**yper**T**ext **M**arkup **L**anguage) are următoarea structură:

```html
<!DOCTYPE html>
<html lang='ro'>
<head>
    <title>Titlu</title>.
    <meta charset='utf-8'>
</head>
<body>
    <!--
    Conținutul documentului
    -->
</body>
</html>
```

#### Observații

- Un document `HTML` este un *fișier text* cu extensia `.html`
- Este format dintr-un *corp* precedat de un *antet*
- Antetul trebuie să conțină obligatoriu un *titlu*
- Titlul este redat în *bara de titlu* a browserului sau pe fila tabului
- Elementul meta indică browserului că documentul va folosi codificarea `utf-8` atfel
  încât diacriticele românești să fie recunoscute
- Limba folosită în document se specifică folosind atributul `lang` al elementului `html`
- Elementul `<!--  -->` permite introducerea unor *comentarii* în cod 


### Structura unui site

Un site este un **folder** pe un server de web care conține diverse resurse:

- documente html
- fișiere imagine
- fișiere video
- fișiere de tip document

Este important ca folderul să conțină un fișier numit `index.html` care este **pagina principală** a sitului.


