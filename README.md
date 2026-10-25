# Sito Dott.ssa Maria Grazia Grosso

Sito vetrina (one-page) per la **Dott.ssa Maria Grazia Grosso** — Psichiatra e Psicoterapeuta a Belvedere Marittimo (CS).

Sito statico: un singolo file [`index.html`](index.html) con CSS inline e i loghi in [`assets/logo/`](assets/logo). Nessuna build, nessuna dipendenza.

## Pubblicazione

Il sito è ospitato su GitHub Pages dal ramo `main`, con dominio `dottoressamggrosso.it` registrato su Host.it. Il file `CNAME` mantiene il collegamento al dominio; `www` punta a `vage88sg1.github.io` e viene reindirizzato al dominio principale. L’indicizzazione resta temporaneamente bloccata tramite meta `noindex, nofollow` in entrambe le pagine e `Disallow: /` in `robots.txt`.

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

Dati professionali confermati: P.IVA `02586370500`, Ordine dei Medici di Pisa n. `07118`. Email definitiva: `dottoressamg.grosso@gmail.com`. Durate e tariffe sono confermate per la pubblicazione.

Restano da confermare:

- Stato di conseguimento dei master: sono riportati come percorsi formativi; gli anni non sono pubblicati, come richiesto dall’utente.
- Profilo **Appuntoo**: quello collegato è temporaneamente disattivato e contiene ancora `/pisa`. Verificare sede, prestazioni e tariffe prima di riattivarlo; non ricostruire un nuovo URL per ipotesi.

La pagina **Privacy** riguarda esclusivamente navigazione e funzionamento del sito (hosting, tema, mappa e apertura dei servizi esterni). Prenotazioni, comunicazioni con lo studio e attività clinica saranno disciplinate da un'informativa separata, come indicato dall'utente. Appuntoo è considerato già verificato.

La sezione "Chi sono" presenta biografia e formazione affiancate su desktop e in sequenza su mobile, senza riquadro fotografico. La mappa OpenStreetMap è un'immagine locale (`assets/mappe/studio-belvedere-osm.jpg`) con attribuzione e link a Google Maps: non carica iframe, cookie o risorse da servizi di mappe esterni. Google Maps, OpenStreetMap e WhatsApp si aprono soltanto su richiesta tramite link esterni.

Lo sfondo iniziale usa l’illustrazione approvata dei neuroni stilizzati (`assets/sfondi/neuroni-organici.webp`), ospitata localmente e ottimizzata in WebP. Intensità, tonalità e posizione si adattano al tema e allo schermo; l’immagine è decorativa e non contiene testi o loghi.

La revisione responsive protegge le unità numeriche (tariffe, durate, anni, telefono e dati professionali), separa durata e prezzo nelle schede visita e mantiene il menu entro l’altezza disponibile. Il simbolo WhatsApp è l’asset ufficiale Meta, ospitato localmente; provenienza e condizioni d’uso in `assets/icons/WHATSAPP-SOURCE.md`.

Immagine della mappa e coordinate (`39.617406, 15.858948`) provengono dalla sede di Belvedere Marittimo nel repository [sito-gaetano-grosso](https://github.com/vage88sg1/sito-gaetano-grosso/blob/76457b95decc8ac6760966be8329c297144dbf8b/index.html). Dati cartografici © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

> I materiali sorgente del brand, i questionari e le note di revisione sono conservati in `_sources/`, esclusa dal repo tramite `.gitignore`.
