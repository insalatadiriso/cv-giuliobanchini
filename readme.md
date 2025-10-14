# CV Web + PDF Compatto — Template per Web Agency (Giulio Banchini)

Questo repository contiene:
- `index.html` — versione **web** responsive e interattiva (GitHub Pages ready).
- `cv-compact.html` — versione **compatta** ottimizzata per **stampa A4** (esporta con `Ctrl/Cmd+P → Salva come PDF`).
- `CHANGELOG.md` — cronologia modifiche.

## Aggiornamenti inclusi (richiesta 2025-10-14)
- **Sommario** reintrodotto nella versione web (con il testo fornito).
- **Sfondo fisso** con contenuti che scorrono sopra (trasparenza invariata).
- **CV compatto in dark** con la stessa palette del principale.
- Nessuna modifica ulteriore a palette/tipografia/layout oltre a quanto sopra.
- Nessun commento superfluo lasciato nel markup.

## Come personalizzare rapidamente
- Modifica direttamente i testi in `index.html` e `cv-compact.html`.
- Sostituisci la foto in `assets/profile.jpg` (1000×1000px consigliati).

## Pubblicare su GitHub Pages
1. Crea un repo e carica i file.
2. **Settings → Pages →** “Deploy from branch” → `main` (root).
3. Apri l’URL `https://<utente>.github.io/<repo>/`.

## Generare il PDF compatto
1. Apri `cv-compact.html`.
2. `Ctrl/Cmd+P → Salva come PDF`.
3. **Scala 100%**, **Margini standard/minimi** a piacere, “Stampa sfondi” facoltativo.
4. Il layout è pensato per **≤ 2 pagine A4** (dipende dalla lunghezza dei testi).

## Design system (coerente web/print)
- **Colori**: Primario `#2D6CDF` · Secondario `#3B1C67` (viola) · Accento `#00D1B2`  
  Neutri: `#0F172A`, `#1E293B`, `#94A3B8`, `#F1F5F9`, `#FFFFFF`
- **Tipografia**: Titoli **Poppins**, corpo **Inter** (fallback system-ui)
- **Accessibilità**: WCAG AA, focus visibile, semantica pulita.

## CHECKLIST DI VERIFICA
- [ ] Contrasto AA superato  
- [ ] Test mobile (360–414px), tablet (~768px), desktop (≥1280px)  
- [ ] Link “Scarica PDF compatto” funzionante  
- [ ] Stampa A4: massimo 2 pagine, nessun taglio di sezioni  
- [ ] Validazione HTML5 senza errori critici  
- [ ] Nessun dato inventato
