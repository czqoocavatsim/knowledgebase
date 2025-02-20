# Vatsys Advanced
Information that will allow you to use vatsys like a pro, you will be able to weild it as and how you like.

## Tools
There are quite a few tools and keybinds used to make you life quicker and easier when controlling on VATSYS.

> Note all of these keybinds can be changed in ``Settings > Keyboard…``

### Velocity Vectors
<figure markdown>
![Profile Selction](/controller/img/vatsysvelocityvectors.png){ width="250" }
  <figcaption></figcaption>
</figure>
This is the Line drawn from the aircraft in the direction of travel (suggest you set to 10 mins)

### Short Route Probe
<figure markdown>
![Profile Selction](/controller/img/vatsysshortrouteprobe.png){ width="250" }
  <figcaption></figcaption>
</figure>
This is the line that follows the planed route based of a time/distance from the aircraft. I personally have it set to time > 10 and Default on

### History Trails
Shows you previous refresh positions. By default is 4, controller preference.
### FPASD
Flight Plan Air Situation Display. This is required to be on for all Oceanic controllers and is on by default. This allows you to to visualise positon reports with the square radar symbols

### Closest Approach tool
Closest Approach tool  displays the point at which two flight plan trajectories are closest. Select one track then use the keyboard (F1) and click the other to display closest approach trajectory.
<figure markdown>
![Profile Selction](https://virtualairtrafficsystem.com/images/closest_app01.PNG){ width="250" }
  <figcaption></figcaption>
</figure>
To clear a displayed closest approach, ``MIDDLE CLICK`` either, callsign, time label or distance..

> Note Whilst surveillance data is used to update flight plan trajectories, this tool is not using current radar/ADSB data.

### Conflict Area Tool
Conflict Area Tool determines the area that two flight plan routes are in lateral conflict. Select one track then use the keybind (F2) and click on the other. The drop down values are defined in the current profile and correspond to the required minimum lateral distance between the two routes. On successful calculation of a conflict area, the area with entry and exit times for both aircraft is displayed.
<figure markdown>
![Profile Selction](https://virtualairtrafficsystem.com/images/latc.png){ width="250" }
  <figcaption></figcaption>
</figure>
To clear a displayed conflict area, ``MIDDLE CLICK`` either callsign time label at the entry/exit point.

### BRL tool
Bearing and Range tool displays a bearing in degrees, from star to end. Reverse in the brackets, range in Nautical Miles, and a time to go in minutes when anchored on a track (radar return). Time to go is given as a 4 digit UTC time when one end is anchored to a track and the other is anchored to a point in space.

``backspace`` is used to start the BRL tool on your mouse position, left click can be used to place the other end.
<figure markdown>
![Profile Selction](/controller/img/vatsysbrltool.png){ width="250" }
  <figcaption></figcaption>
</figure>
> This example shows the ETH78 is flying 251 degrees M, and will reach 78.5nm at time 22:14z
## keybinds

### F9 Scratch Pad
Scratchpads placeable anywhere on your radar screen. Can be moved with ``Right Click``

### Numbpad +
Numbpad plus can be used primarily as a time save, is used as the quickest method to open the handoff window. 

All that is required is to have the track or strip selected. To select the track just click on the radar symbol so that an octagon appears around it. To select the strip, click the callsign so there is a coloured highlight around the strip. ``Numbpad +`` will then quickly open the handoff menu

### Enter

Similar to the above, Enter is the quick way to pickup a tag. Select the track or strip then simply hit enter and the tag is yours!

### View Point - Right Click

Right Click can be used to set the precise location of where you want the view point. 
Start by right clicking where you want the center of your screen to show. Then, move out to select how large you want the area.

### View Point - MMB “peak”

You can move your view point around freely with middle mouse held down. This allows you to peak your view point somewhere until you let go returning it back to the previous location.

### Tag/track Highlight
You can highlight a tag/track for your attention later my ``middle clicking`` the track symbol.

### Refuse or Hide a tag
You can refuse or hide a tag having the track/strip selected and using the keybind ``SHIFT numb+``

This can also be used to completely remove a FSPAD

## Mid Connection Sector Changing
In the event you’re controlling NAT_FFS and another controller wishes to logon Gander, when they connect the sectors/airspace associated with their connection will automatically remove from you. However should you wish to re-open to extend to the other sector. You can go to ``settings > Sectors…``

Sectors listed on the left are sectors you own, all the other sectors defined in the profile are listed on the right. Note that sectors not controllable by you are listed here.

To pickup a sector, use one of the following options NATOC, SHANO, GANOC. Simply move the ones you want to the left and hit apply. This will manage all the little subsectors and transitional areas for you. 

## Uncoupled flight plan?
If a pilot enters your vis range or you connect and they are too far from their route their flight plan will be unable to couple as it is looking for them along their route. To resolve this you can use manual coupling. By locating the flight plan either in your strips (usually preactive) or by searching the flight plan ``Windows > Flight plan``

Select the track, and click couple on the flight plan to couple it to that track. This will then allow you to control it as normal (note you almost definitely will get a RAM as that is usually the reason it didn’t couple in the first place)
## Decoupling a flight plan
If for some reason you wish to decouple the flight plan, you can do so the same way, simply click decouple when you open the flight plan window.
## Further Reading
Vatsys has a lot of useful tools and keybinds, if you wish to deepen your knowledge beyond what is covered in our Gander Knowledgebase, you can check out the [vatsys docs](https://virtualairtrafficsystem.com/docs/). Please note that the vatsys docs are designed around the Australian profile and will have some contradicting information. For anything that disagrees with the Gander Knowledge base, assume our information is correct for your NAT usage of the client.

VATSYS Docs were directly used for applicable information/images