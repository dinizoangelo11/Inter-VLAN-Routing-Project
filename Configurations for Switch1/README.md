# Switch1 Configuration

## VLAN Setup
<img width="461" height="130" alt="Screenshot 2026-09-21 085807" src="https://github.com/user-attachments/assets/12050c42-84c9-414b-9a6a-ffe83cc9a6c2" />

- Need to go into global configuration mode to make changes to the configs
- Naming the Switch so there is no confusion
- Naming VLAN 2 as HR
- Naming VLAN 3 as IT



## Enabling Access Ports
<img width="313" height="134" alt="Screenshot 2026-09-21 085817" src="https://github.com/user-attachments/assets/0f76c683-2b55-459d-9833-b6188844b1e8" />

- Go into each interface one by one
- Enable each interface as an access port (access port carries traffic from the same VLAN over a switch)
- Assign that specific port for the VLAN it will be in (int0/1 will be in VLAN 2 because that is an HR computer)



## Enabling Trunk Port to SwitchL3
<img width="650" height="134" alt="Screenshot 2026-09-21 085825" src="https://github.com/user-attachments/assets/1e34e6ca-c2b7-4d1b-bbf0-653d6cbfd516" />

- Go into the gigabit interface that is connected to SwitchL3 (g0/2)
- Enable port as trunk port (trunk port carries traffic to different VLANs)
- I created a description to remind me that it connects to the Layer 3 Switch
