---
title: Updates und Upgrades
parent: Home
nav_order: 2
layout: default
---

## Inhalt
{: .no_toc .text-delta }

- TOC
{:toc}

# Updates

Anwendungen in Linux sind in Paketen organisiert, ein Programm wie z.B. LibreOffice besteht aus mehreren Paketen. Diese Pakete werden auf Servern (sogenannten Repositories) weltweit vorgehalten und diese weltweiten Server synchronisieren sich untereinander. 

Ein Betriebssystem wie Linux Mint führt eine Liste der aktuell installierten Pakete und ihrer installierten Versionen. Es lädt in regelmäßigen Abständen von zwei Servern eine Liste der aktuellen Pakete (und ihrer aktuellen Version) für die Ubuntu-Basis und Linux Mint. Dann werden die Server-Versionen mit den installierten Versionen verglichen und bei Bedarf eine Aktualisierungsliste erzeugt und die Benutzer*in auf ein mögliches Update hingewiesen durch den roten Punkt am entsprechenden Icon (Schild) <img src="{{ site.baseurl }}//assets/images/software/updates_available.png" alt="Shield" width="25"> im rechten Bereich der Leiste am unteren Bildrand. Die Software-Aktualierung wird durch einen Klick auf dieses Icon gestartet.

*Übrigens werden bei diesem Prozess keine Daten von meinem Notebook auf die Paket-Server übertragen. Niemand weiß, wer ich bin, wo ich wohne und welche Anwendungen ich auf meinem Rechner installiert habe.*

## Aktualisierungsverwaltung

Hier sieht man, welche Updates verfügbar sind. Durch Klick auf "Aktualisierungen installieren" wird der Prozess gestartet und da es eine Adminstrationsaufgabe ist, muss mit der Eingabe des eigenen Passworts authorisiert werden.

<img src="{{ site.baseurl }}/assets/images/software/updates_list.png" alt="Updates-Liste" width="500">

Während das Update läuft, kann beliebig weiter gearbeitet werden.

In sehr seltenen Fällen ist ein Neustart des Rechners erforderlich, z. B. wenn der Linux Kernel, die Hauptkomponente des Betriebssystems, aktualisiert werden soll. Da der Kernel sicherheitsrelevant ist, sollte der Neustart schnell erfolgen. Linux Mint weist darauf hin:

<img src="{{ site.baseurl }}/assets/images/software/restart-reqd.png" alt="Restart required" width="500">

Manchmal wird auch die Anwendung "Aktualisierungsverwaltung" selbst aktualisiert. Dann sieht man statt einer Software-Liste dieses Bild:

<img src="{{ site.baseurl }}/assets/images/software/upgrade4update.png" alt="Restart required" width="500">

Durch Klick auf den Knopf wird erst dieses Update durchgeführt. Danach startet die Anwendung neu und zeigt eventuell vorhandene andere Aktualisierungen.

## Paket-Quellen

Diese Einstellung nehmen wir i.d.R. im Linux-Café für Sie vor ...

Die Paket-Quellen legen fest, von welchen Servern irgendwo auf der Welt ich Software-Updates herunterlade und installiere.

Nach einer Neuinstallation bzw. nach einem Versions-Upgrade, d.h. dem Wechsel auf eine neue Version von Linux Mint, sind die Standard-Paket-Quellen eingetragen, die sind sehr weit weg von uns. Die Software-Aktualisierung weist uns darauf mit der Frage, ob wir die Spiegel-Server wechseln wollen, hin:

<img src="{{ site.baseurl }}/assets/images/software/mirror.png" alt="Mirror" width="500">

Die Paket-Quellen sind auch eine Option in den Mint Systemeinstellungen in der Gruppe "System-Verwaltung".

<img src="{{ site.baseurl }}/assets/images/software/paketquellen.png" alt="Paketquellen" width="500">

In den Paketquellen sucht man sich einen Server für Haupt (= Linux Mint-Pakete) und Basis (= Ubuntu-Pakete), indem man einfach auf das Feld mit der Server-Adresse klickt (1). 

Mint testet die Verbindung zu den Servern und sortiert nach der schnellsten Verbindung (2). Ich persönlich nutze immer den Server, der möglichst dicht bei mir ist, für Stuttgart bietet sich (3) Hochschule Esslingen University of Applied Sciences an, das sind die Server der Hochschule (FH) Esslingen.

