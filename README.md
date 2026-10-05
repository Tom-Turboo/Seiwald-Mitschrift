# Seiwald-Mitschrift

Mitschrift Imcm

- text=auto
  das ist die README.md Datei MD steht für Markdown, eine einfache Auszeichnungssprache (Markup Language) [https://de.wikipedia.org/wiki/Markdown](https://de.wikipedia.org/wiki/Markdown)

weitere bekannte Auszeichnungssprachen sind:

- HTML (Hypertext Markup Language)
- XML (Extensible Markup Language)
- yaml (YAML Ain't Markup Language)

# Installation von nodeJS

Javascript läuft unter normalen Unständen in einer Browser-Sandbox (nur im Browser). Seit ca. 2010 gibt es eine Laufzeitumgebung (_Runtime Enviroment_) für JS, damit man auch serverseitig JS programmieren und ausführen kann: [Node.js](www.https://nodejs.org/en)

## Installation von pnpm

Der standarmäßige Paketmanager von nodeJS ist npm (Node Package Manager). Es gibt aber auch Alternativen, wie z.B. pnpm (Performant NPM), das schneller und effizienter sein soll als npm: [https://pnpm.io/](https://pnpm.io/)

## Installation von strapi

Installation mit pnpm: `pnpm create strapi daraufhin führt das CLI (_Comand Line Interface_) durch die Installation.
Fallss bei der Installation sogenannte build scripts nicht ausgeführt werden können, schlägt die CLI die Fehlerbehandlung selbständig vor:

1. Wechsele in das Installationsverzeichnis (z.B. mit `cd strapi-project`)
2. Führe den Befehl `pnpm install` aus, um die fehlenden Pakete zu installieren und die Build-Skripte auszuführen. Dieser scheitert in der Regel - die Build-Skripte müssen mit pnpm approve-builds manuell freigegeben werden.

---

# Historische Entwicklung von WebDev

Webdecelopment hat im Laufe der letzten 35 Jahre viele verschiedene Phasen durchlaufen.

1. Statische Website (HTML, CSS, JS) - initale Phase des Webdevelopments
2. Dynamische Website (mit Serverseitiger Programmiersprach - PHP, Python, NodeJS - und Datenbananbindung). Dominante Phase des Webdevelopments in 2000 Jahren.
3. Single-Page-Applications (SPA) - mit JS-Frameworks erstellte "Webapps", die klassische Desktop-Anwendungen bzw, Handyapps bieten. Dominante Phase des Webdevelopments in 2010 Jahren.

# VibeCoding / AgenticEngineering mit VS-Code und GitHub Copilot

VibeCoding passiert in VS-Code in erster Linie über die neu eingeführte Agent View.
Dort können alle Anpassungen des "_Coding Harrness_" vorgenommen werden. Wir können unseren _Harness_ mit verschiedenen Methohden anpassen:

- **MCP-Server**: MCP shteth fpr _Model Context Protocoll_. Es ist ein Standard, der von Anthropic entwickelt wurde. Mit hilfe con MCP können Chatots/LLMs (_Large Language Models_) auf zustätliche Tools zugreifen, die sie zu Experten in einem besitmmten Themenbereich machen.
