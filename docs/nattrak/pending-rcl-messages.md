---
title: Pending RCL messages page
description: 
published: true
date: 2022-03-27T06:59:09.889Z
tags: 
editor: undefined
dateCreated: 2022-03-27T06:49:58.148Z
---

> Guidance for oceanic ATC only.

![screenshot_2022-03-27_171413.png](/assets/nattrak/screenshot_2022-03-27_171413.png)

## Filtering by track

The top dropdown menu labelled *Change track* allows you to filter RCL messages by a specific track. By default filtering is disabled and all tracks+RRs will be displayed.

![screenshot_2022-03-27_171519.png](/assets/nattrak/screenshot_2022-03-27_171519.png)

Eventually the number of pending requests per track will be displayed in the dropdown too. 

## Receiving new messages

The table of pending RCL messages will automatically populate with new messages as they come in, at the bottom of the page (they're ordered by request time). 

Alternatively you can refresh the page. Your filter option won't be closed providing you just do F5 with the same URL e.g. `controllers/clx/pending?sortByTrack=A`.

## Table structure

The table will show:

* Callsign - CS
* Destination ICAO - DEST
* Route - Track or RR
* Entry - entry fix
* ETA - entry ETA
* FL - requested FL
* MFL - maximum FL
* Mach - requested mach
* REQ Time - request time
* **[ACTION]** - open new tab with clearance issuing form
* [DEL] - dismiss the clearance. Only use if you cannot issue it via natTrak or if it's irrelevant data.

## Issuing a clearance

View issuing clearance page. [Issuing clearances.](/nattrak/issuing-clx)