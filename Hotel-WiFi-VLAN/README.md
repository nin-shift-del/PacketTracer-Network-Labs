Scenario / Problem:
- 3-floor hotel: Lobby, Rooms, Staff Office

Devices: 
- 3 switches, 6 APs, 12 clients, 1 router

VLANs:
- VLAN 10 → Staff network
- VLAN 20 → Guest network

IP Scheme (example):
- Staff: 192.168.10.0/24
- Guests: 192.168.20.0/24

Tasks:
- Configure switches for VLANs and trunking
- Assign ports to VLANs
- Configure APs with correct SSIDs (Staff vs Guest)
- Test connectivity between devices in same VLAN
- Troubleshoot a scenario where one AP cannot connect
