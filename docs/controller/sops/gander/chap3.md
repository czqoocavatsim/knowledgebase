# Coordination and Procedures with Adjacent Sectors
CHAPTER 3

## 3.1 Reykjavík ACC (BIRD)
Reykjavík provides a domestic radar service and borders the Northern edge of the Gander OCA.

| **Attribute**                  | **Details**          |
|--------------------------------|----------------------|
| **RTF Callsign**               | Reykjavik Control    |
| **Equipment**                  | Non-radar            |
| **Lateral Separation Minima**  | 10NM at and above FL270, 5NM below FL270 |
| **Longitudinal Separation Minima** | 10NM at and above FL270, 5NM below FL270 |
| **Special Transfer Conditions**| None                 |

<figure markdown>
![Profile Selection](/controller/img/sopsbird.png){ width="550" }
    <figcaption><sup>Figure 18 – Reykjavík ACC Sectorisation</sup></figcaption>
</figure>

> Note: BIRD_1_CTR is the bandbox position and covers all BIRD sectors top-down.

### 3.1.1 West Sector

| BIRD_6_CTR |
| :-: |
| 124.400 MHz |

| BIRD_1_CTR |
| :-: |
| 119.700 MHz |

### 3.1.2 South Sector
> Note: The south sector can be dynamically split (vertically) according to demand, refer to the diagram for the correct sector.

| BIRD_1_CTR |
| :-: |
| 119.700 MHz |

| BIRD_2_CTR |
| :-: |
| 125.700 MHz |

| BIRD_3_CTR |
| :-: |
| 128.600 MHz |

## 3.2 New York Oceanic ARTCC (KZWY)
New York Oceanic provides a procedural service augmented by ADS-C, with 15NM longitudinal and 30 NM lateral separation between eligible aircraft pairs. ZWY borders Gander to the South West between Gander Domestic and Santa Maria. All handoffs are to the Mercury Sector (21-24 on the diagram below). New York delegates a rectangle of airspace to Gander Oceanic North of N45 30’, between 40W and 50W up to the FIR boundary. New York also delegates another portion of airspace to Gander (domestic) to the west of this rectangle.

| **Attribute**                  | **Details**          |
|--------------------------------|----------------------|
| **RTF Callsign**               | New York Radio       |
| **Equipment**                  | Non-radar            |
| **Lateral Separation Minima**  | 30NM                 |
| **Longitudinal Separation Minima** | 30NM             |
| **Special Transfer Conditions**| None                 |

<figure markdown>
![Profile Selection](/controller/img/sopsnewyork.png){ width="550" }
    <figcaption><sup>Figure 19 – New York Oceanic ARTCC Sectorisation</sup></figcaption>
</figure>

### 3.2.1 Mercury

| NY_ML_FSS |
| :-: |
| 17.946 MHz (130.600 MHz) |

| NY_FSS (NY_CL_FSS) |
| :-: |
| 5.550 MHz (130.000 MHz) |

### 3.2.2 Mercury High (FL365 - UNL)
> The Mercury sector split is established at FL365 by default, but this level can be varied according to demand.

| NY_MH_FSS |
| :-: |
| 21.925 MHz (130.650 MHz) |

## 3.3 Santa Maria OAC (LPPO)
Santa Maria provides a mixture of radar and procedural services within their FIR. Radar stations at the Azores allow for a central area of radar coverage surrounded by procedurally controlled airspace which Gander borders. All handoffs are to the primary non-radar sector.

| **Attribute**                  | **Details**          |
|--------------------------------|----------------------|
| **RTF Callsign**               | Santa Maria Radio    |
| **Equipment**                  | Non-radar            |
| **Lateral Separation Minima**  | 50NM                 |
| **Longitudinal Separation Minima** | 10 Minutes       |
| **Special Transfer Conditions**| None                 |

<figure markdown>
![Profile Selection](/controller/img/sopssantam.png){ width="550" }
    <figcaption><sup>Figure 20 – Santa Maria OAC Sectorisation</sup></figcaption>
</figure>

### 3.3.1 Non-radar Sector

| LPPO_FSS |
| :-: |
| 132.075 MHz |

## 3.4 Montreal ACC (CZUL)
Montreal provides a domestic radar service. Sectors are split vertically at FL290, of which the lower sectors share boundaries with Gander Oceanic underneath the GOTA.

| **Attribute**                  | **Details**          |
|--------------------------------|----------------------|
| **RTF Callsign**               | Montreal Center      |
| **Equipment**                  | Radar equipped       |
| **Lateral Separation Minima**  | 5NM                  |
| **Longitudinal Separation Minima** | 5NM              |
| **Special Transfer Conditions**| None                 |

### 3.4.1 Montreal Sectorisation below FL290

<figure markdown>
![Profile Selection](/controller/img/sopsmontreal.png){ width="550" }
    <figcaption><sup>Figure 21 – Montreal ACC Sectorisation Below FL290</sup></figcaption>
</figure>

### 3.4.2 Montreal Nuvilik

| MTL_NK_CTR |
| :-: |
| 135.100 MHz |

| MTL_BJ_CTR |
| :-: |
| 125.900 MHz |

| MTL_HV_CTR |
| :-: |
| 134.650 MHz |

| MTL_CTR |
| :-: |
| 128.775 MHz |

> Note: MTL_TH_CTR may be used instead of MTL_CTR when the sector is split.

## 3.5 Gander (Domestic) ACC (CZQX)
Gander (domestic) provides a domestic radar service. Gander (domestic) is delegated the following areas by adjacent sectors:
- The Gander Oceanic Transition Area (GOTA) at FL290 and above
- A small fillet of airspace west of 50W in the southwest corner of the Gander OCA by Gander Oceanic
- An area of airspace south of 45N and west of 50W by New York Oceanic.

When Gander is offline, its airspace is covered top-down by Moncton Center.

| **Attribute**                  | **Details**          |
|--------------------------------|----------------------|
| **RTF Callsign**               | Gander Center for CZQX, Moncton Center for CZQM |
| **Equipment**                  | Radar equipped       |
| **Lateral Separation Minima**  | 5NM                  |
| **Longitudinal Separation Minima** | 5NM              |
| **Special Transfer Conditions**| None                 |

### 3.5.1 Gander (Domestic) Sectorisation FL290 and Above

<figure markdown>
![Profile Selection](/controller/img/sopsgander.png){ width="550" }
    <figcaption><sup>Figure 22 – Gander (Domestic) ACC Sectorisation FL290 and Above</sup></figcaption>
</figure>

### 3.5.2 Gander (Domestic) Sectorisation below FL290

<figure markdown>
![Profile Selection](/controller/img/sopsganderbelow.png){ width="550" }
    <figcaption><sup>Figure 23 – Gander (Domestic) ACC Sectorisation Below FL290</sup></figcaption>
</figure>

### 3.5.3 All Gander Sectors

| CZQX_CTR |
| :-: |
| 132.100 MHz |

| CZQM_CTR |
| :-: |
| 132.200 MHz |