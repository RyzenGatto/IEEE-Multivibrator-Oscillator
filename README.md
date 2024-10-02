# IEEE-Multivibrator-Oscillator
Unused Soldering Workshop for IEEE's University of Arizona Student Chapter

## Renders and Diagrams 

This is a 3D render of the (very very rough) PCB. Since this will not be a part of the soldering workshop, it's unlikely to be updated, but raw KiCad files are available in the repository.
![3D Render](https://github.com/user-attachments/assets/28bcd248-1590-4e18-901f-48760e8664b0)

This is a diagram of the circuit. Again, ugly and unlikely to be revised but it's functional.
![Circuit](https://github.com/user-attachments/assets/0e951e6c-be0b-4673-af1b-1d383ac5e9a1)

# Parts
Resistors are as marked on the circuit diagram. A Capacitor of 220uF is highly unrecommended as it will take far too long to charge and your oscillator will be very slow. Around 20uF will be fine for low voltage and low current. 
Both LED's should be the same color/same voltage for equal oscillation. Updated circuit coming soon.

The transistors used are BC547 and act as switches in this circuit. They are NPN transistors which is wanted because we want the transistors to open when voltage is applied to it, or when voltage is high.

# How it works

The capacitors are connected to the bases of the opposite transistor. As the capacitor voltage rises to 700mV, the attached transistor will close and the capacitor will discharge. This is due to the capacitor on the same side as the open transistor experiencing a drop in current, which can be visualized in a simulation of the circuit.  At the same time, the capacitor controlling the opposite transistor gains voltage and opens. Very cool.
