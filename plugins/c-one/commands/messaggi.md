---
description: I tuoi Messaggi in c-one («messaggi», «mi ha scritto qualcuno?», «rispondi a…»): gli stessi Messaggi dell'app, prima quelli da leggere, con Rispondi e Ho letto.
---

Segui le istruzioni che c-one ti dà nelle descrizioni dei suoi strumenti: una scheda per messaggio, un tasto, mai una scrittura senza il sì della persona.

1. Chiama `messaggi` senza parametri: apre la scheda «Messaggi» (la stessa tabella dei Messaggi dell'app di c-one). Mostra la scheda e scrivi **una riga** tua (il primo da leggere: chi ti ha scritto e su cosa), senza riscrivere i fili.
2. Per rispondere: `rispondi_messaggio` con l'id del filo e il testo, **senza** `conferma` (anteprima), poi aspetta il sì della persona. Per «Ho letto»: `messaggi` con `segna_letti`, anteprima e sì.
3. Per scrivere su un'attività a chi la gestisce (o a chi la fa): `messaggio` con `legato_a` {tipo: attivita | occorrenza, id}; c-one sceglie la persona giusta come l'app.
4. Non inventare messaggi o risposte: se la scheda è vuota, è vuota. Chi guarda soltanto legge e non scrive.

$ARGUMENTS
