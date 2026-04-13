# Specifica `project.yaml` per i progetti

Ogni progetto deve includere un file `project.yaml` nella root del progetto (in alternativa, è possibile usare gli stessi campi come **front matter** nel `README.md`).

## Campi obbligatori

- `titolo` *(stringa)*: nome del progetto.
- `classe` *(stringa)*: classe destinataria (es. `3A ITI`, `2B Liceo Scientifico`).
- `anno_scolastico` *(stringa)*: anno di riferimento in formato `YYYY-YYYY`.
- `livello` *(enum)*: uno tra `base`, `intermedio`, `avanzato`.
- `argomenti` *(lista di stringhe)*: macro-temi trattati (es. `sensori`, `attuatori`, `seriale`, `IoT`).
- `durata_ore` *(numero intero)*: stima ore totali.
- `valutazione` *(lista di stringhe)*: criteri principali di valutazione.

## Esempio (`project.yaml`) compilato

```yaml
titolo: "Serra smart con ESP32"
classe: "4A Informatica"
anno_scolastico: "2025-2026"
livello: "intermedio"
argomenti:
  - "sensori"
  - "attuatori"
  - "IoT"
  - "seriale"
durata_ore: 10
valutazione:
  - "Acquisizione corretta dei dati ambientali"
  - "Controllo automatico di pompa/ventola"
  - "Qualità del codice e documentazione"
  - "Presentazione finale e troubleshooting"
```

## Variante in front matter (`README.md`)

```md
---
titolo: "Serra smart con ESP32"
classe: "4A Informatica"
anno_scolastico: "2025-2026"
livello: "intermedio"
argomenti: ["sensori", "attuatori", "IoT", "seriale"]
durata_ore: 10
valutazione:
  - "Acquisizione corretta dei dati ambientali"
  - "Controllo automatico di pompa/ventola"
  - "Qualità del codice e documentazione"
---
```

> Nota: usare sempre gli stessi nomi campo per uniformare raccolta, ricerca e confronto tra progetti.
