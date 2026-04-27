# 💊 MediScadenza v2 — PWA

App PWA per gestire le scadenze dei medicinali di casa. Funziona su iPhone, Android e desktop senza installazione da App Store.

## ✨ Novità v2

- **Logo** — icona con croce + pillola, identità visiva coerente
- **Backup & Ripristino** — esporta/importa `.json` per trasferire i dati o conservarne una copia
- **Annulla inserimento** — pulsante "Annulla" nel form (con messaggio di conferma)
- **Quantità come numero digitabile** — campo numerico + pulsanti +/− combinati
- **Ordine alfabetico** — medicinali ordinati A→Z in lista, home e categorie

## 🚀 Metti online in 2 minuti

### Netlify Drop (più semplice)
1. Vai su [netlify.com/drop](https://app.netlify.com/drop)
2. Trascina la cartella `MediScadenza-PWA-v2`
3. Ottieni un URL pubblico immediato

### GitHub Pages (permanente e gratuito)
```bash
cd MediScadenza-PWA-v2
git init && git add . && git commit -m "MediScadenza v2"
git remote add origin https://github.com/TUO-USERNAME/mediscadenza.git
git push -u origin main
# Poi: Settings → Pages → Source: main / root
```

## 📲 Installa su iPhone
1. Apri l'URL su **Safari**
2. Tocca **Condividi** (□↑)
3. Tocca **"Aggiungi a schermata Home"**

## 📁 File
```
index.html     ← tutta l'app (HTML + CSS + JS)
manifest.json  ← metadati PWA
sw.js          ← funzionamento offline
icons/         ← icone app
```

## 📦 Backup
- **Esporta**: genera un file `.json` con tutti i medicinali
- **Importa**: carica un file di backup precedente (i dati esistenti vengono sostituiti)

## 📄 Licenza
MIT
