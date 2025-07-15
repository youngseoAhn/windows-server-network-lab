# DNS adding forwarder 

## DNS manager install
- on powershell use Install-WindowsFeature -Name DNS -IncludeManagementTools

## Run DNS
- open run then type dnsmgmt.msc
- open properties of server 
- on forwarder, add www.google.com as 8.8.8.8