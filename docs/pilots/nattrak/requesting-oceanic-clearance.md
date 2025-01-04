# Requesting Oceanic Clearance
natTrak allows you to request oceanic clearance when you are an active pilot on VATSIM.

As with all [oceanic clearances](/pilots/atc/clearances), be sure to submit your request at least 30 minutes prior to entry. If you submit it via natTrak **less than 15 minutes prior to entry**, it will not be possible to request clearance via the website and you will need to do so via voice.

## Notes Flying Oceanic
There are a few different things to take into account when flying Oceanic airspace:

* Oceanic Controllers have ADS-B (Satalite Radar) capabilities, but they can not vector you. So you need to fly your route as cleared.
* Your Simulator Time must be set to the correct time. You need this in order to correctly provide your entry time into the OCA.

## Accessing the oceanic clearance request page
Log onto the [natTrak Website](https://nattrak.vatsim.net/) with your VATSIM Account. When logged on as a pilot on VATSIM, you will see a Navigation Bar with options to Request Clearance, as well as viewing a history of clearance message.

<figure class="image image-style-align-right image_resized" style="width:70%">
<img src="/pilots/img/nattraknavbar.png">
</figure>

## Filling out the form

You should see a form asking for your flight details. 

### Section 1 - Callsign, destination, level, speed

The first section of the form asks for your callsign, destination, requested flight level, maximum flight level, and requested mach speed.

<figure class="image image-style-align-right image_resized" style="width:100%">
<img src="/pilots/img/nattrakclrpt1.png">
</figure>


<div style="display: flex; align-items: flex-start;">
    <div style="flex: 1;">
        <ul>
            <li><strong>Callsign:</strong> Your callsign as per your VATSIM connection. natTrak will attempt to detect this for you.</li>
            <li><strong>Destination ICAO:</strong> The ICAO code of your final destination airport, EGLL for example. natTrak will attempt to detect this for you.</li>
            <li><strong>Requested flight level:</strong> The flight level you wish to fly during your crossing. For Cross the Pond, <em>this must be the flight level that was allocated to you in your booking details.</em> Type this as three digits, for example FL420 will be 420.</li>
            <li><strong>Maximum flight level:</strong> The highest possible flight level you can fly at the beginning of your oceanic crossing. This is generally given to you in your aircraft's VNAV FMC page.</li>
            <li><strong>Requested mach number:</strong> The mach number you are requesting to fly during your crossing. Type this as three digits beginning with 0. For example, mach .81 will be 081.</li>
        </ul>
    </div>
    <figure class="image image-style-align-right image_resized" style="flex: 0 0 35%; margin-left: 20px;">

        <small>LNAV Page in PMDG 777</small>
        <img src="/pilots/img/b77wcrz.png" alt="Maximum flight level example">
        
    </figure>
</div>


### Section 2 - Routeing

<figure class="image image-style-align-right image_resized" style="width:100%">
<img src="/pilots/img/nattrakclrpt2.png">
</figure>

Here you can specify whether you are requesting a NAT Track, or a random routeing. 

The tracks dropdown will display the current active NAT tracks available. Select the one you are requesting. Leave the random routeing box blank. If you are flying a random routeing, paste it into the second box. Select `None` on the tracks dropdown.

### Section 3 - Oceanic entry

Here you enter the oceanic entry point (typically the first waypoint on your track/random routeing) and your calculated estimate of arriving at that waypoint. It is critical that you use real world time for the estimate.

![nattrakclrpt3](/pilots/img/nattrakclrpt3.png)

<div style="display: flex; align-items: flex-start;">
    <div style="flex: 1;">
        <ul>
            <li>For example, if you are flying track A routeing by `NEBIN 54/20 55/30 55/40 53/50 PELTU`, your entry fix will be `NEBIN`. Your estimate for arriving at `NEBIN` can be found in your FMS.</li>
        </ul>
    </div>
    <figure class="image image-style-align-right image_resized" style="flex: 0 0 35%; margin-left: 20px;">

        <small>RTE Page in PMDG 777</small>
        <img src="/pilots/img/b77wrte.png" alt="Maximum flight level example">
        
    </figure>
</div>


### Section 4 - TMI, free text

<figure class="image image-style-align-right image_resized" style="width:100%">
<img src="/pilots/img/nattrakclrpt4.png">
</figure>

Enter the current TMI (see [NAT Tracks](/basics/nats) for details). For Cross the Pond this may be different from the current real world one - check the menu bar on the top of the page for the current one.

You can also enter free text if you wish. Use this for extra details or the like. 

**You can now submit the form using the blue button. If there are errors in your input, you will be redirected back to the form and shown what to fix.**

## What now?

You should be presented with your message history page with your request details. Continue reading on [this page](/pilots/nattrak/receiving-clearance) for more details!

## Need more help?

Please join us via the [Gander Oceanic Discord](/additional-resources/myczqo).