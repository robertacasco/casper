# Cas-Per / AnnunciFunebri.it

Nuovo sito Astro per Cas-Per Srl e AnnunciFunebri.it, pensato per il dominio `casper-af.vercel.app`.

## Obiettivo

Costruire un sito veloce, sobrio e orientato all'acquisizione di imprese funebri affiliate ad AnnunciFunebri.it.

La prima versione include:

- homepage Cas-Per;
- landing `Diventa impresa affiliata AnnunciFunebri.it`;
- numeri di leadership;
- testimonianze B2B;
- asset selezionati dal backup WordPress;
- stile ispirato al vecchio sito, ma semplificato e ricostruito in Astro.

## Comandi

```bash
npm run dev
npm run build
npm run preview
```

## Struttura

- `src/layouts/BaseLayout.astro`: layout globale, header, footer e CSS.
- `src/pages/index.astro`: homepage.
- `src/pages/diventa-impresa-affiliata.astro`: landing B2B.
- `src/components/StatsStrip.astro`: numeri di leadership.
- `src/components/Testimonials.astro`: testimonianze selezionate.
- `public/assets/`: immagini recuperate dal backup WordPress.

## Note

La strategia, gli audit e i materiali di lavoro sono conservati nella cartella separata:

`C:\Users\Roberta\Documents\GitHub\cas-per marketing`

