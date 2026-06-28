# Sito Dott.ssa Maria Grazia Grosso

Sito vetrina (one-page) per la **Dott.ssa Maria Grazia Grosso** — Psichiatra e Psicoterapeuta, Pisa.

Sito statico: un singolo file [`index.html`](index.html) con CSS inline e i loghi in [`assets/logo/`](assets/logo). Nessuna build, nessuna dipendenza.

## Anteprima in locale

```bash
python3 -m http.server 4521
# poi apri http://localhost:4521
```

## Stack

- HTML + CSS (inline), zero framework
- Font: Cormorant Garamond + Mulish (Google Fonts)
- Palette ottanio: `#356b77` / `#5f9aaa`

## Da completare prima della pubblicazione

Cerca i segnaposto `[...]` e `INSERISCI-LINK-APPUNTOO` in `index.html`:

- Link agenda **Appuntoo** (4 occorrenze)
- Numero **Ordine dei Medici**, **P.IVA**
- **Indirizzo**, **telefono**, **email**, **orari**
- **Foto** della dottoressa (sezione "Chi sono")
- Embed **Google Maps** dello studio
- Testo/pagina **Privacy**

> I materiali sorgente del brand (pacchetti logo, bozze) sono tenuti fuori dal repo tramite `.gitignore`.
