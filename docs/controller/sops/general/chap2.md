# Separation Standards
CHAPTER 2
## 2.1 General
> Separation on VATSIM is subject to some simplification. As such, an understanding of the
separation requirements in this document will be sufficient for the purpose of oceanic control
on VATSIM.

Standard vertical or horizontal separation shall be provided between all flights in Class A airspace. At
least one form of procedural separation must be maintained between all flights:<br>
▪ Vertical<br>
▪ Longitudinal<br>
▪ Lateral

Note: “longitudinal” and “lateral” refer to aircraft orientation, not the lines of longitude or
latitude.

The separation standards defined in this document are divided into two categories based on ADS-B
equipage. In order to apply ADS-B based separation minima between two aircraft, both aircraft must
be equipped with ADS-B. This requirement can be referred to with the phrase “suitably equipped
aircraft pairs”.

> ADS-B does not allow controllers to assign headings to aircraft as they would in domestic, radarcontrolled airspace. It merely allows for more accurate monitoring of aircraft position. The only
practical way to intervene in order to prevent a conflict at a late stage is to apply vertical
separation.

> Note: Concorde Separation Rules are defined in Annex B - Concorde Procedures.

## 2.2 Vertical Separation

Vertical separation exists when the vertical distance between aircraft is never less than the
prescribed minimum. The vertical separation minima are:

▪ Between aircraft flying subsonic:<br>
a. Up to FL290 apply 1000ft;<br>
b. Above FL290 apply 2000ft, except that between FL290 and FL410 inclusive, 1000ft
may be applied between RVSM approved aircraft operating in airspace designated
as being notified for the application of this separation standard.

▪ Between aircraft flying supersonic and between aircraft flying supersonic and aircraft flying
subsonic:<br>
a. Up to FL450 apply 2000ft;<br>
b. Above FL450 apply 4000ft.

> On VATSIM, all aircraft with an RFL above FL290 are assumed to be RVSM approved

## 2.2.1 Cruise Climbs and Level Blocks
During cruise climbs and level blocks aircraft are considered to occupy all levels specified in the
clearance, regardless of ADS or verbal level reports. In a cruise climb, aircraft may only climb,
whereas level blocks allow aircraft to climb or descend to any level within the block.

## 2.3 Lateral Separation
Lateral separation is established distance between the routes of two aircraft (note: this is not the
distance between aircraft at any given point, but distance between any 2 points along 2 different
routes).
### 2.3.1 Parallel or Non-Intersecting Tracks
Parallel or non-intersecting **tracks** are deemed separated provided that they are spaced by at least:

| ADS-B Equipped Aircraft Pairs | Other Aircraft Pairs |
| ----------------------------- | -------------------- |
|  19 NM  | 60 NM or 1 degree (subject to gentle slope rules) |

If **tracks** are not deemed laterally separated then either longitudinal or vertical separation must be
ensured
<figure markdown>
![Profile Selction](/controller/img/sops19nmsep.png){ width="550" }
  <figcaption><sup>Figure 2 – 19NM Lateral Separation</sup></figcaption>
</figure>

In Figure 2, aircraft A and B are laterally separated for the first portion of their route (green),
however lateral separation does not exist once aircraft A’s track deviates south. As soon as the first
aircraft reaches the route portion that is no longer laterally separated, separation is lost. Therefore,
another form of separation must be in place and separation ensured <u>before this point is reached by
either aircraft.</u>

### 2.3.1.1 Gentle-Slope Rules

> Gentle slope rules are only relevant if one of the aircraft in the pair is not ADS-B equipped.

Considering coordinates on a flat surface, parallel tracks separated by 1 degree would equate to
60NM. However, as the earth is spherical, the separation between parallel tracks actually falls to
below 60NM. For this reason, the gentle-slope rules ensure separation never falls below 50.5NM.
The gentle slope rules allow lateral separation to be defined in terms of degrees, rather than
nautical miles. At different latitudes, slopes of different gradients may be deemed separated from
each other.

Tracks separated by 1 degree latitude are deemed separated from each other, provided that when
travelling over 10 degrees longitude, the change in latitude of one of the tracks does not exceed:<br>
▪ 3 degrees at or South of 58N<br>
▪ 2 degrees between 58N and 70N<br>
▪ 1 degree at or North of 70N and South of 80N

**Example**
Two aircraft travel on parallel tracks. The table shows different possible parallel tracks travelling
west over the next 10° longitude (from 20W to 30W) – are the aircraft separated?

Aircraft A | Aircraft B | Change in Latitude | Allowable Maximum | Separated?
 --------- | ---------- | ------------------ | ----------------- | ---------
5820N to 5830N | 5920N to 5930N | 0° | 3° | Yes
5820N to 5530N | 5920N to 5630N | 3° | 3° | Yes
5820N to 6130N | 5920N to 6230N | 3° | 2° | **No**
6720N to 6930N | 6820N to 7030N | 2° | 2° | Yes
6820N to 7030N | 6920N to 7130N | 2° | 1° | **No**

