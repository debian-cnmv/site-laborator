---
title: "setw și setfill"
date: "2022-03-18"
tags:
- C++
---

### Afișarea unei valori întregi

O valoare întreagă se poate afișa *aliniată la dreapta* pe un număr specificat
de poziții folosind `setw`:


```cpp
#include<iomanip>
// ...
int x;
cout<<'|'<<setw(10)<<x<<'|';
```

De exemplu, dacă `x` este `2022`, pe ecran se va afișa:

```
|      2022|
```

Caracterul implicit de *umplere* la stânga este *spațiul* care poate fi
schimbat cu `setfill` astfel:

```cpp
cout<<'|'<<setw(10)<<setfill('#')<<x<<'|';
```

iar rezultatul este:

```
|######2022|
```

