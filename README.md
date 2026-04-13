# arduino

## 1. Scopo del repository
Questo repository è pensato per **uso didattico**: raccoglie progetti Arduino organizzati in modo uniforme per facilitare studio, revisione e manutenzione.

- **Destinatari:** studenti, docenti e tutor di laboratori Arduino.
- **Obiettivo:** imparare a strutturare un progetto embedded in modo chiaro e replicabile.
- **Lingua di riferimento:** italiano (documentazione e naming descrittivo dove possibile).

## 2. Struttura delle cartelle
Ogni progetto deve vivere in una cartella dedicata, con una struttura prevedibile.

```text
arduino/
├── README.md
└── projects/
    ├── nome-progetto-01/
    │   ├── README.md
    │   ├── sketch/
    │   │   └── nome-progetto-01.ino
    │   ├── schema/
    │   │   ├── schema.png
    │   │   └── collegamenti.md
    │   └── componenti/
    │       └── lista-componenti.md
    └── nome-progetto-02/
        └── ...
```

> Nota: se la cartella `projects/` non esiste ancora, creala prima di aggiungere il primo progetto.

## 3. Come aggiungere un nuovo progetto
Passi concreti consigliati:

1. Crea la cartella progetto in `projects/` usando un nome breve e descrittivo (kebab-case).
2. Crea le sottocartelle minime: `sketch/`, `schema/`, `componenti/`.
3. Inserisci lo sketch Arduino in `sketch/` con nome coerente al progetto.
4. Aggiungi lo schema elettrico in `schema/` (immagine/PDF) e una nota testuale dei collegamenti.
5. Crea `componenti/lista-componenti.md` con elenco materiale e quantità.
6. Scrivi il `README.md` locale del progetto (obiettivo, requisiti, upload, test rapidi).
7. Verifica che il progetto sia autoesplicativo anche per chi lo apre per la prima volta.

## 4. Convenzioni di naming
Per mantenere coerenza nel tempo:

- **Cartelle progetto:** `kebab-case` (es. `semaforo-pedonale`).
- **File sketch Arduino:** stesso nome della cartella progetto (es. `semaforo-pedonale.ino`).
- **File Markdown descrittivi:** nomi espliciti in minuscolo (es. `lista-componenti.md`, `collegamenti.md`).
- **Branch Git:**
  - nuove feature: `feature/<nome-breve>`
  - fix: `fix/<nome-breve>`
  - documentazione: `docs/<nome-breve>`

## 5. Requisiti minimi per ogni progetto
Ogni progetto deve includere almeno:

1. **README locale** (`projects/<nome-progetto>/README.md`) con:
   - scopo del progetto,
   - componenti principali,
   - istruzioni di compilazione/upload,
   - eventuali note di test.
2. **Schema elettrico** nella cartella `schema/` (immagine o PDF).
3. **Lista componenti** in `componenti/lista-componenti.md` con quantità minime.

## Esempio pratico completo
Esempio reale di percorso che gli studenti possono replicare senza ambiguità:

```text
projects/semaforo-pedonale/
├── README.md
├── sketch/
│   └── semaforo-pedonale.ino
├── schema/
│   ├── schema-semaforo-pedonale.png
│   └── collegamenti.md
└── componenti/
    └── lista-componenti.md
```

Checklist veloce:
- il nome cartella e il file `.ino` coincidono;
- README locale presente;
- schema presente;
- lista componenti presente.


## 6. Template riusabile per nuovi progetti
Per iniziare rapidamente usa `templates/project-template/` e copialo nella cartella del progetto:

```text
templates/project-template/
├── README.md
├── src/
│   └── main.ino
├── BOM.md
└── REPORT.md
```

