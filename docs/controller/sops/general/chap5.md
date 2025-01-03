# Route Structures
CHAPTER 5

## 5.1 Organised Track System (OTS)
### 5.1.1 North Atlantic (NAT) Tracks
**Introduction**
To minimise flight time and thereby the cost of operating aircraft through oceanic airspace, all
operators desire to operate in a relatively small portion of oceanic airspace. The optimum routings
vary according to departure and destination airfields, enroute weather, winds aloft and aircraft
performance.

**Design**
To maximise the flow of traffic along the preferred, optimal routings, Shanwick & Gander publish a
list of set North Atlantic (NAT) Tracks each day. The process of track design depends upon input
from operators, upper wind conditions, limitations of airspace and feasibility for surrounding
controlling authorities. This system can accommodate a higher flow of traffic than using ‘random
routings’ for all aircraft.

The published tracks are defined by a list of permissible flight levels and series of waypoints, which
include an oceanic entry and exit point. These are positioned on the domestic FIR boundaries and
are generally named using the standard five-letter convention. Between the entry and exit points,
waypoints are defined by Latitude and Longitude (e.g. 57N 040W, also written 5740N or 57/40) and
are generally positioned every 10 degrees of longitude.

**Validity**
In the real world, the tracks are only valid at certain times of day, with a westbound set published
for use for aircraft crossing the 30 degrees west line between 1130 and 1900Z and an eastbound set
for aircraft crossing the same line between 0100 and 0800Z. The two sets of tracks are not
necessarily laterally separated as they are never valid at the same time.

Shanwick OAC (Prestwick) publishes the westbound tracks around 2200z before activation in the
morning and Gander OAC publishes the eastbound tracks around 1400z in the afternoon.

**Naming**
NATs are named using letters of the alphabet. Westbound tracks are named with the most northerly
track designated ‘Alpha’ and working down the alphabet to the final westbound track. Eastbound
tracks are identified with the most southerly track designated ‘Zulu’ and working up through the
alphabet to the final eastbound track. These names are re-used every day when old tracks are
removed and new tracks published, though the number of tracks each day may vary.

**Random Routes**
The use of the OTS is not mandatory, pilots may file routes that over/under-fly, cross join or leave
the system. Any route that does not follow the OTS for the entire track is referred to as a “random
route”.

### 5.1.2 Track Message Identifier (TMI)
The NAT Tracks are published in a single NAT Track Message (NTM) with a Track Message
Identification (TMI) number. This is simply the Julian calendar day that the tracks are published.
Checking this number confirms that both the pilot and the controller have the latest track
information. “Track Alpha” from one day to another will be a different published route, however
“Track Alpha, TMI 001” will only be repeated once every year (1st January). Occasionally if the NAT
message is amended after publication, a letter will be appended to the TMI number (e.g. 001A) and
the entire message is re-issued.

### 5.1.3 NAT Track Message
Here is an example of a NAT Track Message (NTM) issued by Gander on 11th March 2021 specifying
eastbound tracks valid for the next morning. Only one track is published (Track Z) with only
eastbound flight levels specified. The TMI is 071 and further important information is published
regarding the provision of ATS below.

<figure markdown>
![Profile Selction](/controller/img/sopsnotam.png){ width="350" }
  <figcaption>Figure 7 – NOTAM Example</figcaption>
</figure>

### 5.1.4 Use of OTS on VATSIM
On VATSIM, the most recently published tracks can be used at any time and are not limited to the
levels published. As such, controllers should be aware that there is the possibility of traffic on
eastbound and westbound tracks (where one set is ‘out of date’) will conflict.

If the eastbound and westbound tracks do conflict, coordination must occur between controllers
responsible for clearing aircraft in both directions along the OTS. It is advised, in this instance that
controllers should clear aircraft on levels that follow the semi-circular rule.

## 5.2 Tango Routes
The Tango routes are a fixed set of routes in the South Eastern of the Shanwick OCA.
Clearance delivery must be conducted over HF for northbound aircraft (due to range requirements)
but may be conducted on VHF for southbound aircraft.

### 5.2.1 T9 and T290
T9/T290 are unidirectional routes established just west of the BOTA. They connect the SOTA to the
Madrid FIR and are generally used by aircraft from the British Isles to Portugal, the Canaries and
Cape Verde Islands.<br>
▪ T9 - Southbound - LASNO to BEGAS<br>
▪ T290 - Northbound - ADVAT to GELPO

> Note: T9/T290 are laterally separated from each other.
### 5.2.1.1 Transponder Operation on T9/T290
Pilots will reset their assigned SSR code to 2000, 10 minutes after passing LASNO, BEGAS, TAMEL or
BERUX.

### 5.2.2 T213
T213 is a bi directional route established to the West of T290 and connecting the SOTA to the
Madrid FIR.<br>
▪ T213 – Bi-directional – TAMEL to BERUX

### 5.2.3 T13 and T16
T13/T16 are unidirectional routes established just west T213 and cross into Santa Maria Oceanic
airspace eventually terminating just North of the Madeira Archipelago.<br>
▪ T13 - Northbound – NILAV to OMOKO<br>
▪ T16 - Southbound - OMOKO to GONAN

> Note: T13/T16 share a common waypoint (OMOKO) and are therefore not laterally separated.
## 5.3 North American Routes
The North American Routes (NARs) are fixed routes designed for application to aircraft flying
oceanic random routes at and above FL290 to transition to domestic airspace. Occasionally the NAT
Message will specify NARs which must be used in conjunction with certain tracks.
> Note: Oceanic controllers do not assign NARs. This section is for information only.

Westbound NARs consist of 2 portions;

1. The coastal fix is linked to an inland fix (INF) by what is termed the ‘common portion’.
2. The ‘non-common portion’ will then link the inland fix towards the system airports.
Where an airport does not have defined non-common portions, pilots should file the full route of
the common portion to the inland fix.

Eastbound NARs consist of a single portion - the ‘common portion’ which connect the inland fix to
the coastal fix. 

All NARs are designated by N*, where ‘N’ is spoken “North American Route” and * is the published
designator (usually a 1/2-digit number followed by a letter).

Most of the routes are divided into two portions:
1. Common Portion - That portion of the route between a specified coastal fix or an oceanic
entry/exit point and a specified Inland Navigation Fix (INF). Some routes have a common
portion only (N598A-N700A);
2. Non-Common Portion - That portion of the route between a specified INF and a system
airport. The routes are within the high-level airspace structure with a transition to/from
system airports.

The routes are prefixed by the abbreviation "N" with the numbering for the common portions
orientated geographically from south to north. The ODD numbers have eastbound application while
the EVEN numbers apply to westbound.

Aircraft can only join the NAR System:
▪ At the identified coastal fix or oceanic entry/exit point; or
▪ On departure from one of the identified system airports; or
▪ At an identified INF.

NARs may be assigned by ATC for the tactical management of air traffic in Canadian Domestic
airspace.