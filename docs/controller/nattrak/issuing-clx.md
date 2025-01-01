---
title: Issuing clearances
description: 
published: true
date: 2022-03-27T06:59:01.500Z
tags: 
editor: undefined
dateCreated: 2022-03-27T06:58:44.901Z
---

> Guidance for oceanic ATC only.

<!-- ![screenshot_2022-03-27_172249.png](/assets/nattrak/screenshot_2022-03-27_172249.png) -->

<figure markdown>
![YPAD Maneuvering Area Responsibility](/assets/nattrak/screenshot_2022-03-27_172249.png){ width="500" }
  <figcaption>YPAD Maneuvering Area Responsibility</figcaption>
</figure>

## Request Data

The request data will show:

* Callsign - CS
* Destination ICAO - DEST
* Route - Track or RR
* Entry - entry fix
* ETA - entry ETA
* FL - requested FL
* MFL - maximum FL
* Mach - requested mach
* REQ Time - request time

## ATC Requirements

Here you can issue restrictions or change flight level/mach.

### Datalink authority

This is the oceanic sector issuing the clearance. It *should* auto populate with your active sector providing you are logged into VATSIM correctly. If it cannot auto detect your sector, it will default to NAT bandbox. You may change this if you need. 

### Flight level, mach number

You can use the dropdowns to change the flight level/mach for the clearance. The pilot's request and maximum FL will be highlighted in the dropdown menu. *Don't use these dropdowns unless you are deviating from the request.*

### Entry time requirement for XXXXX

Use this to issue an entry time requirement for their entry fix. Format it as `NOT BEFORE 1000Z` for example. 

### Free text

Any extra details?

## Transmitting clearances

### Pilot CID

Displayed is the pilot CID in case you need to contact them via the network.

### **[Transmit Clearance]**

This button will send the clearance to the pilot. It will reject your submission if you filled out the form incorrectly in one way or another.

### [Delete]

This will delete the request, same as on the pending RCL messages page.

## What next?

![screenshot_2022-03-27_172749.png](/assets/nattrak/screenshot_2022-03-27_172749.png)

The clearance you just issued will be displayed. 

You can safely close the tab.
