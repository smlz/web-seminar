# TFBern Web Seminar

## Links

* Vue: https://vuejs.org
* Node.js: https://nodejs.org

## Installation Node.js

* Node.js mit dem [Paktemanager installieren](https://nodejs.org/en/download/package-manager/)

* Standartverzeichnis von Node.js anpassen
    1. Ein Ordner für die globale Installation erstellen: `mkdir ~/.npm-global`
    1. Npm mit dem neuen Pfad konfigurieren: `npm config set prefix '~/.npm-global'`
    1. In der Datei _~/.profile_ folgende Zeile einfügen: `export PATH=~/.npm-global/bin:$PATH`
    1. System Variablen aktualisieren: `source ~/.profile`

* vue-cli installieren `npm install -g vue-cli`

* Projekt mit `vue-cli` initialisieren:

```
cd code
vue-cli init webpack-simple mein-projekt
# Fragen beantworten

cd mein-projekt
npm install
```

* Entwicklungsserver starten: `npm run dev`
