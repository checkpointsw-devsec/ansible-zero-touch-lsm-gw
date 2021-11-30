# ansible-zero-touch-lsm-gw
This project demonstrates how to orchestrate large scale deployment of Security Gateway appliances using Ansible modules

## One Time Tasks
The following should be done manually:
In Smart Dashboard: Create LSM Profile (Network Topology, Cluster Members, NAT etc.)


## For Each Gateway
The following is performed automatically by orchestration scripts:
* In Smart Provisioning: 
  * Add LSM Gateway object
  * Establish SIC
  * generate VPN certificate
  * Define VPN topology
  * define dynamix objects
  * Assign SmartProvissioning profile

* In Zero Touch Portal: 
  * Create a template if it does not exist
  * Claiming gateway
  * Assigning template
  * adding specific gateway configuration
