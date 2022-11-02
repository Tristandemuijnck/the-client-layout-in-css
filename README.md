# Layout in CSS

## :pencil2: Beschrijving!

Een oefening in document layout met CSS.

<img src="https://user-images.githubusercontent.com/43402897/199609157-7f5ebeda-e86b-411b-bfd9-cc571b551245.png" width="500">




## :mag: Kenmerken

:page_facing_up: HTML

Voor de layout maak ik gebruik van: 

  `<main>`
  `<nav>`
  `<footer>`
  
:art: CSS

Een belangrijk css onderdeel tijdens deze opdrachten is het gebruik van grid:

```
body{
        display: grid;
        grid-template-rows: 1fr 5fr 1fr;
        grid-template-columns: 1fr 15fr;
        gap: 0.6em;
        grid-template-areas: 
        "head head"
        "navigatie content"
        "footer footer";
      }

      header{
        grid-area: head;
      }

      nav{
        grid-area: navigatie;
      }

      main{
        grid-area: content;
      }

      footer{
        grid-area: footer;
      }
```


## 🔴 Live versie

De live versie van dit project is hieronder te vinden:

https://tristandemuijnck.github.io/the-client-layout-in-css/src/
