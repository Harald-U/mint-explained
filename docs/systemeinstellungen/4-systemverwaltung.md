---
title: Sytemverwaltung
parent: Linux Mint Systemeinstellungen
nav_order: 4
layout: default
---

# Gruppe „Systemverwaltung“
{: .no_toc }

Funktionen, für die ich mich meist zusätzlich legitimieren muss, also FORTSCHRITTLICH.

## Inhalt
{: .no_toc .text-delta }

1. TOC
{:toc}

## Anmeldefenster

Aussehen und Verhalten des Bildschirms, der nach dem Start von Mint angezeigt wird und an dem man sich anmeldet. FORTSCHRITTLICH

## Benutzer und Gruppen

Verwalten von eben diesen.  FORTSCHRITTLICH

## Fingerabdrücke

Falls der Rechner (Notebook) einen unterstützten Fingerabruckscanner hat, können hier die Fingerabdrücke registriert werden.

<img src="{{ site.baseurl }}/assets/images/verwaltung/fingerprint.png" alt="Fingerabdrücke" width="400">

Über das „Hamburger“-Menü (3 waagerechte Striche, links oben), kann der Fingerabruckscanner wieder ausgeschaltet werden.

## Firewall

Linux Mint installiert immer die UFW, die „uncomplicated firewall“, die ist aber erst mal ausgeschaltet (und kann auch aus der Willkommen-Anwendung heraus eingeschaltet werden). Wenn man sie einschaltet, werden alle Zugriffe von außen abgelehnt (Eingehend: Verweigern), alle Zugriffe nach außen gehen durch (Ausgehend: Erlauben). Das sollte für die meisten Anwender ausreichen.

<img src="{{ site.baseurl }}/assets/images/verwaltung/firewall.png" alt="Firewall" width="400">

Bei Bedarf müssen Regeln hinzugefügt werden, das ist dann aber alles andere als unkompliziert. Aber Firewalls sind nirgends wirklich einfach, wenn Regeln ins Spiel kommen … Ein Beispiel dafür ist im Dokument [Warpinator]({{ site.baseurl }}/docs/warpinator){:target="_blank"} beschrieben.

## Paket-Quellen

Anwendungen in Linux sind in Paketen organisiert, ein Programm wie z.B. LibreOffice besteht aus mehreren Paketen. Diese Pakete werden auf Servern (sogenannten Repositories) weltweit vorgehalten und diese weltweiten Server synchronisieren sich untereinander. 

Ein Betriebssystem wie Linux Mint führt eine Liste der aktuell installierten Pakete und ihrer installierten Versionen. Es lädt in regelmäßigen Abständen von zwei Servern eine Liste der aktuellen Pakete (und ihrer aktuellen Version) für Ubuntu und Linux Mint. Dann werden die Server-Versionen mit den installierten Versionen verglichen und bei Bedarf eine Aktualisierungsliste erzeugt und die Benutzer*in auf ein mögliches Update hingewiesen durch den roten Punkt am entsprechenden Icon (Schild) in der Leiste.

<img src="{{ site.baseurl }}/assets/images/verwaltung/paketquellen.png" alt="Paketquellen" width="500">

In den Paketquellen sucht man sich einen Server für Haupt (= Linux Mint-Pakete) und Basis (= Ubuntu-Pakete), indem man einfach auf das Feld mit der Server-Adresse klickt (1). 

Mint testet die Verbindung zu den Servern und sortiert nach der schnellsten Verbindung (2). Ich persönlich nutze immer den Server, der möglichst dicht bei mir ist, für Stuttgart bietet sich (3) Hochschule Esslingen University of Applied Sciences an, das sind die Server der Hochschule (FH) Esslingen.

Alle anderen Einstellungen in den Paketquellen sind für fortgeschrittene Anwender.

Übrigens werden bei diesem Prozess keine Daten von meinem Notebook auf die Paket-Server übertragen. Niemand weiß, wer ich bin, wo ich wohne und welche Anwendungen ich auf meinem Rechner installiert habe.

## Systemverwaltung

FORTSCHRITTLICH! Einstellungen des Boot-Menüs (GRUB).

## Treiberverwaltung

Für bestimmte Hardware, z.B. Grafikkarten von Nvidia, Netzwerkadapter o. dgl. kann eventuell über die Treiberverwaltung ein proprietärer Treiber installiert werden, soweit einer in den Paketquellen vorhanden ist. 
