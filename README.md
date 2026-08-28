# Sito società di calcio - pronto per Netlify

## Struttura

- `index.html` -> pagina principale
- `styles.css` -> grafica e responsive
- `script.js` -> menu mobile, animazioni e galleria
- `assets/images/` -> inserisci qui le foto
- `assets/iscrizione.pdf` -> inserisci qui il PDF di iscrizione

## Foto

Rinomina le tue fotografie così:

- `foto-1.jpg`
- `foto-2.jpg`
- `foto-3.jpg`
- `foto-4.jpg`
- `foto-5.jpg`

e copiale dentro `assets/images/`.

Puoi usare anche immagini `.webp`, ma in quel caso devi modificare i nomi dentro `index.html`.

## PDF di iscrizione

Metti il tuo PDF dentro la cartella `assets` e rinominalo:

`iscrizione.pdf`

Il pulsante "Scarica il PDF per iscrizione" punterà automaticamente a:

`assets/iscrizione.pdf`

Il file rimarrà fisso sul server Netlify e potrà essere scaricato dagli utenti.

## Pubblicazione su Netlify

Metodo semplice:

1. Vai su Netlify.
2. Crea un nuovo sito con "Deploy manually".
3. Trascina l'intera cartella del progetto, oppure lo ZIP dopo averlo estratto.
4. Netlify pubblicherà il sito.

Se aggiorni foto o PDF, ricarica la cartella del sito con i nuovi file.

## Personalizzazione

Nel file `index.html` puoi cambiare:
- nome della società
- testi
- contatti
- indirizzo
- link
- eventuale logo

Nel file `styles.css` puoi cambiare i colori principali nelle variabili all'inizio del file.


## Aggiornamenti
- La hero mostra `assets/images/iscrizione.png`.
- Alberto Zappella è indicato come Vice Presidente.
- Nella sezione Contatti Google Maps è incorporato con iframe sotto il pannello contatti.
- I file `iscrizione.png` e `iscrizione.pdf` sono in minuscolo per compatibilità con Netlify/Linux.


## Ultima modifica
- Menu/header fissato in alto durante tutto lo scroll.
- Logo sempre visibile nella barra di navigazione.
- Rimossa la voce e il codice della Galleria.


## Social
Aggiunta sezione social con collegamenti a:
- Instagram: https://www.instagram.com/asdsoccergatticoveruno/
- Facebook: https://www.facebook.com/profile.php?id=61562465916101
