# Futur-Tech Zabbix Monitoring Template for VMware ESXi
Custom Template for VMware ESXi

Modification Futur-Tech:
- Item "VMware: Full name" modified to decrease heartbeat. Needed for trigger.
- Modified LLD rules for Hypervisors and VMs
- Disable: Discover VMware hypervisors
- Disable: Discover VMware VMs
- Disable: vmware.fullname[{$VMWARE.URL}]

Added templates:
- **Template Futur-Tech Module VMware ESXi Port Monitoring:** this template is to monitor open port on ESXi hypervisor. It use the agent interface IP address.