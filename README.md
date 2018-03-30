# My Personal Synth

Il "mio synth personale" è un piccolo progetto didattico per realizzare
un semplice sintetizzatore con Arduino e un circuito dotato di:

* 2 LED di colore diverso
* 1 SWITCH (o pulsante) che consenta di accendere alternativamente uno dei 2 LED
* 1 POTENZIOMETRO che possa variare durata o frequenza di un suono a seconda del LED attivo
* 1 BUZZER PASSIVO che emetta il suono della durata e frequenza impostata tramite POTENZIOMETRO a seconda del LED ATTIVO

## Files

I files presenti nel repository sono:

* `mysynth.ino`: codice completo del sintetizzatore (con funzione map personalizzata volutamente non attiva e non funzionante)
* `mysynth.ino-simple.ino`: codice semplificato senza debounce per lo SWITCH e senza funzione `map` personalizzata
* `debounce.ino`: codice di test per effettuare il debounce della lettura dallo SWITCH: eliminazione dei disturbi, detti in questo caso rimbalzi

## Consegna

Di questo lavoro si consengerà:

* diagramma di flusso
* pseudo-codice
* codice
* descrizione

per martedi successivo alla Pasqua, giorno nel quale ci sarà il compito in classe sui temi relativi.

NOTA: il diagramma di flusso e lo pseudo-codice devono essere realizzati senza vedere il codice finale
che deve servire solo come termine di paragone dopo che l'alunno ha provato a scrivere autonomamente il programma.

Sia il diagramma di flusso che lo pseudo-codice sono passaggi che non riguardano il codice specifico,
ma si avvicinano ad esso e ci danno strumenti per implementarlo, per questo è necessario evitare ogni qual volta
possibile di mettere righe di codice e dettagli sia nel diagramma che nel codice.

Va bene che l'alunno scriva il programma senza funzionalità "debounce".


