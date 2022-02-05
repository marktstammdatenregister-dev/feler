---
name: Gesamtdatenexport
about: Melde ein Problem in einer Gesamtdatenexport-Datei.
title: "[Export]"
labels: export
assignees: ''

---

# Beschreibe das Problem

Ein kurze Beschreibung des Problems.

# Wie kann man das Problem reproduzieren?

So kann man das Problem nachvollziehen:

1. Gesamtdatenexport_XXX_YYY_ZZZ.zip herunterladen.
2. ABC.xml entpacken.
3. Suche nach "XYZ" in ABC.xml. Es kommt nur ein einziges Mal vor.

# Was hast du stattdessen erwartet?

Zum Beispiel: "XYZ" sollte mindestens dreimal in ABC.xml vorkommen.

# Konsolenausgabe

Die Ausgabe eines Konsolenprogramms kann sehr hilfreich sein, um das Problem eindeutig zu beschreiben. In diesem Fall zum Beispiel:

```console
$ unzip Gesamtdatenexport_XXX_YYY_ZZZ.zip ABC.xml
$ grep 'XYZ' 'ABC.xml'
[... Ausgabe von grep hier ...]
```

# Verweise

- Dateiname des Gesamtdatenexports, idealerweise mit Archivlink, zum Beispiel: [Gesamtdatenexport_20220203__840cfde7b693453982d28db827025ff0.zip](https://s3.eu-central-1.wasabisys.com/mastr-backup/Gesamtdatenexport_20220203__840cfde7b693453982d28db827025ff0.zip)
- (Falls relevant) Direkter Archivlink zum relevanten Abschnitt in der Dokumentation, zum Beispiel: [Version 1.0.1, Abschnitt 5.6.1: EinheitenWind](https://web.archive.org/web/20211222091956if_/https://www.marktstammdatenregister.de/MaStRHilfe/files/gesamtdatenexport/Dokumentation%20MaStR%20Gesamtdatenexport.pdf#%5B%7B%22num%22%3A46%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22XYZ%22%7D%2C68%2C542%2C0%5D)
