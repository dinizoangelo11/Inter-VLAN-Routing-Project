# Switch A Configuration

### VLAN setup
<img width="461" height="129" alt="Screenshot 2026-09-17 143343" src="https://github.com/user-attachments/assets/02f66711-49e8-4f17-82b3-de0010af6ac7" />

- Need to go into global config mode
- Naming VLAN 2 as HR
- Naming VLAN 3 as IT
  
### Enabling Access Ports
<img width="371" height="121" alt="Screenshot 2026-09-17 143359" src="https://github.com/user-attachments/assets/8e47594d-23a3-4e77-8602-d038a7ab75bd" />

- Go in each interface one by one
- enable each interface as an access port (access port carries traffic from the same VLAN over a switch)
- assign that specific port for the VLAN it will be in (int f0/1 will be in VLAN 3 because that will be an IT computer)
  
### Enabling Trunk Port to SwitchL3
<img width="668" height="131" alt="Screenshot 2026-09-17 143551" src="https://github.com/user-attachments/assets/a2a23fc0-004b-40f5-ab41-bd08d2ee7fbf" />
- Go into the gigabit interface that is connected to SwitchL3
- Enable port as a trunk port (trunk port carries traffic to different VLANs)
- I created a description to remind me that it connects to the Layer 3 Switch
- Added 'no shut' so the port never shuts down
