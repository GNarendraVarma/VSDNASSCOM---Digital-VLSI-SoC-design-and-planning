# THEORY:
# CMOS Fabrication Process – 16 Mask Flow
## 1. Active Region Formation

**Substrate:** Lightly P-doped silicon wafer.

**Isolation (LOCOS method):**
- Grow 40 nm of SiO₂.
- Deposit 80 nm of Si₃N₄.
- Apply photoresist and use Mask-1 to define active regions.
- Expose to UV light, remove unmasked areas.
- Strip photoresist and grow thick oxide in exposed areas.
- Remove Si₃N₄ using hot phosphoric acid.

## 2. Well Formation (Twin-Tub Process)

- Apply photoresist with Mask-2 to define N-well regions.
- Apply Mask-3 to define P-well regions.
- Perform ion implantation:
  - Boron for P-well.
  - Phosphorus for N-well.

## 3. Gate Terminal Formation

**Threshold Voltage Adjustment:**
- Mask-4: Implant Boron for PMOS.
- Mask-5: Implant Phosphorus or Arsenic for NMOS.

**Gate Formation:**
- Strip damaged oxide and re-grow gate-quality SiO₂.
- Deposit polysilicon.
- Pattern gate using Mask-6.

## 4. Lightly Doped Drain (LDD) Formation

- Mask-7: Lightly dope N⁻ for NMOS.
- Mask-8: Lightly dope P⁻ for PMOS.
- Deposit and etch oxide spacers using anisotropic etching.

**Purpose:** Reduces electric field near the drain to prevent hot carrier degradation in short-channel devices.

## 5. Source and Drain Formation

- Add screen oxide to prevent ion channeling.
- Mask-9: Heavily dope N⁺ for NMOS.
- Mask-10: Heavily dope P⁺ for PMOS.
- Perform high-temperature annealing to activate dopants.

## 6. Local Interconnect Formation

- Remove oxide over source, drain, and gate regions.
- Deposit Titanium to form TiSi₂ (silicide).
- Pattern using Mask-11.
- Clean residual Titanium Nitride using RCA cleaning.

## 7. Higher Metal Layer Formation

**Planarization:**
- Deposit doped oxide (PSG or BPSG).
- Perform CMP (Chemical Mechanical Polishing).

**Metallization:**
- Mask-12: Etch first contact vias.
- Mask-13: Deposit and pattern first Aluminum layer.
- Mask-14: Etch second contact vias.
- Mask-15: Deposit and pattern second Aluminum layer.
- Mask-16: Define final pad openings for bonding.

## Summary

The 16-mask CMOS process integrates NMOS and PMOS transistors using well-defined photolithographic and doping steps. This process enables high-performance, scalable, and reliable IC fabrication suitable for modern digital circuits.


# LAB:
## Cloning the VSD Standard Cell Design Repository in OpenLane

To begin working with the standard cell design lab in OpenLane, follow the steps below

Copy the clone URL from the repository and run the following command in the OpenLane terminal:

git clone https://github.com/nickson-jose/vsdstdcelldesign

- Then we have to open the mag file of the inverter which is being present as we are going to work on that inverted file only which is a .mag file and we are going to open it with the help of the magic tool and later calculate some of the metrics which is being done below:

![Screenshot 163413](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163413.png)
![Screenshot 163436](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163436.png)
![Screenshot 163451](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163451.png)
![Screenshot 163503](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163503.png)
![Screenshot 163559](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163559.png)
![Screenshot 163621](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20163621.png)
![Screenshot 164319](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20164319.png)
![Screenshot 164417](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20164417.png)
![Screenshot 164441](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20164441.png)
![Screenshot 165148](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20165148.png)
![Screenshot 172428](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20172428.png)
![Screenshot 173415](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20173415.png)
![Screenshot 173534](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20173534.png)
![Screenshot 175029](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20175029.png)
![Screenshot 175642](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20175642.png)
![Screenshot 175750](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20175750.png)
![Screenshot 180417](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20180417.png)
![Screenshot 180558](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20180558.png)
![Screenshot 180609](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20180609.png)
![Screenshot 180712](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20180712.png)
![Screenshot 180724](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20180724.png)
## Rise Transition=2.24471-2.18209=0.06262ns
![Screenshot 181019](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181019.png)
![Screenshot 181052](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181052.png)

![Screenshot 181104](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181104.png)
## Fall time =2.17981-2.11976=0.06005ns
![Screenshot 181319](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181319.png)
![Screenshot 181329](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181329.png)
## Propagation Delay=2.21097-2.15=0.06097ns
![Screenshot 181502](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181502.png)
![Screenshot 181514](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20181514.png)
## Cell Fall delay = 4.07752-4.05=0.02752ns
# Introduction to Magic Tool Options and DRC Rules by Tim Edwards

This document introduces the use of the **Magic VLSI Layout Tool**, focusing on Design Rule Checking (DRC) and related tool options as explained by **Tim Edwards**.

## Reference Links

- **Skywater PDK Design Rules:**  
  [Skywater Design Rules Documentation](https://skywater-pdk.readthedocs.io/en/main/rules/periphery.html)

- **Official Skywater GitHub Repository:**  
  [github.com/google/skywater-pdk](https://github.com/google/skywater-pdk)

- **Magic VLSI Layout Tool (Tutorial & Docs):**  
  [opencircuitdesign.com/magic](https://opencircuitdesign.com/magic)

  - Recommended Sections:  
    - **Section 2:** Introduction to Layout  
    - **Section 6:** Design Rule Checking and Tool Configuration

## Lab Preparation

To begin working with the lab:

### Download Lab Files

Use the following command in your terminal:

- wget http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz
- tar -xvzf drc_tests.tgz


![Screenshot 182638](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20182638.png)
![Screenshot 182745](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20182745.png)
![Screenshot 182802](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-23%20182802.png)
![Screenshot 163204](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20163204.png)
![Screenshot 164334](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20164334.png)
![Screenshot 165621](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20165621.png)
![Screenshot 165940](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20165940.png)
![Screenshot 170020](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170020.png)
![Screenshot 170417](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170417.png)
![Screenshot 170544](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170544.png)
![Screenshot 170600](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170600.png)
![Screenshot 170626](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170626.png)
![Screenshot 170850](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20170850.png)
![Screenshot 171119](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20171119.png)
![Screenshot 172207](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20172207.png)
![Screenshot 172234](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20172234.png)
![Screenshot 172717](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20172717.png)
![Screenshot 175254](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20175254.png)
![Screenshot 175617](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20175617.png)
![Screenshot 180354](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20180354.png)
![Screenshot 180545](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20180545.png)
![Screenshot 181225](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20181225.png)
![Screenshot 2025-06-24 181552](https://github.com/user-attachments/assets/6776edc5-2ec0-4e7a-a2a2-601e7032bd00)

![Screenshot 2025-06-24 181803](https://github.com/user-attachments/assets/e98e3545-7288-4243-8fbf-db8ca656f559)

![Screenshot 181956](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/3/Screenshot%202025-06-24%20181956.png)
