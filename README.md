# 💊 MediScadenza — PWA

App per gestire le **scadenze dei medicinali** di casa. Funziona come **Progressive Web App** — nessuna installazione da App Store, nessun Xcode, nessun account.

---

## ✨ Funzionalità

- 📊 Dashboard con 4 statistiche (totale / validi / attenzione / urgenti)
- 🔴 Semaforo visivo: verde / giallo / arancio / rosso per ogni medicinale
- 🔍 Ricerca e filtri (Tutti / Scaduti / Urgenti / Attenzione / Validi)
- 🗂️ Vista per categorie (Analgesico, Antibiotico, Vitamina, ecc.)
- ✏️ Aggiungi / Modifica / Elimina medicinali
- 💾 Dati salvati localmente (localStorage, nessun cloud)
- 📲 Installabile su iPhone da Safari
- ✈️ Funziona offline dopo il primo caricamento (Service Worker)

---

## 🚀 Come usarla

### Opzione 1 — GitHub Pages (gratuito, consigliato)

1. Crea un repository su GitHub (es. `mediscadenza`)
2. Carica tutti i file in questo ZIP
3. Vai su **Settings → Pages → Source: main branch / root**
4. L'app sarà disponibile su `https://TUO-USERNAME.github.io/mediscadenza/`

### Opzione 2 — Netlify Drop (più semplice)

1. Vai su [netlify.com/drop](https://app.netlify.com/drop)
2. Trascina la cartella `MediScadenza-PWA`
3. In 30 secondi hai un URL pubblico

### Opzione 3 — Locale (per test)

```bash
cd MediScadenza-PWA
python3 -m http.server 8080
# Apri http://localhost:8080
```

---

## 📲 Installare su iPhone

1. Apri l'URL su **Safari** (non Chrome)
2. Tocca l'icona **Condividi** (□↑)
3. Scorri e tocca **"Aggiungi a schermata Home"**
4. Conferma → l'icona appare come un'app vera

---

## 📁 File inclusi

```
MediScadenza-PWA/
├── index.html      ← tutta l'app in un file (HTML + CSS + JS)
├── manifest.json   ← metadati PWA (nome, icona, colori)
├── sw.js           ← service worker per funzionamento offline
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🔧 Personalizzare

Apri `index.html` con qualsiasi editor di testo:

| Cosa | Dove cercare |
|------|-------------|
| Aggiungere categorie | array `CATS` nel `<script>` |
| Cambiare colori | variabili CSS in `:root` |
| Opzioni notifica | array `NOTIFS` nel `<script>` |
| Nome app | `<title>` e `manifest.json` |

---

## 📋 Requisiti

- Qualsiasi browser moderno (Safari, Chrome, Firefox)
- Per installare come app → Safari su iOS/iPadOS
- Nessun server backend, nessun database cloud

---

## 📄 Licenza

MIT — libero di usare, modificare e distribuire.
