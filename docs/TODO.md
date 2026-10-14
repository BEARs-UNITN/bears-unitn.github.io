# BEAR website: TODO

Sito: https://bear.disi.unitn.it/ · Repo: https://github.com/BEARs-UNITN/bears-unitn.github.io

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
- [ ] Per ogni nuovo repo di codice: descrizione, campo *Website* e topics (compaiono in automatico nella pagina Code)
- [ ] Cancellare il branch locale `site-redesign` (già unito in `main`)

## Dominio

- [x] **bear.disi.unitn.it**: record DNS `bear.disi.unitn.it CNAME bears-unitn.github.io` attivato dal DISI
- [x] Dominio impostato in *Settings → Pages*, file `CNAME` nel repo, `baseURL` aggiornato in `config/_default/hugo.yaml`
- [ ] **Enforce HTTPS**: spuntarlo in *Settings → Pages* (il certificato è già attivo)
- [ ] **Website dell'organizzazione**: cambiarlo da `https://bears-unitn.github.io` a `https://bear.disi.unitn.it`
- [ ] **Website del repo**: cambiarlo da `http://bear.disi.unitn.it/` a `https://bear.disi.unitn.it/`
- [ ] **Nome del repo**: rinominarlo da `bear.github.io` a `bears-unitn.github.io` (*Settings → General → Repository name*), per allinearlo al record DNS `bear.disi.unitn.it CNAME bears-unitn.github.io`. Con il nome attuale i vecchi link `https://bears-unitn.github.io/...` danno 404 invece di reindirizzare al dominio

## Fatto

- [x] Redesign del sito (logo, tipografia, homepage, People, Projects, News, Open Positions)
- [x] 7 tesi MSc dalle slide "Info MSc theses"
- [x] Rimozione delle pagine demo del template e del credito Hugo Blox
- [x] Indirizzo confermato: Via Sommarive 9, Povo (TN)
- [x] Repo rinominato in `bears-unitn.github.io`, sito su https://bears-unitn.github.io/
- [x] Website dell'organizzazione e homepage del repo aggiornati
- [x] Vecchio repo `bear.github.io` eliminato
