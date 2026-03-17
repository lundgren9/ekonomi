# CLAUDE.md – Instruktioner för AI-assistenter i detta repo

Det här dokumentet innehåller regler som ska följas av Claude och andra
AI-assistenter när de arbetar i repot **lundgren9/ekonomi**.

---

## Korsreferensregel — alltid obligatorisk

Varje gång ett nytt delprojekt (undermapp) skapas i detta repo gäller:

### 1. Uppdatera root-README.md

Lägg till delprojektet i `README.md` (repots rot) med:

- En kort beskrivning av vad projektet gör
- Länk till källkodsmappen:
  `https://github.com/lundgren9/ekonomi/tree/main/<PROJEKTMAPP>`
- Länk till GitHub Pages-liveversionen:
  `https://lundgren9.github.io/ekonomi/<PROJEKTMAPP>/index.html`

Lägg länken i sektionen **"Liveversioner (GitHub Pages)"** i README.md.
Lägg projektbeskrivningen i sektionen **"Innehåll"** i README.md.
Lägg filen i tabellen under **"Filer"** i README.md.

### 2. Lägg in tillbaka-länk i projektets HTML-fil

Varje `index.html` (eller motsvarande huvudfil) i ett delprojekt ska
innehålla en diskret länk tillbaka till repot. Exempel på implementation:

```html
<!-- Diskret källkodslänk — länk tillbaka till GitHub-repot -->
<a id="repo-link"
   href="https://github.com/lundgren9/ekonomi/tree/main/<PROJEKTMAPP>"
   target="_blank"
   rel="noopener"
   title="Källkod &amp; README på GitHub">
  github.com/lundgren9/ekonomi
</a>
```

Länken ska:
- Vara diskret och inte störa presentationen (låg opacitet, liten typsnittsstorlek)
- Placeras i ett hörn av sidan (t.ex. nere till vänster, utanför huvudinnehållet)
- Öppna i ny flik (`target="_blank"`)
- Ha ett `title`-attribut som förklarar vart länken leder

### 3. Uppdatera "Senast uppdaterad" i README.md

Uppdatera alltid datumet i sista raden av `README.md` när ändringar görs.

---

## Befintliga delprojekt och deras korsreferenser

| Projektmapp | README-sektion | GitHub Pages |
|---|---|---|
| `Balanskrav/` | ✅ Finns i README | https://lundgren9.github.io/ekonomi/Balanskrav/index.html |
| `Investeringar_2027_2031/` | ✅ Finns i README | https://lundgren9.github.io/ekonomi/Investeringar_2027_2031/index.html |

---

## Övriga regler för detta repo

- Alla filer är ren HTML/CSS/JavaScript — inga byggsteg, inga ramverk
- Kommentera kod på **svenska** (kommentarer och variabelnamn)
- README.md och CLAUDE.md skrivs på **svenska**
- Använd alltid relativa sökvägar i HTML (`./` som bas)
- Testa alltid att sidan fungerar lokalt innan commit

---

*Skapat: mars 2026 · Repo: https://github.com/lundgren9/ekonomi*
