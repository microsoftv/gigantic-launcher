# Gigantic Launcher
### [Download](https://github.com/sleepycrow/gigantic-launcher/releases)

A graphical launcher for the game Gigantic.
This branch is specialized for the E3 2015 Alpha build.

![Screenshot](https://s15.postimg.cc/44482e9uz/gig.png)

## Getting Started

# Build Prerequisites

1. It is recommended that you build using Yarn. Visit the electron-builder install instructions page for details: https://www.electron.build/#installation

# Build Instructions

1. Assuming you have [yarn](https://yarnpkg.com/getting-started/install), [electron-builder](https://www.electron.build/#installation), and their subsequent prerequisties installed, you may build using the following commands:
`cd path/to/gigantic-launcher`, `yarn electron-builder`

## Installation & Launcher Setup

1. You may install using the pre-made Gigantic Launcher Setup or you may download the zip with all of the files directly.
* You will need to extract the zip to a folder.
* After extraction or installation, run the launcher and go to the Config tab to setup the path to your "Gigantic\Binaries\Win64\RxGame-Win64-Test.exe" file.
* You may now join or host a server, just make sure to make a unique name, otherwise the connection will become messy.

# Hosting Instructions
1. In order to host using the alpha build of Gigantic, you will need to port forward (unless you only want local connections).
* The port you forwarded must be the same as the one entered into the launcher.
2. After portforwarding, you will need to enable the "Dedicated Server" option in the launcher.

# Tips
1. Normally the Alpha build only has 2 maps, internally named "lv_canyon_v2" (Ghost Reef), and "lv_mistforge_stripped" (Sanctum Falls).
2. You can edit the map list of the launcher by editing the "gigantic-launcher\config.json" file.
3. Default installation location is "C:\Users\yourname\AppData\Local\Programs\gigantic-launcher".