# 🎵 Festival Italia 2026

Guida completa ai festival musicali italiani 2026.  
**83+ festival · 350+ artisti · 3 pagine interattive**

---

## Come pubblicare il sito

### Opzione A — Vercel (consigliata, gratuita, 2 minuti)

1. Crea un account su [vercel.com](https://vercel.com) se non ce l'hai
2. Vai su [github.com](https://github.com) → crea un nuovo repository → carica tutti questi file
3. Su Vercel: **Add New Project** → importa il tuo repo GitHub
4. Vercel rileva automaticamente Create React App → clicca **Deploy**
5. In 60 secondi hai un URL tipo `festival-italia-2026.vercel.app` ✅

### Opzione B — Netlify (altrettanto semplice)

1. Vai su [netlify.com](https://netlify.com) → **Add new site** → **Deploy manually**
2. Trascina l'intera cartella `festival-italia` nell'area di drag-and-drop
3. Netlify fa il build automaticamente → URL pronto in 1 minuto ✅

### Opzione C — Build locale

```bash
# Installa dipendenze
npm install

# Avvia in sviluppo (localhost:3000)
npm start

# Build per produzione
npm run build
# → cartella `build/` pronta da caricare su qualsiasi hosting
```

---

## Struttura del progetto

```
festival-italia/
├── public/
│   └── index.html          # HTML base con meta tag e font
├── src/
│   ├── index.js            # Entry point React
│   └── App.jsx             # App completa (dati + componenti)
├── package.json            # Dipendenze
├── vercel.json             # Config Vercel
├── netlify.toml            # Config Netlify
└── README.md               # Questo file
```

---

## Funzionalità

- **📋 Lista** — tutti i festival filtrabili per regione e genere
- **📅 Calendario** — navigazione mensile con filtro per genere e colori per densità
- **🎤 Artisti** — tutti gli artisti in lineup, filtrabili per genere, nome e periodo, con dettaglio festival per artista

---

*Dati aggiornati a maggio 2026 · Fonti: siti ufficiali, Festivals Backpack, AllMusicItalia, RadioDoc, NoisyRoad*
