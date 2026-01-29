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

Ein Betriebssystem wie Linux Mint führt eine Liste der aktuell installierten Pakete und ihrer installierten Versionen. Es lädt in regelmäßigen Abständen von zwei Servern eine Liste der aktuellen Pakete (und ihrer aktuellen Version) für Ubuntu und Linux Mint. Dann werden die Server-Versionen mit den installierten Versionen verglichen und bei Bedarf eine Aktualisierungsliste erzeugt und die Benutzer*in auf ein mögliches Update hingewiesen durch den roten Punkt am entsprechenden Icon (Schild) in der Leiste ![Update](/assets/images/software/updates_available.png). 

## Paket-Quellen

Die Paket-Quellen legen fest, von welchen Servern irgendwo auf der Welt ich Software-Updates herunterlade und installiere.

Nach einer Neuinstallation bzw. nach einem Versions-Upgrade, d.h. dem Wechsel auf eine neue Version von Linux Mint, sind die Standard-Paket-Quellen eingetragen, die sind sehr weit weg von uns. Die Software-Aktualisierung weist uns darauf mit der Frage, ob wir die Spiegel-Server wechseln wollen, hin:

<img src="{{ site.baseurl }}/assets/images/software/mirror.png" alt="Mirror" width="300">

Die Paket-Quellen sind auch eine Option in den Mint Systemeinstellungen in der Gruppe "System-Verwaltung".

<img src="{{ site.baseurl }}/assets/images/software/paketquellen.png" alt="Paketquellen" width="500">

In den Paketquellen sucht man sich einen Server für Haupt (= Linux Mint-Pakete) und Basis (= Ubuntu-Pakete), indem man einfach auf das Feld mit der Server-Adresse klickt (1). 

Mint testet die Verbindung zu den Servern und sortiert nach der schnellsten Verbindung (2). Ich persönlich nutze immer den Server, der möglichst dicht bei mir ist, für Stuttgart bietet sich (3) Hochschule Esslingen University of Applied Sciences an, das sind die Server der Hochschule (FH) Esslingen.

Nachdem man die Spiegel-Server geändert hat, sollte man den "APT-Zwischenspeicher" aktualisieren, das ist die Liste der auf den Servern verfügbaren Software.

<img src="{{ site.baseurl }}/assets/images/software/mirror3.png" alt="APT-Cache" width="300">

Alle anderen Einstellungen in den Paketquellen sind für fortgeschrittene Anwender.

*Übrigens werden bei diesem Prozess keine Daten von meinem Notebook auf die Paket-Server übertragen. Niemand weiß, wer ich bin, wo ich wohne und welche Anwendungen ich auf meinem Rechner installiert habe.*



