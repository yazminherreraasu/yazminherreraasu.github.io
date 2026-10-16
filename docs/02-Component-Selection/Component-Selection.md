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

  *Table 2: NPN Transistor*

**External Clock Module**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366) | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed | 
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed |

**Choice:** Option 1:

**Rationale:**    

*Table 3: NPN Transistor*

**External Clock Module**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366) | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed | 
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed |

**Choice:** Option 1:

**Rationale:** 

*Table 4: NPN Transistor*

**External Clock Module**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366) | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed | 
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed |

**Choice:** Option 1:

**Rationale:** 

*Table 5: NPN Transistor*

**External Clock Module**

| **Solution**    | **Pros**      | **Cons**   |
| ------------ | ------------ | -------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366) | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed | 
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed |

**Choice:** Option 1:

**Rationale:** 
