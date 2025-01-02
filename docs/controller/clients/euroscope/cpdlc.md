# Topsky CPDLC
## Prerequisites
1. For the use of CPDLC on the network, one requires a Hoppies acars account. [Registration](https://hoppie.nl/acars/system/register.html)

2. TOPSKY plugin for euroscope OR standalone CPDLC client for VATSYS (further info bellow)

## TOPSKY plugin setup
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
 
# Further reading
[Hoppie's ATC client information](https://www.hoppie.nl/acars/prg/atc/)  
[Message log](https://www.hoppie.nl/acars/system/log.html)  
[Stations online](https://www.hoppie.nl/acars/system/online.html)
