# lab-temp
This is a temporary repo for getting the lab started. Eventually each section will have its own repo.


## Lab Overview
This homelab aims to teach myself and others how to install and manage various enterprise services commonly used in the real world. Such as but not limited to:
- Active Directory
- Exchange
- ADFS
- vCenter
- Horizon
- Splunk
- Elastic Stack
- Linux Management
- Windows Management
- Networking
- Storage
- Kubernetes
- Docker


## Lab Hardware
- Dell R710
  - 2x Intel Xeon X5670
  - 48GB DDR3
  - 4x 4TB HDD
  - 1x 120GB SSD
- Dell R420
  - 2x Intel Xeon E5-2430
  - 128GB DDR3
  - 6x 400GB SSD
- HP Switch
  - 24 Port Gigabit
  - 4 Port 10Gbe


## Virtualization
### VMware vSphere Version 8.0
VMware vSphere, vCenter, and ESXi will be used to host most of the lab. Each bare metal server will run ESXi and be managed by vCenter. The vCenter server will be a VM running on the R710. The R420 will be used for the majority of the VMs.
