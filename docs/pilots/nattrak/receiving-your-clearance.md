# Receiving your clearance
> Follow these instructions after reviewing and completing the [Requesting Oceanic Clearance](/nattrak/requesting-oceanic-clearance) page.


## Message history page
After requesting oceanic clearance, you will be presented with the **Message History** page. This shows your requests and replies to them from ATC.

![natTrak Oceanic Clearance Message](/pilots/img/nattrakmessagept1.png)

You can see the oceanic clearance request as done on the last page. It is presented in the datalink format similar to CPDLC. 

* `NEBIN/1837` refers to an entry waypoint of `NEBIN`, with an estimate time of reaching at 1837 Zulu. 
* `Track E` is the track you requested, replaced with the random routeing if you requested that instead. 
* `F340 M083` refers to your requested flight level and mach speed. 
* `MAX F350` is the maximum flight level you specified.


## Receiving an oceanic clearance
As soon as you request is submitted, you will recieve an Automatic Acknowledgement of your Oceanic Clearance. This advises you to expect to enter the Ocean per your Clearance Request.
![natTrak Auto Ack Message](/pilots/img/nattrakmessagept2.png)

> Note: A Controller may make an ammendment to your clearance, so it is vital that you ensure to check the natTrak Website in order to ensure no changes are made.

### Get notified if a clearance amendment is made
When you go onto the page for the first time, your browser should ask if you wish to receive notifications from nattrak.vatsim.net. If you allow it, you should be notified via a browser push notification when your clearance is available providing you leave the page open in the background.

![natTrak Oceanic Clearance Message](/pilots/img/nattrakmessagenotify.png)

The ammendement ```(called a reclearance)``` will appear as follows:

![natTrak Oceanic ReClearance](/pilots/img/nattrakmessagept3.png)

You can see both a datalink and voice clearance format. 

The datalink format is as follows:

* `CLX 1739 030125 NAT CLRNCE` Oceanic clearance at 1735Z, date 03/01/25, from NAT (bandbox EGGX/CZQO) oceanic controller.
* `KLM621 CLRD TO KATL VIA NEBIN` You're cleared to KATL via NEBIN, your entry waypoint.
* `NAT E` your NAT track/random routeing.
* `NEBIN 54/20 55/30 55/40 53/50 PELTU` The track routeing.
* `FM NEBIN/1837 MNTN F350 M085` From PIKIL (estimating arrival at 10:33Z), maintain FL350, mach .83.

> **NOTE:** Changes from your initial request will appear with a ```/``` infront of them. Examples can be found in the above image. A reclearance will always appear with one change, so make sure to take note of what the new restriction is.

The voice format below that represents the usual voice formats as per [Getting Your Clearance](/atc/clearances).


## Acknowleding your clearance and reverting to voice

There is no requirement to acknowledge oceanic clearances on natTrak, unlike on voice.

If needed, ATC may reject your oceanic clearance request via natTrak and contact you asking to request via voice. Some controllers will utilise the 'revert to voice' feature on natTrak, which sends a message to you on natTrak. Others will send a message via your pilot client.


## Need more help?

Feel free to ask any questions you may have in the [Gander Oceanic Discord](/additional-resources/myczqo/#discord-server)