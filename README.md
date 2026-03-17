# Ekonomi – Kommunal ekonomisk analys

**Skapare:** Kent Lundgren, [www.kentlundgren.se](https://www.kentlundgren.se)

---

## Beskrivning

Det här projektet innehåller interaktiva webbverktyg för att visualisera och analysera
ekonomiska förutsättningar i en mindre svensk kommun med vikande befolkningsunderlag.

---

## Innehåll

### Balanskrav
Visualiserar sambandet mellan **balanskravsresultat i procent** och **finansiellt utrymme**
för drift respektive investeringar under perioden **2027–2031**.

Inkluderar även ett exempel på kultur- och fritidsnämndens investeringsutrymme.

**Underlag:** En mindre svensk kommuns ekonomiska underlag (budgetberedning 2026).

Den grundläggande ekonomiska logiken bakom visualiseringen – varför ett positivt balanskravsresultat
är en förutsättning för kommunala investeringar – diskuteras utförligt i blogginlägget
[*Ingen vinst, ingen nyinvestering*](https://controllerutangranser.wordpress.com/2026/03/15/ingen-vinst-inga-investeringar/)
(Lundgren, 2026).

---

### Investeringar 2027–2031
Interaktiv bildspelspresentation av Kultur- och fritidsnämndens prioriterade investeringsprojekt
för perioden 2027–2031. Presentationen innehåller 14 bilder med budget, driftseffekter,
konsekvensanalyser och fokusområden för samtliga 20 projekt i budgetskrivelsen.

**Underlag:** Simrishamns kommun (2026). *Budgetskrivelse för investeringar 2027–2031*, daterad 2026-03-10.

**Källkod:** [Investeringar_2027_2031/](https://github.com/lundgren9/ekonomi/tree/main/Investeringar_2027_2031)

---

## Liveversioner (GitHub Pages)

> Applikationerna är tillgängliga publikt via GitHub Pages:

**[▶ Öppna Balanskrav – Finansiellt utrymme 2027–2031](https://lundgren9.github.io/ekonomi/Balanskrav/index.html)**

**[▶ Öppna Investeringar 2027–2031 – Bildspelspresentation](https://lundgren9.github.io/ekonomi/Investeringar_2027_2031/index.html)**

---

## Filer

| Fil | Beskrivning |
|-----|-------------|
| `Balanskrav/index.html` | Interaktiv visualisering – balanskrav och finansiellt utrymme |
| `Balanskrav/Balanskravsresultat10.html` | Tidigare version av balanskravsresultat |
| `Investeringar_2027_2031/index.html` | Bildspelspresentation – investeringar 2027–2031 (14 bilder) |

---

## Teknisk information

- Ren HTML/CSS/JavaScript – inga byggsteg krävs
- Diagram renderas med [Chart.js](https://www.chartjs.org/) via CDN
- Typsnitt laddas från Google Fonts (kräver internetanslutning)
- Fungerar direkt i webbläsaren, lokalt eller via GitHub Pages

---

## Kopiera och kör lokalt

```bash
git clone https://github.com/lundgren9/ekonomi.git
```

Öppna därefter `Balanskrav/index.html` direkt i en webbläsare.

---

## Källor

Lundgren, K. (2026). *Ingen vinst, ingen nyinvestering – om det kommunala sparandets logik*.
Controller, lärare och coach utan gränser reflekterar \[Blogg\], 15 mars.
Tillgänglig: [controllerutangranser.wordpress.com](https://controllerutangranser.wordpress.com/2026/03/15/ingen-vinst-inga-investeringar/)

---

*Senast uppdaterad: mars 2026*

---

> **Tips:** Varje delprojekt i detta repo innehåller en tillbaka-länk till denna README och till GitHub Pages-versionen — se respektive `index.html`.
