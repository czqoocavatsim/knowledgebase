# PAGE UPDATE WIP
# Prerequisites
1. For the use of CPDLC on the network, one requires a Hoppies acars account. [Registration](https://hoppie.nl/acars/system/register.html)

2. TOPSKY plugin for euroscope OR standalone CPDLC client for VATSYS (further info bellow)

# TOPSKY plugin setup
Once connected to the netowork, you wish to provide a CPDLC service, assuming you're using the Gander Sector files, you're 90% of the way there!

For CPDLC logon locate TOPSKY Menu bar (grey one with time on left). Navigate `Setup > CPDLC Setting...`

<img width="83" alt="image" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/7c51f587-fe75-424d-ba92-ff2ddb3f1fcb">

A new window should have appeared, the `Login` box may have auto filled with the correct code. If not refer to [ATC LOGON CODES] for further information.

<img width="81" alt="image" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/fa6e6702-e4e1-4310-8637-5a4bbe79f913">

Place your Hoppie logon code (*you will have recived this via email upon regestering with hoppies*) Ensure you have Auto-accept logon **OFF** this will be on by deafult and may cause aircraft to logon without having made voice contact and selcal watch. The Rest of the settings are ideal as is.

That's it, you're ready to provide a CPDLC service.

## Accepting logons and reviewing messages

You May start hearing a new noise once you annouce your CPDLC capability and aircraft may have flashing [] either side of their callsign, not to stress. Navigate to ***Tools > CPDLC > Current Messages***

<img width="139" alt="image" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/1d4a418e-38c2-4542-bcf1-52aa2e7a7f43">
<img width="187" alt="image" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/ffaa8d3f-d20f-4848-a6b4-171ab1055a9a">

A window like this will have appeared, you can interact with mesages by clicking on them. `ACCEPT` Means you will allow them to Logon, `UNABLE` Will deny the logon request. 
you may ocasionally get freetext messages that WILL let you respond to them here. clickiing `REPLY` will allow you to write free text in the box, and dictate what repsonse you're allowing the pilot to give. Eg. "AFK approved, report back" with "Roger" as a response.

Don't forget to Archive messages once they are no longer needed to ensure you can maintain situational awareness.

## Logged on Aircraft

Once an aircraft is logged on their callsign will have solid [] square brakets (as shown bellow). This means they are logged on to CPDLC and will recive every intruction you add to their tag, eg updating their mach or FL. 

<img width="100" alt="Screenshot 2024-05-16 165739" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/766070db-d094-440c-9fba-d22a8dd3ff0e">

In the event they logon to CPDLC before you copy their Mach and FL they will recive the "maintain FLXYZ" and "Maintain Mach X.YZ" via CPDLC and may be confused.
<img width="189" alt="Screenshot 2024-05-16 165842" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/7d25020f-f5e0-42ad-a6bd-8afdc1d814ed">

Don't stress!! This can be prevented! with a CPDLC logged on aircraft, you will now see two options when selecting a mach/FL a `R/T` and `CPDLC` option. If you have discussed the change on freq and don't wish to send the pilot a CPDLC, click the `R/T` option. Which will allow you to change it silently. 

<img width="80" alt="Screenshot 2024-05-16 165814" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/3542c813-946c-4d27-8ddf-e289c39f8b02">

## CPDLC Mach and FL instructions?

Once you've sent a CPDLC instruction to climb/descend or change MACH a set for square brakets [] will appear around the info in Blue. <img width="80" alt="Screenshot 2024-05-16 165825" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/e774b239-8337-4768-870e-17ea904d1361"> 
Once the pilot responds with `WILCO` to the instruction, the brakets will go away. 
If the pilot says `UNABLE` the change will revert. 

In the event the pilot takes too long to respond the uplink will go brown on both tag and messages.

<img width="80" alt="Screenshot 2024-05-16 170027" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/bac267e4-ae7e-442b-995d-8c49ebc830ef">
<img width="250" alt="Screenshot 2024-05-16 170034" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/5f2dbed0-dbbc-432a-888e-52fdc621e4e6">

## Free text messages?

Sadly unlike the pilots we're unable to send "free text" although we are teased with the idea. To send a "free text" message to inform the pilot of something, click on the tag callsign. 
> [!NOTE]
> (aircraft has to already be logged onto CPDLC)
Click the `CPDLC Free Text` option. which provide a series of suggested messages includind AFK, the only response to an oceanic request, and some unicom handoff statments...

<img width="100" alt="Screenshot 2024-05-16 165941" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/98b58b67-d73f-41f9-b178-bf26f55c2986">
<img width="316" alt="Screenshot 2024-05-16 165956" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/f85319c4-f131-4e02-8e28-afb35a2c4c64">

## Ending a CPDLC service

Handing the aircraft off to unicom via CPDLC is the most underwhelming to do it, how ever if work load dictates it's easier then send it. you can find the option of unicom statments above. 
Once the Aircraft has responded to the handoff statment **AND NOT BEFORE TO PREVENT RECIVING AN UPLINK ERROR** you may click the `END CPDLC` button free the aircraft. This will remove the logon and return the aircraft to lonley com.

<img width="380" alt="Screenshot 2024-05-16 170141" src="https://github.com/czqoocavatsim/knowledgebase/assets/169089251/e1de7142-1372-463f-917c-1525f78d3d61">

and you can continue with Rulling one of the 7 seas. well, ocean.

# VATSYS / Standalone Client
## Download

Unlike Euroscope, VATSYS doesn't (at time of writing) have any working plugin for hoppies ACARS, so we have to use the Standalone Client. 
[Download Hoppies](https://hoppie.nl/acars/prg/atc/acarsatc-1.5.1-install.exe)

When running the installer, note where you install it as you will need to refrence this as we get you setup. The Defualt location is `C:\Program Files (x86)\Hoppie\ACARS-ATC`

## Setup and Config
Unless you would like to keep the Roadrunner noise as your notification you're going to need to download new .wav Files, these may be what ever you like, how ever here are our suggested ones. 
[Download Audio Files](https://ganderoceanic.ca/ACARS_AUDIO.zip)
> NOTE THIS LINK WILL BE PROVIDED BY MUFASSIL

You will also need an "Uplink" file which specifies what messages you can send and what pilots can respond with. **This File is NOT optional for Gander CPDLC**
[Download Uplink Files](https://ganderoceanic.ca/NAT_Plus_Uplink.zip)

Once you have these files downloaded let's place them in the right location. 

Copy both the Audio files to (defualt location) `C:\Program Files (x86)\Hoppie\ACARS-ATC\lib` If you did choose to use ours. If you chose to use your own, 
> [!IMPORTANT]
> the names aren't important, and you may leave them in any folder on your machine.

For the Uplink file. Place it in (deualt location) `C:\Program Files (x86)\Hoppie\ACARS-ATC\uplink` This MAY be empty be defualt.

### Finally, it's time to open the software

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

### Planes online
planes online gives you a list of aircraft which have logged onto CPDLC. You may start a CPDLC uplink to an callsign by left clicking on them. If for some reason you need to manually log an aircraft on, you may add their callsign in the box down the bottom.
> [!NOTE]
> It is common for planes to not respond with a "logoff" statment when you log them off, so they will remain in the list. At the time of writing there is no known way to remove said aircraft.

If a callsign turns yellow it means the recipient is no longer on the HOPPIES ACARS network. You may disregard this callsign.

### TELEX

Where all your sent and recived telex's can be found.

You may click any downlink and reply either with CPDLC or telex. 

CPDLC can be sent by clicking CPDLC once the callsign has been entered into the `To:` box. (you may enter a new one by typing it in.)

Telex can be sent in a similar, with the callsign in the `To:` box, write the telex content in the box bellow, and click send.

All previously sent TELEXs will sit in `TELEX Uplinks`

### Current Msgs

Shockingly, Current messages provide you with a view of all your current messages. There are 4 different colours found in the current messages window.

#### Green, interactable text. 
(left click to open a menu) options are as follows;

-   `STANDBY` (sends this plain text, Will leave the message green for you to interact with again when you get a chance.)
-   `ACCEPT LOGON` (this option only appears when you're interacting with a CPDLC logon request. This will add the callsign to your planes online window and log their aircraft onto your CPDLC.)
-   `Editor...` (opens the CPDLC editor so you may respond. This message will remain green untill a reponse is sent.)
-   `REQEST DEFFERED` (sends the plain text. Provides no explination, ideally you'll clarify with voice.)
-   `UNABLE` (sends plain text. Provides no explination.)
-   `UNABLE DUE TRAFFIC` (sends plain text.)
-   `UNABLE DUE AIRSPACE` (sends plain text.)

#### Cream, intereacted messages.

This message *MAY* have been a blue message. If it was it will now be accompanied with a Blue message or a second cream message.
You have no further need to see cream messages and may delete/remove them by right clicking.

#### Blue, Uplink Message

A blue message is one YOU sent, this will be awaiting a reply... Once it has turned Creame it may be removed. DO NOT delete a blue message before hand. (unless control sesion over)

#### Black, A reply
Simply, a Black message is a reply to your message. usually consisting of "WILCO, ROGER, UNABLE" etc.

#### Sumary
Green, left click to reply.

Blue, DO NOT REMOVE
 
Cream and Black. Complete messages, remove with right click.   
 
# Further reading
[Hoppie's ATC client information](https://www.hoppie.nl/acars/prg/atc/)  
[Message log](https://www.hoppie.nl/acars/system/log.html)  
[Stations online](https://www.hoppie.nl/acars/system/online.html)
