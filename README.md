# FPGA_Pre_Test

This simple project is for testing power rails and external oscillator to use them on FPGA circuit design.

## 1. Objectives
1. Check power rails ON/OFF sequencing works properly
2. Check oscillator(25MHz) works properly
3. Get output voltage ripple data by
    + different output capacitance(~200uF) of buck converter
    + different output voltages(1.0~5.0V) of buck converter
    + different load(resistive, ~1.5W consume)

## 2. Architecture Diagram
### 2.1 Module Diagram
<img src="./readme_img/001_module_diagram.PNG" width="70%" style="margin-left: auto; margin-right: auto; display: block;"/>

### 2.2 Block Diagram
<img src="./readme_img/002_block_diagram.PNG" width="70%" style="margin-left: auto; margin-right: auto; display: block;"/>

### 2.3 Block Ports
<img src="./readme_img/003_block_ports.PNG" width="70%" style="margin-left: auto; margin-right: auto; display: block;"/>

## 3. Circuit Schematic
Footprints of resistors R16~20 will be used as solder jumper. Therefore, there is no actual component needed.

<img src="./schematic/schematic.jpg" width="90%" style="margin-left: auto; margin-right: auto; display: block;"/>

## 4. PCB Design
Manufacturer : JLC PCB </br>
Gerber File : ./kicad_proj/output
              (./kicad_proj/pcb_output.zip)

<img src="./pcb/pcb.png" width="40%"/>
&nbsp;&nbsp;
<img src="./pcb/pcb_3d_render.png" width="40%"/>
