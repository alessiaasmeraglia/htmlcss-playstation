# htmlcss-playstation

Replica responsive della home page PlayStation realizzata con **HTML, CSS e Bootstrap 5**.

## Obiettivo

Riprodurre il layout della homepage PlayStation seguendo gli screenshot forniti come riferimento, senza usare il sito live come sorgente.

Il progetto è stato sviluppato con approccio **mobile first**, sfruttando Bootstrap per:

- griglia responsive
- navbar responsive
- utilities di spaziatura
- flexbox helpers
- gestione di container, row e col

Il CSS custom è stato usato solo per:

- palette colori PlayStation
- hero con background image
- stati attivi di thumbnail e accessori
- card promo non standard
- piccoli aggiustamenti tipografici e responsive

## Tecnologie usate

- HTML5
- CSS3
- Bootstrap 5

## Struttura progetto

```text
htmlcss-playstation/
├── index.html
├── css/
│   └── style.css
├── img/
│   └── assets del progetto
└── README.md
```

## Struttura della pagina

La pagina è composta da queste macroaree:

1. top bar Sony
2. header con navbar
3. hero principale
4. thumbnails sotto hero
5. intro PlayStation 5
6. sezione console PS5
7. sezione accessori PS5
8. hero secondaria
9. nuove uscite
10. esplora PlayStation 4
11. PlayStation Plus
12. sconti PlayStation Store
13. PlayStation Now
14. sezione social
15. footer

## Responsive

Breakpoints principali usati:

- **xs**: `< 576px`
- **sm**: `>= 576px`
- **md**: `>= 768px`
- **xxl**: `>= 1400px`

Il layout è stato adattato seguendo gli screenshot forniti per più dimensioni schermo.

## Note sviluppo

- Gli screenshot forniti sono il riferimento principale del lavoro.
- Bootstrap è stato usato il più possibile per ridurre CSS superfluo.
- Il CSS custom è stato mantenuto essenziale e organizzato per sezioni.
- Alcuni asset sono stati adattati in base ai file realmente disponibili nel progetto.

## Autore

Progetto realizzato come esercitazione front-end su replica layout responsive PlayStation.

