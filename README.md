# Passwort-Generator

Ein Python-Skript zur Generierung und Versendung von sicheren Passwörtern per E-Mail.

## Beschreibung

Dieses Projekt beinhaltet ein Python-Skript, das ein zufälliges Passwort generiert, sich in ein Gmail-Konto einloggt und das generierte Passwort per E-Mail an den Benutzer sendet. Das Skript bietet auch eine Funktion `Password12`, die es dem Benutzer ermöglicht, ein benutzerdefiniertes Passwort zu erstellen, basierend auf verschiedenen Kriterien wie Länge, enthaltene Zeichenarten (Zahlen, Großbuchstaben, Kleinbuchstaben, Sonderzeichen).

## Funktionen

- **Automatische Passwortgenerierung:** Erzeugt ein zufälliges Passwort mit einer Länge von 16 Zeichen, das Zahlen, Großbuchstaben, Kleinbuchstaben und Sonderzeichen enthält.
- **E-Mail-Versand:** Sendet das generierte Passwort per E-Mail an die angegebene Empfängeradresse.
- **Benutzerdefinierte Passworterstellung:** Ermöglicht es dem Benutzer, ein Passwort nach eigenen Wünschen zu erstellen, indem er die enthaltenen Zeichenarten und die Länge angibt.

## Voraussetzungen

- Python 3.x
- Bibliotheken: `string`, `random`, `smtplib`, `email`, `time`

## Installation

1. Klonen Sie das Repository:

```bash
git clone https://github.com/Alfayad96/Passwort-Generator.git
