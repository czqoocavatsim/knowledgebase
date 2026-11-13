# Using the Flight Data Display

The Flight Data Display (FDD) is where you work. Almost everything you do in EuroScope can also be done here.

## The screen

- **Left (large panel):** the filter bar, the controls bar, the natTrak **PENDING** and **CLEARED** boxes, and below them the flight strips.
- **Right, top:** the Flight Plan panel for the selected aircraft.
- **Right, middle:** natTrak information.
- **Right, bottom:** the Tracks panel (today's NATs, with the TMI in the heading).
- **Pop-ups:** the aircraft menu (click a callsign), the CPDLC drawer and the position reports table.

## Filters and the header

| Control | What it does |
| :------ | :----------- |
| ALL TK / RR | All tracks, or random routings only. |
| TRKD, EB, WB, RR, TANGO | Show only flights you are tracking, eastbound, westbound, random routings or Shanwick Tango routes. With nothing ticked you see everything. Boxes in different groups narrow each other (TRKD + WB is your westbound flights). Within a group, either counts. |
| Search or add | Type part of a callsign or fix to filter the list. To bring a flight onto the display, type its full callsign and press **Add**. |
| Show | The default, entry -60 / exit +15 min, shows a flight from 60 minutes before its oceanic entry estimate until 15 minutes after its exit estimate. **All flights** shows everything. |
| Group / Sort | Group by track, entry fix or level. Sort by newest first, entry ETA, callsign, level or last changed. |
| CPDLC button | Opens the CPDLC drawer. See [CPDLC in vNAAATS](cpdlc.md). |
| Auto RCL | The automatic RCL reminder. See [natTrak and RCL reminders](nattrak.md). |
| Warning triangle | The number of flights that currently have a warning on their strip. |

Flights with no times, the selected flight, flights on CPDLC, pending natTrak requests and flights tracked by an oceanic controller always show.

## Flight strips

Each flight is one strip, grouped under its track or entry fix. The strip shows the callsign, type, departure and arrival, level, Mach, track and the estimated time over each fix.

| Symbol | Meaning |
| :----- | :------ |
| `[CALLSIGN]` | The pilot is logged on to CPDLC with vNAAATS. |
| `*` after the callsign | The aircraft is not AGCS equipped (worked out from the PBN and remarks of the flight plan). |
| Red `*` | You sent the pilot the natTrak reminder (RCL REQ). It clears when the pilot requests clearance or an oceanic controller tracks the aircraft. |
| Pencil | Something on this strip was changed in the last 10 minutes. Hover to see who and when. |
| Warning triangle | Two aircraft enter on the same track and level within 10 minutes of each other, or the level is not one of the track's levels. Hover for the reason. |
| Headset | Who the pilot is talking to, from the tuned frequency: bold green is an oceanic controller, faded green is a domestic controller, orange is UNICOM (122.800), red and crossed out is on neither. |
| Clipboard with a tick | The clearance was processed on natTrak. |
| Flashing strip | A natTrak request is waiting, a CPDLC message or logon needs a look, or a position report is overdue. |

!!! note
    The display does not check separation between aircraft. That is the controller's job.

A one-page icon key with every symbol and colour is available as a PDF at [vnaaats.com/icons](https://vnaaats.com/icons).

## The aircraft menu

Click a callsign. The tabs are:

- **Track:** check or change the level, Mach and SELCAL, then **Track aircraft**. If another controller is handing the aircraft to you, this also accepts the handoff.
- **Transfer:** pick the controller to hand the aircraft to. If nobody suitable is online, use UNICOM in the CPDLC drawer.
- **Release Tag:** releases the aircraft in EuroScope.
- **SELCAL:** enter or change the 4-letter code, send a SELCAL check, or copy the `.selcal` command.
- **CPDLC:** opens the CPDLC drawer for this aircraft if the pilot is connected.
- **Note:** a short note (up to 15 characters), shown under the tag in EuroScope.
- **Contact Me:** runs EuroScope's contact-me command.
- **RCL REQ:** the reminder asking the pilot to request clearance on natTrak.
- **Hide:** hides the strip for you only, for 12 hours.
- **Position reports:** for Concorde, or any flight with **Voice reports** switched on.
- **Supervisor:** write a message to the supervisors, or use **No Contact** for the standard text.

Track, transfer, SELCAL and contact me need you to be signed in with a position and EuroScope connected.

## The flight plan panel

Shows the flight you last clicked. Boxes you can type in are saved on the server, and every other controller sees the change within seconds. Your EuroScope flight plan window updates by itself.

- **Entry:** the time at the oceanic entry fix. Edit it and all the fix times move by the same amount.
- **Level, Mach, Track:** editable. A warning appears if the level is not one of the track's levels.
- **Route (edit):** amend the route. Write latitude and longitude fixes as two numbers over two numbers (for example `51/20`). This changes the FDD and server only, not the flight plan in EuroScope or on VATSIM.
- **Note and SELCAL:** editable.
- **Last change:** who last changed level, Mach, track, SELCAL or the route.

## Position reports

Aircraft without ADS-B or ADS-C report by voice. For those flights:

1. Click the callsign to open the aircraft menu.
2. Press **Voice reports: off**. It changes to **Voice reports: ON**, and a **Position reports** button appears.
3. Type each report as the pilot gives it, as four digits. Press **now** for the current time.

Reported times replace the calculated times on the strip. It is for that one flight only and switches itself off after 18 hours. A flight whose next fix is more than 3 minutes past its time with no report flashes, and the top bar shows an overdue count.

## Shanwick Tango routes

Flights filed on a Tango route (T9, T290, T213, T13, T16) are listed together in one **TANGO ROUTES** group, below the NAT tracks and above RANDOM. They need an oceanic clearance like any other flight. A Gander position does not list them unless it is tracking one.

## A typical shift

1. Connect EuroScope to VATSIM as your position. The FDD opens on that position.
2. Check the Tracks panel for today's NATs and the **Show** setting for the strips you want.
3. If an aircraft approaching the boundary has not asked for clearance, open its menu and use **RCL REQ > Send**.
4. When a pilot requests clearance, the PENDING box flashes. Click the row to open natTrak and issue it.
5. Check the level, Mach, track and SELCAL in the flight plan panel. Fix anything that is wrong.
6. When the aircraft is yours, use **Track aircraft** (or accept the handoff).
7. When a pilot logs on to CPDLC, open the drawer and reply or send the standard messages you need.
8. When an aircraft leaves your area, use **Transfer**. With nobody online, use UNICOM in the CPDLC drawer.

## What you see in EuroScope

- Aircraft icons on the radar point along the heading. Filled means cleared, outline means not cleared yet.
- `[CALLSIGN]` on the tag: the pilot is on CPDLC. `*` under the callsign: not AGCS equipped. Red `*`: the natTrak reminder was sent.
- Anything you change in EuroScope shows on the FDD within seconds, and the other way round.
- Tracking an aircraft no longer changes its transponder code. Pilots who log on to CPDLC are sent a message to squawk 2000 within 10 minutes of entering the OCA.
