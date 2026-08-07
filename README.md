# Lokomoto Centar — Landing: Edukacija "Bol u donjem delu leđa"

Statička stranica. Nema build koraka.

## Sadržaj
- index.html — cela stranica
- support.js — runtime (mora stajati pored index.html)
- assets/ — slike (optimizovane, ~2 MB ukupno) i video

## Deploy
Kopiraj ceo folder na server, npr. u lokomoto.rs/edukacija/, ili ga poveži kao GitHub Pages / Netlify projekat (root = ovaj folder).

## Šta još treba uneti
- Imena i uloge članova tima (trenutno "Ime i prezime / Fizioterapeut")
- Portret predavača (potvrditi da je trenutna fotografija ispravna)
- Broj računa za uplatu
- Tačno vreme početka i kraja oba dana
- Da li je ručak uključen
- Facebook Pixel (id=1428426252619099) i GA4 — hook za CTA klikove već postoji (window.dataLayer.push + fbq Lead)
