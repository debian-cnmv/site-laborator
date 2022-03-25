---
title: "Conectarea la serverul MySQL"
date: "2022-01-21"
tags:
- mysql
---

### Conectarea la server

Conectarea se face după un login cu succes la serverul `Linux`:

![Conectare](/img/login1.png)

folosind comanda

```sh
mysql -u user -p
```

ca în exemplul de mai jos în care numele de utilizator este `ariton`:
![Conectare](/img/login2.png)

### Selectarea bazei de date de lucru

După conectare trebuie selectată *baza de date* de lucru al cărei nume este
același cu numele de utilizator, folosind comanda:

```sql
use user_name
```

![Conectare](/img/login3.png)


### Afișarea tabelelor din baza de date


```sql
show tables;
```

![Conectare](/img/login4.png)


### Deconecarea de la serverul `MySQL`


```sql
quit
```

![Conectare](/img/login5.png)
