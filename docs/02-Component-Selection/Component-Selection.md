---
title: Component Selection 
---





> 

*Table 1: NPN Transistor*

**NPN Transistor**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image)<br>\*Option 1:  <br>\* 2N3904(from class) <br>\* $0.29 for qty 1 <br> [link to digikey](https://www.digikey.com/en/products/detail/onsemi/2N3904BU/1413) <br> [link to datasheet](https://www.onsemi.com/download/data-sheet/pdf/2n3903-d.pdf)| \* Inexpensive <br>\*  Meets PCB mount constraints <br>\* Used in provided speaker circuit, therefore compatible with PIC | \* Requires external components and support circuitry <br>\* Lower current capacity compared to other alternatives <br>\* 200 mA limit|
| ![](image)<br>\* Option 2: <br>\* 2N4401BU <br>\* $0.28 for qty 1 <br> [Link to digikey](https://www.digikey.com/en/products/detail/onsemi/2N4401BU/1417) <br> [link to datasheet](https://www.onsemi.com/pdf/datasheet/mmbt4401-d.pdf)| \* Inexpensive <br>\* High current limit of 600 mA <br> \* Meets PCB mount constraints |  <br>\* Requires external components and support circuitry  | 
| ![](image)<br>\* Option 3: <br>\* PN222AFS-ND <br>\* $0.32 for qty 1 <br>[Link to digikey](https://www.digikey.com/en/products/detail/onsemi/PN2222ABU/6534) <br> [link to datasheet](https://www.onsemi.com/pdf/datasheet/pn2222a-d.pdf)| \* Meets PCB mount constraints <br>\* High current limit of 1A  | * More expensive <br>\* Requires external components and support circuitry |

**Choice:** Option 1:  2N3904

**Rationale: The part was already tested, used and was successful with the PIC as well in a previous lab for the class. It is inexpensive, and easy to solder.** 

  *Table 2: PNP Transistor*

**PNP Transistor**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image)<br>\*Option 1:  <br>\* 2N3906(from class) <br>\* $0.28 for qty 1 <br> [link to digikey](https://www.digikey.com/en/products/detail/onsemi/2N3906BU/1414) <br> [link to datasheet](https://www.onsemi.com/download/data-sheet/pdf/2n3906-d.pdf)| \* Inexpensive <br>\*  Meets PCB mount constraints <br>\* Used in provided speaker circuit, therefore compatible with PIC | \* Requires external components and support circuitry <br>\* Lower current capacity compared to other alternatives <br>\* 200 mA limit|
| ![](image)<br>\* Option 2: <br>\* 2N4403 <br>\* $0.31 for qty 1 <br> [Link to digikey](https://www.digikey.com/en/products/detail/on-semiconductor/2N4403BU/1418) <br> [link to datasheet](https://www.onsemi.com/pdf/datasheet/2n4403t.pdf)| \* Inexpensive <br> \* Meets PCB mount constraints |  <br>\* 625 mW power max <br>\* Requires external components and support circuitry | 
| ![](image)<br>\* Option 3: <br>\* PN2907ABU <br>\* $0.33 for qty 1 <br>[Link to digikey](https://www.digikey.com/en/products/detail/onsemi/PN2907ABU/6538) <br> [link to datasheet](https://www.onsemi.com/pdf/datasheet/pzt2907a-d.pdf)| \* Meets PCB mount constraints | * More expensive <br>\* Requires external components and support circuitry |

**Choice:** Option 1: 2N3906

**Rationale:The part was already tested, used and was successful with the PIC as well in a previous lab for the class. It is inexpensive, and easy to solder.**    

*Table 3: Speaker*

**Speaker**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![VECO Speaker](f91437e7-ed4c-416a-ae14-3dfe034e174c.jpg)<br>\*Option 1:  <br>\* VECO 50CS08FH-1(from class) <br>\* TBD for qty 1 <br>\* link to digikey not available <br>\* link to datasheet not available| \* Inexpensive <br>\* Used in provided speaker circuit, therefore compatible with PIC <br>\* Used in provided speaker circuit, therefore compatible with PIC <br> \* 8 ohm impedance | \* Requires external components and support circuitry <br>\* Limited output of sound <br>\* No price <br>\* No datasheet|
| ![](image)<br>\* Option 2: <br>\* D0050008NM14BAR <br>\* $9.87 for qty 1 <br> [Link to digikey](https://www.digikey.com/en/products/detail/stetron/D0050008NM14BAR/22155810) <br> [link to datasheet](https://www.stetron.com/wp-content/uploads/2024/01/DB04-050-Rev2.4-D0050008NM14BARJune-23-2020.pdf)| \* Similar size to option 1 <br>\* 8 ohm impedance <br> \* Meets PCB mount constraints |  <br>\* Requires external components and support circuitry <br>\* Solder required for connecting wires to the component <br>\* Expensive| 
| ![](image)<br>\* Option 3: <br>\* 20660 <br>\* $3.12 for qty 1 <br>[Link to digikey](https://www.digikey.com/en/products/detail/sparkfun-electronics/20660/16688097) <br> [link to datasheet](https://cdn.sparkfun.com/assets/3/8/1/5/4/cvs-1508.pdf)| \* Inexpensive <br>\* Small in size  <br> \* 8 ohm impedance  | * Limited sound output <br>\* Requires external components and support circuitry <br>\* Different mounting from option 1 and 2 <br>\* PCB mounting is required|

**Choice:** Option 1: VECO 50CS08FH-1(from class)

**Rationale:The part was already tested, used and was successful with the PIC as well in a previous lab for the class. The part was also easy to solder.** 

*Table 4: 5V Regulator*

**5V Regulator**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image)<br>\*Option 1:  <br>\* LM7805(from class) <br>\* $1.53 for qty 1 <br> [link to digikey](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805ABV-DG/3945936) <br> [link to datasheet](https://www.st.com/content/ccc/resource/technical/document/datasheet/41/4f/b3/b0/12/d4/47/88/CD00000444.pdf/files/CD00000444.pdf/jcr:content/translations/en.CD00000444.pdf)| \* Inexpensive <br>\*  Meets PCB mount constraints <br>\* Fixed 5V output <br>\* Current output 1.5A <br>\* Input voltage max 35V <br>\* Easy to solder | \* Requires external components and support circuitry <br>\* High input voltage needed|
| ![](image)<br>\* Option 2: <br>\* LM2940T-5.0/NOPB <br>\* $2.22 for qty 1 <br> [Link to digikey](https://www.digikey.com/en/products/detail/texas-instruments/LM2940T-5-0-NOPB/148142) <br> [link to datasheet](https://www.ti.com/lit/ds/symlink/lm2940-n.pdf?HQS=dis-dk-null-digikeymode-dsf-pf-null-wwe&ts=1792167838898&ref_url=https%253A%252F%252Fwww.ti.com%252Fgeneral%252Fdocs%252Fsuppproductinfo.tsp%253FdistId%253D10%2526gotoUrl%253Dhttps%253A%252F%252Fwww.ti.com%252Flit%252Fgpn%252Flm2940-n)| \* Fixed 5V output  <br>\* Easy to solder <br> \* Meets PCB mount constraints <br>\* Built in protection|  <br>\* Requires external components and support circuitry <br>\* Input voltage max 26V  <br>\* Current output 1A <br>\* Expensive | 
| ![](image)<br>\* Option 3: <br>\* MC7805ACTG <br>\* $1.07 for qty 1 <br>[Link to digikey](https://www.digikey.com/en/products/detail/onsemi/MC7805ACTG/1481210) <br> [link to datasheet](https://www.onsemi.com/pdf/datasheet/mc7800-d.pdf)| \* Meets PCB mount constraints <br>\* Inexpensive <br>\* Easy to solder| * Current output 1A <br>\* Requires external components and support circuitry |

**Choice:** Option 1:  LM7805

**Rationale:The part was already tested, used and was successful with the PIC as well in a previous lab for the class. The part was also easy to solder.** 

*Table 5:  9V Power Source*

**9V Power Source**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image)<br>\*Option 1:  <br>\*Model: 0930(from class) <br>\* TBD for qty 1 <br> link to digikey not available <br>\* link to datasheet not available| \* Provides 9V DC <br>\* Current capacity 3A <br>\* No batteries needed| \* Requires outlet
<br>\* Not portable <br>\* Requires barrel jack that will work with this part |
| ![](image)<br>\* Option 2: <br>\* SWH24-9-NB-P5 <br>\* $19.54 for qty 1 <br> [Link to digikey](https://www.digikey.com/en/products/detail/bel-power-solutions/SWH24-9-NB-P5/17736489?s=N4IgjCBcoCwBxVAYygMwIYBsDOBTANCAPZQDaIAzAAwCsMA7AgLqEAOALlCAMrsBOASwB2AcxABfQgFoYiECkgYcBEADchaLHkIlI5MFQCcAJhoUQLEBy4TpxuQv4BXFbvI0QhQxckgpANgcoZ1cySh9xcSA&utm) <br> [link to datasheet](https://www.belfuse.com/media/datasheets/products/power-supplies/SWH24-N.pdf)| \* Provides 9V DC <br>\* No batteries needed|  <br>\* Current capacity 2A <br>\* Requires barrel jack that will work with this part  <br>\* Requires outlet  <br>\* Not portable | 
| ![](image)<br>\* Option 3: <br>\* SWH24-12-NB-P5 <br>\* $19.54 for qty 1 <br>[Link to digikey](https://www.digikey.com/en/products/detail/bel-power-solutions/SWH24-12-NB-P5/17736479) <br> [link to datasheet](https://www.belfuse.com/media/datasheets/products/power-supplies/SWH24-N.pdf)| \* Provides 12V DC <br>\* No batteries needed | * Requires barrel jack that will work with this part <br>\* Requires outlet  <br>\* Not portable |

**Choice:** Option 1: Model 0930

**Rationale: The part was successfully used in previous labs. Is compatible with the provided barrel jack and voltage regulator as well. It also provides the required 9V output.** 
