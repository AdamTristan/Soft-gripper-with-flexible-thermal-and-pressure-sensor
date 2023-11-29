

<center><big><b>Guangxuan Xu's soft robotics project</b></big></center>
<center><small>2023.11.29<small></center>

<center><em>This is an unpublished paper on an open-source project related to experimental data and experiment replication.</em></center>

First, we need to set up the preparation of the flexible mechanical claw. Please prepare: 1. Silicone rubber 2. Vacuum pump 3. Oven 4. Stirring rod 5. Flexible fabric 
> You can 3D print the mold from the .SLDPRT file on my GitHub.
> 

![avatar](/figure1.jpg)

Secondly, utilize ANSYS for simulation to experiment with different air pressures to test the symmetry and repeatability of the mechanical claw.
> You can simulate the mold from the .wbpj file on my GitHub.

![avatar](/figure2.jpg)


Third step, test the performance of temperature and pressure sensors and calibrate them.
![avatar](/figure3.jpg)
![avatar](/figure4.jpg)

Fourth step, assemble the control circuit using STM32. You will need: 1. STM32F104 microcontroller 2. Pressure sensor 3. CMOS switch 4. Air pump 5. Solenoid valve
![avatar](/figure5.jpg)
![avatar](/figure6.jpg)