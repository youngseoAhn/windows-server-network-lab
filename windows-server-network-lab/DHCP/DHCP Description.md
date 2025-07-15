# DHCP Process and result 

## Command to install 
- Install-WindowsFeature -Name DHCP -IncludeManagementTools

## Progress with DHCP set up 
- open run
- type dhcpmgmt.msc
- click IPv4, check actions then click new scope
- add default gateway "192.168.100.1"
- for DHCP server scope(address range) start to 192.168.100.100 to 192.168.100.200
- check on VM-Side to check if it applied with ipconfig

## Result
- IP address received to 192.168.100.100
- Default gateway is 192.168.100.1


