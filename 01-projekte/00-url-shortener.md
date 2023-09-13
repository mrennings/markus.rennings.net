# URL-Shortener

Das zweite Projekt innerhalb meiner DevOps-Weiterbildung war ein Full-Stack-Projekt mit freier
Gruppenwahl (max. fünf Personen) und Themenauswahl aus einem Pool. Meine Gruppe bestand aus
[Deniz Durmaz](https://github.com/Aquilero), [Jason Krimmel](https://github.com/xKatsuoo),
Sebastian Hufeld, Andreas Brühl und mir. Wir haben uns – als einzige – als Thema den URL-Shortener
ausgesucht.

## Anforderungen der Aufgabe

- URL-Kürzung
  - Implementierung eines Algorithmus zur Generierung kurzer Links aus eingegebenen URLs.
  - Generierung von eindeutigen und nicht leicht vorhersagbaren Kurzlink-Codes
- Benutzeroberfläche
  - Erstellung einer benutzerfreundlichen Web-Oberfläche zur Eingabe und Generierung von Kurzlinks.
  - Möglichkeit zur Anzeige von bereits erstellten Kurzlinks.
- Datenbank
  - Speicherung der ursprünglichen URLs und zugehörigen Kurzlinks in einer Datenbank.
  - Verknüpfung der Kurzlinks mit eindeutigen Schlüsseln (Keys).
- API
  - Entwicklung einer API zur Interaktion zwischen Frontend und Backend für das Erstellen von Kurzlinks und Abrufen von Statistiken.
- URL-Validierung
  - Implementierung einer URL-Validierung, um sicherzustellen, dass die eingegebenen URLs gültig sind.
- Statistik und Analyse
  - Sammlung und Speicherung von Daten über Klicks auf generierte Kurzlinks.
  - Generierung detaillierter Statistiken, einschließlich Anzahl der Klicks, Zeitpunkt der Nutzung und OS & Browser der Nutzer.
- Passwort für Link-Bearbeitung und Statistik
  - Generierung eines eindeutigen Schlüssels/Passworts für jeden generierten Kurzlink.
  - Mit dem Schlüssel/Passwort können Benutzer den Link bearbeiten und die Statistiken einsehen.

## Meine Aufgabe

Ich habe mich bei diesem Projekt um die API/das Backend gekümmert. Dazu gehörten das API-Design, das Erstellen des Backends, inkl. der Routen. Auch um die Auswertung der Clients für die Statistiken habe ich mich mit gekümmert.

Zur Dokumentation der API habe ich mich in OpenApi eingelesen und eine entsprechende Datei (yaml) erstellt. Für die [Projektdokumentation (PDF, 276 kB)](media/files/gruppe-3-shorties.pdf){.tm-download file-pdf} habe ich meine XeLaTeX-Kenntnisse – welche ich teilweise schon vergessen hatte – wieder aufgefrischt. Für die gemeinsame Arbeit habe ich auf [GitHub ein Repo](https://github.com/aws2302/P2){target="_blank"} erstellt.
