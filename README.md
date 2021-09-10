# Move an Azure VM into a specific zone

The script does not move VM extensions or any identities assigned to the Virtual Machine.
Also, the script will not work for VMs with public IP addresses. 
Remove these upfront manually.

# Example:

```ps1

./move-vm-to-zone.ps1 -SubscriptionName "Azure Subscription Name" -ResourceGroupName <RG> -VirtualMachineName <VM> -ZoneNumber <x> 

```
