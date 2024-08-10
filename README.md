# NeoMem-MICRO-2024
The Artifact of  NeoMem: Hardware/Software Co-Design for CXL-Native Memory Tiering. This project is developed on Intel's CXL FPGA platform 


## Overview


[1. Introduction](#1-introduction)  
[2. Hardware Requirements](#2-system_setup)
[3. Installation](#3-installation)  
[4. Run Experiments](#4-experiments) 
[5. Check Results](#5-checkresults)

## 1. Introduction

NeoMem project consists of three submodules: [NeoMem_FPGA](), [linux]() and [experiments](). `NeoMem_FPGA` contains the FPGA code of NeoProf. The `linux` folder contains NeoMem's host-side driver, daemon and user-space interface implementation. You can find some  click-to-run scripts in the `experiments` folder, which helps you reproduce the main results of NeoMem paper. 


## 2. Hardware and Software Requirements

Here are the hardware and software setups used in NeoMem:
1. Supermicro SYS-741GE-TNRT platform
2. Intel Agilex-7 I series FPGA Dev Kit @400Mhz
3. 32GB DDR5 4800Mhz DRAM x4
4. Single Socket Xeon 4th 6430 CPU @ 2.1GHz
5. Quartus 22.3 with CXL 1.1 IP

## 3. Installation 

## 4. Run Experiments 

## 5. Check Results
