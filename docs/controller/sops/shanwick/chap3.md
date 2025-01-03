# Coordination and Procedures with Adjacent Sectors
CHAPTER 3

## 3.1 Santa Maria OAC (LPPO)
Santa Maria provides a mixture of radar and procedural services within their FIR. Radar stations at the Azores allow for a central area of radar coverage surrounded by procedurally controlled airspace which Shanwick borders. All handoffs are to the primary non-radar sector.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Santa Maria Radio|
| **Equipment**                  | Non-radar        |
| **Lateral Separation Minima**  | 50NM             |
| **Longitudinal Separation Minima** | 10 Minutes  |
| **Special Transfer Conditions**| None             |

<figure markdown>
![Profile Selction](/controller/img/sopssantam.png){ width="550" }
  <figcaption><sup>Figure 12 – Santa Maria OAC Sectorisation</sup></figcaption>
</figure>

### 3.1.1 Non-radar Sector

| LPPO_FSS |
| :-:|
| 132.075 MHz |

## 3.2 Reykjavík ACC (BIRD)
Reykjavík provides a domestic radar service and borders the Northern edge of the Shanwick OCA.
The “RATSU triangle” is delegated from Scottish to Reykjavík (East Sector) at the junction between
Reykjavík, Scottish and Shanwick – refer to Scottish ACC.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Reykjavik Control|
| **Equipment**                  | Non-radar        |
| **Lateral Separation Minima**  | 10NM at and above FL270, 5NM below FL270 |
| **Longitudinal Separation Minima** | 10NM at and above FL270, 5NM below FL270 |
| **Special Transfer Conditions**| None             |

<figure markdown>
![Profile Selction](/controller/img/sopsbird.png){ width="550" }
  <figcaption><sup>Figure 13 – Reykjavík ACC Sectorisation</sup></figcaption>
</figure>

> Note: BIRD_1_CTR is the bandbox position and covers all BIRD sectors top-down.

### 3.2.1 South Sector
The south sector can be dynamically split (vertically) according to demand, refer to Figure 13.

| BIRD_1_CTR |
| :-:|
|  119.700 MHz |

| BIRD_2_CTR |
| :-: |
| 125.700 MHz |

| BIRD_3_CTR |
| :-: |
| 128.600 MHz |

### 3.2.2 East Sector
The east sector can be dynamically split (vertically) according to demand, refer to Figure 13.

| BIRD_4_CTR | 
| :-:| 
| 126.750 MHz |

| BIRD_5_CTR 
| :-: |
| 132.300 MHz |

## 3.3 Scottish ACC (EGPX)
Scottish Area Control (ScAC) provides a domestic radar service and borders Shanwick at 010W between Reykjavík and the NOTA. The “RATSU triangle” is delegated from Scottish to Reykjavík.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Scottish Control |
| **Equipment**                  | Radar equipped   |
| **Lateral Separation Minima**  | 7NM for aircraft following ATS routes |
| **Longitudinal Separation Minima** | 15NM dropping to 5NM if speed control is applied |
| **Special Transfer Conditions**| None             |

> Note: Shanwick is responsible for the coordination of east and westbound traffic at GOMUP, on the edge of NOTA. Shanwick must inform ScAC West if westbound traffic is to be transferred to Shannon rather than Shanwick.

<figure markdown>
![Profile Selction](/controller/img/sopsscott.png){ width="550" }
    <figcaption><sup>Figure 14 – Scottish ACC Sectorisation</sup></figcaption>
</figure>

### 3.3.1 ScAC North

| SCO_N_CTR |
| :-: |
| 129.225 MHz |

| SCO_E_CTR |
| :-: |
| 121.325 MHz |

| SCO_CTR |
| :-: |
| 135.525 MHz |
### 3.3.2 ScAC West

| SCO_W_CTR |
| :-: |
| 132.725 MHz |

| SCO_WD_CTR |
| :-: |
| 133.875 MHz |

| SCO_CTR |
| :-: |
| 135.525 MHz |

## 3.4 Shannon ACC (EISN)
Shannon provides a domestic radar service and borders Shanwick from GOMUP counter-clockwise around the Shannon FIR to TULTA. Shannon also provides a domestic radar service to traffic inside the NOTA and SOTA. Although Shannon has defined a day-to-day configuration of the high-level airspace, they use a dynamic sectorisation above FL245 that varies according to the particular traffic demands. The airspace can also be split vertically at FL355; when this occurs, the sector from FL245-FL355 will be referred to as ‘Upper’, with the sector above FL355+ referred to as ‘Super’.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Shannon Control  |
| **Equipment**                  | Radar equipped   |
| **Lateral Separation Minima**  | 5NM              |
| **Longitudinal Separation Minima** | 5NM          |
| **Special Transfer Conditions**| Eastbound aircraft between SUNOT and BEDRA (inclusive): Transfer of Control – sector boundary, Transfer of Communications – 1 degree prior to sector boundary. |

