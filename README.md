# EPOS4_Two_Motor_Run
This repository contains source code to run two motors simultaneously using two EPOS4 controllers in current control mode 
- This is a code developed by editing the demo code provided by maxongroup for their EPOS4 motor controller
- The code has been modified for maxon EC 90 Flat BLDC motor, but can be easily customised for any other EPOS4 compatible motor
- The code can only be used to run two motors simultaneously using two EPOS4 controllers connected to the PC via USB
- The code runs the motors in CurrentMode, where a target current is specified by the user. Before running the code, it is recommended
to tune the PID gains for the motor using the EPOS Studio (see EPOS4 manual for more informaion: 
https://www.maxongroup.com/medias/sys_master/root/8837359304734/EPOS4-Application-Notes-Collection-En.pdf)
