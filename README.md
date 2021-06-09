# DDK_ARP_tool
* It is an ARP tool for consistent attack.
* I will implement it someday.

# Features
* light

# Behaviors
* If the MAC address is not found in the ARP table, then...
* Send packet to get the remote PC's mac address.
* Send ARP packet consistently forever even if the net stuffed.
* arp -n
* Total length of ethernet head plus arp packet is 42 octets.
* Put this particular format of data to a buffer and send it.
* So easy.

# Refrences
* https://en.wikipedia.org/wiki/Address_Resolution_Protocol
