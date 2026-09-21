# Creating VLANs for Project

Note: I wanted to create two separate VLANs for this project just to keep it simple for understanding, HR and IT. Each VLAN (HR and IT) would have three PCs in their respective VLAN, locally connecting to each other through access ports but needs more configuration when it travels from one VLAN to the next using trunk ports over the Layer 3 Switch.

- HR VLAN is under the 20.20.20.0 IP scheme. 

- IT VLAN is under the 20.20.30.0 IP scheme.

# HR VLAN
HR VLAN IPs Include:
- 20.20.20.11/24
- 20.20.20.12/24
- 20.20.20.13/24

# IT VLAN
IT VLAN IPs Include:
- 20.20.30.11/24
- 20.20.30.12/24
- 20.20.30.13/24

# Default Gateways (SVIs on SwitchL3)
HR VLAN:
- 20.20.20.1/24


IT VLAN:
- 20.20.30.1/24
