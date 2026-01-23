---
title: Geräte
parent: Linux Mint Systemeinstellungen
nav_order: 3
layout: default
---

# Gruppe „Geräte“

## 1. Bildschirm

Bei Rechnern mit mehr als einem Bildschirm, z.B. Desktop mit 2 Monitoren, Laptop mit externem Bildschirm oder Beamer kann die Anordnung der Bildschirme zueinander eingestellt werden. 

<img src="{{ site.baseurl }}/assets/images/geraete/bildschirm.png" alt="Bildschirm" width="400">

Im Beispielbild ist z.B. der rote Bildschirm 1 der im Notebook eingebaute, der Bildschirm 2 ein externer Monitor, der sich links und etwas oberhalb des Notebook-Bildschirms befindet. Die roten und grünen Felder können mit der Maus entsprechend verschoben werden. Die Lage der Felder zueinander erlaubt es dann, den Mauszeiger ganz „natürlich“ vom internen auf den externen Bildschirm und umgekehrt zu bewegen. 

Ändert man die Einstellung von „Bildschirme verbinden“ auf „Spiegel“, stellen beide Bildschirme den gleichen Inhalt bei gleicher Auflösung dar, ist bei Beamern manchmal hilfreich.

## 2. Bluetooth

Öffnet den Bluetooth-Manager, um Bluetooth ein- bzw. aus-zuschalten, den eigenen Bluetooth-Namen zu ändern und den Rechner für andere sichtbar zu machen  (> Adapter > Adaptereinstellungen) und andere Bluetooth-Geräte zu suchen (Lupe).

<img src="{{ site.baseurl }}/assets/images/geraete/bluetooth.png" alt="Bluetooth" width="400">

## 3. Drucker

Einrichten und Konfigurieren von Druckern.

