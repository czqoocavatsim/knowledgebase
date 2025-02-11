There are a variety of different alias commands which are avaiable for Oceanic Controllers to utilise while controlling Oceanic Airspace. The below list is a complete and total list for all controllers to review.

> Note: Explanations of variables are notated at the bottom of this page.

## General Messages
| Shortcut| Message|
| :--------------- | :-------------------------------------------------------------------------------------------- |
|.gd|$radioname, Good Day.|
|.gm|$radioname, Good Morning.|
|.ga|$radioname, Good Afternoon.|
|.ge|$radioname, Good Evening|
|.v?|Are you able to recieve voice|
|.pym|Pass your message.|
|.r|Roger|
|.a|Affirm|
|.n|Negative|
|.d|Disregard|
|.stby|Standby|
|.s|.selcal|
|.proc|.msg $aircraft Hello, here is some great information to asisst you in understanding Oceanic Procedures within EGGX/CZQO Airspace - https://knowledgebase.ganderoceanic.ca/|

**Note:** *```.msg $aircraft``` will automatically open a chat message with the pilot when clicking on their callsign.*

## Aircraft Contact
| Shortcut| Message|
| :--------------- | :-------------------------------------------------------------------------------------------- |
| .clr | .msg $aircraft Hello, you will soon be entering oceanic airspace. Please request oceanic clearance via nattrak.vatsim.net no later than 20 minutes before your oceanic entry point. Clearance via CPDLC is unavailable.|
|.clrv|Please request an oceanic clearence on $freq|
|.nattrak| Please request an oceanic clearence via https://nattrak.vatsim.net|
|.cpos| .msg $aircraft Hello, you are currently in oceanic airspace. Please contact me with your last position report on $freq. Thanks!|

## Oceanic Clearances


## Ammended Oceanic Clearances

.c Amended clearance. $radioname clears $aircraft, climb $alt.
.df Amended clearance. $radioname clears $aircraft, descend $alt.
.m Amended clearance. $radioname clears $aircraft, maintain Mach $1.

## Position Reports
| Shortcut| Message|
| :--------------- | :-------------------------------------------------------------------------------------------- |
|.co|Over $1, call $radioname($2) on $freq($2), good day.|
|.con|Call $radioname($1) on $freq($1), good day.|
|.uni|Leaving Oceanic Airspace,  Monitor Advisory 122.800, enjoy your flight.
|.unio|Over $1 you will be leaving Oceanic Airspace, please monitor advisory 122.800. Enjoy the rest of your flight!|
|.posr|Go ahead with your Position Report|
|.pr|$radioname copies $aircraft passing $2 at time $3, FL$4, estimating $5 at time $6, $7 thereafter|

## Change Levels


## Handovers

## Variables used within Messages
| Variable | Function|
| :--------------- | :-------------------------------------------------------------------------------------------- |
|.chat|Opens a chat with a specific aircraft (when clicked)|
|.msg $aircraft|Opens a msg with the selected Aircraft
|$1 (etc)|Variable which allows the controller to type a message in (tab moves between them)