# vNAAATS

vNAAATS is the oceanic controller toolset used for Gander and Shanwick. It gives every oceanic controller the same live flight data, so level, Mach, track, SELCAL and notes are the same on every screen within a few seconds.

!!! note
    vNAAATS is an independent community project. It is not run or endorsed by VATSIM. The latest information, downloads and videos are on [vnaaats.com](https://vnaaats.com).

## What it is made of

vNAAATS has three parts that share one set of flight data:

| Part | What it does |
| :--- | :----------- |
| **Flight Data Display (FDD)** | A web page ([vnaaats.com/fdd](https://vnaaats.com/fdd)) where you work. It lists every oceanic flight as a strip. You can change flight data, track and transfer aircraft, send messages and run CPDLC. |
| **EuroScope plugin** (`VatsimNAAATS.dll`) | Shows the same aircraft on your radar and in EuroScope's flight plan windows, and carries out what you ask for on the FDD (track, untrack, transfer, SELCAL, contact me). |
| **vNAAATS server** | Keeps everything in step, so every controller sees the same data. |

The FDD is your main screen. Keep EuroScope connected to VATSIM as your oceanic position, with the plugin loaded, and keep the FDD open next to it. EuroScope still does what only it can do: radar, your own tracking and the flight plan windows.

**FDD for Windows** is the recommended way to run it. It opens the display in its own window, looks after your plugin, airline list and font, and opens EuroScope, VACS and your audio client for you. A browser also works (for example, on an iPad).

## Who can use it

Controllers who are certified or endorsed to control the oceanic positions: Gander Oceanic, VATSIM UK (Shanwick), Virtual New York ARTCC (NYACC) and any other division endorsed to control them.

## How access works

Access is a personal key plus a live VATSIM connection. There is no password to remember and nobody has to approve you each time.

1. **Get your key** at [vnaaats.com/get-key](https://vnaaats.com/get-key). Gander Oceanic controllers can also take it from their profile on the Gander Oceanic website. The key lasts 90 days.
2. **Install** FDD for Windows, or use a browser. See [Installing](install.md).
3. **Paste your key once.** The EuroScope plugin reads it from `vnaaats.cfg` (`key=...`).
4. **Connect to VATSIM on an oceanic position.** The display waits on "Awaiting an active VATSIM connection" and opens by itself, on your position, a few seconds after you connect. An observer connection does not count.

### Positions that open the display

- `NAT_FSS` (the oceanic bandbox), with `NAT_I_FSS` for instructors and `NAT__FSS` for a relief
- `CZQO_` positions (Gander Radio and Delivery), including the extra positions and a relief `CZQO__CTR`
- `EGGX_` positions (Shanwick Radio and Delivery), including the extra positions and a relief `EGGX__CTR`

!!! warning
    Never share your key or ask for one for someone else's CID. The key only works while you are connected to VATSIM, as yourself, on one of the positions above.

## Where to go next

- [Installing](install.md): first-time setup, about 15 minutes.
- [Using the Flight Data Display](fdd.md): strips, the aircraft menu and a typical shift.
- [natTrak and RCL reminders](nattrak.md): pending and cleared requests, and the automatic reminder.
- [CPDLC in vNAAATS](cpdlc.md): signing in with your Hoppie code and working with pilots.
- [Problems and questions](troubleshooting.md).

The full user manual, with videos, is at [vnaaats.com/manual](https://vnaaats.com/manual).
