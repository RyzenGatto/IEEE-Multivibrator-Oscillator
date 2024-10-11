# IEEE-Multivibrator-Oscillator
Unused Soldering Workshop for IEEE's University of Arizona Student Chapter

## Renders and Diagrams 

This is a 3D render of the PCB. Since this will not be a part of the soldering workshop, it's unlikely to be updated, but raw KiCad files are available in the repository.
![3D Render](https://github.com/user-attachments/assets/5e25edbd-a0d7-4e0a-a8b0-00d6232f5b41)


This is a diagram of the circuit. Again, it's unlikely to be revised.
![Circuit](https://github.com/user-attachments/assets/de409615-34d5-4ec8-8547-cdcc67b7556c)


# Parts
Resistors are as marked on the circuit diagram. A Capacitor of 220uF is highly unrecommended as it will take far too long to charge and your oscillator will be very slow. Around 20uF will be fine for low voltage and low current. 
Both LED's should be the same color/same voltage for equal oscillation.

The transistors used are BC547 and act as switches in this circuit. They are NPN transistors which is wanted because we want the transistors to open when voltage is applied to it, or when voltage is high.

# How it works

The capacitors are connected to the bases of the opposite transistor. As the capacitor voltage rises to 700mV, the attached transistor will close and the capacitor will discharge. This is due to the capacitor on the same side as the open transistor experiencing a drop in current, which can be visualized in a simulation of the circuit.  At the same time, the capacitor controlling the opposite transistor gains voltage and opens. Very cool.
