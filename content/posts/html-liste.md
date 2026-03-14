---
title: "HTML - Liste "
date: "2026-03-11"
tags:
- html
---

### Liste ordonate

Se creează folosind elementul `ol` (ordered list) și elementul `li` (list item):

```html
<ol>
    <li>Element
    <li>Element
    ...
</ol>
```

#### Variante de marcatori

Marcatorul implicit este cu cifre arabe (`1.`, `2.`, `3.`, ...).

##### Litere mici

```html
<ol type='a'>
    <li>Element
    <li>Element
    ...
</ol>
```

##### Litere mari

```html
<ol type='A'>
    <li>Element
    <li>Element
    ...
</ol>
```

##### Cifre romane mici

```html
<ol type='i'>
    <li>Element
    <li>Element
    ...
</ol>
```

##### Cifre romane mari

```html
<ol type='I'>
    <li>Element
    <li>Element
    ...
</ol>
```

### Liste neordonate

Se creează folosind elementul `ul` (unordered list) și elementul `li` (list item):

```html
<ul>
    <li>Element
    <li>Element
    ...
</ul>
```
#### Variante de marcatori

Marcatorul implicit este de tipul `disc`.

##### Marcator pătrat

```html
<ul type='square'>
    <li>Element
    <li>Element
    ...
</ul>
```

##### Marcator cerc gol

```html
<ul type='circle'>
    <li>Element
    <li>Element
    ...
</ul>
```
### Liste de definiții

Se creează folosind elementul `dl` (definition list), `dt` (definition term) și `dd` (definition description):

```html
<dl>
    <dt>Termen
    <dd>Definiție

    <dt>Termen
    <dd>Definiție

    <dt>Termen
    <dd>Definiție

    ...
</dl>
```