Nachdem man die Spiegel-Server geändert hat, sollte man den "APT-Zwischenspeicher" aktualisieren, das ist die Liste der auf den Servern verfügbaren Software.

<img src="{{ site.baseurl }}/assets/images/software/mirror3.png" alt="APT-Cache" width="300">

Alle anderen Einstellungen in den Paketquellen sind für fortgeschrittene Anwender.

# Upgrades

In regelmässigen Abständen wird Linux Mint selbst aktualisiert, also ein Upgrade von den Entwicklern angeboten. Dabei gibt es zwei verschiedene Upgrades:

* Haupt-Versionen, z.B. Linux Mint 21 oder Linux Mint 22
* Zwischen-Versionen, z.B. Linux Mint 22.1 oder Linux Mint 22.3

Die Haupt-Versionen basieren auf den Ubuntu Langzeitversionen (LTS), die alle zwei Jahre herauskommen, immer in geraden Jahren im April, daher heissen diese Versionen z.B. Ubuntu 24.4. Die Version Ubuntu 24.4 war die Basis für Linux Mint 22, das im Juli 2024 freigegeben wurde.

In den zwei Jahren zwischen zwei Ubuntu LTS-Versionen veröffentlichen die Linux Mint-Entwickler in der Regel drei Linux Mint Zwischenversionen, es gibt aktuell also die Hauptversion 22 und die darauf folgenen Zwischen-Versionen 22.1, 22.2 und aktuell 22.3.

## Upgrade von Linux Mint Zwischen-Versionen

Die Upgrades des Zwischen-Versionen sind recht einfach, die Anweisungen dazu werden auf dem Linux Mint Blog veröffentlich, z.B. [How to upgrade to Linux Mint 22.3](https://blog.linuxmint.com/?p=4980){:target="_blank"}.

Linux Mint gibt aber selber auch Hinweise auf eine neue Betriebssystemversion. 

Manchmal taucht im rechten Bereich der Leiste ein Icon auf (Clipboard mit Ausrufezeichen). Wenn man den Mauszeiger darüber bewegt, sieht es wie folgt aus:

<img src="{{ site.baseurl }}/assets/images/software/systembericht.png" alt="Systembericht" width="300">

Wenn man auf das Icon klickt, wird es konkreter:

<img src="{{ site.baseurl }}/assets/images/software/systembericht2.png" alt="Systembericht Upgrade" width="500">

Wenn man jetzt auf den grünen Knopf klickt, wird man Schritt für Schritt durch den Prozess durch den Prozess geführt.

    **WICHTIG:** Ein Upgrade birgt immer die Gefahr, dass etwas schief geht und der Rechner hinterher nicht mehr funktioniert. Daher sollte man vor einem Upgrade **unbedingt alle wichtigen persönlichen Daten sichern**"**!!!

Zuerst gibt es Infos (auf Englisch): 

* Versions-Hinweise beschreiben bekannte Probleme und deren mögliche Lösung. 
* Neue Funktionen, die mit dieser Version verfügbar sind. 
* Anforderungen - diesen Punkt hätte ich sicher anders genannt. Hier wird auf das Risiko eines Uprades hingewiesen:
<img src="{{ site.baseurl }}/assets/images/software/upgrade_agree.png" alt="Zustimmung" width="500">

Wenn man den Haken setzt und auf "Anwenden" klickt, wird das Passwort abgefragt und dann geht das Upgrade auch direkt los. Das Upgrade modifiziert die Paketquellen und installiert dann eine Menge Pakete. Das geht eigentlich immer erstaunlich schnell. Wenn alles fertig ist, wird man zum Neustart aufgefordert. Wenn alles gut ging, startet der Rechner dann in neume Glanz mit der neuen Version. 

Man sollte sofort überprüfen, ob es Aktualisierungen (Updates) gibt, dann hat das Schild-Icon in der Leiste einen roten Punkt. Wenn man dann die Aktualisierungsverwaltung öffnet, wird man aufgefordert, zu einem lokalen Spiegelserver zu wechseln. Wie das geht, steht [hier](#paket-quellen). Nachdem das erfolgt ist, werden wie gewohnt die Updates eingespielt.


