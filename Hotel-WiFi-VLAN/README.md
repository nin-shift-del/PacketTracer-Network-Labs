Scenario / Problem:
- Building: 3 floors (Lobby, Guest Rooms, Staff Offices)

MDF / IDF Setup:
- MDF: 1st floor (Lobby) → Main router + core switch
- IDF: 2nd & 3rd floor → Floor switches
  
Devices per floor:
- Each floor: 1 switch, 2 APs, 4–6 clients

VLANs:
- VLAN 10 → Staff
- VLAN 20 → Guests

IP Scheme Example:
- Staff: 192.168.10.0/24
- Guests: 192.168.20.0/24

Tasks:
- Configure VLANs on all switches and trunk links to MDF
- Configure APs with correct SSID & VLAN tag
- Assign switch ports to VLANs
- Test connectivity for clients in same VLAN and across floors
- Troubleshoot scenario: AP on 3rd floor not connecting
