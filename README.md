# Portfolio di Alessio Tampone

Portfolio UX/UI in stile Netflix. Sito statico (HTML, CSS e JavaScript in un unico file), pubblicato su Cloudflare.

## Struttura
- `public/index.html`: il sito
- `public/_headers`: header di sicurezza
- `wrangler.jsonc`: configurazione Cloudflare (serve la cartella `public/`)

## Provare in locale
    npx wrangler dev

## Modificare i contenuti
Progetti, testi e email sono nell'oggetto `P` e nel dizionario `U` dentro `public/index.html`
(cerca `var P=[` e `var U=`). L'email è anche nel footer.

## Flusso di lavoro con Git
- `main` è il ramo pubblicato: ogni push su `main` aggiorna il sito.
- Per ogni modifica crea un ramo (`git switch -c nuovo-progetto`), poi una Pull Request.
  Cloudflare genera un link di anteprima per i rami diversi da `main`.
- Per una versione stabile: `git tag v1.1.0 && git push --tags`, e aggiorna `CHANGELOG.md`.

## Deploy
Cloudflare Workers Builds, comando di deploy `npx wrangler deploy`.
