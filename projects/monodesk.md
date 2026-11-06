# Monodesk

**Eigenprojekt · Desktopanwendung · Quellcode derzeit nicht öffentlich**

## Ausgangspunkt

Bei der Arbeit mit Coding-Agenten gehören Aufgaben, Dateien, Terminals und Prüfergebnisse zusammen. Wenn mehrere Agenten gleichzeitig Änderungen vorbereiten, muss außerdem nachvollziehbar bleiben, wer an welchem Stand arbeitet und welche Prüfungen dazu gehören.

## Umsetzung

Monodesk verbindet eine Angular-Oberfläche mit Electron und einem Node.js-/Express-Backend. Dateibaum, Editor, Dokumentenvorschau, Kanban und Terminal stehen in einer gemeinsamen Arbeitsumgebung zur Verfügung. KI-Modelle und Coding-Agenten werden über Schnittstellen und MCP angebunden.

Für parallele Arbeiten kommen getrennte Git-Worktrees zum Einsatz. Werkzeugrechte und Hooks begrenzen Aktionen; Prüfabläufe verknüpfen Änderungen mit Tests und Reviews. Dokumentierte Regeln werden an ausgewählten Stellen durch automatisierte Tests mit der Implementierung abgeglichen.

## Mein Beitrag

Ich konzipiere und entwickle die Anwendung mit KI-Programmierassistenten. Dazu gehören Oberfläche, Backend, Integration der Werkzeuge sowie die Weiterentwicklung der Prüf- und Freigabeabläufe. Ich strukturiere die Aufgaben und prüfe die Ergebnisse.

## Technische Entscheidungen

- **Electron und Angular:** Desktopfunktionen und eine gemeinsame Oberfläche für unterschiedliche Arbeitswerkzeuge.
- **Git-Worktrees:** getrennte Arbeitsstände bei paralleler Bearbeitung.
- **Hooks und Tests:** prüfbare Regeln für Aktionen und Übernahme von Änderungen.
- **Dokumentation mit Prüfungen:** Änderungen am Verhalten sollen nicht unbemerkt zu veralteten Anleitungen führen.

## Stand und Grenzen

Monodesk ist eine laufend weiterentwickelte eigene Arbeitsumgebung. Die hier beschriebene Desktopversion richtet sich an macOS auf Apple Silicon. Diese Beschreibung ist kein öffentliches Release und keine Aussage über eine allgemeine Fehlerfreiheit oder einen vollständigen Sicherheitstest.

[Zurück zum Profil](https://github.com/OnurUenal)
