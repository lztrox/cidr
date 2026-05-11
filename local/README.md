# What is this?

### These are local IPs that are recommended to bypass in split tunnelling

192.168.0.0/16 - RFC1918 (local network)

172.16.0.0/12 - RFC1918 (local network)

10.0.0.0/8 - RFC1918 (local network)

169.254.0.0/16 - Link-local (Uses to automatically assign an IP in local network ⚠️)

100.64.0.0/10 - Carrier-Grade NAT (May expose your real IP if bypassed ⚠️)

224.0.0.0/4 - Multicast (Uses to find devices in local network)