# Workflow di lavoro (versione semplice)

Questo è il flusso consigliato per consegnare il progetto in modo corretto.

## 1) Fork + branch

1. Fai il **fork** del repository nel tuo account GitHub.
2. Clona il tuo fork sul PC.
3. Crea un branch con il formato richiesto, ad esempio:
   - `3A/stazione-meteo`

## 2) Commit

1. Lavora sul tuo branch.
2. Salva cambi piccoli e chiari con commit frequenti.
3. Usa messaggi corretti (`feat:`, `fix:`, `docs:`).

Esempio:
- `feat: aggiunge menu seriale per calibrazione`

## 3) Pull Request

1. Fai push del branch sul tuo fork.
2. Apri una **Pull Request** verso il repository principale.
3. Nella descrizione indica:
   - cosa hai fatto
   - perché l'hai fatto
   - eventuali foto/schema allegati

## 4) Revisione docente

1. Il docente (CODEOWNERS) controlla la PR.
2. Se ci sono richieste di modifica, aggiorna lo stesso branch.
3. Quando la PR è approvata, si può fare il merge.

---

## Esempio rapido

`fork -> branch 3A/robot-line-follower -> commit feat/fix/docs -> pull request -> revisione docente`
