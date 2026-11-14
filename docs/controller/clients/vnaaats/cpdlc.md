# CPDLC in vNAAATS

Pilots connect to the vNAAATS CPDLC station, and you talk to them from the CPDLC drawer, opened with the CPDLC button in the controls bar. It uses the Hoppie ACARS network, so you need your own Hoppie logon code. [Register here](https://hoppie.nl/acars/system/register.html).

!!! note
    If you use the Topsky plugin for CPDLC instead, see [Topsky CPDLC](/controller/clients/euroscope/cpdlc/).

## Signing in

1. Open the CPDLC drawer and type your Hoppie logon code. It is kept in the server's memory only while you are signed in, and is never saved.
2. Your position sets the station: `CZQO_` positions use **CZQX**, `EGGX_` positions use **EGGX**, and `NAT_FSS` uses **NATX**. Delivery positions and observers do not use CPDLC.
3. Use **sign out of CPDLC** when you leave. Restarting the server logs everyone out of CPDLC, so sign in again if that happens.

Only one controller can use each station.

### If a station is stuck

If someone left without signing out, use **Force log out a CPDLC callsign...** in the drawer. Type the callsign (for example `CZQX`), read the warnings, then type `LOG OUT`. The station is cleared at once, its aircraft lose their CPDLC connection, and nobody can sign in to that station for 3 minutes. Check with the other controller first.

## Working with pilots

Make voice contact and a SELCAL check before you accept a logon.

- **Connected aircraft** are listed at the top of the drawer. Click one to see the message thread.
- **New logon:** the alert sound plays once, the callsign flashes in the drawer and on the strip, and the button flashes "new logon".
- **New message:** a sound plays, the button shows an envelope with the unread count, and the strip flashes until you open it.
- **Replying:** use the quick buttons (unable, standby, roger), the **reply...** choices to set the response type, or write your own text and press **Send**.
- **Standard messages...** gives you the TopSky message list.

## Handing off

- **Transfer:** when you hand an aircraft that is on CPDLC to another controller, the pilot is sent `CONTACT <station> ON <frequency>` and is logged off when they answer WILCO or ROGER.
- **UNICOM:** asks you to confirm, then sends "THERE IS NO FURTHER ATC AVAILABLE. SERVICE TERMINATED. MONITOR ADVISORY ON 122.800". The pilot is logged off when they answer WILCO or ROGER, and the tag is released in EuroScope.

You need a controller position to send messages.
