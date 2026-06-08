# SERVIS-BOJLERA

High-converting landing stranica za **Servis Bojlera Beograd** — popravka, ugradnja i čišćenje bojlera, 0-24, sa garancijom.

## Pokretanje
Otvori `index.html` u browseru. Nema build koraka — jedan samostalan fajl.

## Izmena kontakta (jedno mesto)
Na dnu `index.html`, u `<script>` bloku:

```js
const BIZ = {
  phone:      "+38160000000",       // pravi broj, bez razmaka
  phoneHuman: "060 / 000-00-00",    // kako se prikazuje
  email:      "kontakt@servis-bojlera-beograd.rs",
  mapsUrl:    "https://maps.app.goo.gl/"
};
```

Broj se automatski upisuje u sva dugmad, `tel:`, Viber i footer.

## Hosting
Radi na bilo kom statičkom hostingu: GitHub Pages, Netlify, Vercel.
