# Windows Server Network Lab

This repository is a portfolio for Network Practices on Windows Server Environment.
I set DHCP, DNS, NAT(RRAS), File Share, and Internal Domain.

## VM Composition

- MAIN VM
	- IP: 192.168.100.1
	- Roles: DHCP, DNS, NAT, File Server

- SIDE VM
	- Assigned to IP automatically by DHCP

Major components of practices

1. DHCP Scope set up and checking IP assigned to SIDE VM
2. Set up for DNS Zone
3. Setting up NAT and RRAS to connect internet on SIDE VM 
4. Create Internal Domain and File share 

## Test Result
- 'ping client.internal.local' successful 
- 'ping 8.8.8.8' NAT connection ping successful 

## Included screenshot result
- Attached screenshots of process and explanation with result

## Virtual environment information 
- Windows Server 2019
- Hyper-V VM (VM-Main, VM-Side)
- 2GB Memory