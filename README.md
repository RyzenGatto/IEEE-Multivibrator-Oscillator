# IEEE-Astable Multivibrator 
Unused Soldering Workshop for IEEE's University of Arizona Student Chapter

## Renders and Diagrams 

These are the 3D renders of the PCB. Raw STEP and Gerber files are available in the repository.

**Top**

![3D Render](https://github.com/user-attachments/assets/646e99a1-a1e6-4e54-877c-bfa34c5836af)

**Bottom**

![PCB Rear](https://github.com/user-attachments/assets/c76d0a30-c155-405b-8779-5264b1107cfc)


**PCB layout from KiCad**

![PCB Net](https://github.com/user-attachments/assets/cbb96ef4-1def-498e-b085-6d09324706a6)



This is a diagram of the circuit.
![Circuit](https://github.com/user-attachments/assets/b6eabcd3-883c-4e86-bed4-6aeffe1d4ba5)





# Parts
Resistors are 10k where used. Capacitors are 20uF 
Both LED's should be the same color/same voltage for equal oscillation.
Input voltage is designed to be 3 volts from a coin cell battery. More voltage would require resistors to the LEDs.

The transistors used are BC547 and act as switches in this circuit. They are NPN transistors which is wanted because we want the transistors to open when voltage is applied to it, or when voltage is high.

# How it works

The capacitors are connected to the bases of the opposite transistor. As the capacitor voltage rises to 700mV, the attached transistor will close and the capacitor will discharge. This is due to the capacitor on the same side as the open transistor experiencing a drop in current, which can be visualized in a simulation of the circuit.  At the same time, the capacitor controlling the opposite transistor gains voltage and opens. Very cool.
