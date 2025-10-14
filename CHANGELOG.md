# Changelog

## v1.0.0 – Prima release
- Creato **index.html**: versione web responsive con:
  - Hero con pill di 3 skill, CTA “Scarica PDF compatto” e “Contattami”.
  - Navigazione sticky con ancore.
  - Sezioni: Sommario, Competenze (chip + barre), Esperienze (timeline), Progetti (card), Formazione, Contatti.
  - SEO: `<title>`, meta description, Open Graph, favicon SVG.
  - JSON-LD `schema.org/Person`.
  - Accessibilità: focus visibile, semantica HTML5, contrasto AA.
  - Performance: immagini con `<picture>` e placeholder SVG, nessuna libreria esterna.

- Creato **cv-compact.html**: versione a 2 colonne per stampa A4, con:
  - Header compatto (nome, ruolo, micro-sommario, avatar).
  - Colonna sinistra: contatti, competenze (barre), soft skills, formazione.
  - Colonna destra: esperienze e portfolio sintetici.
  - Regole `@media print`: link in chiaro, gestione orfani/vedove, massimo 2 pagine (dipende dai contenuti).

- Aggiunto **README.md**: istruzioni di personalizzazione, pubblicazione su GitHub Pages e generazione PDF.

### Decisioni di design
- **Mood minimal/tech** con cromie sobrie, accento ciano per segnali positivi.
- **Tipografia Poppins/Inter** per equilibrio tra personalità e leggibilità.
- **Barre competenze** gradient primario→accento per gerarchia visiva immediata.
- **Timeline verticale**: mette in evidenza progressione e impatto.
- **Coerenza web/print**: stessi token, grafica senza sfondi in stampa.

### TODO futuri
- Opzione **tema chiaro/scuro** con toggle (disabilitato per la stampa).
- Micro-componenti per esperienze con tag KPI strutturati.
- Selettore rapido per esportare solo 1 pagina A4 (ulteriore compressione spaziature).
