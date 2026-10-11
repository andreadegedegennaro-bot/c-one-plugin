---
description: Apri o chiudi il tuo turno in c-one («sono arrivato» / «ho finito»): l'Oggi del turno, le consegne di chi c'era prima e quelle che lasci a chi arriva dopo.
argument-hint: [inizio | fine | domani dalle … alle …]
---

Segui le istruzioni che c-one ti dà nelle descrizioni dei suoi strumenti: una scheda per messaggio, un tasto, mai una scrittura senza il sì della persona.

- **Inizio** («sono arrivato», «inizio»): SOLO `inizio_turno` senza `conferma` (mai `apertura_turno` o `oggi` prima: una scheda sola). Se lavori in più strutture chiedi dove. La scheda Oggi mostra la giornata, le **consegne** di chi c'era prima e in cima il tasto «Apro il turno»: scrivi una riga («Ecco il tuo turno: premi “Apro il turno” quando ci sei.»). Il clic apre la presenza nella scheda stessa; se la persona dice «sì» in chat, `conferma: true` con il `conferma_id` e una riga, senza ridisegnare l'Oggi. Dove le schede non si vedono: l'anteprima in una riga e «Apro il turno?».
- **Fine** («ho finito», «vado»): `fine_turno` senza `conferma`: c-one propone le cose rimaste aperte come consegne per chi arriva dopo. Mostrale una per una (mai nomi di persone), la persona corregge, sì, poi `conferma: true`.
- **I turni dei prossimi giorni** («domani lavoro dalle … alle …»): `turni_prossimi` con l'elenco in anteprima. Se non coincidono con quelli dichiarati dal responsabile, vince il responsabile: dillo.

Non è un cartellino né un sistema paghe: serve a c-one per sapere chi c'è.

$ARGUMENTS
