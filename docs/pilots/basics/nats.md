
<!--
title: NAT Tracks
description: Complex but efficient, here we explain how to decide your route over the ocean.
published: true
date: 2020-10-02T03:52:59.045Z
tags: 
editor: undefined
dateCreated: 2020-09-11T03:38:36.738Z
-->

# North Atlantic Tracks

## The Organised Track System (OTS)
<p>Due to passenger demand, time zone differences and noise restrictions at airports, most air traffic in the North Atlantic contributes to two major alternating traffic flows, a westbound flow in the morning and an eastbound flow at night. As a result of these flows, most traffic is concentrated uni-directionally depending on the time of day. Peak westbound traffic crosses 30W between 1130z and 1900z, whilst peak eastbound traffic crosses 30W between 0100z and 0800z.</p>
<p>On top of these operational characteristics, wind, airline requests and controller separation requirements play essential roles. Aircraft typically need to fly between a narrow level band (between FL310 and FL400) and will attempt to fly with the strongest tailwind (eastbound crossing) or will try to avoid the headwind (westbound crossing). All of these considerations prompt the need for a system of dynamic routes across the North Atlantic. This system is known as the Organised Track System, or OTS for short.</p>
<p>Each day, the OTS is constructed with the cooperation of all relevant OACCs (Oceanic Area Control Centres) to ensure that the best possible routes are chosen for the conditions. The agreed OTS for the day is then forwarded through the ‘NAT track message’. The NAT track message details all of the agreed-upon North Atlantic routings for the flow and messages are typically published twice a day, at 2200z and 1400z.</p>

