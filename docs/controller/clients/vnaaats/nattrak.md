# natTrak and RCL reminders

Pilots request their oceanic clearance on natTrak. The FDD shows the requests in two boxes under the controls bar:

- **PENDING:** callsign, NAT, entry fix, level, Mach and ETA. A new request flashes and plays a sound. Click the row to open natTrak on that track's pending list.
- **CLEARED:** clearances already issued, with the time. Clicking one selects that flight.

At the top of the CLEARED box, **Visual** turns the flashing on or off, **Audio** turns the sound on or off, and **Tone** cycles through Ping, Chime and Beep. Browsers only play sound after you have clicked somewhere on the page.

For how to issue a clearance on natTrak, see the [natTrak pages](/controller/nattrak/issuing-clx/).

## The automatic RCL REQ reminder

Pilots must request clearance on natTrak at least 30 minutes before the entry point. After that, they must use voice. vNAAATS can send the reminder for you, and it is switched on by default.

A flight is sent the reminder when all of these are true:

- Its oceanic entry estimate is between 30 and 90 minutes away. If it has no times, it is within 200 nm of a fix on its route and more than 30 minutes of flying from it.
- It is online and moving, has no natTrak request, and is not tracked by an oceanic controller.
- It has not been reminded already, by hand or automatically.

It never reminds a flight that is already inside, or through, the oceanic area (between 53W and 15W).

The server waits 5 minutes after an oceanic controller comes online before sending anything. Flights that are already in, or within 30 minutes of, the oceanic area at that moment are marked as handled and are never reminded.

### Who sends it

The message is typed into EuroScope by one oceanic controller who is online with the plugin and `autotype=1` (the first one alphabetically, if there are several). By default it asks first. A box appears on that controller's FDD listing each callsign with its estimated time and fix:

- **Send now:** sends them one at a time. Do not switch windows until they finish. The plugin stops if you switch away from EuroScope.
- **Later:** asks again in 5 minutes.
- **Skip:** does not send them.

Each strip gets the red `*` when its message has gone. If a send fails it tries again after 5 minutes, up to three times. The ask-first behaviour and the on/off switch are in the Auto RCL settings.

### Sending it by hand

Open the aircraft menu and choose **RCL REQ**:

- **Send** types the message into EuroScope for you.
- **Copy** copies it, so you can paste it into EuroScope yourself.
- **I have sent it - mark with red \*** puts the red `*` on the strip and radar tag. **Remove mark** clears it.

After you send **Contact me**, the callsign cell turns yellow. If 20 minutes later nobody is tracking the flight and it is still in oceanic airspace, it turns red.
