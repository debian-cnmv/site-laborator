---
title: "Comenzi Linux - II"
date: "2022-03-17"
tags:
- Linux
---

## Obținerea de informații despre o comandă

Pentru a obține *informații de bază* despre o comandă se poate
utiliza comanda `whatis`:

```sh
whatis comandă
```

Majoritatea comenzilor au opțiunile `-h` sau `--help` care permit
obținerea unor informații *mai detaliate*:


```sh
comandă --help
```

sau 

```
comandă -h
```

## Manualul unei comenzi

Informații detaliat despre o anumită comandă se pot obține folosind comanda
`man`:

```sh
man comandă
```

## Exemple

```sh
whatis cal
date --help
calendar -h
man ls
```


