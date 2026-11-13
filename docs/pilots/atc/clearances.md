
<!--
title: Oceanic Clearances
description: Another clearance? We explain why.
published: true
date: 2021-07-31T10:54:55.084Z
tags: 
editor: undefined
dateCreated: 2020-09-11T03:45:45.724Z
-->

<h1>Oceanic Clearances</h1>

## Introduction to Oceanic Clearances

<p>An Oceanic Clearance is similar to the typical clearance you get at your departure airport from the clearance delivery controller, except, instead of receiving a clearance to your destination, you get cleared across the Atlantic Ocean. An Oceanic Clearance is normally issued to an aircraft at least 30 minutes before they enter the Oceanic Control Area.</p>
<p>An Oceanic Clearance contains three key elements:</p>
<ul>
  <li>Route, usually the NAT / Routing across the North Atlantic</li>
  <li>Speed, your cruise speed in MACH (not IAS)</li>
  <li>Level, your cruise altitude as a Flight Level</li>
</ul>
<p>These elements serve to provide the three basic elements of separation: lateral, longitudinal, and vertical as early as possible since the controllers are controlling procedural airspace without any radar coverage.</p>

<h3>How this differs from the real world</h3>
<p>In the real world, crews first send a <strong>Request for Clearance (RCL)</strong> to the oceanic centre. The RCL gives the entry point, the estimate, the Mach number, the requested level and the highest acceptable level (&quot;MAX FL&quot;). It is <strong>not a clearance</strong>. NAT Doc 007 asks for it 90-60 minutes before entry for Gander and 90-30 minutes before entry for Shanwick, and by voice if the entry estimate is less than 30 minutes away. Any change to route, level or speed is then issued by the controller. Whether a separate oceanic clearance follows depends on the centre, and Shanwick still issues one.</p>
<p>On VATSIM we simplify this. You make one request that combines the RCL and the clearance, and it should be made <strong>at least 30 minutes before</strong> the oceanic entry point, as described below. If a controller asks you to do it differently, follow the controller.</p>
<p>You can now also send your RCL by data link, using your aircraft's oceanic clearance request page or a TELEX (see <a href="/pilots/cpdlc/">Hoppie's Usage</a>), or on <a href="https://nattrak.vatsim.net">nattrak.vatsim.net</a>. This only applies if the controller's details field says <strong>"Oceanic Clearance via CPDLC available"</strong> or <strong>"via nattrak.vatsim.net"</strong>. If it does not, use voice.</p>

## Further Information

<p>Oceanic Clearances are required for all flights within the Oceanic Controlled Airspace at or above FL55 (5500 ft). To assist the Oceanic Controllers in planning clearances efficiently and using airspace optimally, pilots requesting an oceanic clearance should notify the clearance controller of their highest possible altitude whenever possible at the oceanic boundary. Considering that the climb to the assigned oceanic flight level must be achieved before entering the oceanic airspace, this should generally be done while the aircraft is within radar controlled airspace such as Shannon or Moncton/Gander.</p>
<p>In some airports close to the oceanic boundary such as Gander, Halifax, Moncton, Dublin &amp; Shannon it may be necessary for a pilot to obtain their Oceanic Clearance on the ground. This is usually done to save time so that the pilot can fly straight to the boundary without the need to contact the clearance controller. However, pilots must make sure that they are already at their assigned parameters by the time they reach the oceanic boundary.</p>
<p>After pilots obtain and read back their oceanic clearance, pilots should monitor their FIX estimate for oceanic entry. If a change of 3 minutes or more is observed, the pilot must pass the revised estimate to ATC. This is done to recalculate your position in relation to other aircraft so that there is no conflict when entering the oceanic airspace.</p>
<p>If a pilot has not received their Oceanic Clearance before entering the Oceanic Airspace, they must contact domestic ATC and request instructions to remain clear of the Oceanic Airspace until they receive their clearance. Aircraft must avoid entering Oceanic Airspace if a controller is online unless they have received their clearance. If in doubt, pilots should ask the Oceanic controller when they can expect their clearance.</p>
<p>Each aircraft will be cleared to a specific flight level and Mach number. If a pilot cannot accept a certain level or Mach number they must report it to ATC and provide their available options so that ATC can best accommodate.</p>

## Workflow from start to finish

<p>The following section will explain each element of the clearance exchange.&nbsp;</p>
<p>A pilot should call up the Oceanic Controller first to establish initial contact and to make the controller aware that the pilot is looking to request their oceanic clearance.&nbsp;</p>
<blockquote>
  <p><strong>BAW123: </strong>Gander Radio, BAW123, request oceanic clearance.</p>
  <p><strong>CZQO_CTR</strong>: BAW123, Gander Radio, pass your message</p>
</blockquote>
<p>Once the Oceanic Controller has given the “pass your message” or “go ahead” instruction, BAW123 may now request their oceanic clearance. In the request, the following must be included:</p>
<ul>
  <li>Destination airport</li>
  <li>Requested NAT Track</li>
  <li>Estimate for the NAT / Oceanic Airspace entry in ZULU time</li>
  <li>Requested Mach number</li>
  <li>Requested flight level, and the maximum (highest) flight level you can accept at the entry point (the real-world oceanic clearance request calls this &quot;MAX FL&quot;)</li>
</ul>
<p>With all their information collated, BAW123 may now go ahead and request their oceanic clearance:</p>
<blockquote>
  <p><strong>BAW123: </strong>Gander Radio, BAW123 request Oceanic Clearance to London Heathrow via Track Yankee. Estimating ALLRY at 1240 zulu. Requesting Flight Level 350, able Flight Level 370. Mach .80</p>
