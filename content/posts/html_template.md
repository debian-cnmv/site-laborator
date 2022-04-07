---
title: "Structura unui document HTML"
date: "2022-04-07"
tags:
- html
---


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

### Observații

- Un document `HTML` este un *fișier text* cu extensia `.html`
- Este format dintr-un *corp* precedat de un *antet*
- Antetul trebuie să conțină obligatoriu un *titlu*
- Titlul este redat în *bara de titlu* a browserului sau pe fila tabului
- Elementul meta indică browserului că documentul va folosi codificarea `utf-8` atfel
  încât diacriticele românești să fie recunoscute
- Limba folosită în document se specifică folosind atributul `lang` al elementului `html`
- Elementul `<!--  -->` permite introducerea unor *comentarii* în cod 


