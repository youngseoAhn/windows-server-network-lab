# Setting up RRAS and check if VM-Side can get connection through VM-Main

# Install RRAS
- on powershell type Install-WindowsFeature -Name RemoteAccess -IncludeManagementTools
- also type Install-WindowsFeature -Name Routing

## Set up RRAS
- open run then type rrasmgmt.msc 
- on local server device click Configure and Enable Routing and Remote Access
- Check both NAT and LAN and finish configuration
- then On IPv4, Click NAT and click new Interface
- on NAT Click public interface connected to internet, enable NAT on this interface
- also, on adding network address translation properties, check on Private interfaces connected to private network

## Setup Result
- ping 8.8.8.8 from VM-Side completed 