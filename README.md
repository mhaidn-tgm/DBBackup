DBBackup
========

Evaluierung und Dokumentation der Backup-Tools für MySQL und Postgres.


Aufgabenstellung
----------------

Untersuchen Sie die Backup-Tools von MySQL (mysqldump, mysqlhotcopy, ibbackup) und PostgreSQL (pg_dump) und lösen Sie folgende Aufgaben:


1. Finden und dokumentieren Sie (für ihr System OS/DBMS) die etsprechenden Optionen der Tools für folgende Anforderungen:
  - Speichern einer/mehrerer/aller Datenbanken des Systems in einer Datei mit/ohne Datenbankstruktur, Trigger und Stored-Routines
  - Verwendung der "IF EXISTS"- und "DROP"-Klausel unter MySQL bzw. PostgreSQL
  - Logisches vs. Physisches Backup: Was sind die Vor- bzw. Nachteile der beiden Arten und worauf muss man achten
  - Online-Backup: Wie kann man einen Dump der DB während des Betriebs ausführen (Locking, ...)


2. Wie können Sie auf gemieteten DB-Servern (remote) ebenfalls Backups ausführen? Geben Sie zwei Möglichkeiten an.
3. Wie könnte man die Backupvarianten aus Punkt 1 automatisieren (Uhrzeit als Trigger)? Geben Sie entsprechend für ihr Betriebssystem (Windows, Linux, Mac, ...) Möglichkeiten an.
  - Verwendung eines Zeitstempels zur Speicherung der Dumps (in den Filenamen inkludiert; z.B. DBNAME_20100413_0952.sql)

Abgaberichtlinien:

- PDF-Dokument, ca. 15 Seiten, formatiert und strukturiert ähnlich wie das Technik-/Machbarkeits-Kapitel der Diplomarbeit (Zitate, Quellen, Fußnoten, Tabellen, Grafiken, Screenshots, Inhaltsverzeichnis, ...)
- Bitte in Zweier-Teams arbeiten, alle im Team mitarbeitenden Autoren müssen aber in der Lage sein, jedes Thema/Detail auch selbst zu präsentieren.
- Arbeitsaufwand ca. 10 Stunden pro Team.
- Präsentation am 9.12.2014