## 2.3.2 Lateral Separation of OTS
All co-directional tracks published in a NAT Track Message are laterally separated for ADS-B
equipped aircraft pairs.

Performance Based Communication Surveillance (PBCS) tracks are separated by less than one
degree of latitude (0° 30’ rather than 1° degree). Aircraft that are not ADS-B equipped that are
operating on PBCS tracks are not considered laterally separated from aircraft operating on adjacent
PBCS tracks. It is therefore recommended (but not mandatory on VATSIM) to re-clear non-ADS-B
equipped aircraft via non-PBCS tracks.

As aircraft on VATSIM often fly tracks outside of the published times, conflicts between aircraft on
opposite direction published tracks are possible.

The ‘Concorde Tracks’ are also deemed laterally separated for all aircraft.

## 2.3.3 Strategic Lateral Offset Procedure (SLOP)
The Strategic Lateral Offset Procedure allows pilots to deviate from their route up to 2 NM right of
track at any increment of 0.1 NM, remaining parallel to the centreline. The purpose of the SLOP is to
reduce wake turbulence encounters and also to reduce the chance of a collision when aircraft are
required to conduct emergency descents or deviate from their cleared route/level. Pilots will not
deviate until entering oceanic airspace and will re-join their cleared track before leaving.

Aircraft conducting SLOP do not require a clearance to do so and are not required to inform the
controlling agency. For the purposes of ensuring separation, the effect of SLOP is not required to be
considered by controllers – this information is included here for reference only

## 2.4 Longitudinal Separation
### 2.4.1 Crossing Tracks Same Direction
For aircraft operating on the same or intersecting tracks (tracks are not laterally separated) where
the relative angle between the tracks is less than 90 degrees, aircraft must be longitudinally
separated by:

| ADS-B Equipped Aircraft Pairs | Other Aircraft Pairs |
| :---------------------------: | :------------------: |
| 4 minutes at the oceanic entry point <br> and <br> 15 NM thereafter | 10 minutes on the same track <br> and <br> 15 minutes on crossing tracks |

> Note: 10 minutes separation may be reduced subject to the Mach Number Technique

<figure markdown>
![Profile Selction](/controller/img/sopscrosstrack.png){ width="650" }
  <figcaption><sup>Figure 3 – Crossing Tracks (Same Direction)</sup></figcaption>
</figure>

### 2.4.1.1 Mach Number Technique (MNT)
> The Mach number technique is only relevant if one aircraft in the pair is not ADS-B equipped.

Where turbojet aircraft flying a constant Mach number converge on the same point (which must be
reported by both aircraft or confirmed by other means) and then proceed down the same track or
diverging tracks, the 10 minutes longitudinal separation may be reduced if the following aircraft
maintains a slower speed:

| Following Aircraft | slower by Separation |
| :-----------------:| :------------------: |
| 0.01 Mach | 10 minutes |
| 0.02 Mach | 9 minutes |
| 0.03 Mach | 8 minutes |
| 0.04 Mach | 7 minutes |
| 0.05 Mach | 6 minutes |
|0.06 Mach or more | 5 minutes |

### 2.4.2 Crossing Tracks Opposite Direction
For aircraft operating on the same or intersecting tracks (i.e. tracks that are not laterally separated)
where the relative angle between the tracks is between 90 and 180 degrees, longitudinal separation
cannot be established throughout. Vertical separation must be established at least 15 minutes prior
to the closest point of approach.

<figure markdown>
![Profile Selction](/controller/img/sopscrossingopposite.png){ width="350" }
  <figcaption><sup>Figure 4 – Crossing Tracks (Opposite Direction)</sup></figcaption>
</figure>
Vertical separation is no longer required once both aircraft have passed each other by:

| ADS-B Equipped Aircraft Pairs | Other Aircraft Pairs | 
| :-: | :-: |
| 5 NM | 10 minutes|

## 2.4.3 Applying Longitudinal Separation on Parallel Tracks not Laterally Separated
Where non-intersecting or parallel tracks are not laterally separated, longitudinal separation must
be established. Refer to [Crossing Tracks Same Direction](chap2.md/#241-crossing-tracks-same-direction) for required minima.

> Note: the following diagram illustrates the application of longitudinal minima for ADS-B
equipped aircraft. For non-ADS-B equipped aircraft, the minima must be substituted for the
correct values.

<figure markdown>
![Profile Selction](/controller/img/sopsparllong.png){ width="450" }
  <figcaption><sup>Figure 6 – Longitudinal Separation on Parallel Tracks</sup></figcaption>
</figure>

### 2.4.4 Operations Without A Fixed Speed (OWAFS)
All oceanic clearances shall include an assigned Mach number (or airspeed).

After oceanic entry, aircraft may be instructed to RESUME NORMAL SPEED on a tactical basis. This
allows aircraft to fly a cost index (ECON) speed. ATC must be informed if the speed changes by
M0.02 or more from the last assigned Mach number.

It is recommended that OWAFS is only applied to aircraft whose planned minimum longitudinal
separation from other aircraft is 60NM or greater. Longitudinal separation must be monitored and a
fixed Mach number may be re-assigned if necessary.