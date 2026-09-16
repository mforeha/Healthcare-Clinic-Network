# Healthcare-Clinic-Network
 a small healthcare clinic network in Cisco Packet Tracer with VLAN segmentation, inter-VLAN routing, DHCP, a clinic server, and troubleshooting.

## Objectives
- Segment departments using VLANs
- Configure router-on-a-stick
- Configure DHCP
- Configure trunking
- Test connectivity
- Troubleshoot a deliberately broken network

## VLANs
| VLAN | Name | Network |
|---|---|---|
| 10 | ADMIN | 192.168.10.0/24 |
| 20 | CLINICAL | 192.168.20.0/24 |
| 30 | GUEST | 192.168.30.0/24 |
| 40 | SERVERS | 192.168.40.0/24 |
| 99 | MGMT | 192.168.99.0/24 |


## Technologies
- Cisco IOS
- VLANs
- 802.1Q trunking
- Router-on-a-stick
- DHCP
- IPv4
- Basic network troubleshooting
  
## Verification
Document successful pings and relevant `show` commands.


## Troubleshooting
Describe the intentional VLAN misconfiguration:
1. Symptom
2. Evidence collected
3. Root cause
4. Corrective command
5. Verification

## Files
- Packet Tracer topology
- Addressing plan
- Configuration notes
- Screenshots
