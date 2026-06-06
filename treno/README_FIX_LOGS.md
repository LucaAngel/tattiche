# Fix log e storico Agenda Treno 4ITA

File inclusi:
- treno/index.html
- treno/agenda-treno-log.txt

Caricare/sostituire `treno/index.html` nel repository.
Se il file `treno/agenda-treno-log.txt` non esiste, caricarlo una prima volta.

Il frontend invia al Worker `logLines` e `logPath: treno/agenda-treno-log.txt`.
Il Worker deve supportare l'append del log testuale per scrivere realmente il file.
