---
title: Systemverwaltung
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

[Paket-Quellen]()

## Systemverwaltung

FORTSCHRITTLICH! Einstellungen des Boot-Menüs (GRUB).

## Treiberverwaltung

Für bestimmte Hardware, z.B. Grafikkarten von Nvidia, Netzwerkadapter o. dgl. kann eventuell über die Treiberverwaltung ein proprietärer Treiber installiert werden, soweit einer in den Paketquellen vorhanden ist. 
