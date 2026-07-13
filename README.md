<p align="center">
  <img src="assets/logo.png" alt="Diario logo" width="120">
</p>

<h1 align="center">PelviNote</h1>

Una semplice web app (PWA) per tenere traccia di eventi urinari durante la giornata. Utile per monitoraggi medici, diari minzionali o semplice tracciamento personale della salute.

Nessun server, nessun account: tutto funziona nel browser e i dati vengono salvati in locale sul dispositivo.

## Funzionalità

- Registrazione rapida con un tap tramite 5 pulsanti dedicati
- Statistiche giornaliere con conteggio automatico per ogni categoria
- Registro cronologico raggruppato per giorno, con orario e intervallo di tempo dall'evento precedente (es. `+15min`, `+2h 30min`)
- Esportazione in PDF del diario per condividerlo facilmente con il proprio medico
- Eliminazione di singole voci o svuotamento completo del registro
- Salvataggio automatico nel `localStorage` del browser: i dati restano sul dispositivo anche chiudendo l'app
- PWA installabile: può essere aggiunta alla schermata home su iOS/Android come un'app nativa

## Come usarla

1. Apri il file `index.html` in un browser (oppure ospita la cartella su un servizio statico come GitHub Pages).
2. Tocca il pulsante corrispondente ogni volta che si verifica un evento.
3. Consulta le statistiche del giorno e il registro cronologico in tempo reale.
4. Usa "Esporta PDF" per generare un report stampabile, o "Svuota" per azzerare il diario.

### Installazione come app (PWA)

Su smartphone, apri la pagina nel browser e seleziona "Aggiungi a schermata Home" (iOS Safari) o "Installa app" (Android Chrome) per usarla come un'app a schermo intero.
