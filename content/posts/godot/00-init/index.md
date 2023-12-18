+++
title = 'Moin Godot'
date = 2023-12-17T12:00:00+00:00
draft = false
tags=["hugo","games","programming"]
categories=["godot"]
[cover]
image = "/posts/godot/00-init/fight-godot.png"
+++

Ungeachtet dessen, was bei Unity geschieht, habe ich mich für Godot entschieden. Der Übergang zu einer neuen IDE und Skriptsprache ist eine willkommene Herausforderung. Bisherige Erkenntnisse:

- Jede Entität in Godot ist eine Szene.
- Der Wechsel zwischen 2D und 3D ist nahtlos.

Godot bietet ein intuitives und erfreuliches Entwicklungserlebnis. Die Installation ist simpel, und innerhalb von Minuten kontrollierte ich bereits den Godot-Charakter mit meiner Tastatur.

```c
func _init():
    print("Hello, Godot!")
```

## Das erste 2D Spiel

Auf der Jagd nach weiteren Erkenntnissen erschließe ich die nächste Quest. Das Schreiben eines Dodge Spiels mit einer braunen Qualle. Aber ersteinmal gehen lernen.

![walk](/posts/godot/00-init/walk.gif)

Die Animationen sind schon irgendwie cute. Aber der Flip beim Down-Walk ist schon ein bisschen irritierende. Aber diese Massen an Monstern die ich dann losgelassen habe fühlen sich irgendwie Falsch an. Lag natürlich daran, dass ich die Monster nicht auf dem Ende vom Timer freilasse, sondern mit jedem einzelnen Frame 😶.

## Dann noch schnell in das 3d reingeschnuppert

Ja okay, ich habe jetzt Boxen mit Collidern versehen und cute `Incognitos` gegeneinander antreten lassen. Nette Idee mit dem springen und dem Platzieren von Zylindern außerhalb des `Views` der Kamera.

![squash_3d](/posts/godot/00-init/squash_3d.gif)

Irgendwie bin ich hooked und gespannt auf die nächsten Schritte. Ich habe noch überhaupt keinen Überblick, welche Nodes wie verstrickt werden können und bin ein bisschen von dem Kamera-Pivot irritiert... Aber ich werde ihn verwenden und schauen was passiert

## Das eigene Spiel

Nun ist es Zeit, ein Spielkonzept zu entwickeln und einen schnellen Proof of Concept zu starten.
