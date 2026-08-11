# Chimica Pratica

Raccolta di appunti e schede di procedura tratte da testi di riferimento di chimica pratica.

## Testi di riferimento

- **Brauer** — *Handbook of Preparative Inorganic Chemistry* (G. Brauer)
- **Vogel** — *Vogel's Textbook of Practical Organic Chemistry*

## Struttura del repository

```
chimica_pratica/
├── inbox/           # note grezze in attesa di essere organizzate
├── Brauer/          # schede tratte dal testo Brauer
├── Vogel/           # schede tratte dal testo Vogel
└── _template.md      # template per nuove schede
```

Attualmente il contenuto è organizzato **per testo** (una cartella per libro), fase più comoda per la stesura iniziale. Ogni scheda però riporta nel frontmatter un campo `processo` (es. sintesi, purificazione, distillazione, cristallizzazione, estrazione...): quando servirà, questo permetterà di **riorganizzare o indicizzare i contenuti per processo/tecnica** senza dover riscrivere le schede, semplicemente raggruppandole per quel campo (es. con un indice generato o spostando i file).

## Come aggiungere una scheda

1. Copia `_template.md` nella cartella del testo corretto (`Brauer/` o `Vogel/`).
2. Rinominalo in modo descrittivo (es. `Vogel/distillazione-frazionata.md`).
3. Compila il frontmatter e il contenuto.

## Inbox

Se non hai tempo di organizzare subito una nota, mettila in `inbox/` così com'è. Verrà poi smistata in `Brauer/` o `Vogel/` seguendo il template.