Drucker, die nicht zu alt sind und vor allem Netzwerkdrucker beherrschen meistens Druckverfahren wie Apple AirPrint oder das in Android verwendete Mopria der Mobile Printing Alliance. Diese Drucker benötigen keine installierten Druckertreiber, sie arbeiten [driverless](https://openprinting.github.io/driverless/){:target="_blank"}, also treiberlos und zwar als Netzwerkdrucker und per USB-Kabel. Linux Mint bzw. das Drucksystem CUPS in Linux Mint sieht diese Drucker und konfiguriert sie, sobald sie eingeschaltet werden, das dauert um die 30 Sekunden. Wird ein Drucker ausgeschaltet, verschwindet der Druckereintrag in Linux Mint nach einer kurzen Zeit wieder.

<img src="{{ site.baseurl }}/assets/images/geraete/drucker.png" alt="Drucker" width="400">

Unterstützt der Drucker keines der Driverless-Verfahren, müssen die Treiber evtl. von Hand installiert werden. Eine englische Anleitung bzw. Infos sind hier [hier](https://linuxmint-user-guide.readthedocs.io/en/latest/printers.html#printers-and-scanners){:target="_blank"} 

Im Beispiel oben ist übrigens ein Multifunktionsdrucker von Brother auch als Faxgerät eingebunden. Dabei musste der Fax-Treiber von Brother (BRFAX) manuell installiert werden.

Neuere Scanner bzw. die in Multifunktionsdruckern eingebauten Scanner unterstützen meist Apple AirScan und werden vom Scannertreiber SANE in Mint ebenfalls automatisch erkannt und eingerichtet, sobald sie eingeschaltet werden.

## 4. Energieverwaltung

Der Dialog unterscheidet sich bei Desktop und Notebook, bei Notebooks (mit Akku) gibt es viel mehr Einstellungen (s. Bild).

<img src="{{ site.baseurl }}/assets/images/geraete/power.png" alt="Energieverwaltung" width="400">

* Wann wird der Bildschirm bzw. die Beleuchtung ausgeschaltet? Geht der Rechner irgendwann von selbst in Bereitschaft? Was passiert, wenn der Notebook-Deckel geschlossen wird?
* Was passiert, wenn der Netzschalter gedrückt wird? Bei „Fragen“ kommt ein Dialog, in dem man zwischen Bereitschaft, Neustart und Herunterfahren entscheiden kann.
* Energiemodus ist der Stromsparmodus der CPU (der sog. Governor), mögliche Einstellungen: Energie sparen, Ausgeglichen oder Leistung (powersave, balanced, performance).

## 5. Farbe, Grafiktablett 

Fortgeschritten. Hinzufügen und Auswählen von Farbprofilen (für Grafiker, Fotografen) und Einstellungen von Grafiktabletts (hat der normale Haushalt eher nicht).

## 6. Klang

Hier sind alle Audioeinstellungen zusammengefasst. Die Klangeinstellungen kann man auch über das Lautsprecher- oder Klangsymbol in der Leiste erreichen.

**Ausgang:**

<img src="{{ site.baseurl }}/assets/images/geraete/ausgang.png" alt="Ausgang" width="400">

Regler für Lautstärke (2) und Balance (3).

Bei verschiedenen Ausgabegeräten (z.B. interne Lautsprecher, Bluetooth-Lautsprecher, per HDMI angeschlossener Fernseher) wird hier der Ausgabekanal (1) bzw. das Profil (Bluetooth) (2) ausgewählt. 

Übersteuerung (4) kann eingeschaltet werden, wenn der Kanal nicht laut genug eingestellt werden kann.

**Eingang:**

<img src="{{ site.baseurl }}/assets/images/geraete/eingang.png" alt="Eingang" width="400">

Hauptsächlich Pegel des Mikrofons (soweit vorhanden) (1).

(2) zeigt den Aufnahmepegel an.

Mit dem Knopf (3) kann das Mikrofon stumm geschaltet werden. Manche Notebooks haben dafür auch eine Taste.

**Klänge:**

<img src="{{ site.baseurl }}/assets/images/geraete/klaenge.png" alt="Klänge" width="400">

Systemklänge, also Töne, die Mint von sich gibt, wenn bestimmte Ereignisse eintreten (z.B. das System wird beendet, eine USB-Platte wird angesteckt, usw.). Wie man sieht, kann man die Klänge einzeln ein- bzw. ausschalten.

Außerdem kann man eigene Audiodateien hinterlegen und testen (über den Abspielknopf).

## 7. Laufwerke

**ABSOLUT FORTGESCHRITTEN!** Zeigt interne und externe Laufwerke und ihre Partitionen an. Löschen, Formatieren, Anlegen von Partitionen, hier kann man sein System nach Herzenslust zerschießen! 

## 8. Maus- und Touchpad

Alle möglichen Einstellungen für die Maus: Linkshänder, Geschwindigkeit - Mauszeiger ist zu schnell / zu langsam, Größe des Mauszeigers und einige mehr.

<img src="{{ site.baseurl }}/assets/images/geraete/maus.png" alt="Maus / Touchpad" width="400">

Ähnliches für das Touchpad. 

**Tip für Touchpad-Grobmotoriker und Maus-Bevorzugende wie mich:**  Die Touchpad-Einstellung „Deaktiviert, wenn eine Maus angeschlossen ist“ schaltet das Touchpad im Notebook aus, solange eine Maus eingesteckt ist. Damit gibt es kein Handballen-Ballett für den Mauszeiger …

## 9. Netzwerk 

Netzwerkeinstellungen sind eher fortgeschritten, normalerweise genügt es, Funk-Netzwerke über das Netzwerk-Icon rechts in der Leiste auszuwählen.

## 10. Systeminformation

Die wichtigsten Daten zum System: Betriebssystem, CPU, USB, Grafikkarte, Speicher, BIOS, etc. Außerdem Systemberichte und Absturzberichte.
Wenn man will (und nur dann!), wird diese Information zu den Linux Mint-Entwicklern hochgeladen, für deren Statistik.

## 11. Tastatur

Einstellungen zur Tastatur und zum Cursor (dem blinkenden Textzeiger), Einstellung und Installation zusätzlicher Tastaturlayouts (das wird eigentlich bei der Installation festgelegt), Konfiguration von Hotkeys (Start einer bestimmten Anwendung/Funktion mit einer selbst festgelegten Tastenkombi). Alles eher fortgeschritten.

## 12. Thunderbolt

Infos zu Thunderbolt bzw USB4-Schnittstellen am Rechner (hab ich selber nicht, kann ich daher nicht beschreiben ...)