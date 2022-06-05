
<!--
title: Procedural Reports
description: Help us know where you are!
published: true
date: 2021-07-31T11:36:18.034Z
tags: 
editor: undefined
dateCreated: 2020-09-11T03:46:30.382Z
-->

# Reporting Your Position
## What is a position report?
<p>Previously, given the lack of radar coverage over the North Atlantic, controllers had to resort to other methods to work out aircraft position. Nowadays, with the widespread surveillance coverage provided by ADS-B and ADS-C surveillance technologies, the 'no-radar' problem has largely been solved in the real world. However, there are still many aircraft - especially on VATSIM that are not equipped with ADS-B or ADS-C equipment. This is where position reports come in.</p>
<p>Many routes over the North Atlantic define designated ‘reporting points’; points at which a pilot must report their position. However, for routes without designated reporting points, then a report must be sent at every significant point, or every ten degrees of longitude, whichever is more often.</p>
<p>If the estimate provided to ATC for the waypoint immediately following the current reporting point has changed by three minutes or more, a revised estimate must be transmitted to the appropriate controller as soon as possible. Pilots must always report to ATC when reaching new flight levels, and optionally when leaving the old flight level.</p>
<h2>Contents of A Position Report</h2>
<p>A position report requires the following information:</p>
<ul>
  <li>Current position and time crossed</li>
  <li>Flight level</li>
  <li>The point directly after the current reporting point and the time estimate</li>
  <li>The point after that, commonly referred to as the ‘next’ point, no time estimate required</li>
</ul>
<p>For flights outside domestic route networks, the position is expressed in terms of latitude and longitude except when flying over named reporting points.&nbsp;<br>Example: "<i>five seven north, zero two zero west" (57N020W, or 5720N, etc.)</i></p>

## Tips &amp; Tricks
<p>Standard air/ground message types and formats are used within the NAT Region</p>
<ul>
  <li>State the message type clearly (i.e. "<i>ACA123, with position"</i>)</li>
  <li>Adhere strictly to the sequence of information for the type of message</li>
  <li>All times should be expressed in hours and minutes UTC, pronouncing each individual digit</li>
  <li>Correct the controller if they read-back your position report incorrectly</li>
</ul>

## Examples
<p><strong>Standard Position Report:</strong></p>
<blockquote>
  <p><strong>SWR100:</strong> Shanwick Radio, Swissair 100 with position report</p>
</blockquote>
<blockquote>
  <p><strong>EGGX_FSS: </strong>Swissair 100, Shanwick Radio, pass your message</p>
</blockquote>
<blockquote>
  <p><strong>SWR100: </strong>Shanwick Radio, Swissair 100 reports passing RESNO at time 1235, Flight Level 330, estimating 56 North 020 West at 1310, 56 North 030 West next</p>
</blockquote>
<blockquote>
  <p><strong>EGGX_FSS: </strong>Swissair 100, Shanwick copies Swissair 100 passed RESNO time 1235, Flight Level 330, estimating 56 North 020 West at time 1310, 56 North 030 West next</p>
</blockquote>
<blockquote>
  <p><strong>SWR100:</strong> Shanwick Radio, Swissair 100, correct.</p>
</blockquote>
<p><strong>Revised Estimate:</strong></p>
<blockquote>
  <p><strong>BAW212:</strong> Shanwick Radio, Speedbird 212 with revised estimate</p>
</blockquote>
<blockquote>
  <p><strong>EGGX_FSS: </strong>Speedbird 212, Shanwick Radio, pass your message</p>
</blockquote>
<blockquote>
  <p><strong>BAW212:</strong> Shanwick Radio, Speedbird 212 estimating 57 North 040 West at 0305</p>
</blockquote>
<blockquote>
  <p><strong>EGGX_FSS: </strong>Speedbird 212, Shanwick Radio copies revision 57 North 040 West at time 0305</p>
</blockquote>
<blockquote>
  <p><strong>BAW212:</strong> Shanwick Radio, Speedbird 212</p>
</blockquote>
<p><i>Note: It is not a requirement to include waypoints after the oceanic exit point in a position report. A simple ‘Domestic next’ will suffice.</i></p>

## Sources
<p>NAT 007 Document</p>
