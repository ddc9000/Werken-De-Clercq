# Werken-De-Clercq

**Terminal-style webapp voor ontwerpfiles van Werken De Clercq (DDC9000)**

Minimalistische, hoog-contrast terminal interface voor het aanbieden van professioneel ontwerpwerk als digitale service. 

Gebaseerd op de volledige productlijst van [zwartopwit.be/az-list](https://www.zwartopwit.be/az-list). 

## Kernconcept

- **Geen drukwerk verkopen** — alleen kant-en-klare, print-ready ontwerpbestanden (PDF, AI, etc.)
- Klant kiest hetzelfde product/variant als bij ZwartOpWit
- **Optie 1 (goedkoper voor klant):** Bestel alleen het ontwerp → print zelf goedkoper bij zwartopwit.be
- **Optie 2 (full service):** Werken De Clercq regelt het drukwerk + kwaliteitscontrole + surplus

Dit maakt het voor de klant vaak voordeliger dan direct full-service bij een drukker bestellen.

## Huidige status (v0.1)

- Volledig functionele single-file webapp (`index.html`)
- Donkere high-contrast terminal look (lime accents op diepzwart)
- ~12 representatieve producten met meerdere varianten & vaste ontwerp-prijzen
- Volledige order flow met briefing, service level keuze, simulated checkout & order history (localStorage)
- Zoek/filter, keyboard friendly, responsive
- Uitleg "Hoe werkt het?" exact volgens jouw specificatie

## Tech stack (maximaal minimalistisch)
- Pure HTML5 + Tailwind CSS (Play CDN) + vanilla JS
- Geen build step, geen dependencies in runtime
- Klaar voor GitHub Pages (`/` of `/docs`)
- Uitbreidbaar: products data array makkelijk aan te vullen

## Live demo

Open `index.html` lokaal of deploy via GitHub Pages.

## Roadmap / volgende stappen

1. User feedback op UI/prijzen/flow
2. Meer producten toevoegen uit de A-Z lijst (data-driven)
3. Echte backend (Formspree / Supabase / email) voor orders
4. Optioneel: klant login + echte file delivery portal
5. PWA manifest + offline support
6. Integratie met jouw bestaande ddc90.com of Kwekerij tooling

## Lokale development

```bash
git clone https://github.com/ddc9000/Werken-De-Clercq.git
open index.html
```

Of serve met:
```bash
python -m http.server 8000
```

---

Gemaakt met precisie en minimalisme. Klaar voor iteratie.

**Contact:** ddc90@proton.me | +32 473 62 26 15
