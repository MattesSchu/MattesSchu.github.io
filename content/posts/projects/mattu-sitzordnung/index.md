+++
title = 'Mattu-Sitzordnung - wie kann ich Schüler im Klassenraum verteilen'
date = 2024-01-21T12:00:00+00:00
draft = false
tags=["project", "finance", "vue"]
categories=["projects"]
[cover]
image = "thumbnail.png"
+++

Ein sehr kleines Tagesprojekt, um SchülerInnen mit ihren FreundInnen im Klassenraum zu verteilen.

- <https://mattesschu.github.io/mattu-sitzordnung/>

## Aufbau

Erst wird eine Liste mit einer beliebigen Anzahl an SchülerInnen erstellt. Dabei kann als "FreundIn" immer nur ein/e bestehende/r SchülerIn zugewiesen werden. Also am besten erst einmal alle SchülerInnen mit Namen anlegen und danach deren FreundIn zuordnen.

Beim Erstellen der Liste wird gleichzeitig der "Klassenraum" befüllt. Immer wenn ein/e SchülerIn in "FRONT", "MIDDLE" oder "BACK" zugewiesen wurde, erscheint der Nane in der Klassenraum Übersicht.

Bei Bedarf kann eine `Freunde Metrik` aktiviert werden, die zu jeder Sitzreihe ("FRONT", "MIDDLE", "BACK") die gewollten "Freunde/innen" anzeigt.

## Ergebnis

Abschließend wir versucht die Zufriedenheit der SchülerInnen abzubilden. Diese gibt an, wie viele angegebene FreundInnen in der gleichen Reihe wie die eigene Person sitzt.

## ToDo's

Es ist nur ein Versuch für eine Klassenraumplanung und es fehlen noch seeeehr viele Dinge. Mögliche Ideen:

- Eine Liste, die die Überschreibung der Sitzplätze darstellt, damit der ursprüngliche Wunsch ersichtlich bleibt
- Variable Reihen
- Einen individuellen Klassenraum mit graphischen Sitzplätzen
- Erweiterte Auswertung
- Einen Vorschlag nach Algorithmen erstellen
- Speicher und Laden der Listen
