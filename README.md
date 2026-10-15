# Grepp & Gummi (Kumla) — Modern Kundfokuserad Webbplats

Välkommen till den officiella webbplatsen för **Grepp & Gummi**, en lokal däck- och fälgverkstad på **Västra Drottninggatan 23 i Kumla**.

Webbplatsen är en modern, responsiv och konverteringsoptimerad one-page-lösning som är **100% kundfokuserad**. Den lyfter fram verkstadens viktigaste kundfördelar: de generösa öppettiderna (**Måndag–Söndag: 07:00–22:00**), snabbt hjulskifte, balansering, däckguide och ett smidigt online-bokningssystem integrerat direkt via **Cal.com**.

---

## 🌟 Huvudfunktioner

1. **Strikt Kundfokuserat Gränssnitt:**
   - Inga interna adminmenyer, exportknappar eller onödig administration visas för kunden.
   - Allt är utformat för att en bilägare snabbt ska kunna hitta verkstaden, se öppettider, välja rätt däckservice och boka en tid på under 60 sekunder.

2. **Visuell Identitet från Verkstadsskylten i Kumla:**
   - Varm verkstadsgul/amber (`#E5A93C`) och djup asfalt/grafit (`#161A20` / `#1E232B`).
   - Digital replika av Grepp & Gummis takskylt med däckmönster och klickbart telefonnummer (`070-657 49 48`).
   - Tydliga tjänstekort med tidsåtgång och tydlig information.

3. **Realtidsindikator för Öppettider:**
   - Automatisk avkänning av klockslag: Visar en pulserande grön lampa `"Öppet nu (07:00–22:00)"` under dagtid och `"Öppnar kl. 07:00 imorgon"` under natten.

4. **Strukturerade Tjänster & Svensk Däckguide:**
   - **Hjulskifte + Balansering (★ Populärast & Bästa valet):** Vårt mest rekommenderade val för stabil och skakfri motorvägskörning samt jämnare däckslitage.
   - **Hjulskifte / Däckbyte (Standard):** Kontroll av lufttryck, mönsterdjup och momentdragning.
   - **Endast Balansering:** Separat maskinell balansering av 4 hjul vid vibrationer.
   - **Däck & Fälg:** Helhetsservice, montering, punkteringshjälp och rådgivning.
   - **Drop-in & Akuttid:** Möjlighet till drop-in och snabb hjälp mellan 07:00 och 22:00.
   - Komplett däckguide med lagstadgade datum i Sverige (1 dec – 31 mar för vinterdäck, 1 okt – 15 apr för dubbdäck, 1,6 mm vs 3 mm mönsterdjup).

5. **Mobilanpassad & Thumb-Friendly UX:**
   - Direktklickbara telefonlänkar (`tel:0706574948`) överallt.
   - Fast åtgärdslist längst ner på mobilen med snabbval: *"Ring 070-657 49 48"* och *"Boka tid nu"*.

6. **Interaktiv Google Maps-karta:**
   - Inbäddad karta centrerad på Västra Drottninggatan 23, Kumla.
   - 1-klicksknapp för direkt GPS-navigering i Google Maps.
   - Snabbknapp för att kopiera adressen till telefonens urklipp.

---

## 📅 Bokningsmotor med Cal.com

Bokningsgränssnittet är direkt inbäddat via [Cal.com](https://cal.com) i ljust tema och hanterar verkstadens bokningsbara tjänster i separata flikar:

1. **Hjulskifte + Balansering (Populärast):** [cal.com/grepp-gummi/hjulskifte-balansering](https://cal.com/grepp-gummi/hjulskifte-balansering)
2. **Hjulskifte / Däckbyte:** [cal.com/grepp-gummi/hjulskifte](https://cal.com/grepp-gummi/hjulskifte)
3. **Endast Balansering:** [cal.com/grepp-gummi/endast-balansering](https://cal.com/grepp-gummi/endast-balansering)
4. **Däck & Fälg / Montering:** [cal.com/grepp-gummi/dack-falg-montering](https://cal.com/grepp-gummi/dack-falg-montering)

### Så fungerar kundflödet:
1. **Steg 1 — Tjänsteflikar:** Kunden klickar på önskad tjänst (eller klickar på "Boka" under respektive tjänstekort på sidan).
2. **Steg 2 — Interaktiv Kalender:** Cal.coms månadsvy visar automatiskt lediga tider mellan 07:00 och 22:00.
3. **Steg 3 — Bokning:** Kunden anger namn, e-post, telefonnummer och eventuella önskemål.
4. **Steg 4 — Direktbekräftelse:** Cal.com skickar automatiskt en kalenderinbjudan och bekräftelse till kunden och verkstaden.

---

## 🛠 Filstruktur & Teknik

```
GreppOchGummi/
├── index.html     # Komplett, självgående HTML5 one-page webbplats
└── README.md      # Dokumentation och driftguide
```

- **HTML5:** Semantisk, tillgänglighetsanpassad och sökoptimerad (`lang="sv"`).
- **Tailwind CSS (CDN):** Blixtsnabb laddning utan kompileringskrav eller `node_modules`.
- **Vanilla JavaScript:** Modulär och robust logik utan ramverksberoenden.
- **Schema.org LocalBusiness (JSON-LD):** Optimerar verkstadens synlighet i lokala Google-sökningar och på kartor i Kumla och Närke.

---

## 🚀 Drift & Publicering

Webbplatsen kan köras lokalt eller publiceras på valfritt webbhotell:

### Lokal testning
Dubbelklicka på `index.html` eller kör en enkel lokal server i terminalen:

```bash
cd /Users/ramtin/RiderProjects/GreppOchGummi
python3 -m http.server 8080
```

Öppna sedan `http://localhost:8080` i din webbläsare.

### Publicering
- **Netlify / Vercel / Cloudflare Pages:** Dra och släpp mappen för gratis hosting med automatiskt SSL-certifikat.
- **GitHub Pages:** Slå på Pages under Settings -> Pages i ert GitHub-repo.
- **Vanligt webbhotell (One.com, Loopia, Inleed, Miss Hosting m.fl.):** Ladda upp `index.html` via FTP eller webbhotellets filhanterare till er `public_html`-mapp.

---

## 📞 Verkstadsuppgifter

- **Företag:** Grepp & Gummi
- **Verkstad:** Västra Drottninggatan 23, 692 34 Kumla, Sverige
- **Telefon:** 070-657 49 48 (`tel:0706574948`)
- **Öppettider:** Måndag – Söndag: 07:00 – 22:00
