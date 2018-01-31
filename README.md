# Hyper-V Management Pack Extensions 2012 / 2012 R2
Management Pack to monitor the performance of your Hyper-V 2012 and 2012 R2 Servers and Clusters. Requires SCOM 2012 RTM or higher. SCOM 2012 SP1 recommended.

## Project Description
Management Pack to monitor the performance of your Hyper-V 2012 and 2012 R2 Servers and Clusters. Requires SCOM 2012 SP1 or higher.

## New features on release 1.0.1.282
* Support for Windows Server 2012 R2 hyper-V
* Hyper-V Extended Replica Monitoring and Dashboard
* Minor code optimizations 

## Features on release 1.0.1.206 
* VMs Integration Services Version monitor 
* Hyper-V Replica Health Monitoring Dashboard and States 
* SMB Shares I/O latency monitor 
* VMs Snapshots monitoring 
* Managment Pack Performance improvements

## Included features from previous release
* Hyper-V Hypervisor Logical processor monitoring
* Hyper-V Hypervisor Virtual processor monitoring
* Hyper-V Dynamic Memory monitoring
* Hyper-V Virtual Networks monitoring
* NUMA remote pages monitoring
* SLAT enabled processor detection Hyper-V VHDs monitoring
* Physical and Logical Disk monitoring
* Host Available Memory monitoring
* Stopped and Failed VMs monitoring
* Failed Live Migrations monitoring

## Requirements
SCOM 2012 SP1 UR4
Management Packs:
* Windows OS Management Pack 6.0.7061.0 or higher: http://www.microsoft.com/download/en/details.aspx?id=9296
* System Center 2012 Management Pack for Windows Server Hyper-V 2012 6.2.6641.0 or higher: http://www.microsoft.com/en-us/download/details.aspx?id=36438 
* System Center Management Pack for Windows Server Cluster 6.0.7063.0 or higher: http://www.microsoft.com/download/en/details.aspx?id=2268

## Additional information
Physical and Logical disk monitoring is based on the new OS MP monitors CSV monitoring is based on the new OS MP monitors. The configured thresholds on the monitors should cover most common scenarios but you may need to tune some of them to cover your own needs.

## This MP is provided “as is” without any official support from Microsoft.
