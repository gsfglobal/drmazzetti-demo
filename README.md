# Demo sito Dott. Vincenzo Mazzetti

Anteprima dimostrativa realizzata da Dental Go. Il repository contiene un flusso GitHub Actions per compilare e pubblicare il progetto Next.js incluso nello ZIP `mazzetti-demo.zip`.

## Pubblicazione

1. Da GitHub, apri **Add file → Upload files** e carica nella radice del ramo `main` il file **`mazzetti-demo.zip`**, senza estrarlo.
2. Conferma con **Commit changes**. Il caricamento attiva il workflow in `.github/workflows/publish.yml`.
3. In **Settings → Pages → Build and deployment → Source**, seleziona **GitHub Actions**.
4. Apri **Actions → Pubblica demo Mazzetti** per verificare che la compilazione e la pubblicazione abbiano successo.

Dopo il deploy il sito è disponibile su:

**https://gsfglobal.github.io/drmazzetti-demo/**

Il workflow imposta automaticamente `BASE_PATH=/drmazzetti-demo`, aggiorna l'indirizzo nel contenuto, esegue la build Next.js e pubblica `out/`.

## Avvertenze

Demo **non approvata** per la pubblicazione ufficiale. Mantiene `demo: true` e `noindex`; il modulo è dimostrativo e non invia dati. È necessario verificare con lo studio orari, recapiti, qualifiche, foto e dati legali. `noindex` non equivale a un accesso privato.
