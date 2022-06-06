## Prerequisites

#### Download and install the Hoppie's ATC client

You need the Hoppie's ATC client (not easyCPDLC or TopSky!) to use CPDLC in oceanic controlling.

[Download Hoppie's](https://www.hoppie.nl/acars/prg/atc/){ .md-button }

#### Download the templates file

Once you have installed the client, please download the Gander Oceanic templates file. It will be a file named `uplinks.txt`. Copy and overwrite the file into `C:\Program Files (x86)\Hoppie\ACARS-ATC\etc`.

[Download templates](https://cdn.ganderoceanic.ca/resources/files/atc/uplink.txt){ .md-button }

## Setup your client

Open the client and click *File* then *Setup*.

In the window, enter your Hoppie's [logon code](https://www.hoppie.nl/acars/system/register.html) and datalink authority code into "ATC Callsign".

*Datalink authorities*

* NAT_FSS: NATX
* CZQO_CTR/DEL: CZQX
* EGGX_CTR/DEL: EGGX

!!! warning

    When using the NAT_FSS authority `NATX`, this has the possibility to cause confusion with a NAT Track identified by X. Therefore, `NATX` will be the code that you logon as and put in your controller info, and the one pilots will enter into their CPDLC client such as easyCPDLC, but you will *reply* to messages as EGGX/CZQX depending on where the aircraft is. See an example of this in the [composition example.](#composing-an-oceanic-clearance-message-clx)

## Using the client

When connected your client will look like this. The green box at the bottom right indicates you are connected. It may take a few seconds to do that.

![Online client](https://ganderoceanicoca.ams3.digitaloceanspaces.com/resources/media/img/kb_cpdlc/online.png)

### Current messages

Retrieve the **Current Messages** window by clicking View and then Current Messages. This will show all the messages sent to you and from you to aircraft. When a message comes in, a "meep meep" sound will play.

![rcl](https://ganderoceanicoca.ams3.digitaloceanspaces.com/resources/media/img/kb_cpdlc/rcl.png)

### Replying to a message

Click on a new message to reply to it.

![rcl-dropdown](https://ganderoceanicoca.ams3.digitaloceanspaces.com/resources/media/img/kb_cpdlc/rcl-dropdown.png)

You can click STANDBY to tell the aircraft to standby. Use the other options with a note to the pilot via Euroscope messages as to why you've sent that response.

### Composing an oceanic clearance message (CLX)

![clx-compose](https://ganderoceanicoca.ams3.digitaloceanspaces.com/resources/media/img/kb_cpdlc/Screenshot%202022-06-06%20214630.png)

Clicking "Editor" will show this complex looking dialog. You need the options in the OCEANIC list. Click the relevant option. In the elements box, click on the blank `TEXT` and fill in the relevant information as per the template shows above (e.g. `ATC_LOGON`). `ATC_LOGON` should be your datalink authority code, except if you are on NAT_FSS, in which you use `CZQX` or `EGGX` depending on the aircraft's location.

If you cannot find some information such as destination or track, look at the vNAAATS data on EuroScope for help. If you can't find it still, reply UNABLE and establish voice contact with the pilot.

When you're ready, enter the information into vNAAATS flight plan and probe the clearance for conflicts. Then click `Send to (callsign)` in the CPDLC editor.

### Receiving a reply 

When the pilot has replied, you will see their response in the current messages window as per the screenshot.

![clx-response](https://ganderoceanicoca.ams3.digitaloceanspaces.com/resources/media/img/kb_cpdlc/clx-response.png)


### Sending messages

To send a message to a pilot such as "return to domestic", open the TELEX window. Under TELEX uplinks, type the callsign in the TO window. Then click CPDLC and compose the message.

### Seeing aircraft connected

You can open the Planes Online window to see who is connected to you.

## Further reading

[Hoppie's ATC client information](https://www.hoppie.nl/acars/prg/atc/)  
[Message log](https://www.hoppie.nl/acars/system/log.html)  
[Stations online](https://www.hoppie.nl/acars/system/online.html)