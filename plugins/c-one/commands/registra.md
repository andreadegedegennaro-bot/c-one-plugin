---
description: Registra una cosa che hai fatto (con l'esito) nell'Oggi di c-one. Prima ti mostro cosa registro, poi aspetto il tuo sì.
argument-hint: [cosa hai fatto]
---

Segui le istruzioni che c-one ti dà nelle descrizioni dei suoi strumenti: una scheda per messaggio, un tasto, mai una scrittura senza il sì della persona.

1. Se l'utente ha detto cosa ha fatto, cercalo in `oggi` (o `cerca_procedura`). Se due voci possono essere quella, chiedi quale. Se non ha detto niente, chiedilo.
2. Chiedi l'**esito con le sue parole**, se serve. Non scrivere mai un esito che non ha detto lui.
3. Chiama `registra` **senza** `conferma`, mostra l'anteprima (cosa, quando, esito) e chiedi: «Confermi?».
4. Solo dopo il suo sì, richiama con `conferma: true` e lo stesso `conferma_id`. Una registrazione alla volta: per più cose, mostra l'elenco e fai un sì per quell'elenco.
5. Se c-one dice che la volta non è sua, riportalo com'è.

Cosa ha fatto: $ARGUMENTS
