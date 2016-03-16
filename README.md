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
1. Install [CloudMonkey](https://github.com/apache/cloudstack-cloudmonkey)
2. Configure your CloudStack account in CloudMonkey
3. Configure CloudMonkey table display (add a line "display = table" in .cloudmonkey/config, or "set display table" in cli)
4. chmod +x cloudzor.sh
5. If you want to create VM with Cloudzor, edit cloudzor.sh and modify the new VM variables section to feet your system. (You can see all needed service offering with "./cloudzor.sh list")
6. ./cloudzor.sh
