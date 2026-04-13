# Come contribuire al progetto

Grazie per il tuo contributo! Questo file spiega **regole semplici** per lavorare in modo ordinato nel repository.

## 1) Nome del branch

Usa sempre un nome branch nel formato:

`classe/nome-progetto`

Esempi:
- `3A/robot-line-follower`
- `3B/stazione-meteo`
- `4A/app-sensore-temperatura`

> Suggerimento: usa parole brevi e separate da `-`.

---

## 2) Messaggi di commit

Ogni commit deve iniziare con un tipo chiaro:

- `feat:` per una nuova funzionalità
- `fix:` per una correzione
- `docs:` per modifiche alla documentazione

Esempi:
- `feat: aggiunge lettura del sensore ultrasuoni`
- `fix: corregge il pin del buzzer nel codice`
- `docs: aggiorna istruzioni di montaggio nel README`

Regola pratica: il messaggio deve spiegare **cosa hai fatto** in una sola riga.

---

## 3) Checklist prima del commit

Prima di fare `git commit`, controlla sempre:

- [ ] Il progetto compila senza errori
- [ ] Il `README.md` è aggiornato (se hai cambiato uso o struttura)
- [ ] Hai allegato foto/schema utili nella PR (se richiesti dal docente)

Se anche solo un punto non è completo, risolvi prima e poi fai il commit.

---

## Mini esempio completo

1. Creo branch: `git checkout -b 3A/robot-line-follower`
2. Faccio modifiche al codice
3. Verifico la checklist
4. Commit: `git commit -m "feat: aggiunge controllo motori base"`
5. Push e apro la Pull Request

Buon lavoro! 🚀
