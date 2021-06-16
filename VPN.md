# VPN (Virtual Private Network)
## What is a VPN
- It is a concept of creating a virtualised private network between two networks
- To secure network traffic between sites and users, organisations use vpns to create an end to end private network connections

### 4 Major Protocols
- PPTP (point to point tunneling protocol)
- GRE (generic route encapsulation)
- L2TP (layer 2 tunneling protocol)
- IPsec (ip security)
- SSL (secure sockets layer)

## How does it work
- Two main functions, tunnelling and encryption
    - Tunnel connects the hosts to communicate
    - Encryption is used to hide the data whilst travelling through the tunnelling
- Creates a virtual connection across the internet that is encrypted
- Connection established through a router, data transfer through the vpn
- Vpn gateway is not on the servers, just on the networks
- Vpn server can run on a vpn gateway, a router and a firewall

When using a vpn for professional purposes, it creates a secure IP for the host to talk to the main site which also has a secure VPN and the communication is encrypted


# Network Address Translation (NAT)
- Helps with IP address shortages (IPv4)
- Translates private address to public addresses
- Can turn many private addresses on one network to one public address
