# Il cervello che suona — Brain Project adattato

Questa è una modifica del progetto open source Brain Project (autore Itay Inbar), con schede divulgative italiane dedicate all'esecuzione musicale.

## Avvio
Pubblicare la cartella `brain-atlas` su un hosting statico (per esempio GitHub Pages) oppure avviare un server HTTP locale nella cartella: `python3 -m http.server 8000`, quindi aprire `http://localhost:8000`.

Il modello GLB è incluso; le librerie JavaScript React, Three.js e Babel vengono caricate da CDN e richiedono connessione Internet.

## Funzionamento
- Clic su una regione anatomica 3D: se corrisponde a una delle strutture musicali, si apre una scheda italiana.
- Menu `IL CERVELLO CHE SUONA`: seleziona una struttura e orienta la vista verso la regione corrispondente.
- Alcune regioni funzionali (premotoria, SMA, prefrontale) non sono delimitate esattamente nell'atlante anatomico; la scheda lo segnala.

## Licenze
Codice originale Brain Project: Apache-2.0; dati anatomici secondo attribuzioni e licenze dichiarate nel README originale, fra cui CC BY-SA 4.0. Mantenere gli avvisi di attribuzione in eventuali pubblicazioni.
