# Long List of DNS servers
This repository contains various lists of different types of DNS servers. I've provided both IPv4 and IPv6 lists for each of the DNS server types listed below:
- Regular DNS servers - 5785 DNS Servers
- DoH/DoT DNS servers - 68 DNS Servers
- Regular & DoH/DoT DNS server - 5816 DNS Servers

## Note:
I've chosen to combine the DoH (DNS over HTTPS) and DoT (DNS over TLS) lists into one list. This is because the primary purpose of this list is to block general DoH/DoT servers in firewall rules to disallow cases of devices attempting to bypass network applied DNS servers such as a Pi-Hole DNS filter. It would also be fairly redundant to separate the lists as most support both DoH and DoT.
