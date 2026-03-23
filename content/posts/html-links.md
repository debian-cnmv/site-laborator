---
title: "HTML - Hiperlegături"
date: "2026-03-23"
tags:
- html
---

### Hiperlegături

Se creează folosind elementul `a` cu atributul `href` pentru a preciza destinația:

```html
<a href='adresa-destinației'>
    Text/imagine care activează hiperlegătura
</a>
```

#### Exemplu

```html
<a href='https://cnmvslobozia.ro'>
    Mergi la pagina CNMV Slobozia
</a>

```

### Ancore

Se creează folosind elementul `a` cu atributul `name`:

```html
<a name='nume-ancoră'>
    Conținut
</a>
```

Pentru a crea o hiperlegătură către o ancoră se folosește ca destinație numele
acesteia precedat de caracterul `#`:

```html
<a href='#nume-ancoră'>
    Text/imagine care activează hiperlegătura
</a>
```

#### Exemplu

```html
<a name='titlu'><h1>Un titlu</h1></a>
...
...
...
<a href='#titlu'>Mergi la titlu!</a>
```

