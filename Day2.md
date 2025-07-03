# THEORY:
Here we were taught how to make a good floorplan and also we were taught about the library cells.In this day the following concepts were being learnt, they are as follow:
- Utilisation Factor and Aspect Ratio : So, after we have created the RTL Netlist we would have that in the form of the gates and flipflops but in general during the floorplan each of the module that is the gates or flipflops or mux are taken as a block and they are represented as a block and are being placed on the chip. So, here in the floorplan we would calculate how much are from the core would be utilized by us to for the placement of all of all of the cells which are being present. So for this we calcualte the total area of the core avialable to us and the total area being utilised by all of the blocks which are being present for a given implementation that is the total area occupied by the netlist. Usually the Utilization factor is kep at 50%.
  
- Utilization Factor = Area taken by the netlist/Total area of the Core
  
- Aspect Ratio: The Aspect ratio is nothing but the ratio of the Height to Width
- Aspect Ratio = Height/Width

- Then we were being introducted to the concept of the Pre-Placed Cells. The Pre-Placed cells are the logic blocks that are being frequently being reused in our given chip or whole process. So, the pre-placed cells will be given to those logical blocks which would be accessed on a regular basis on at different times so instead of taking the multiple copies of them as wasting the space on the core we would keep the location of the Pre-placed cells on our chip so that when ever they are need they would be acting from the same spot instead of creating the multiple components of them and the location allocated for the pre-placed cells cannot be taken by any other logical block in our chip. These pre placed cells are sually the memory, clock gating cells, comparator, MUX or etc. Then on the basis of this pre-placed cells we would keep the othere components on our chip and this planning is called as the floorplanning where we would just make a plan on where to keep which logical block.

- Then we were being taught about the decoupling capactiors and their importance. The decoupling capacitors are the capacitors which would help in providing the proper power supply to our circuit and let it always be in the acceptable noise margin range. These capacitors are being mainly used because here we can see that even if we give the proper vdd from the source we wont get the complete vdd at the logic because of the parasitic properties or wires, resistors, capactiors and inductors being present on the way so there is a chance that at times the input power would be so less that i would be out of the noise margin range causing the error to happen and making to circuit to go into an unstable state so to avoid this only we are going to use the decoupling capactiors and these even help in maintaining the stability in the input power given to it.

- 
![Screenshot 182439](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20182439.png)
![Screenshot 184256](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20184256.png)
![Screenshot 184332](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20184332.png)
![Screenshot 184427](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20184427.png)
![Screenshot 184604](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20184604.png)
![Screenshot 185046](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20185046.png)
![Screenshot 190325](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20190325.png)
![Screenshot 192504](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-20%20192504.png)
![Screenshot 153317](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20153317.png)
![Screenshot 154251](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20154251.png)
![Screenshot 155238](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20155238.png)
![Screenshot 155725](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20155725.png)
![Screenshot 155937](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20155937.png)
![Screenshot 155948](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20155948.png)
![Screenshot 160052](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20160052.png)
![Screenshot 160129](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20160129.png)
![Screenshot 160623](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20160623.png)
![Screenshot 160724](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20160724.png)
![Screenshot 161250](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161250.png)
![Screenshot 161437](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161437.png)
![Screenshot 161454](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161454.png)
![Screenshot 161508](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161508.png)
![Screenshot 161619](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161619.png)
![Screenshot 161718](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/2/Screenshot%202025-06-23%20161718.png)

