# ⚡ D.C. circuits

## Series circuits

* In a series circuit, the current flowing through each component is the same ($$I_{total} = I_1 = I_2 =I_3$$​)
* The p.d. across the whole circuit is equal to the sum of the p.d. across each component ($$V_{total} = V_1 +V_2+ V_3$$​)
* The total resistance in a series circuit is equal to the sum of the resistance of each component ($$R_{total} = R_1 +R_2+ R_3$$)

## Parallel circuits

* In a parallel circuit, the total current is equal to the sum of the current flowing through each parallel branch $$I_{total} = I_1 +I_2+I_3$$
* The voltage across several parallel branches is the same$$V_{total} = V_1 = V_2=  V_3$$
* The total resistance in a parallel circuit is $$R_{total} = \frac{1}{R_1} +\frac{1}{R_2}+ \frac{1}{R_3}$$

## Potential dividers

* A potential divider is a line of resistors connected in series to provide a fraction of the voltage of a source to another part of the circuit
* This fraction of the voltage is known as the output voltage, $$V_{out}$$
*   Formula: $$V_{out} = \frac {R_2}{R_1+R_2} \times V_\varepsilon$$​

    <figure><img src="../.gitbook/assets/image (3) (2).png" alt=""><figcaption></figcaption></figure>
* A variable potential divider can be made by using a **rheostat**&#x20;

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

* A rheostat is a type of variable resistor
* The resistance of the rheostat can be adjusted by moving the slider
* Since $$V_{out} = \frac {R_2}{R_1+R_2} \times V_\varepsilon$$, when $$R_1$$​is increased, $$V_{out}$$ decreases
* A variable potential divider can also be made using a potentiometer, with the symbol<img src="../.gitbook/assets/image (17) (2).png" alt="" data-size="line">, which is a rheostat connected at 3 points, A, B and C

<figure><img src="../.gitbook/assets/image (37) (1).png" alt=""><figcaption></figcaption></figure>

* Contact C is the sliding point
* Since the resistance is proportional to the length of the wire, the position of the slider determines the resistance of AC to BC
* $$V_{out}$$​is connected across B and C, so $$V_{out} = \frac {R_{BC}}{R_{AC}+R_{BC}} \times V_\varepsilon$$
* When slider C moves towards A, $$R_{AC}$$decreases and $$R_{BC}$$decreases, hence $$V_{out}$$increases
* When slider moves towards B, $$R_{AC}$$​ increases and $$R_{BC}$$​decreases, hence $$V_{out}$$​increases

## Input transducers

* **An input transducer is an electronic device that converts non-electrical energy into electrical energy**
* Input transducers could also be connected in a potential divider circuit to control the output voltage according to changes in physical conditions

### Thermistor

* A thermistor is a resistor whose resistance varies with temperature
* Commonly, resistance **decreases** as temperature **increases** and vice versa
* Circuit symbol of <img src="../.gitbook/assets/image (33).png" alt="" data-size="line">

### LDR

* An LDR (Light-Dependent resistor) is a resistor that **decreases** as the amount of light shining on it **increases** and vice versa
* Circuit symbol of <img src="../.gitbook/assets/image (43).png" alt="" data-size="line">

