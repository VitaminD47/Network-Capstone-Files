This directory is for all WGU instructors needing to evaluate Task #2.
Everything that is required pertaining to device configurations is in this folder. 
The only exception would be static IP's of servers. They can be manually set according to the topology screenshot as needed.

# Important topology note : When adding OPNSense firewalls to topology for testing, create them with 4 network interfaces and set the adapter type to Paravirtualized Network I/O virtio-net-pci. If this isn't done, they will not behave normally as GNS3 doesn't seem to like their default ethernet interfaces.

