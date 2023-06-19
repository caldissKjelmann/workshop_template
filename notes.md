https://gohugo.io/getting-started/installing



https://themes.gohugo.io//theme/hugo-book/docs/example/table-of-contents/without-toc/



Brug Learn-tema: https://learn.netlify.app/en/



Tag inspiration fra Carpentries: https://github.com/carpentries/lesson-example/blob/gh-pages/_episodes/02-tooling.md

- https://carpentries.github.io/lesson-example/







**Valgfag**

Enkelt repo med beskrivelser, kurser og litteratur

Links til de enkelte workshops



https://jmalarcon.github.io/markdowntables/



## Script til notebooks

- Brug H1 og "kapitel" til at lave kapitel
  - Alle H1 med "afsnit" under denne laves til afsnit i kapitlet
- Øvrige H1 som enkeltstående sider



**Kapitler**

- Eksempel: "# {#Kapitel}Python sproget"
- Variabel til at holde styr på antal kapitler/vægt + pre
- Skal oversættes til:

```
title: Python sproget
type: chapter
weight: 1
pre: "<b>1. </b>"
```

- Heading skal bevares (uden {#Kapitel})
- Mappe dannes med navn efter kapitelnavn (pastet sammen med "-")
- Fil gemmes som "_index.md" i den nye mappe



**Afsnit**

- Eksempel: "# {#Afsnit}Funktioner"
- Variabel til at holde styr på vægt
- Skal oversættes til:

```
title: Funktioner
weight: 1
```

- Heading fjernes
- Fil gemmes som "funktioner.md" i aktuelle kapitelmappe