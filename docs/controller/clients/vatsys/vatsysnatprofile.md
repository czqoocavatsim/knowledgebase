# NAT profile
Our Vatsys profile has A LOT of bespoke functionality that doesn’t appear in standard profiles. Which will be outlined in this document for people who are already familiar with standard VATSYS profiles. 

The main thing that may call your attention is the new strips and tags. You’ll also see the tracks on your screen they will appear and disappear based on their validity periods. Additionally VATACARs, once it’s ready will be built directly into the profile. Once it’s ready more info on its usage will be listed here.

## Stips differences
<figure markdown>
![Profile Selction](/controller/img/vatsysstrip.png){ width="750" }
  <figcaption>Handoff Menu</figcaption>
</figure>
Immediately you can tell the strips are a lot longer than they used to be. But also not as tall. 

### Box 1 

1. Status (Controlled/Uncontrolled) shown as CO* and UN* **<sup>^1</sup>**

2. controlling sector if applicable (NATOC in this example) **<sup>^2</sup>**

3. Aircraft type A388, 

4. Aircraft crossing track (RR for random routing in this case), 

5. First observed height (FL349 in this example), 

6. SELCAL is shown IF it is valid and listed in the flight plan (ABCD in this example), <br>

<sup> line 2 </sup>

1. Callsign (BAW268), **<sup>^!~3</sup>**

2. Departure (KLAX), 

3. Destination (EGLL), **<sup>^4</sup>**

4. Cleared level (350), **<sup>^5</sup>**

5. Mach if cleared (0.85)

**<sup>^</sup>** = left clickable, **<sup>!</sup>** = Middle clickable, **<sup>~</sup>** = Right Clickable

 <sup>^1</sup> Only clickable on PR* strips that failed to activate for any reason.<br>
<sup>^2</sup> Click to hand the aircraft to another controller<br>
<sup>^!~3</sup> Click to Highlight and lock in place. MMB to hide strip, RMB to cock strip to the right<br>
<sup>^4</sup> Open the aircraft option menu:<figure markdown>
![Profile Selction](/controller/img/vatsyscontrollermenu.png){ width="150" }
  <figcaption>control menu</figcaption>
</figure>
<sup>^5</sup> Open level clearance menu:<figure markdown>
![Profile Selction](/controller/img/vatsyslevelselect.png){ width="100" }
  <figcaption>Cleared level selector</figcaption>
</figure>

### Box 2-9 (position boxes)
Waypoint or Lat/long
Time Estimate

### Box 10 
contains a global ops field (scratch pad) on top (text says GLOBAL) <br>
And a local ops field (scratch pad) underneath (currently blank)	

## Position reports

Aircraft who are NOT ADS-B equipped should be instructed to turn their XPDR off to allow full position reporting functionality. Aircraft who are ready for position reports look like the square below. Enter the information they provide into the strip by clicking on the times. 
<figure markdown>
![Profile Selction](/controller/img/vatsyspositionreport.png){ width="850" }
  <figcaption>position reports</figcaption>
</figure>
Any point that is highlighted is “armed”, when a position report is received both times should be entered even if they remain unchanged to disarm the waypoint. 

If an armed point is not disarmed by 2 mins you will get an MPR warning.


## Tag/Label and radar symbols

### Colours
<figure markdown>
![Profile Selction](/controller/img/vatsyscolourful.png){ width="850" }
  <figcaption>COLOURS</figcaption>
</figure>
Purple, unowned or owned by other controller

Orange, Owner by you

Cyan, in/out aircraft

Yellow, handed out aircraft

Blue, uncorrelated aircraft
### Layout/info
<figure markdown>
![Profile Selction](/controller/img/vatsystagram.png){ width="850" }
  <figcaption>controlled tag with RAM</figcaption>
</figure>	

Line 0: Any Alerts will appear in yellow here. 
 <sub>(RAM=route adherence monitor, CLAM= Cleared Level Adherence Monitor, MPR= Missed position report, STCA= Short Term Conflict Advisory, RAD= Radio Failure (squawk 7600), EMER= General Emergency (Squawk 7700).) These can be middle mouse clicked to mute/acknowledge.</sub>

Line 1:<br>Callsign **<sup>^~1</sup>** (BAW113) <br> Direct message and Voice identifier **<sup>^!2</sup>** (+ symbol) <br> Track Identifier and ADS-B confirmation **<sup>^3</sup>** (? means unknown track, Else there will be a letter for a track or RR. If there is an underline, like this image, they are NOT ADS-B equipped. Track E non ADS-B in this case)

Line 2:<br>Observed/reported Level **<sup>^4</sup>**(340) <br> Cleared level **<sup>^!5</sup>** (340) <br> observed ground speed (44 meaning 440 knots)

Line 3: <br>Destination (KFJK) <br> Aircraft (B77W) <br> RNP rating (Z = NO RNP, else a number specified how many nautical miles accurate)

^ = left clickable, ! = Middle clickable, ~ = Right Clickable<br>
**^~1** provides a drop down visible below. (RMB = SAR watch time or AFK time)