## The NAT Track Message
<p>Below is an example of a NAT track message, published on the 1st of May detailing the tracks valid for the 2nd of May.</p>
<pre><code class="language-plaintext">011941 EGGXZOZX
(NAT-1/2 TRACKS FLS 310/390 INCLUSIVE
MAY 02/1130Z TO MAY 02/1900Z
PART ONE OF TWO PARTS-
A MALOT 52/20 51/30 49/40 47/50 RONPO COLOR
EAST LVLS NIL
WEST LVLS 310 320 330 340 350 360 370 380 390
EUR RTS WEST NIL
NAR NIL-
B LIMRI 51/20 50/30 48/40 46/50 URTAK BANCS
EAST LVLS NIL
WEST LVLS 310 320 330 340 350 360 370 380 390
EUR RTS WEST NIL
NAR NIL-
C DINIM 50/20 49/30 47/40 45/50 VODOR RAFIN
EAST LVLS NIL
WEST LVLS 310 320 330 340 350 360 370 380 390
EUR RTS WEST NIL
NAR NIL-
D SOMAX 49/20 48/30 46/40 44/50 42/60 DOVEY
EAST LVLS NIL
WEST LVLS 310 320 330 340 350 360 370 380 390
EUR RTS WEST NIL
NAR NIL-

011941 EGGXZOZX
(NAT-2/2 TRACKS FLS 310/390 INCLUSIVE
MAY 02/1130Z TO MAY 02/1900Z
PART TWO OF TWO PARTS-
REMARKS.
1.TMI IS 121 AND OPERATORS ARE REMINDED TO INCLUDE THE
TMI NUMBER AS PART OF THE OCEANIC CLEARANCE READ BACK.
PRMS.
...</code></pre>
<p>Let's unpack what this describes:</p>
<p><strong>011941:</strong> Published on the 1st of the month at 1941Z</p>
<p><strong>EGGXZOZX:</strong> Shanwick</p>
<p><strong>NAT-1/2:</strong> Part 1 of 2 of this NAT track message</p>
<p><strong>MAY 02/1130Z:</strong> Start of track validity</p>
<p><strong>MAY 02/1900Z:</strong> End of track validity</p>
<p><strong>A MALOT 52/20 51/30 49/40 47/50 RONPO COLOR</strong><br>Track A, following the route above from MALOT to COLOR</p>
<p><strong>EAST LVLS NIL</strong><br>Not available travelling eastbound at any level</p>
<p><strong>WEST LVLS 310 320 330 340 350 360 370 380 390</strong><br>Available westbound between FL310-390 (inclusive)</p>
<p><strong>EUR RTS WEST NIL</strong><br>No NERS (North Atlantic European Routing Scheme, an occasional domestic route dictating an exact path into domestic airspace from certain tracks) published today for this track</p>
<p><strong>NAR NIL-</strong><br>No NARs (North American Routings, published routings from the North American airway system to the coastal fixes) specifically published and associated with this track</p>
<p>There are no named waypoints over the North Atlantic aside from the entry/exit points at the border. Instead, ‘coordinate points’ are used, often formatted as 50/30, translating as 50 North, 30 West.</p>
<p>Each message is issued a <strong>TMI </strong>(Track Message Identifier), which is simply the current Julian calendar day (up to 365, assuming non-leap year). In situations where an amendment needs to be made, a letter is appended to the end of the TMI (e.g. 123A), and the message is re-issued. It is important to clarify the TMI in all clearance readbacks, as it is possible to have received an outdated NAT message by mistake.</p>

## It Takes Five to Tango
<p>Five routes exist in the far south-east corner of Shanwick's airspace to connect routes between Shannon's SOTA area and Spain, the Canaries and the Lisbon FIR. These routes do not change daily and are known as the ‘Tango Routes’ or ‘T Routes’ for short.</p>
<p><strong>T9: </strong>provides a north/south route connecting airways routing between the west of the Portuguese Coast to eastbound routings across the north of Spain. T9 connects SOTA to the Madrid FIR between LASNO and BEGAS. This Tango Route is uni-directional and can only be received by southbound flight.</p>
<p><strong>T213</strong>: also connects SOTA to the Madrid FIR routing TAMEL and BERUX, forming more limited connections to the western edge of the Lisboa FIR and several southbound routes through Spain towards Tunisia. This Tango Route is bi-directional.</p>
<p><strong>T16: </strong>connects SOTA to the Canaries, routing OMOKO and GONAN. This Tango Route is uni-directional, and can only be received by southbound flight</p>
<p><strong>T13:</strong> sister to T16, routing OMOKO and NILAV. This Tango Route is uni-directional, and can only be received by northbound flight</p>
<p><strong>T290: </strong>new as of 30th Jan 2020, connecting SOTA to the Madrid FIR, routing GELPO and ADVAT. This Tango Route is uni-directional and can only be received by southbound flight.</p>
<p><i>Note: Expect to hear the waypoints for these routes individually read out in the clearance to reduce the chance of a misunderstanding.</i></p>
<figure class="image image_resized" style="width:28.09%;"><img src="/diagrams/tango_routes.png">
  <figcaption>The Tango (T) Routes</figcaption>
</figure>

## What about Concorde?
<p>Even though the Concorde hasn't been seen in the real-world skies since 2003, pilots looking for a nostalgia kick might want to dust off their Concorde on the network. Therefore, the three legacy Concorde tracks remain available for use today on the network. Unlike regular NAT tracks, these tracks are static and did not change daily because the Concorde's high cruising altitude (between FL550 and FL600) meant that the aircraft flew above most weather systems that impact normal NAT track selection. Let's have a look at these routes.</p>
<p><strong>Track SM (Sierra Mike)</strong> - Westbound Concorde flight<br><strong>Track SN (Sierra November) </strong>- Eastbound Concorde flight<br><strong>Track SO (Sierra Oscar)</strong> - Alternate overflow flight (used only when necessary)</p>
<figure class="image image_resized" style="width:65.49%;"><img src="/img/concorde_routes.png">
  <figcaption>Diagram of the legacy Concorde routes.</figcaption>
</figure>

## Sources
<p>NAT Document 007<br>Oceanic Control Document - Version 1.0</p>
<p>&nbsp;</p>
