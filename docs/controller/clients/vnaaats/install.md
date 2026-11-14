# Installing vNAAATS

For controllers using EuroScope on Windows. Allow about 15 minutes.

## Before you start

- EuroScope installed and working, and a VATSIM controller rating.
- The official Gander Oceanic sector package from AeroNav. It also keeps your AIRAC up to date.
- Your key from [vnaaats.com/get-key](https://vnaaats.com/get-key) (or your Gander Oceanic profile).
- Optional: VACS (voice between controllers) and an audio client, such as Audio for VATSIM or TrackAudio.

## 1. Get the Gander package

Download and run the Gander Oceanic package from AeroNav ([files.aero-nav.com/EXCXO](https://files.aero-nav.com/EXCXO)). Open EuroScope with that package once, so you can see the oceanic map, then close EuroScope. Note where your `EXOCO` folder is (the folder that holds `Plugins`).

## 2. Install FDD for Windows

Download it from [vnaaats.com/download](https://vnaaats.com/download) and run the installer. Windows may say "Windows protected your PC" because the installer is not code-signed yet. Choose **More info**, then **Run anyway**. No administrator rights are needed.

## 3. One-time setup

The setup screen appears the first time the app opens. Work down the steps:

1. **Your EXOCO folder.** Choose the folder from step 1.
2. **The vNAAATS plugin.** The app looks for `VatsimNAAATS.dll` in `EXOCO\Plugins\vNAAATS`. If it is missing or old, close EuroScope and press **Update now**. It also installs the airline list and the vNAAATS font.
3. **Your key.** Paste your key. The app writes it into `vnaaats.cfg` for you.
4. **EuroScope.** Point the app at `EuroScope.exe`. Leave "Open EuroScope for me when I choose my position" ticked.
5. **VACS and audio client (both optional).** Point the app at each program.

When every line is green, press **Continue**.

!!! tip
    To see incoming VACS calls on the headphones button in the FDD, open VACS (version 2.1.0 or newer), go to Advanced Settings and tick **Enable remote control**. Change the **Listen addr.** box to `127.0.0.1:9600`, so only your own computer can connect.

## 4. Load the plugin in EuroScope (once)

1. Open EuroScope with the Gander package.
2. Go to **Other SET > Plug-ins > Load** and pick `VatsimNAAATS.dll` (the one in `EXOCO\Plugins\vNAAATS`).
3. Only vNAAATS should be loaded. Remove any other plugin from the list while you work oceanic.

## 5. Open the vNAAATS screen (once)

1. Open the file menu and choose **New vNAAATS radar screen**. You get a blank screen with a blue bar at the top.
2. Open the file menu again, choose **Open**, and pick `vNAAATS.asr` (it is in the plugin pack zip on the download page).
3. If EuroScope warns about a different sector file, pick your latest Gander (EXCXO) sector file.
4. The oceanic map appears. Choose **Save** so you never have to do this again.

## 6. Every day after that

1. Open FDD for Windows. It opens EuroScope, VACS and your audio client for you (each only if ticked in setup).
2. In EuroScope, connect to VATSIM as your oceanic position (for example `NAT_FSS`, `CZQO_CTR` or `EGGX_CTR`) and open your saved vNAAATS screen.
3. Within a few seconds the display opens by itself on that position.
4. If an update is available, the app tells you and asks before it downloads anything. Close EuroScope first.

To check that it works, open `vNAAATS.log` (next to the DLL). Its first line shows the version.

## Autotype

The example config has `autotype=1` switched on. The **Send** buttons for SELCAL, contact me and RCL REQ then type the command into EuroScope for you. With `autotype=0`, or if Windows refuses, the command is copied instead, and you paste it into EuroScope's command line.

## Without the app

You can use the display in any browser at [vnaaats.com/fdd](https://vnaaats.com/fdd) and install the plugin by hand.

1. Get `VatsimNAAATS-plugin.zip` from the download page and unzip it somewhere you will remember.
2. Put `VatsimNAAATS.dll`, `ICAO_Airlines.txt`, `vNAAATS.ttf` and your `vnaaats.cfg` in the same folder.
3. For the config, rename `vnaaats.example.cfg` to `vnaaats.cfg`, set `server=https://vnaaats.com` and paste your `key=`.
4. Follow steps 4 and 5 above.

To update by hand, close EuroScope and replace only `VatsimNAAATS.dll`. Keep your existing `vnaaats.cfg` and saved screen. Do not copy the example config over it, or you will lose your key.
