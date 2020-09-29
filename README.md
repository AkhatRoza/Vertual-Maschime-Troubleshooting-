# Vertual-Maschime-Troubleshooting-
VM problem with Guard and HyperV
This rep will help you fix your VM 

Use the commands via coammad line as the administrartor aafer that you can desible Guard via path 


HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\DeviceGuard
Create a new value with the name EnableVirtualizationBasedSecurity. Assign the value data “0” 

HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\LSA
Create a new DWORD value with the name LsaCfgFlags. To disable this component, assign the value data “0”.
