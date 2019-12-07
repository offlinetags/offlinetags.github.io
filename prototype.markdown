---
layout: page
title: Prototype
permalink: /prototype/
---

Die Offlinetags-Software nimmt in festgelegten Intervallen ein Foto über deine Webcam auf. Auf diesem Bild sucht die Software nun nach Gesichtern und den Tags. Wenn Gesichter und Tags gefunden wurden, werden diese noch einander zugeordnet und die Gesichter werden mit einer entsprechenden Markierung versehen:

* Tag Me: Ein grüner Rahmen wird um das Gesicht gezeichnet.
* Blur Me: Ein blauer Rahmen wird um das Gesicht gezeichnet. Zusätzlich wird das Gesicht unkenntlich gemacht.
* Upload Me: Ein gelber Rahmen wird um das Gesicht gezeichnet. Zusätzlich wird der Text „Upload me!“ eingeblendet.
* No Photos: Das Gesicht wird mit einem roten Kreuz versehen.

Wenn ein Gesicht keinem Tag zugeordnet werden konnte, wird dieses mit einem durchsichtigen Fragezeichen über dem Gesicht gekennzeichnet.

Die Software (und deren Funktionsumfang) ist momentan lediglich ein Prototyp zur Demonstration der Offlinetags ouf der re:publica. Ein Beispiel dafür ist, dass sich die Software momentan noch aufhängt, wenn keine Webcam angeschlossen ist.

## Installation (Windows only):

Ein Doppelklick auf die „setup.exe“ startet den Installationvorgang. Dort kannst du auswählen, wohin die Software installiert werden soll. Über die Datei „Offlinetags.exe“ das Programm starten.

## Steuerung:

* Strg + Leertaste: Hält das Programm an und lässt es auch wieder weiter laufen.
* Alt + Enter: Wechselt in den Vollbildmodus und wieder zurück.
* Strg + Alt + O: Blendet das Optionenfenster ein und wieder aus.

## Optionen:

* _Device_: Steuert eine andere Kamera an. Falls diese nicht gefunden wird, wird die Standardkamera weiter benutzt.
* _Intervall_: Gibt an, in welchem Intervall die Aufnahmen gemacht werden (in ms).
* _Blur_: Bei schlechten Ergebnissen kann das Bild verwischt werden. Davon siehst du aber bei der Benutzung nichts.
* _Contrast and Brightness_: Das Bild kann in 4 verschiedenen Stufen nach Tags durchsucht werden. Dafür kannst du jeweils einen individuellen Kontrast und eine Helligkeit einstellen. Das solltest du dann  machen, wenn ein oder mehrere Tags nicht gefunden werden. Die Änderungen kannst du bei der Benutzung nicht direkt sehen.
* _Faces_: Zeichnet einen Rahmen um alle gefundenen Gesichter. Das solltest du aktivieren, wenn du nicht alle oder zu viele Gesichter findest. Danach kannst du „Blur“ aktivieren und schauen, ob sich das Ergebnis verbessert.
* _Circles_: Zeichnet Kreise um alle gefundenen Kreise im Bild. Zur Erkennung der Tags werden zunächst alle Kreise im Bild durchsucht. Das solltest du aktivieren, wenn du zu wenige oder fehlerhafte Tags findest. Danach kannst du „Blur“ aktivieren, Kontrast und Helligkeit variieren oder die Einstellungsmöglichkeiten vom „Circle Detector“ verändern um das Ergebnis zu verbessern.
* _Tags_: Zeichnet entsprechend gefärbte Kreise um alle gefundenen Tags. Das solltest du aktivieren, wenn du zu wenige oder fehlerhafte Tags findest. Danach kannst du „Blur“ aktivieren, Kontrast und Helligkeit veriieren oder die Einstellungen vom „Tag Detector“ ändern, um dein Ergebnis zu verbessern.
* _Result_: Zeichnet die entsprechenden Markierungen auf die gefundenen Gesichter. Das kannst du deaktivieren, wenn du grade Einstellungen änderst und testen möchtest.
* _Circle Detector_: Diese Parameter sind nur für erfahrene Benutzer empfohlen. Eine genauere Definition findest du hier: <http://tinyurl.com/6nlrpo8>
* _Tag Detector_: Diese Parameter sind nur für erfahrene Benutzer empfohlen. Eine genauere Definition findest du hier: <http://tinyurl.com/6q48tuv> und hier: <http://tinyurl.com/7zf8sn3>

## Download

[Offlinetags_Software.zip](/assets/Offlinetags_Software.zip)

## Source-Code

[GitHub](https://github.com/offlinetags/offlinetags-demonstrator)

Lizenz: [GPL v.3](http://www.gnu.org/licenses/gpl-3.0.en.html); entwickelt mithilfe von [OpenCV](http://opencv.org/) und [QT](http://qt-project.org/)

