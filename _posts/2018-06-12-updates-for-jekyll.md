**Aprite questo .md con Typora per vedere bene tutti gli snippet di codice**

## Metatags

`---`

`title: "Titolo del post" categories:`

`- A scelta tra "2016 COST Action" e "2017 COST Action"`

`tags:`

`- keywords presenti nel report`

`- una`

`- per`
  
`- riga`

`---`

## Sottotitolo progetto
Inserire sotto i meta tags una riga con il sottotitolo (seconda parte del titolo). Se non presente, usare la prima riga del report.

Esempio: `*Descrizione del progetto*`

## Team
Ogni riga così formattata:

`**Project leader:** Charles van den Heuvel`

con un doppio a capo dopo per i paragrafi

## Titoli
Non scendere sotto H4 (è già molto piccolo, da sistemare in CSS)

## Link (references, bibliografia...)
Sintassi:
`[Link](http://url.com)`

Risultato: [Link](http://url.com)

## Immagini
Sintassi: `![Nome immagine]({{ site.url }}{{ site.baseurl }}/assets/images/cartella-gruppo/nome-immagini-no-spazi.png)`

Risultato (immagine non esistente):
![Nome immagine]({{ site.url }}{{ site.baseurl }}/assets/images/cartella-gruppo/nome-immagini-no-spazi.png)

## Nome del post

`YYYY-MM-DD-titolo-del-post.md`