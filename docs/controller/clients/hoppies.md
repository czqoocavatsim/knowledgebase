# Standalone ACARS Client

## Prerequisites
1. For the use of CPDLC on the network, one requires a Hoppies acars account. [Registration](https://hoppie.nl/acars/system/register.html)

2. TOPSKY plugin for euroscope OR standalone CPDLC client for VATSYS (further info bellow)

## Download

Unlike Euroscope, VATSYS doesn't (at time of writing) have any working plugin for hoppies ACARS, so we have to use the Standalone Client. 
[Download Hoppies](https://hoppie.nl/acars/prg/atc/acarsatc-1.5.1-install.exe)

When running the installer, note where you install it as you will need to refrence this as we get you setup. The Defualt location is `C:\Program Files (x86)\Hoppie\ACARS-ATC`

## Setup and Config
Unless you would like to keep the Roadrunner noise as your notification you're going to need to download new .wav Files, these may be what ever you like, how ever here are our suggested ones. 
[Download Audio Files](https://ganderoceanic.ca/ACARS_AUDIO.zip)

You will also need an "Uplink" file which specifies what messages you can send and what pilots can respond with. **This File is NOT optional for Gander CPDLC**
[Download Uplink Files](https://ganderoceanic.ca/NAT_Plus_Uplink.zip)

Once you have these files downloaded let's place them in the right location. 

Copy both the Audio files to (defualt location) `C:\Program Files (x86)\Hoppie\ACARS-ATC\lib` If you did choose to use ours. If you chose to use your own, 
> [!IMPORTANT]
> the names aren't important, and you may leave them in any folder on your machine.

For the Uplink file. Place it in (deualt location) `C:\Program Files (x86)\Hoppie\ACARS-ATC\uplink` This MAY be empty be defualt.

## Finally, it's time to open the software

With the client open, click `File -> Setup...` This will open the CPDLC setup window. now, unlike Euroscope, we only need to enter the ACARS (hoppies) Logon code once. So, pull the logon code from your email and place it in the `ACARS Logon` box. 
>[!IMPORTANT]
>Leave the ACARS server as is. 

Now, you may tell the Client what Uplink file you wish to use. click the Browse button next to the "Uplink Files" and locate where you placed your uplink file. (defult `C:\Program Files (x86)\Hoppie\ACARS-ATC\uplink\uplink.txt`)

Just repeate the same for both Audio files, our audio files have been named according to which one they fit best: Telex sound `C:\Program Files (x86)\Hoppie\ACARS-ATC\lib\TELEX.wav` and CPDLC sound `C:\Program Files (x86)\Hoppie\ACARS-ATC\lib\CPDLC.wav`

Now you're ready to connect.

## getting connected
Fill your "ATC Callsign" with the correct logon code. refer [ATC LOGON CODES] for relevent codes.
> [!NOTE]
> you will only need to input your ACARS code once. AND the client will attempt to log you in as your last callsign upon opening

Ensure your ACARS code is correct, then click `Ok` 

## What's where?

The Primary screen shows you the following information
    - Uplink file info
    - Status bar and coloured box.

That's it.

To open other tabs, Right click the top bar of the primary window.

you will be displayed with;
-    `Current Msgs`
-    `Planes online`
-    `TELEX`

## Planes online
planes online gives you a list of aircraft which have logged onto CPDLC. You may start a CPDLC uplink to an callsign by left clicking on them. If for some reason you need to manually log an aircraft on, you may add their callsign in the box down the bottom.
> [!NOTE]
> It is common for planes to not respond with a "logoff" statment when you log them off, so they will remain in the list. At the time of writing there is no known way to remove said aircraft.

If a callsign turns yellow it means the recipient is no longer on the HOPPIES ACARS network. You may disregard this callsign.

## TELEX

Where all your sent and recived telex's can be found.

You may click any downlink and reply either with CPDLC or telex. 

CPDLC can be sent by clicking CPDLC once the callsign has been entered into the `To:` box. (you may enter a new one by typing it in.)

Telex can be sent in a similar, with the callsign in the `To:` box, write the telex content in the box bellow, and click send.

All previously sent TELEXs will sit in `TELEX Uplinks`

## Current Msgs

Shockingly, Current messages provide you with a view of all your current messages. There are 4 different colours found in the current messages window.

### Green, interactable text. 
(left click to open a menu) options are as follows;

-   `STANDBY` (sends this plain text, Will leave the message green for you to interact with again when you get a chance.)
-   `ACCEPT LOGON` (this option only appears when you're interacting with a CPDLC logon request. This will add the callsign to your planes online window and log their aircraft onto your CPDLC.)
-   `Editor...` (opens the CPDLC editor so you may respond. This message will remain green untill a reponse is sent.)
-   `REQEST DEFFERED` (sends the plain text. Provides no explination, ideally you'll clarify with voice.)
-   `UNABLE` (sends plain text. Provides no explination.)
-   `UNABLE DUE TRAFFIC` (sends plain text.)
-   `UNABLE DUE AIRSPACE` (sends plain text.)

### Cream, intereacted messages.

This message *MAY* have been a blue message. If it was it will now be accompanied with a Blue message or a second cream message.
You have no further need to see cream messages and may delete/remove them by right clicking.

### Blue, Uplink Message

A blue message is one YOU sent, this will be awaiting a reply... Once it has turned Creame it may be removed. DO NOT delete a blue message before hand. (unless control sesion over)

### Black, A reply
Simply, a Black message is a reply to your message. usually consisting of "WILCO, ROGER, UNABLE" etc.

### Sumary
Green, left click to reply.

Blue, DO NOT REMOVE
 
Cream and Black. Complete messages, remove with right click.   
 
## Further reading
[Hoppie's ATC client information](https://www.hoppie.nl/acars/prg/atc/)  
[Message log](https://www.hoppie.nl/acars/system/log.html)  
[Stations online](https://www.hoppie.nl/acars/system/online.html)
