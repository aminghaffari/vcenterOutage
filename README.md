# vcenterOutage
ESXi host scanner script for VM discovery during vCenter outages

This PowerShell script scans an IP range to find reachable
ESXi hosts when vCenter is unavailable.

It connects to each detected ESXi host using VMware PowerCLI
and retrieves the list of virtual machines.

The script displays VM names and their ESXi host location
to help administrators during outages or troubleshooting.

Designed as a lightweight VMware recovery and inventory tool.
