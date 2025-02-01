# Hardened custom image

## Additions
* Nftables wireguard killswitch

## Get started
* Killswitch
  * Activate a wireguard VPN.
  * Set or allow the port(s) in /etc/nftables.conf to correspond with the port(s) you're using to connect to the VPN.
  * wg0 is the default interface, you may change it.
  * run ```systemctl enable nftables```
