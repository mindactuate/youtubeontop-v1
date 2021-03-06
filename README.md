[Deutsch](/README_de.md) || [English](/README.md)

<img src="/_img/icon_youtubeontop_dark.png" width="128">

# Outdated: Unfortunately I do not have the time to continue the development of this tool.

But for Chrome users there is a nice tool out there: [Picture-in-Picture Extension (by Google)](https://chrome.google.com/webstore/detail/picture-in-picture-extens/hkgfoiooedgoejojocmhlaklaeopbecg)

Perhaps there are extensions for the other browsers out there, but the mentioned one works like a charm.

## This is YouTubeOnTop V1.0 - The first "public" version of the app. :)

A small youtube-player that will stick in a corner of your screen and stay always on top of all other windows. Focus on your work and not on searching for the youtube tab in your browser.

### Download

[Download here](https://github.com/mindactuate/youtubeontop-v1/releases)

Password is _pw1234_

-   **Windows:** _YouTubeOnTop-win32-x64.zip_
-   **Linux:** _YouTubeOnTop-linux-x64.zip_
-   **MacOS:** _erscheint demnächst_

I hope you like it. I love the project and I am willing to develop the app further. (Besides other projects.)

#### Best on

-   Windows 10
-   Ubuntu 18.04 LTS

#### Current releases

You can find all current releases here:
[https://github.com/mindactuate/youtubeontop-v1/releases](https://github.com/mindactuate/youtubeontop-v1/releases)

### Installation

-   Download the correct zip file
-   Extract the whole zip to a folder (Right click -> extract all)
    -   use the password _pw1234_
-   On Windows:
    -   Start the executable YouTubeOnTop.exe via double click
-   On Linux:
    -   in Linux its the file YouTubeOnTop
    -   Right click -> Properties -> Permissions -> Check "Allow executing file as program"
    -   Start the file YouTubeOnTop via double click

### [FAQ see below](#faq)

### Always on top

The window stays always on top. :)

<img src="/_img/video_windows.gif">

### Cross platform

You can use it with **Windows**, **Linux** or **MacOS** (coming soon).

<img src="/_img/linux.png" width=500>

### Portable / no installation required

The app is fully portable. Copy the complete app folder to a USB stick and you are ready to go. No installation necessary. No administrator rights necessary.

### Stick in the corner

You decide in which corner of your screen you want to see the window.

<img src="/_img/positioning.png" width=500>

### Transparency

(Currently not on Linux)

Use the different transparency settings to continue reading on the background and still have control over your YouTube player.

<img src="/_img/transparency.png" width=500>

### Fully functionable YouTube

All functions, native youtube.

-   full sceen videos
-   day / night mode
-   adjustable quality
-   adjustable speed
-   subtitles
-   standard youtube search
-   login and stay logged in
-   ...

<img src="/_img/allfunctions.png" width=500>

### Proxy

Set up your [proxy](#what-the-hack-is-a-proxy) settings and keep on watching.

<img src="/_img/offline_1.png" width=400>

<img src="/_img/proxy.png" width=500>

### Funny offline mode

Without Internet? It's like the Jurassic period, isn't it? Google's famous dinosaur game is integrated into this desktop app and takes you through internet-less times. :)

<img src="/_img/offline_2.png" width=500>

### One Euro is all I need :)

The app was a lot of work - despite the support of great frameworks, libraries and tools. The app costs a small amount of 1€. Of course, unlimited free testing is still allowed.

[<img src="/_img/icon_donate.png" width=128>](https://www.paypal.me/mindactuate)
(click me)

### Tech Stack

-   [VS Code](https://code.visualstudio.com/) (as IDE)
-   [Electron.js](https://electronjs.org/) (awesome! I love it!)
-   [Bootstrap](https://getbootstrap.com/) + [popper.js](https://popper.js.org/) + [jQuery](https://jquery.com/) (for the proxy window)
-   [Keytar](https://atom.github.io/node-keytar/) (for saving your proxy settings in the OS' credentials storage safely)
-   [Google's Dinosaur Game](https://www.chromium.org/Home)
-   [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) (for all the icons)
-   [Github](github.com)
-   [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)
-   Some little helpers (via npm)
    -   electron-packager
    -   electron-rebuild
    -   electron-log
    -   electron-reload
    -   get-proxy-settings

### FAQ

#### I've got a Network Error info box at program start

-   Please stay calm, click "Ok" and just play the Dinosaurier game for a while. Just joking. :)
-   There is just a network error.
    -   Please check your internet connection (use your normal browser and check).
    -   If there is internet, it might be, that you're behind a proxy server (often in companies).
    -   To solve that, please right click in YouTubeOnTop and click on _Proxy_.
    -   There is lots of guidance for how to find and how to set your proxy. It is easy - I promise. :)

#### Where can I download?

[See here](#download-here)

#### How can I install?

[See here](#installation)

#### What the hack is a proxy?

When you connect to the Internet, you may sometimes need to go through a proxy server — a computer system that sits between you and the Internet. Proxies are commonplace in schools, colleges, and workplaces and can limit and control access to the Internet. ([Text source](https://www.dummies.com/social-media/spotify/spotify-and-proxy-servers/))

If your Internet connection requires a proxy, you need to enter the details in the proxy settings window (right click on the YouTubeOnTop icon <img src="/_img/icon_youtubeontop_dark.png" width="16"> in the tray or right click in the YouTubeOnTop main window). Within the proxy settings window there is lot's of guidance to help you to find out your proxy settings. If that does not help, ask your school or workplace’s IT department, or your Internet Service Provider helpdesk, for the credentials.

#### Are you allowed to use the Google Dinosaur Game?

I have huge respect for all the awesome developers and designers out there in the world. For sure that includes also the chromium authors who developed and designed the Google Dinosaur Game.

You find an extra file with all the [LICENSES](/LICENSES.md).

**I want to thank all the great creators out there.**

_I am a dwarf standing on the shoulders of giants._

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MDEzNjc4NzMsLTg1NzQ5NzI2M119
-->
