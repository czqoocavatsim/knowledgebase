# Provision of Air Traffic Services
CHAPTER 1
## 1.1 Roles and Responsibilities

▪ Provide the appropriate ATS within their stated AoR in order to ensure a safe, orderly and
expeditious flow of air traffic. <br>
▪ Verify flight data including updating and managing the relevant datablock.<br>
▪ Maintain a listening watch and conduct standard radiotelephony communication with
aircraft.<br>
▪ Provide ATS to aircraft using ADS-B derived surveillance data within their area of
responsibility (AoR).<br>
▪ Provide assistance to aircraft in a state of emergency.<br>
▪ Coordinate the movement of aircraft into and out of the sector.<br>
▪ Issue clearances to aircraft to join, leave or cross regulated airspace.<br>
▪ When aircraft are accepted into the sector, ensure separation exists in accordance with this
document.<br>
▪ Confirm all data transfer, revisions and estimates have been effected as required in local
instructions.
## 1.2 ATS Surveillance Systems
On VATSIM, ADS coverage is assumed throughout the Shanwick & Gander OCAs. Simulated ADS-B
data and position reports are assumed to be received through the VATSIM network which are then
interpreted and displayed by controller clients or relevant plugins.
## 1.3 Assumptions of Aircraft Equipment
In the real-world, a series of navigation, communications and surveillance standards are defined in
order to enhance the provision of ATS within the shared Oceanic Control Area. These specifications
allow for reduced separation standards to be implemented between suitably equipped aircraft pairs
as well as reduce the need for voice communications.

On VATSIM, these specifications are simplified and divided into 2 categories:<br>
▪ ADS-B equipped aircraft;<br>
▪ Non-ADS-B equipped aircraft (other aircraft)

### ADS-B equipped aircraft are assumed to:<br>
▪ comply with the requirements and specifications of the Datalink Mandate (DLM);<br>
▪ comply with the requirements for Performance Based Communication and Surveillance
(PBCS);<br>
▪ comply with the requirements for Advanced Surveillance Enhanced Procedural Separation
(ASEPS);<br>
▪ provide electronic position reports through ADS-C and/or CPDLC (are AGCS equipped)
### Non-ADS-B equipped aircraft (other aircraft) are assumed to:<br>
▪ not comply with the requirements and specifications of the Datalink Mandate (DLM);<br>
▪ not comply with the requirements for Performance Based Communication and Surveillance
(PBCS);<br>
▪ not comply with the requirements for Advanced Surveillance Enhanced Procedural
Separation (ASEPS);<br>
▪ not provide electronic position reports through ADS-C and/or CPDLC.

The vNAAATS plugin indicates to controllers which category each aircraft falls into based on the
equipment code. ADS-B equipped aircraft are marked as Air-Ground Communications System
(AGCS) equipped

## 1.4 Position Reports
On VATSIM, the requirement for voice position reports is dependent on aircraft equipment code.<br>
▪ ADS-B equipped aircraft – position reports optional<br>
▪ Other aircraft – position reports mandatory<br>

Note: Aircraft that are not equipped with ADS-B are also considered to not be equipped with
ADS-C or CPDLC, which would provide automatic/electronic position reporting functionality.

Note: For some events, it may be necessary to mandate that all pilots do not provide position
reports due to frequency congestion.
## 1.5 Oceanic Clearance
Pilots must request oceanic clearance at least 30 minutes prior to the oceanic entry point. Clearance
can be requested via:<br>
▪ HF Voice Frequency<br>
▪ VHF Voice Frequency - (Only available within range of VHF receivers – see chart below)<br>
▪ [natTRAK Website](https://nattrak.vatsim.net/index.php)<br>
Phraseology for oceanic clearances is provided in Annex A.<br> <!--TODO:Add link to phraseology-->
When the delivery function is not split with another controller, track controllers may operate a
second VHF clearance delivery frequency alongside HF to improve readability. 
<figure markdown>
![Profile Selction](/controller/img/sopsvhfrange.png){ width="550" }
  <figcaption><sup>Figure 1 – Shanwick and Gander VHF Frequency Range at FL350</sup></figcaption>
</figure>

## 1.5.1 Oceanic Clearance Prior to Departure
At some airfields proximate to the NAT HLA, an oceanic clearance is required prior to departure. On
VATSIM, VHF coverage is assured at these airfields.

| Departure Point | Jet Departures | Non-Jet Departures |
| --------------- | -------------------------------- | ---- |
| EIDW,<br> EIWT,<br> EIME | For all Oceanic entry points request when airborne. |
| EICK | If flight planned to enter Shanwick airspace via OMOKO, TAMEL or LASNO, Oceanic clearance required prior to departure. <br> <br> All other Oceanic entry points, if the elapsed time to Shanwick Entry Point is 40 minutes or less Oceanic clearance required prior to departure. | |
EGAA,<br>EGAC,<br>EGAE,<br>EGPF,<br>EGPK | If flight planned to enter Shanwick at GOMUP, oceanic clearance is required prior to departure. <br> <br> For all other Oceanic entry points, | Request when airborne. |
|All other aerodromes | If the elapsed time to the Shanwick entry point is 40 minutes or less oceanic clearance is required prior to departure.|

## 1.6 Selective Calling (SELCAL)
Selective calling or SELCAL (pronounced “sell-call”) is a method by which pilots may be notified that
a controller wishes to contact them on the voice frequency.

SELCAL works by the controller triggering a series of 4 audio tones to play over the HF frequency,
which are then received by the SELCAL units onboard all the aircraft tuned to that frequency. If
these tones correspond to the code assigned to a specific aircraft, a notification is relayed to the
pilots. SELCAL therefore allows pilots to reduce the volume of the tuned HF frequency since in real
life, HF transmissions are subject to significant background static that is both tiring and distracting to
listen to over longer periods of time.

On VATSIM, pilot clients act in the same way as SELCAL units - when a SELCAL that corresponds to
the code the pilot entered when they logged into the network is received, it will generate an alert to
the pilot.

The function of the SELCAL system shall be checked on first contact with each Oceanic Controller.
In EuroScope, controllers can trigger a SELCAL tone (e.g. EM-DG) by using:

▪ “.selcal emdg”<br>
▪ “SELCAL EM-DG”<br>
▪ “.selcal”, then click on the aircraft