**^!2** Provides the “CPDLC” editor, also listed above, for direct message CPDLC functionality, (MMB offsets the tag vertically)

**^3** Takes you Directly to either the Create or pending Nattracks page. IF you’re experiencing a 403 error you should go to the [Nattrack login page](https://nattrak.vatsim.net/auth/redirect){target="_blank"}. Else if you click this on a cleared aircraft it will bring up a window to view and adjust their clearance (LOCALLY) or allow you to visit the website to change these details globally

**^4** Only clickable when dealing with position reports (no coupled radar return)

**^!5** Click to adjust the cleared level.Use the BLK for block level clearances. Once the pilot reads back the clearance you may MMB to acknowledge it.
 
## Symbols
![alt text](../../img/vatsysfaspad.png){ width="30" }FASPAD = a flight plan without a radar return correlated.

![alt text](../../img/vatsys2000adsb.png){ width="30" }Solid Plane = an aircraft squawking the correct oceanic code 2000.

![alt text](../../img/vatsysrandomadsb.png){ width="30" }Hollow plane = Mode Charlie, non 2000 code.

![alt text](../../img/vatsyssecondaryradar.png){ width="30" }Small Octagon = Secondary Domestic radar <sub>(shown with the below symbol)</sub>

![alt text](../../img/vatsysprimaryradar.png){ width="30" }Skeleton Plane = Primary domestic radar return <sub>(this image depicts with the hollow plane as well)</sub>

![alt text](../../img/vatsysradarcoast.png){ width="30" }Hash = Data packets or radar coverage dropped <sub>(never visible for more than a second)</sub>

![alt text](../../img/vatsysrelectedadsb.png){ width="30" } Larger Octagon = Aircraft Selected identification.<sub>(shows the aircraft you have selected, usually for contact me-s or strip locking)</sub>

## Nattracks & window

### Track window
<figure markdown>
![Profile Selction](/controller/img/vatsystrackinfo.png){ width="350" }
  <figcaption>Track Info Window</figcaption>
</figure>	
The Nat track window can be found under ``Windows > NAT Track Info`` 

With the TMI listed on top, in this example 366(happy new year!)<br> All the tracks and their valid times and levels are listed here. <br>If you’d like to refresh the tracks for any reason, you may with the refresh button however it automatically refreshes in the background.

### View inactive tracks
By default tracks are only visible when they are valid (15 mins before and after) If you wish to change the visible tracks, open the NAT track info window and click “Normal” switch it to “All” then “None” 
> NOTE that there is a 60 second refresh timer so don’t expect immediate response
	
## Nat Clearances
All clearances are currently done through the Nattrack.vatsim.net website. You can click the identifier for any aircraft **that you own** to open the website. 
> NOTE it takes up to 15 secs for the website to recognise your connection to the network, and will show 403 error. 

> Note if after this time the error persists, return to the nattracks home page and ensure you are logged in. 
From there clicking the aircraft tag will take you to relevant pages correctly.

## Yellow Track Identifiers
If you spot a Yellow Track identifier on a tag, this is an RCL sitting in the pending list awaiting your review. To clear it, click on the yellow idietifier to fo the the natracks website, move the RCL to processed.
<figure markdown>
![Profile Selction](/controller/img/vatsysunowned.png){ width="150" }
  <figcaption>Example pending RCL</figcaption>
</figure>	

## No RCL received from Aircraft?
Want to send a message reminding pilots of their requirements to send an RCL? you can click on the CPDLC button on their tag/label <sub>(for voice capable aircraft, this button is invisible but clickable, however for aircraft text or receive only, will have a + or - symbol respectively.)</sub>
<figure markdown>
![Profile Selction](/controller/img/vatsyscpdlcclrn.png){ width="350" }
  <figcaption>CPDLC clearance tab</figcaption>
</figure>	

## SELCAL
It should be noted that, unlike Euroscope Vatsys uses SELCAL16 simulation. The rules to which are outlined [here](https://en.wikipedia.org/wiki/SELCAL#Code_registration){ target="_blank" }. 
	
If a SELCAL is filed and is valid, it will be listed in the strip above the mach.
### Calling a SELCAL
To call an aircraft SELCAL there are multiple options, if you own the aircraft you may click on the callsign on the label/tag, or the destination on the strip. Then click the SELCAL option.

Alternatively if you do not own the aircraft, select the aircraft symbol, then in the top bar use ``tool > SELCAL``, which will open the same menu and pre-fill the selected aircraft if they have selcal in their flight plan.

### Adding SELCAL to flight plan
Weather you’re filling a pilot generated SELCAL or Generating one for them you can place the SELCAL in their remarks section by ``modifying`` their flightplan, ensure use of `` SEL/ABCD ``
<figure markdown>
![Profile Selction](/controller/img/vatsysflightplanselcal.png){ width="350" }
  <figcaption>Track Info Window</figcaption>
</figure>	

## Further Reading
[Nat Profile](/controller/clients/vatsys/vatsysbasics) <br>
[vatSys Advanced](/controller/clients/vatsys/vatsysadvanced)