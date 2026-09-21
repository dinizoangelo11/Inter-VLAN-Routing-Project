# SwitchL3 Configuration


## Setting up IP Routing and VLANs
<img width="440" height="172" alt="SwitchL3 Routing and VLANs" src="https://github.com/user-attachments/assets/04c5196c-dd07-4535-aa08-ca3dfd4b148c" />

- enabling IP Routing on the Layer 3 Switch (if you don't enable it, it will not route any traffic)
- same as other switches, set up both VLAN 2 and VLAN 3 on this Switch


## Setting up Trunk Ports for Both Links
<img width="423" height="134" alt="SwitchL3 Trunk Port Config" src="https://github.com/user-attachments/assets/36e08cce-8327-4b7d-aae8-7747ac8d011b" />

- go into each interface and set it as a trunk port
- Implemented the 'switchport trunk encapsulation dot1q'. On older Cisco switches, this had to be specified prior to configuring the interface as a trunk port using 'switchport mode trunk'
- I again created descriptions for both to make it easier for future troubleshooting

## Adding IP Addresses for Each VLAN
<img width="570" height="247" alt="SwitchL3 IP Address for VLANs Config" src="https://github.com/user-attachments/assets/f553e609-bcc6-417f-a716-eb20227d7875" />

- I have to set IP Addresses for each VLAN so the PCs in the VLAN know what gateway to access
- Added no shutdown to both VLAN interfaces to ensure interfaces stay up
