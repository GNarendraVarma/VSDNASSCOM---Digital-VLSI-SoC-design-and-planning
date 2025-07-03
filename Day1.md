# THEORY:
In the theory we were first being shown a sample QFN-48 package and discussed about the various compnents of a chip which is being present inside a package and the different compnents which are being present in a chip are as follow:
- 1.Pads: The pads are basically the ones which are being used to for a connection between the IC and the chip being present it is used for sending the electrical singlas inside the chip.
- 2.Core: The core is the main part of the chip where we have the digital logic components being placed. Here all the main elements like the gates, mux, flip flops are being placed whihc do the functioning of our processor.
- 3.Die: The Die is the main part where the core is being placed a die can contain more than one core being present in it.

Then we have learnt about the foundary IP's these are the components which are being provided by the desinger. These are usually pre designed in nature and are being tested by the foundry. These include the PLL, ADC, SRAM and various other compnents.
Macors : The macros are the ones which are very similary to the Foundry IPs but the only difference is that these have pure digital logic which are being premade for a common use case . Macros can be of various types like the GPIO or the SPI, etc.

Then we were being given introduction about the OPENLANE how it works, what are the different files which are being present in the openlane and different tools available in the openlane. So, here is a breif introduction:
OPENLANE: The OPENLANE is a free RTL to GDS-II tool which is being present to convert from RTL to GDS-II for free without any human intervention with the usage of the free avaialble softwares such as the Yosys, Fault, OpenRoad,Magic,etc.
Then we were being thought about the RTL to GDS flow like what do happens in this process:
1.Synthesis: With the help of the verilog filw we would synthesize it and create the RTL file on which we would do the static timing analysis and send it for floorplanning.
2.FloorPlanning and Power Distribution : In this step based on the RTL information we are having we are going to properly place our cells in our core part of the chip and see that there is an efficient way of planning occuring so that we can place our chips and then in the Power Distribution/Power Planning we create the different power lines and the ground lines all over our chip in order to provide proper power to our chip
3.Placement: After the proper floorplan has been made and the proper power planning is being done, we place our cells on the chip according to the floorplan which we have made. There are two parts in power planning they are the Global Placement and Detailed placement in Global placement we would priovde a rough estimate and keep them on the layout where as we would use the detailed placement to properly keep each of them where they belong to and see that they are in order.
4. Clock Tree Synthese: After all the cells are being placed we would now be giving the clock to the required cells with the help of the Clock Tree Synthesis process here we provide clock to all of them in different methods like the H-Tree or X-tree or etc depending on the user choice and the requirement and see that there is minimum skew and jitter present in the given clock signal.
5. Routing: In the routing step we would now route the compnents which are being present with the wires and see that these donot overlap each other and to avoid the overalp we placethem in the different metal layers.
6.GDS-II: After routing properly we send the chip for the GDS-II process but before sending it we would check for any DRC voilations occuring in our model and then send them finally for the GDS-II process and after this the foundary use this GDS-II information only to make the chip for us and they would give it to us.
In the whole above process we would be using different tools such as the Yosys for RTL generation, ABC for cell mapping ioplacer for the input and output ports, PDN for the power distribution, RePlace for the global placement, Triton CTS for the Clock Tree synthesis and Magic for the checking of any DRC voilations occuring along in the compnent or the whole chip.

# LAB:
Here in the first lab we though about the basics on how to run the OPENLANE what are the different files which would be required to us for the geration from the RTL to GDS II, we were being though about the PDK(Process Design Kits), about the lef files, def files, spef files and where would the results be present where would these all the information files such as the lef, def, spef would be present and how to run all of them and finally we were being taught how to calculate the total flop ratio after doing the synthesis part.
![Screenshot 180446](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180446.png)
![Screenshot 180522](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180522.png)
![Screenshot 180610](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180610.png)
![Screenshot 180729](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180729.png)
![Screenshot 180753](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180753.png)
![Screenshot 180900](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20180900.png)
![Screenshot 181253](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20181253.png)
![Screenshot 181721](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20181721.png)
![Screenshot 181742](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20181742.png)
![Screenshot 181447](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20181447.png)
![Screenshot 181537](https://raw.githubusercontent.com/GNarendraVarma/VSDNASSCOM---Digital-VLSI-SoC-design-and-planning/master/1/Screenshot%202025-06-20%20181537.png)
