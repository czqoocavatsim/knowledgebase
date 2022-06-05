# Requesting oceanic clearance

natTrak allows you to request oceanic clearance when you are an active pilot on VATSIM and there is an oceanic controller online to receive your request.

As with all [oceanic clearances](/atc/clearances), be sure to submit your request at least 30 minutes prior to entry. If you submit it via natTrak less than 15 minutes prior to entry, it will be automatically rejected and you will need to revert to voice operations.

## Accessing the oceanic clearance request page

After you have logged in with your VATSIM account and providing you are an active pilot, you will see this dropdown menu on the home page. Here you can start to request clearance and also see a history of recent messages. 

![screenshot_2022-03-27_162104.png](/assets/nattrak/screenshot_2022-03-27_162104.png)

Click **Request Oceanic Clearance**. You will be presented with a reminder regarding timing and the like. Click through via the big blue button saying **Request Clearance.**

## Filling out the form

You should see a form asking for your flight details. 

### Section 1 - Callsign, destination, level, speed

The first section of the form asks for your callsign, destination, requested flight level, maximum flight level, and requested mach speed.

![screenshot_2022-03-27_162409.png](/assets/nattrak/screenshot_2022-03-27_162409.png)
![screenshot_2022-03-27_163713.png](/assets/nattrak/screenshot_2022-03-27_163713.png){ align=right }

* **Callsign:** Your callsign as per your VATSIM connection. For Cross the Pond, this should be the callsign you booked with unless you had to change it. natTrak will attempt to detect this for you.
* **Destination ICAO:** The ICAO code of your final destination airport, EGLL for example. natTrak will attempt to detect this for you.
* **Requested flight level:** The flight level you wish to fly during your crossing. For Cross the Pond, *this must be the flight level that was allocated to you in your booking details.* Type this as three digits, for example FL420 will be 420.
* **Maximum flight level:** The highest possible flight level you can fly at the beginning of your oceanic crossing. This is generally given to you in your aircraft's VNAV FMC page. *Example on right side of page (courtesy [Flight Simulation Association CTP Pilot Briefing Webinar, March 27 2022](https://www.youtube.com/watch?v=FtcDkTwK2y4)).*
* **Requested mach number:** The mach number you are requesting to fly during your crossing. Type this as three digits beginning with 0. For example, mach .81 will be 081. 

### Section 2 - Routeing

![screenshot_2022-03-27_162838.png](/assets/nattrak/screenshot_2022-03-27_162838.png)

Here you can specify whether you are requesting a NAT Track, or a random routeing. 

The tracks dropdown will display the current active NAT tracks available. Select the one you are requesting. Leave the random routeing box blank.

If you are flying a random routeing, paste it into the second box. Select `None` on the tracks dropdown.

### Section 3 - Oceanic entry

Here you enter the oceanic entry point (typically the first waypoint on your track/random routeing) and your calculated estimate of arriving at that waypoint. It is critical that you use real world time for the estimate.

![screenshot_2022-03-27_163223.png](/assets/nattrak/screenshot_2022-03-27_163223.png)
![screenshot_2022-03-27_163707.png](/assets/nattrak/screenshot_2022-03-27_163707.png){ align=right }
For example, if you are flying track A routeing by `PIKIL 56/20 57/30 57/40 55/50 LOMSI`, your entry fix will be `PIKIL`. Your estimate for arriving at `PIKIL` can be found in your FMS providing your simulator is set to real time. An example on an Airbus MCDU is provided on the right (courtesy [Flight Simulation Association CTP Pilot Briefing Webinar, March 27 2022](https://www.youtube.com/watch?v=FtcDkTwK2y4)).

### Section 4 - TMI, free text

Enter the current TMI (see [NAT Tracks](/basics/nats) for details). For Cross the Pond this may be different from the current real world one - check the menu bar on the top of the page for the current one.

You can also enter free text if you wish. Use this for extra details or the like. 


**You can now submit the form using the blue button. If there are errors in your input, you will be redirected back to the form and shown what to fix.**

## What now?

You should be presented with your message history page with your request details. Continue reading on [this page](/nattrak/receiving-clearance) for more details!

## Need more help?

Feel free to ask in the Gander Oceanic or CTP Discord!