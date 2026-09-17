# Layer-3-Switch-VLAN-Project
Created a VLAN between the IT and HR departments. In between both Layer 2 switches is a Layer 3 switch to route traffic from one VLAN to the other. In this lab I am configuring access ports, trunk ports, creating two separate VLANS with two different IP subnets, and testing my connectivity once configured.


# Lab Topology
<img width="1000" height="392" alt="Screenshot 2026-09-17 140116" src="https://github.com/user-attachments/assets/045cc259-594b-440f-a1e6-4bae569342d0" />



- Switch 0 and Switch 1 are Layer 2 Access Switches
- Multilayer Switch 0 is a Layer 3 Switch
- G0/1 Port on Switch 0 connects to G0/1 Port on SwitchL3
- G0/2 Port on Switch 1 connects to G0/2 Port on SwitchL3
