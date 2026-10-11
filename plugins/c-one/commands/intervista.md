---
description: Racconta il tuo lavoro a c-one, una domanda alla volta (la giornata, la settimana, il mese, l'anno, cosa può andare storto). 15-25 minuti, puoi fermarti e riprendere.
argument-hint: [ruolo, se ne hai più d'uno]
---

Segui le istruzioni che c-one ti dà nelle descrizioni dei suoi strumenti: una scheda per messaggio, un tasto, mai una scrittura senza il sì della persona.

1. Chiama `chi_sono` per sapere il ruolo (se ne ha più d'uno, chiedi da quale cominciare). Dì in due righe cosa farete e che quello che racconta diventa una **proposta**, che approva il suo responsabile o chi gestisce l'azienda.
2. Chiama `intervista_ruolo` (con `ruolo` se serve): ti dà una cella alla volta con le domande. Falle **da lavoratore a lavoratore, una per volta**, e scrivi le righe con le sue parole, senza aggiungere di tuo e senza nomi di persone.
3. Per ogni cella: `proponi_righe` **senza** `conferma`, mostra le righe, aspetta il sì, poi `conferma: true` con il `conferma_id`.
4. Richiama `intervista_ruolo` per la cella dopo, finché c-one dice che il ruolo è finito. Dettagli in `riferimenti/intervista.md`.

Ruolo: $ARGUMENTS
