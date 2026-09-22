# Cosma QR

Landing page statiche per QR code Cosma Srl.

## Struttura

I QR non puntano alla root: ogni biglietto/campagna ha una propria cartella sotto `contacts/`.

```text
/
├── index.html                      # hub (elenco destinazioni)
├── contacts/
│   └── biglietto-visita/           # QR biglietto da visita
│       ├── index.html
│       └── cosma.vcf               # salvataggio contatto
└── assets/
    ├── css/styles.css
    └── img/
```

## URL da usare nel QR

Dopo il deploy (es. GitHub Pages):

```text
https://<tuo-dominio>/contacts/biglietto-visita/
```

## Aggiungere un nuovo QR

1. Crea una cartella in `contacts/` (es. `contacts/fiera-2026/`)
2. Aggiungi `index.html` con i contenuti specifici
3. (Opzionale) collega la nuova pagina dall’hub in `index.html`
4. Genera il QR con l’URL della nuova cartella

## Contatti (biglietto da visita)

- Telefono: +39 0381 319251
- Email: info@cosma-srl.it
- LinkedIn: @cosma-srl-official
- Sito: https://www.cosma-srl.it/
- P. IVA: IT 01668990185

## Deploy

Repository pensata per hosting statico (GitHub Pages o altro). Abilita Pages sulla branch `main` con root `/`.
