# AzureTemplates
Repository of Azure Templates

## Created by: Tom Peffers 
* Contact: Tom@HyperSystemsTech.com

### Azure_Network_Deploy_PAN_v4-0
* Is currently stable
* Is suitible for deployment via Visual Studio or template deployment within an Azure subscription. 
* Is currently configured to only deploy using a /21 or larger Azure subnet for the virtual network. 
* Deploys stanardized  3 tier firewall deployment, Virtual network, an NSG for control of magement interfaces, as well as other resources for High Availability. 
* CopyLoop's determine how many firewalls & underlying infrastructure will be deployed per tier. See code notes for more info. 
* Missing CSV input file
* Missing PowerShell script to deploy template using csv input. 
* Need to remove internal load balencer from Tier 1
* Needs testing
* Palo alto vms need to be configured still. Note Configuration of Firewalls is not a part of this deployment template. 
* Should add feature to encrypt disks for VMS as well as for the storage accounts upon creation.


Please submit feature request or report any issues to the contact email above. 

## This is an experimental deployment template. Please use at own risk. This was developed on my spare time to test out a project deployment design created by: Roger Schotsal at Palo Alto.
The purpose of uploading this to my personal github account was to provide access for others to collaborate on the project, provide input, and to have a single source for the code repository. 

Thanks,
Tom Peffers  

________________________________________________________________________________