</blockquote>
<p>The controller will acknowledge the pilot's request and will tell BAW123 to standby.&nbsp;</p>
<p>When the controller is ready, the clearance is issued:</p>
<blockquote>
  <p><strong>CZQO_CTR</strong>: Gander Oceanic clears BAW123 London Heathrow via ALLRY, track Yankee. From ALLRY maintain Flight Level 350, Mach .80</p>
</blockquote>
<p>BAW123 must, in the readback of their clearance, confirm that their version of the NAT track message is up-to-date by including the TMI (see <a href="/pilots/basics/nats/">North Atlantic Tracks</a>):</p>
<blockquote>
  <p><strong>BAW123: </strong>BAW123 is cleared to London Heathrow, via NAT track Yankee, TMI 115. From ALLRY maintain Flight Level 350, Mach .80</p>
</blockquote>
<p>When BAW123 has made a correct readback, the controller will confirm that the readback was correct and will instruct the pilot to “return to domestic frequency” or to “return to previous frequency”.&nbsp;</p>
<blockquote>
  <p><strong>CZQO_CTR: </strong>BAW123, read-back correct, return to previous frequency.</p>
</blockquote>
<p>For aircraft requesting random routings through Shanwick/Gander OCAthe whole random routing must be included in the request, including all coordinates and the entry/exit fixes. Pilots are additionally required to read back the full route issued by the controller. ‘Cleared as filed’ is not an available phrase.</p>
<p>Below are some more possible examples.</p>

## More Oceanic Clearance Examples

### Clearance flying via a NAT track
<blockquote>
  <p><strong>ACA865:</strong> Shanwick Radio, ACA865 request oceanic clearance.</p>
  <p><strong>EGGX_CTR: </strong>ACA865, Shanwick Radio, pass your message</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 request clearance via Track Bravo. Estimating PIKIL at 1131. Request Mach .80, Flight Level 350, able Flight Level 360.</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>Shanwick Oceanic clears ACA865 to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 350, Mach .80</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 is cleared to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 350, Mach .80</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>ACA865, read-back correct</p>
</blockquote>
<p>(<strong>Note:</strong> coordinates shall be spoken as "five four north, zero two zero west". Times shall be spoken as "one one three one", and not "eleven thirty-one")</p>

### Clearance flying via Random Routing
<p>Sometimes you may be flying on a "random route" instead of a NAT tracks. It's more or less the same as above, except that you need to read the full route instead of "Track A".</p>
<blockquote>
  <p><strong>ACA865:</strong> Shanwick Radio, ACA865 request oceanic clearance.</p>
  <p><strong>EGGX_CTR: </strong>ACA865, Shanwick Radio, pass your message</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 request oceanic clearance via MALOT 54N020W 56N030W 57N040W 56N050W JANJO. Estimating MALOT at 1131. Request Mach .80, Flight Level 350, able Flight Level 360</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>Shanwick Oceanic clears ACA865 to Toronto via MALOT 54N020W 56N030W 57N040W 56N050W JANJO, from MALOT maintain Flight Level 350, Mach .80</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 is cleared to Toronto via MALOT 54N020W 56N030W 57N040W 56N050W JANJO, from MALOT maintain Flight Level 350, Mach .80</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>ACA865, read-back correct</p>
</blockquote>
<p>(<strong>Note:</strong> coordinates are spoken in the same way as above, "five four north, zero two zero west", and times digit by digit, "one one three one", not "eleven thirty-one")</p>
<p><strong>Note: a full read-back of the clearance is always required.</strong></p>

### Clearance issued with an amendment
<p>Sometimes it is not possible for a controller to issue the requested clearance. There are four main types of amendments: reroute, level change, speed change and entry point change.</p>
<blockquote>
  <p><strong>ACA865:</strong> Shanwick Radio, ACA865 request oceanic clearance.</p>
  <p><strong>EGGX_CTR: </strong>ACA865, Shanwick Radio, pass your message</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 request clearance via Track Bravo. Estimating PIKIL at 1131. Request Mach .80, Flight Level 350, able Flight Level 360</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>ACA865, Oceanic Clearance with a <strong>level change</strong>, Shanwick Oceanic clears ACA865 to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 330, Mach .80. Unable requested level.</p>
  <p><strong>ACA865:</strong>&nbsp;ACA865 is cleared to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 330, Mach .80</p>
  <p><strong>EGGX_CTR:&nbsp;</strong>ACA865, read-back correct</p>
</blockquote>
<p>A controller may sometimes include multiple amendments in the same clearance:</p>
<blockquote>
  <p><strong>EGGX_CTR:&nbsp;</strong>ACA865, Oceanic Clearance with a <strong>level change and speed change</strong>, Shanwick Oceanic clears ACA865 to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 330, Mach .81. Unable requested level, unable requested speed.</p>
</blockquote>
<p>A controller may also, on occasion, request a pilot to cross a point at/before/after a certain time:</p>
<blockquote>
  <p><strong>EGGX_CTR:&nbsp;</strong>Shanwick Oceanic clears ACA865 to Toronto via PIKIL, track Bravo, from PIKIL maintain Flight Level 330, Mach .81. Cross PIKIL at or after time 1135.</p>
</blockquote>

## Sources
<p>NAT Document 007<br>Oceanic Control Document - Version 1.0</p>

## After you enter oceanic airspace

<h3>Squawk 2000</h3>
<p>Unless ATC tells you otherwise, keep the last transponder code you were assigned for <strong>10 minutes after passing the oceanic entry point</strong>, then squawk <strong>2000</strong>. Changing to 2000 matters because your original domestic code may not be recognised by the next domestic radar service when you leave oceanic airspace. Reykjavik is the exception, because it provides a radar service in part of its area. The same applies within the radar area around Bermuda. In both cases, keep your assigned code until ATC tells you to change it.</p>
