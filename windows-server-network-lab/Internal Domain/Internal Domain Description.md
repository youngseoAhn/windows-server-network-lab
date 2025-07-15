# Internal Domain Description

## Setting up Internal Domain
- On DNS Manager 

## Run DNS
- open run then type dnsmgmt.msc
- create new zone 
- create forward lookup zone
- set zone name as internal.local
- on new host, name as "web" IP address as 192.168.100.1 (VM-Main)
- for new host client, set name as client
- set ip address as 192.168.100.100 (address given to VM-Side with DHCP)

## Result after setting up Internal Domain 
- ping 192.168.100.1 from VM-Side complete
- ping web.internal.local from VM-Side complete
- ping client.internal.local from VM-Side complete