<figure markdown>
![Profile Selection](/controller/img/sopsshann.png){ width="550" }
    <figcaption><sup>Figure 15 – Shannon ACC Sectorisation</sup></figcaption>
</figure>

### 3.4.1 Shannon NOTA

**Super (FL355+)**

| EISN_4_CTR |
| :-: |
| 127.125 MHz Shannon NOTA – Upper |

**Upper (FL245-FL355)**

| EISN_N_CTR |
| :-: |
| 122.975 MHz Shannon West – Upper |

### 3.4.2 Shannon West

**Super (FL355+)**

| EISN_2_CTR |
| :-: |
| 125.875 MHz Shannon West – Upper |

**Upper (FL245-FL355)**

| EISN_W_CTR |
| :-: |
| 120.050 MHz |

| EISN_CTR (EISN_E_CTR) |
| :-: |
| 131.150 MHz |

### 3.4.3 Shannon Ocean

**Super (FL355+)**

| EISN_6_CTR |
| :-: |
| 134.625 MHz Shannon Ocean – Upper |

**Upper (FL245-FL355)**

| EISN_O_CTR |
| :-: |
| 129.675 MHz Shannon West – Upper |

### 3.4.4 Shannon SOTA

**Super (FL355+)**

| EISN_6_CTR |
| :-: |
| 134.625 MHz Shannon SOTA – Upper |

**Upper (FL245-FL355)**

| EISN_S_CTR |
| :-: |
| 135.600 MHz Shannon West – Upper |

### 3.4.5 Shannon Low Level

**Low Level (DB-FL245)**

| EISN_L_CTR |
| :-: |
| 124.700 MHz |

| EISN_CTR (EISN_E_CTR) |
| :-: |
| 131.150 MHz |

## 3.5 Brest ACC (LFRR)
Brest splits are defined in a “top-up” manner. The main bandbox sector covers airspace below FL255 and upper sectors are split off when required.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Brest Control    |
| **Equipment**                  | Radar equipped   |
| **Lateral Separation Minima**  | 5NM              |
| **Longitudinal Separation Minima** | 5NM          |
| **Special Transfer Conditions**| None             |

> Note: Eurocontrol West (EURW_FSS) covers all French airspace above FL245 in the absence of local ATC.

<figure markdown>
![Profile Selection](/controller/img/sopsbrest.png){ width="550" }
    <figcaption><sup>Figure 16 – Brest ACC Sectorisation</sup></figcaption>
</figure>

### 3.5.1 Brest W (FL255+) Sector

| LFRR_W_CTR |
| :-: |
| 127.850 MHz |

| LFRR_CTR |
| :-: |
| 125.500 MHz |

### 3.5.2 Brest Lower (SFC-FL255) Sector

| LFRR_CTR |
| :-: |
| 125.500 MHz |

### 3.5.3 Brest AU (FL355-FL660) Sector

| LFRR_A_CTR |
| :-: |
| 131.275 MHz |

### 3.5.4 Brest AS (FL255-FL355) Sector

| LFRR_S_CTR |
| :-: |
| 124.675 MHz |

| LFRR_CTR |
| :-: |
| 125.500 MHz |

## 3.6 Madrid ACC (LECM)
All handoffs to/from Madrid come from the West Sector which is split at FL245.

| **Attribute**                  | **Details**      |
|--------------------------------|------------------|
| **RTF Callsign**               | Madrid Radar     |
| **Equipment**                  | Radar equipped   |
| **Lateral Separation Minima**  | 5NM              |
| **Longitudinal Separation Minima** | 5NM          |
| **Special Transfer Conditions**| None             |

> Note: Eurocontrol West (EURW_FSS) covers all French airspace above FL245 in the absence of local ATC.

### 3.6.1 Madrid W Upper (SFC-FL245) Sector

| LECM_W_CTR |
| :-: |
| 135.950 MHz |

| LECM_N_CTR |
| :-: |
| 125.750 MHz |

| LECM_M_CTR |
| :-: |
| 132.975 MHz |

| LECM_U_CTR |
| :-: |
| 136.350 MHz |

| LECM_CTR |
| :-: |
| 133.750 MHz |

### 3.6.2 Madrid W Lower (FL245-FL660) Sector

| LECM_W_CTR |
| :-: |
| 135.950 MHz |

| LECM_N_CTR |
| :-: |
| 125.750 MHz |

| LECM_M_CTR |
| :-: |
| 132.975 MHz |

| LECM_CTR |
| :-: |
| 133.750 MHz |