---
description: Mostra il tuo Oggi in c-one: la prima cosa da fare, quello che è in ritardo, le procedure da leggere e le novità per te.
---

Segui le istruzioni che c-one ti dà nelle descrizioni dei suoi strumenti: una scheda per messaggio, un tasto, mai una scrittura senza il sì della persona.

1. Chiama `oggi` e `novita_per_me` insieme. Se l'utente ha scritto che è appena arrivato al lavoro, chiama invece SOLO `inizio_turno` senza `conferma` (una scheda sola, con il tasto «Apro il turno») e scrivi una riga.
2. Mostra la scheda di c-one, senza riscrivere le righe. Una frase tua: la prima cosa da fare e, se c'è, cosa è in ritardo.
3. Se l'utente gestisce l'azienda e non ha detto cosa vuole, chiama `prossima_azione_consigliata`.
4. Questo comando legge soltanto: non registra niente.

$ARGUMENTS
