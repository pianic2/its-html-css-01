# 🚀 Responsive HTML Starter Template

Template frontend **modulare, scalabile e manutenibile** per creare rapidamente:

* dashboard
* pannelli admin
* tool interni
* portali didattici
* pagine statiche professionali

Progettato con una logica **production-ready**: separazione delle responsabilità, CSS organizzato, variabili tematiche, componenti riusabili.

Non è una semplice pagina HTML, ma una **base architetturale riutilizzabile**.

---

# ✨ Caratteristiche

✔ Layout responsive (Grid + Flexbox)
✔ Navbar + sidebar doppia + contenuto centrale
✔ Tabelle responsive
✔ CSS modulare diviso per responsabilità
✔ Variabili CSS (themes/dark mode ready)
✔ Struttura scalabile
✔ Zero dipendenze
✔ Funziona offline

---

# 📂 Struttura del progetto

```
.
├── index.html
├── css/
│   ├── variables.css     # design tokens (colori, spaziature, font, radius)
│   ├── base.css          # reset + tipografia globale
│   ├── layout.css        # grid, container, breakpoints
│   ├── components.css    # navbar, sidebar, table, footer
│   ├── utilities.css     # classi helper riusabili
│   └── main.css          # import di tutti i moduli
│
├── js/
│   └── app.js            # logica UI opzionale (toggle sidebar ecc.)
│
└── README.md
```

---

# 🧠 Filosofia del progetto

Questo template segue 3 principi:

### 1. Separazione delle responsabilità

Ogni file fa **una sola cosa**:

* base → reset
* layout → struttura
* components → UI
* utilities → helpers

### 2. Design Tokens

Tutti i valori hardcoded sono vietati.

Esempio:

```css
:root {
  --color-bg: #f1f1f1;
  --space-md: 16px;
}
```

Cambiare il tema = modificare 1 file.

### 3. Scalabilità

Puoi aggiungere:

* nuove pagine
* nuovi componenti
* dark mode
* build system
  senza toccare il resto.

---

# 🚀 Avvio rapido

Apri direttamente:

```
index.html
```

Oppure con server locale:

```
npx serve .
```

o

```
python -m http.server
```

---

# 🎨 Personalizzazione (consigliato)

Modifica solo:

```
css/variables.css
```

Esempio:

## Cambiare colori

```css
:root {
  --color-bg: #121212;
  --color-text: #eeeeee;
}
```

## Cambiare larghezza layout

```css
--container-width: 1400px;
```

---

# 📱 Responsive

Breakpoints:

| Device  | Comportamento                        |
| ------- | ------------------------------------ |
| Desktop | 3 colonne (sidebar + main + sidebar) |
| Tablet  | layout compatto                      |
| Mobile  | sidebar impilate / collapsabili      |

---

# 🧩 Utilities disponibili

```
.flex
.grid
.text-center
.mt-1 .mt-2 .mt-3
.p-1 .p-2 .p-3
.hidden
```

Pensate per evitare CSS duplicato.

---

# ➕ Estensioni consigliate

Se vuoi portarlo a livello "pro":

* [ ] Dark mode toggle
* [ ] Sidebar collapsabile con JS
* [ ] Vite build system
* [ ] Minify CSS
* [ ] Component library
* [ ] GitHub Pages demo
* [ ] Template multipagina

---

# 🛠 Stack suggerito (opzionale)

Per progetti più grandi:

* Vite
* PostCSS
* Autoprefixer
* TypeScript
* oppure integrazione con Django / Flask / Express

---

# 👨‍💻 Quando usarlo

Perfetto per:

✔ Dashboard Raspberry / server di classe
✔ Admin panel Django
✔ Tool interni
✔ Prototipi rapidi
✔ Landing leggere
✔ Progetti didattici

---

# 📜 Licenza

MIT — libero uso personale e commerciale.

---

# ⭐ Contributi

Fork → branch → PR.

Mantieni:

* codice modulare
* niente valori hardcoded
* niente duplicazioni

---

Se ti è utile, lascia una ⭐ su GitHub.
