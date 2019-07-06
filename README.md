Setup:

# Master Kamailio Node
k1.0x300.de - alpine
  eth0 dhcp, eth1 10.10.10.1 / netmask 255.255.255.0 no gateway

# Slave Kamailio Node
k2.0x300.de - alpine
  eth0 dhcp, eth1 10.10.10.1 / netmask 255.255.255.0 no gateway

# Controller / DB-Host
strg.0x300.de - alpine (controller) (optional)
  eth0 dhcp, eth1 10.10.10.253 / netmask 255.255.255.0

