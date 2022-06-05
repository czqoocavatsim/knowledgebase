# Receiving your clearance

> **Follow these instructions after completing [Requesting Oceanic Clearance](/nattrak/requesting-oceanic-clearance)**

## Message history page

After requesting oceanic clearance, you will be presented with the **Message History** page. This shows your requests and replies to them from ATC.

![screenshot_2022-03-27_165147.png](/assets/nattrak/screenshot_2022-03-27_165147.png)

You can see the oceanic clearance request as done on the last page. It is presented in the datalink format similar to CPDLC. 

* `PIKIL/1033` refers to an entry waypoint of `PIKIL`, with an estimate time of reaching of 10:33 zulu. 
* `Track A` is the track you requested, replaced with the random routeing if you requested that instead. 
* `F350 M083` refers to your requested flight level and mach speed. 
* `MAX F390` is the maximum flight level you specified.

## Receiving an oceanic clearance

Your oceanic clearance when issued will be automatically presented on the page when it is issued. 

> **Get notified when it arrives**
> ![screenshot_2022-03-27_165453.png](/assets/nattrak/screenshot_2022-03-27_165453.png)
> When you go onto the page for the first time, your browser should ask if you wish to receive notifications from nattrak.vatsim.net (screenshot is in development environment). If you allow it, you should be notified via a browser push notification when your clearance is available providing you leave the page open in the background.
{.is-info}

The clearance will appear as so:

![screenshot_2022-03-27_165918.png](/assets/nattrak/screenshot_2022-03-27_165918.png)

You can see both a datalink and voice clearance format. 

The datalink format is as follows:

* `CLX 0629 270322 NAT CLRNCE 15` Oceanic clearance at 06:29Z, date 27/03/22, from NAT (bandbox EGGX/CZQO) oceanic controller, number 15 in sequence of the day.
* `BAW14LA CLRD TO KJFK VIA PIKIL` You're cleared to KJFK via PIKIL, your entry waypoint.
* `NAT A` your NAT track/random routeing.
* `PIKIL 56/20 57/30 57/40 55/50 LOMSI` The track routeing.
* `FM PIKIL/1033 MNTN F350 M083` From PIKIL (estimating arrival at 10:33Z), maintain FL350, mach .83.

The voice format below that represents the usual voice formats as per [Getting Your Clearance](/atc/clearances).

## Restrictions and changes

Sometimes ATC may issue a restriction on your clearance or change an element of it for traffic or separation reasons. For example:

![screenshot_2022-03-27_170459.png](/assets/nattrak/screenshot_2022-03-27_170459.png)

In this scenario, Santa Maria (LPPO) has issued you a clearance but with several changes/restrictions. Of course usually there wouldn't be so many!

* `/ATC CROSS PIKIL NOT BEFORE 1035` ATC needs you to cross PIKIL not before 10:35z. You could adjust your mach speed or request instructions from your current domestic sector to achieve this. 
* `/ATC MACH CHANGED` or `/ATC FLIGHT LEVEL CHANGED` ATC has changed your crossing mach speed and/or flight level. Check the `FM PIKIL/1033 MNTN F340 M082` line above - it will contain your new flight level and/or mach number.
* `/ATC ** RECLEARANCE 0634 **` This represents ATC reissuing your clearance if they had already previously issued another one. 

## Acknowleding your clearance and reverting to voice

There is no requirement to acknowledge oceanic clearances on natTrak, unlike on voice.

If needed, ATC may reject your oceanic clearance request via natTrak and contact you asking to request via voice. Expect a private message via your pilot client.

## I haven't got my clearance in 15 or more minutes?!

Talk to your domestic controller if they're online, otherwise contact the oceanic controller. They may have missed your message. 

## Need more help?

Feel free to ask in the Gander Oceanic or CTP Discord!