[Deutsch](/README_de.md) || [English](/README.md)

<img src="/_img/icon_youtubeontop_dark.png" width="128">

## YouTubeOnTop V1.0 - Die erste "veröffentlichte" Version der App. :)

Ein kleiner Desktop-Player für YouTube, der in einer Ecke des Bildschirms "klebt" und immer über allen anderen Fenstern bleibt. Somit kannst du dich voll auf deine eigentlichen Aufgaben konzentrieren und nicht auf die nervenaufreibende Suche nach deinem YouTube Browser Tab.

### Download

**Passwort: _pw1234_**

-   [Windows](https://github.com/mindactuate/youtubeontop-v1/releases/download/V1.0/YouTubeOnTop-win32-x64.zip)
-   [Linux](https://github.com/mindactuate/youtubeontop-v1/releases/download/V1.0/YouTubeOnTop-linux-x64.zip)
-   MacOS: erscheint demnächst

Ich hoffe, dass dir die App gefällt und etwas bringt. Ich liebe das Projekt und bin bereit, die App weiterzuentwickeln. (Neben anderen Projekten.)

#### Aktuelle Veröffentlichungen

Alle aktuellen Releases findest du hier:
[https://github.com/mindactuate/youtubeontop-v1/releases](https://github.com/mindactuate/youtubeontop-v1/releases)

#### [FAQ siehe unten](#faq)

### Optimiert für

-   Windows 10
-   Ubuntu 18.04 LTS

### Installation

-   Lade die richtige zip Datei runter
-   Extrahiere die ganze zip in einen Ordner (Rechtsklick -> Alle extrahieren...)
    -   verwende dabei das Passwort _pw1234_
-   Unter Windows:
    -   starte die Anwendung YouTubeOnTop.exe mit einem Doppelklick
-   Unter Linux:
    -   in Linux heißt die Datei YouTubeOnTop
    -   Rechtsklick -> Eigenschaften -> Zugriffsrechte -> Häkchen setzen bei "Datei als Programm ausführen"
    -   starte die Anwendung YouTubeOnTop mit einem Doppelklick

### Always on top

Das Fenster bleibt immer über allen anderen Fenstern. :)

<img src="/_img/video_windows.gif">

### Plattformübergreifend

Die App läuft unter **Windows**, **Linux** und **MacOS** (erscheint demnächst).

<img src="/_img/linux.png" width=500>

### Portabel / keine Installation notwendig

Die App ist voll portabel. Kopiere den kompletten App-Ordner auf einen USB Stick und du bist startklar. Keine Installation notwendig. Keine Administrator-Rechte nötig.

### Bleibt immer in einer Bildschirmecke

Du entscheidest, in welcher Bildschirmecke das Fenster bleiben soll.

<img src="/_img/positioning.png" width=500>

### Transparenz

(Aktuell nicht unter Linux)

Nutze die verschiedenen Transparenz-Einstellungen, um im Hintergrund weiterzulesen und trotzdem Kontrolle über deinen YouTube-Player zu haben.

<img src="/_img/transparency.png" width=500>

### Voll funktionsfähiges YouTube

Alle Funktionen, natives YouTube

-   Vollbild Videos
-   Tag- und Nacht-Modus
-   Einstellbare Qualität
-   Einstellbare Geschwindigkeit
-   Untertitel
-   Standard YouTube Suche
-   Einloggen und eingeloggt bleiben
-   ...

<img src="/_img/allfunctions.png" width=500>

### Proxy

Stelle deine [Proxy](#was-zum-teufel-ist-ein-proxy) Einstellungen ein und weiter geht´s.
<img src="/_img/offline_1.png" width=400>

<img src="/_img/proxy.png" width=500>

### Lustiger Offline Modus

Ohne Internet? Wie in der Jurazeit, oder? Google's berühmtes Dinosaurier Spiel ist in dieser Desktop App integriert und bringt dich durch internet-lose Zeiten. :)

<img src="/_img/offline_2.png" width=500>

### One Euro is all I need :)

Die App war seeehr viel Arbeit - trotz der Unterstützung von tollen Frameworks, Bibliotheken und Werkzeugen. Die App kostet einen kleinen Betrag von 1€. Natürlich ist trotzdem unbegrenztes kostenfreies Testen erlaubt.

[<img src="/_img/icon_donate.png" width=128>](https://www.paypal.me/mindactuate)
(klick mich)

### Tech Stack

-   [VS Code](https://code.visualstudio.com/) (as IDE)
-   [Electron.js](https://electronjs.org/) (awesome! I love it!)
-   [Bootstrap](https://getbootstrap.com/) + [popper.js](https://popper.js.org/) + [jQuery](https://jquery.com/) (for the proxy window)
-   [Keytar](https://atom.github.io/node-keytar/) (for saving your proxy settings in the OS' credentials storage safely)
-   [Google's Dinosaurier Game](https://www.google.com)
-   [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) (for all the icons)
-   Some little helpers (via npm)
    -   electron-packager
    -   electron-rebuild
    -   electron-log
    -   electron-reload
    -   get-proxy-settings

### FAQ

[nach oben](#download)

#### Ich bekomme einen Netzwerkfehler kurz nach Programmstart

-   Please stay calm, click "Ok" and just play the Dinosaurier game for a while. Just joking. :)
-   There is just a network error.
    -   Please check your internet connection (use your normal browser and check).
    -   If there is internet, it might be, that you're behind a proxy server (often in companies).
    -   To solve that, please right click in YouTubeOnTop and click on _Proxy_.
    -   There is lots of guidance for how to find and how to set your proxy. It is easy - I promise. :)

#### Wo kann ich die App herunterladen?

[Schau hier](#download-here)

#### Wie kann ich die App installieren?

[Schau hier](#installation)

#### Was zum Teufel ist ein Proxy?

Wenn du dich mit dem Internet verbindest, musst du manchmal einen Proxy-Server verwenden - ein Computersystem, das sich zwischen dir und dem Internet befindet. Proxies sind an Schulen, Hochschulen und Arbeitsplätzen üblich und können den Zugang zum Internet einschränken und kontrollieren. ([Textquelle](https://www.dummies.com/social-media/spotify/spotify-and-proxy-servers/))

Wenn deine Internetverbindung einen Proxy erfordert, musst du die entsprechenden Angaben im Fenster Proxy-Einstellungen vornehmen (Rechtsklick auf das YouTubeOnTop-Symbol <img src="/_img/icon_youtubeontop_dark.png" width="16"> im Taskleistenbereich oder Rechtsklick im YouTubeOnTop Hauptfenster). Innerhalb des Fensters _Proxy-Einstellungen_ gibt es viele Anleitungen, die dir helfen können, die entsprechenden Daten herauszufinden. Wenn das nicht hilft, frage doch einfach mal die IT-Abteilung deiner Schule oder deines Arbeitsplatzes oder deinen Internet Service Provider Helpdesk nach den Zugangsdaten.

#### Darfst du das Google Dinosaurierspiel benutzen?

Ich habe großen Respekt vor all den großartigen Entwicklern und Designern da draußen auf der Welt. Dazu gehören natürlich auch die Chromium Autoren, die das Google Dinosaurierspiel entwickelt und gestaltet haben.

Hier findest du eine zusätzliche Datei mit den meisten [LIZENZEN](/LIZENZEN.md).

**Ich möchte allen großen Schöpfern da draußen danken.**

**Ich bin ein Zwerg, der auf den Schultern von Riesen steht.**
