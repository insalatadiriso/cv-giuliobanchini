# CV Web + PDF Compatto — Template per Web Agency (Giulio Banchini)

Contiene:
- `index.html` — versione **web** responsive (GitHub Pages ready).
- `cv-compact.html` — versione **compatta** ottimizzata per **stampa A4** (tema dark).
- `CHANGELOG.md` — cronologia modifiche.

## Ultimi aggiornamenti (mobile)
- **Burger menu** a destra su mobile (≤ 767px) con: Competenze, Esperienze, Formazione, Contatti, e **Contattami**.
- **Rimozione “Scarica PDF compatto” su mobile** (resta su desktop).
- **Nessuna banda nera** su iOS: gradiente coerente ai margini grazie a `viewport-fit=cover`, `safe-area` e gradiente su `html`.

## Pubblicazione (GitHub Pages)
1. Repo con i file.
2. **Settings → Pages** → “Deploy from branch” (`main`/root).
3. Apri l’URL `https://<utente>.github.io/<repo>/`.

## PDF compatto
1. Apri `cv-compact.html`.
2. `Ctrl/Cmd+P → Salva come PDF`.
3. Scala 100%, margini standard/minimi, “stampa sfondi” facoltativa.

## Design system (coerente web/print)
- Colori: Primario `#2D6CDF`, Secondario `#3B1C67`, Accento `#00D1B2`
- Tipografia: Titoli **Poppins**, Corpo **Inter**
- Accessibilità: WCAG AA, focus visibile, semantica pulita
