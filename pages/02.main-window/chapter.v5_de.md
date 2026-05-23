---
title: 'Hauptfenster'
taxonomy:
    category: docs
child_type: docs
media_order: 'main-window-v5.3.png,main-window.png'
---

<style>
    #chapter p {
        text-align: left;
    }
</style>

### Kapitel 2

# Hauptfenster

Das QLC+-Hauptfenster besteht aus vier Hauptbereichen:

1.  Einer oberen Leiste mit den globalen Schaltflächen
2.  Einer kontextbezogene Untermenüleiste mit Steuerelementen für den ausgewählten Kontext
3.  Dem Haupt-Kontextbereich, der entweder eine Vorschau oder ein Arbeitsbereich sein kann
4.  Seitenpanels, um die aktuelle Ansicht zu bearbeiten, ohne Platz zu verschwenden

![](/main-window/main-window-v5.3.png)

Die meisten Steuerelemente in QLC+ verfügen über Tooltips, die angezeigt werden, wenn Sie den Mauszeiger eine kurze Zeit darüber halten.

### Obere Leiste (1)

Die obere Hauptleiste enthält die folgenden Verknüpfungen (von links nach rechts):

* * *
#### ![](../basics/qlcplus.svg?resize=48,48) Menü für globale Aktionen

Dieses Menü ist aus jedem QLC+-Kontext heraus zugänglich und dient als Schnellzugriff auf die wichtigsten Projektoperationen.  
Die Menüpunkte sind hier aufgelistet:

![](../basics/filenew.svg) Neues leeres Projekt erstellen (STRG+N)  
![](../basics/fileopen.svg?resize=48,48) Vorhandenes Projekt öffnen (zeigt eine Liste der zuletzt verwendeten Dateien, wenn Mauszeiger darüber bewegt wird) (STRG+O)  
![](../basics/filesave.svg?resize=48,48) Aktuelles Projekt speichern (STRG+S)  
![](../basics/filesaveas.svg?resize=48,48) Aktuelles Projekt unter einem neuen Namen speichern  
![](../basics/import.svg?resize=48,48) Geräte und Funktionen aus einem bestehenden Projekt importieren  

![](../basics/undo.svg) Letzte Aktion rückgängig machen  
![](../basics/redo.svg) Letzte rückgängig gemachte Aktion wiederherstellen  

![](../basics/network.svg) Netzwerk-Einstellungen für Client und Server konfigurieren (entweder nativer Server oder das Web-Interface)  
![](../basics/diptool.svg) Das DIP-Schalter- Berechnungswerkzeug öffnen  
![](../basics/configure.svg) Das Einstellungsfenster für die Benutzeroberfläche öffnen, um Farben, Skalierung usw. anzupassen.  
<i class="fa fa-maximize fa-2x"></i> Vollbildmodus umschalten (STRG+F11)  
<i class="fa fa-earth-europe fa-2x"></i> Die Sprache der Benutzeroberfläche wechseln (möglicherweise ist ein Neustart der Anwendung erforderlich)  
<i class="fa fa-circle-info fa-2x"></i> Informationen zu QLC+ anzeigen  

* * *

#### Schaltflächen zum Wechseln zwischen Kontexten

Durch Drücken dieser Schaltflächen können Sie von einem Kontext zum anderen wechseln.  
Kontexte können bei der Entwurfsphase, dem Live-Betrieb oder der Konfiguration von Ein- und Ausgängen hilfreich sein.  
Kontexte können durch einen Rechtsklick auf ihre Schaltfläche vom Hauptfenster getrennt und so als separates Fenster geöffnet werden. 
 
![](../basics/editor.svg?resize=48,48) Den Kontext [„Geräte und Funktionen“](/fixtures-functions-manager) anzeigen  
![](../basics/virtualconsole.svg?resize=48,48) Die [Virtuelle Konsole](/virtual-console) anzeigen  
![](../basics/simpledesk.svg?resize=48,48) Die [Einfache Oberfläche](/simple-desk) anzeigen  
![](../basics/showmanager.svg?resize=48,48) Den [Show-Manager](/show-manager) anzeigen  
![](../basics/inputoutput.svg?resize=48,48) Den Konfigurationsmanager für die [Ein- und Ausgabe](/input-output) anzeigen

#### Globale Hilfsprogramme

Die obere Leiste des Hauptfensters enthält auf der rechten Seite des Bildschirms weitere Hilfsfunktionen.

![](../basics/dmxdump.svg?resize=48,48) Öffnen Sie das Popup [DMX Dump](dmx-dump), um schnell Szenen zu erstellen  
<i class="fa fa-wave-square fa-2x"></i>    BPM-Steuerung: Zeigt die aktuelle BPM-Zahl an und öffnet das Popup [BPM-Steuerung](/bpm-system)  
![](../basics/stopall.svg?resize=48,48) Die Anzahl der laufenden Funktionen anzeigen und sie alle auf einmal stoppen  

### Kontext-Unterleiste (2)

Dies ist eine weitere Menüleiste, die sich je nach Kontext ändert (oder gar nicht vorhanden ist) und in der Sie entweder den Kontext-Vorschaumodus auswählen oder eine Symbolleiste mit verschiedenen Steuerelementen finden können.  

* „Geräte und Funktionen“ zeigt den Vorschaumodus- und Universums-Auswahlfelder an
* „Virtuelle Konsole“ zeigt eine Seitenauswahl an
* „Einfache Oberfläche“ zeigt ein Universums-Auswahlfeld und eine Reset-Schaltfläche an
* „Show-Manager“ zeigt Editor- und Wiedergabesteuerungen an
* „Eingabe/Ausgabe“ hat keine Unter-Steuerleiste

### Hauptarbeitsbereich (3)

Hier passiert alles. Welches Panel aktiv ist, hängt davon ab, welcher Kontext gerade ausgewählt ist.

### Seitenpanels (4)

Seitenpanels wurden in Version 5 eingeführt, um Platz zu sparen und schnelle Werkzeuge zur Verbesserung der Projektbearbeitung bereitzustellen.  
In diesen Panels finden Sie Werkzeuge wie:
* Geräte-Browser
* Editoren für Fixtures, Funktionen, Paletten oder Widgets
* Liste der Eingabe/Ausgabe-Plugins, Eingangsprofile oder Widgets auf der Virtuellen Konsole
