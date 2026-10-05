# BEARLab website: TODO

Sito: https://bears-unitn.github.io/ · Repo: https://github.com/BEARs-UNITN/bears-unitn.github.io

Spunta le voci (`[x]`) man mano che vengono completate.

## Candidature e contatti

- [ ] **Email del lab**: inserirla nel campo `email:` di `data/join.yaml` (fa comparire i pulsanti "Send your application", "Ask about a thesis", "Propose a collaboration")
- [ ] **Form di candidatura**: creare un unico form (Microsoft Forms / Google Forms / Tally) con
  - tipo di candidatura (spontanea / tesi / visiting / collaborazione)
  - nome ed email
  - caricamento di CV e lettera di motivazione
- [ ] Inserire il link del form nei campi `form_url:` di `data/join.yaml` e in `apply_url:` di `content/join.md`

## Tesi

- [ ] **Relatori**: compilare `supervisors: []` nelle 7 tesi in `content/thesis/*/index.md`
- [ ] **QR code dell'esempio MATI** (slide "Info MSc theses"): capire dove porta (paper/repo) e aggiungere il link alla sezione "Example to follow"
- [ ] Quando una tesi viene assegnata: impostare `status: assigned` e `student:` nel suo `index.md`

## Contenuti

- [ ] **Pubblicazioni**: la pagina `/publications/` è vuota. Fornire un file BibTeX o il link a Google Scholar / ORCID per importarle in `content/publication/`
- [ ] **Progetti**: aggiungere i progetti finanziati (nome, periodo, finanziatore, link) copiando `content/project/_example/`
- [ ] **News**: aggiungere news vere (paper accettati, conferenze, eventi) copiando `content/post/_example.md`
- [ ] **Premi**: aggiungerli in `data/awards.yaml` (compaiono in fondo alla pagina News)
- [ ] **People**: aggiungere link personali (Google Scholar, ORCID, LinkedIn, GitHub) nei profili in `data/authors/`

## GitHub

- [ ] **Profilo dell'organizzazione**: creare un repo pubblico `.github` in BEARs-UNITN e copiare `docs/github-org-profile/README.md` e `bearlab-mark.png` in `profile/`
- [ ] **Vecchio repo `bear.github.io`**: archiviarlo o eliminarlo (il suo link dà 404)
- [ ] Per ogni nuovo repo di codice: descrizione, campo *Website* e topics (compaiono in automatico nella pagina Code)
- [ ] Cancellare il branch locale `site-redesign` (già unito in `main`)

## Dominio

- [ ] **bearlab.disi.unitn.it**: inviare la richiesta al supporto tecnico del DISI (record DNS `bearlab.disi.unitn.it CNAME bears-unitn.github.io`, oppure spazio web su server di ateneo)
- [ ] Quando il DNS è attivo: aggiungere il file `CNAME` nel repo, impostare il dominio in *Settings → Pages* e aggiornare `baseURL` in `config/_default/hugo.yaml` (**non prima**, altrimenti il sito va offline)

## Fatto

- [x] Redesign del sito (logo, tipografia, homepage, People, Projects, News, Open Positions)
- [x] 7 tesi MSc dalle slide "Info MSc theses"
- [x] Rimozione delle pagine demo del template e del credito Hugo Blox
- [x] Indirizzo confermato: Via Sommarive 9, Povo (TN)
- [x] Repo rinominato in `bears-unitn.github.io`, sito su https://bears-unitn.github.io/
- [x] Website dell'organizzazione e homepage del repo aggiornati
