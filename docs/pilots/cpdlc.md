# Hoppie's Usage (CPDLC)

CPDLC (Controller-Pilot Data Link Communications) lets you exchange text messages with the oceanic controller instead of talking on the radio. On VATSIM it runs through the Hoppie ACARS network. In the real world it is the primary way of communicating with oceanic ATC, with voice as the alternative.

> [!IMPORTANT]
> CPDLC does **not** replace the first voice contact. Check in with Oceanic ATC by voice first, including a SELCAL check, and log on to CPDLC afterwards. Controllers expect voice contact before they accept a logon.

## What you need

1. A Hoppie ACARS account. [Register here](https://hoppie.nl/acars/system/register.html). Your logon code is emailed to you.
2. An aircraft or pilot client that supports CPDLC over Hoppie ACARS. Enter your logon code in its ACARS settings.
3. A SELCAL code and the usual voice setup (see [SELCAL](/pilots/atc/selcal/) and [Using HF Radio](/pilots/atc/hf-radio/)).

## Logon codes

Log on to the station that matches the controller you are talking to:

| Controller | Logon code |
| :--------- | :--------- |
| NAT_FSS (NAT Bandbox) | `NATX` |
| CZQO_CTR (Gander) | `CZQX` |
| EGGX_CTR (Shanwick) | `EGGX` |

## Step by step

1. **Check in by voice.** Call the oceanic controller before you enter their airspace and ask for a SELCAL check. Say that you are CPDLC capable.
2. **Log on.** Real-world guidance asks for logon 10-25 minutes before oceanic entry. Send your logon request to the code above. The controller will accept it, and your logon will then show as active.
3. **Use CPDLC as normal.** Level, speed and route instructions will arrive as uplinks. Answer them with `WILCO`, `UNABLE` or `ROGER` as the message requires.
4. **Keep your HF or SELCAL watch.** CPDLC does not remove the need to listen out for the controller. If something does not make sense, or you stop receiving messages, call on the radio.
5. **Leaving the oceanic area.** The controller will send a message telling you to contact the next station or to monitor unicom, and will then end your CPDLC service. Answer the message before you change frequency.

## Requesting your oceanic clearance (RCL) by CPDLC or TELEX

If the controller allows it, you can send your Request for Clearance (RCL) by data link instead of by voice. Use your aircraft's oceanic clearance request page (the ATC clearance request page in the CPDLC or ACARS menu), or send it as a TELEX.

> [!IMPORTANT]
> Only do this if the controller's **details field** (their VATSIM controller information) says **"Oceanic Clearance via CPDLC available"** or **"via nattrak.vatsim.net"**. If it says neither, request your clearance by voice.

Send the same information as a voice request:

- Destination
- Oceanic entry point and the estimate for it
- Requested NAT track, or your full random route
- Requested Mach
- Requested level, and the highest level you can accept

See [Getting your clearance](/pilots/atc/clearances/) for what each item means.

## If CPDLC stops working

If the connection fails after a successful logon, go back to voice and tell the radio station. This is what NAT Doc 007 asks for, and it applies on VATSIM too.

## Notes

- Controllers may send free-text messages (an AFK approval, for example). Reply with whichever response option is offered.
- Aircraft with working ADS-B or ADS-C do not need to give voice position reports. See [Position reports](/pilots/atc/pos-reps/).
