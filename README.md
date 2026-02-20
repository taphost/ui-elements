# 🧩 UI Elements

Una libreria visiva di 32 componenti UI animati, con demo automatiche e layout responsive.

## ✨ Caratteristiche

- 🎬 **Demo automatiche** — ogni componente si anima autonomamente quando entra nel viewport
- ⏯️ **Controllo globale** — pausa e riprendi tutte le demo con un solo bottone
- 📱 **Responsive** — griglia paginata su desktop, carousel con swipe su mobile
- 🎨 **Design coerente** — altezza fissa per tutte le card, nessun salto di layout al cambio pagina
- 🔤 **Font locali** — Space Mono e Syne caricati da cartella `fonts/`, zero dipendenze di rete

## 🚀 Utilizzo

1. Posiziona i file font in `fonts/` (vedi sotto)
2. Apri `index.html` in un browser moderno
3. Sfoglia i componenti con le frecce di navigazione
4. Usa il bottone ⏸ per congelare tutte le animazioni

## 📁 Struttura

```
index.html
fonts/
  SpaceMono-Regular.woff2
  SpaceMono-Bold.woff2
  Syne-Regular.woff2
  Syne-Bold.woff2
  Syne-ExtraBold.woff2
```

## 🧩 Componenti inclusi

Accordion · Badge · Bento Menu · Breadcrumb · Button · Card · Carousel · Checkbox · Comment · Döner Menu · Dropdown · Form · Hamburger Menu · Icon · Input Field · Kebab Menu · Loader · Meatball Menu · Modal · Pagination · Progress Bar · Radio Button · Search Bar · Sidebar · Skeleton Loader · Slider · Stepper · Tab Bar · Tabs · Tags/Chips · Toast · Toggle Switch

## 🛠️ Dettagli tecnici

- File HTML monolitico — nessuna dipendenza esterna
- `IntersectionObserver` per attivare le demo solo quando visibili
- Pattern `{ start(), stop() }` per ogni componente
- Card a dimensione fissa con `contain: layout style` per performance

## 📋 Requisiti

- Browser moderno con supporto ES6
- JavaScript abilitato

## 📄 Licenza

MIT License — libero di usare, modificare e distribuire.
