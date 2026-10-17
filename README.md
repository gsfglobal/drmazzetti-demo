# Demo sito Dott. Vincenzo Mazzetti — Pontecorvo

Concept dimostrativo Dental Go, **non ancora approvato per l'uso ufficiale**.

## Stato del progetto

- Progetto Next.js compilato con successo su GitHub Actions.
- Sorgenti per la pubblicazione: `mazzetti-demo.zip` (già caricato).
- Build statica automatizzata tramite `.github/workflows/publish.yml`.
- **Passaggio da completare:** abilitare GitHub Pages sul repository.

## Attivazione del sito (una sola volta)

1. Accedi a [Settings → Pages](https://github.com/gsfglobal/drmazzetti-demo/settings/pages).
2. In **Build and deployment**, imposta **Source: GitHub Actions** (se non lo è già).
3. Apri [Actions → Pubblica demo Mazzetti](https://github.com/gsfglobal/drmazzetti-demo/actions/workflows/publish.yml).
4. Apri l'ultima esecuzione fallita e premi **Re-run all jobs**, oppure avvia **Run workflow** sul ramo `main`.

La build è già stata eseguita senza errori; il precedente workflow si è interrotto esclusivamente perché GitHub Pages non era ancora abilitato.

**Sito previsto:** https://gsfglobal.github.io/drmazzetti-demo/

L'esportazione usa `BASE_PATH=/drmazzetti-demo` e aggiorna l'URL canonico, rispettando il percorso del repository.

## Note per la presentazione

Tutti i contenuti sono presentati come concept; `demo: true` attivo, pagine `noindex`, modulo contatti non operativo. Prima di un uso definitivo occorrono la conferma del medico su dati, recapiti e qualifiche e l'adeguamento delle informative. `noindex` non protegge l'accesso pubblico.
