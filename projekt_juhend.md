---
layout: page
---

Aine läbimiseks tuleb läbi viia kas praktiline andmeanalüüs ning kirjutada saadud tulemustest populaarteaduslikus vormis artikkel või teha Shiny rakendus. Projekti tulem on illustreeritud asjakohaste joonistega ning on arusaadav ka mitte-statistikule. Projekt tuleb esitada paaristööna. Tulemusi on vaja esitleda suulisel kaitsmisel.

Inspiratsiooniks saab vaadata [2017.](https://andmeteadus.github.io/2017/projektid/), [2018.](https://andmeteadus.github.io/2018/projektid/) ja  [2019.](https://andmeteadus.github.io/2019/projektid/) aasta projekte. 

### Tähtajad 

* Teema valimine - 25.03.2020
* Projekti esitamise tähtaeg - 13.05.2020 kell 10.15.
* Projekti tulemuste müümine (st esitlus) - 20.05.2020 kell 10:15 ja 27.05.2020 kell 10:15 Delta majas aud. 2030

Mõned meie välja pakutud teemad on [siin](https://docs.google.com/spreadsheets/d/1pWFMwq3mPY0OXMGVlFcxJIqnfTv41c8Xvr4rNEOGfpg/edit#gid=0). Teema registreerimine toimub Moodle's Projekti foorumis. Lisa sinna projektiteema, andmete allikas, projekti tegijad ja paari lauseda, mida hakkate tegema/analüüsima/lahendama.

### Mida on vaja esitada?

**a1. Artikkel**

Valminud populaarteaduslik artikkel tehakse avalikuks [aine veebilehel](../projektid/).

Vaja on esitada märgenduskeeles Markdown kirjutatud artikkel.
Kuna aine veebilehe postitused on kirjutatud Markdownis, siis on lihtsam projekte veebilehele lisada, kui need on tehtud Markdownis.
Näiteks selle sama lehe lähtekoodi näed [siit](https://raw.githubusercontent.com/andmeteadus/2020/gh-pages/projekt_juhend.md).

Artikli puhtandi võid kirjutada näiteks RStudios, aga see fail ei tohi sisaldada R-i koodi.
Joonise lisamiseks salvesta see eraldi pildifailina ja lisa see pilt Markdownis kirjutatud artiklisse näiteks nii:

```
![](joonis1.png)
```

aga mitte nii:

```
ggplot(data, aes(x, y)) + geom_point()
```

Abiks on järgmised [Markdowni näpunäited](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images).

**a2. Rakendus**

Ka valminud Shiny rakendused teeme veebis kättesaadavaks. Esitada tuleb nii R-i kood(id) kui ka kasutatud andmetabelid.

**b. Kood**

Vaja on esitada andmeanalüüsi R-i kood.

Selle eesmärgiks on veenduda, et analüüs on reprodutseeritav. 

### Hindamine

* Kas populaarteaduslik artikkel / rakendus on põnev ja selge?
* Kas visualisatsioonid on atraktiivsed ja annavad vastuse uuritud küsimusele?
* Kas andmeanalüüs on reprodutseeritav?
