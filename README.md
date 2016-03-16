# cloudstack-cloudzor
Cloudzor is a bash script to create, start, stop and destroy a large number of VM in CloudStack for testing purposes.

##Capabilities
* stats - Display VMs stats
* startall - Start all VMs of the current account
* stopall - Stop all VMs of the current account
* destroyall - Destroy all VMs of the current account
* destroyerror - Destroy all VMs in error state
* create n - Create n VMs on the current account
* list - List Zone, Templates, Service Offerings, and Networks
* cluster - List Clusters and Hosts
* capacity - Show CloudStack Capacity

##Setup
1. Just install CloudMonkey and configure your CloudStack account.
2. chmod +x cloudzor.sh
3. If you want to create VM with Cloudzor, edit cloudzor.sh and modify the new VM variables section to feet your system.
(You can see all needed service offering with "./cloudzor.sh list")
