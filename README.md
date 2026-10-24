# Sito Dott.ssa Maria Grazia Grosso

Sito vetrina (one-page) per la **Dott.ssa Maria Grazia Grosso** — Psichiatra e Psicoterapeuta a Belvedere Marittimo (CS).

Sito statico: un singolo file [`index.html`](index.html) con CSS inline e i loghi in [`assets/logo/`](assets/logo). Nessuna build, nessuna dipendenza.

## Anteprima in locale

```bash
python3 -m http.server 4521
# poi apri http://localhost:4521
```

## Stack

- HTML + CSS (inline), zero framework
- Font: Cormorant Garamond + Mulish, ospitati in `assets/fonts/`
- Palette ottanio: `#356b77` / `#5f9aaa`

## Contenuti e finalizzazione

I contenuti sono stati aggiornati sulla base delle risposte della dottoressa al questionario del 24 ottobre 2026. Il sito mantiene il blocco dell'indicizzazione tramite meta robots e `robots.txt`.

Restano da confermare:

- Email professionale, provincia e numero d'iscrizione all'Ordine, partita IVA.
- Stato di conseguimento dei master: sono riportati come percorsi formativi con le date fornite.
- Profilo **Appuntoo**: quello collegato è temporaneamente disattivato e contiene ancora `/pisa`. Verificare sede, prestazioni e tariffe prima di riattivarlo; non ricostruire un nuovo URL per ipotesi.
- Informativa **Privacy**, ancora in bozza con dati e aspetti del trattamento da completare e validare.

La sezione "Chi sono" usa il marchio esistente nello spazio della foto, che per ora non è prevista. Google Maps e WhatsApp si aprono soltanto su richiesta tramite link esterni.

> I materiali sorgente del brand, i questionari e le note di revisione sono conservati in `_sources/`, esclusa dal repo tramite `.gitignore`.
