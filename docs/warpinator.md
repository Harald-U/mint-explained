---
title: Warpinator
parent: Home
nav_order: 3
layout: default
---

# Warpinator – Übertragen von Dateien zwischen Rechnern

[Warpinator](https://warpinator.com/){:target="_blank"} erlaubt den Dateitransfer und das Senden von Textnachrichten über das lokale Netzwerk zwischen Rechnern (Linux und Windows) und auch Telefonen bzw. Tablets (Android, iPhone). Ist bei Linux Mint vorinstalliert, die anderen Versionen gibt es [hier](https://warpinator.com/){:target="_blank"}. 

<img src="{{ site.baseurl }}/assets/images/warpinator/warpinator.png" alt="Warpinator" width="400">

Ist die Firewall auf Linux Mint eingeschaltet, müssen Regeln für Warpinator definiert werden, sonst findet der Warpinator keine anderen Rechner. Das kann aus Warpinator heraus gemacht werden oder indem man die Regeln in der [Universal Firewall UFW](https://harald-u.github.io/mint-explained/docs/systemeinstellungen/4-systemverwaltung.html#firewall){:target="_blank"} von Hand einträgt, eines von beiden reicht. 

Die Warpinator-Einstellung findet man über das "Hamburger"-Menü (drei waagerechte Striche) links oben und dort auf der zweiten Seite "Verbindung":

<img src="{{ site.baseurl }}/assets/images/warpinator/warp-settings.png" alt="Warpinator Settings" width="400">

Der (1) "Gruppencode" muss auf allen Warpinator-Instanzen, die sich miteinander verbinden sollen, gleich sein, Mit dem Knopf (2) "Firewall-Regeln aktualisieren" können die Firewall-Regel eingetragen oder angepasst werden.

Möchte man die Firewall-Regeln von Hand anlegen oder ändern, ist hier ein Beispiel, wie man die Regeln von Hand anlegt:

<img src="{{ site.baseurl }}/assets/images/warpinator/warp_ufw.png" alt="Warpinator Firewallregeln" width="400">

Warpinator benutzt die Ports 42000 und 42001, diese müssen erlaubt werden für eingehende Richtung für beide Protokolle (UDP und TCP). 

Das passiert im Bereich Regeln (1), durch Hinzufügen + (2) als „Einfache Regel“ (3), und muss separat für Port 42000 und 42001 gemacht werden. 

Die Regel wird dann zweimal (automatisch) angelegt, für IP V4 und IP V6.