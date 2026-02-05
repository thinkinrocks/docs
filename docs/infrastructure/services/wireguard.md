# Wireguard

Wireguard is a good open-source libre VPN. It is very general and supports various configuration.

Right now it's used to grant access to the Thinkin' Rocks LAN.

- It routes packets to `133.7.0.0/24`, the LAN.
- It routes packets to `192.168.0.0/24`, the overlay network with all Wireguard peers.
- It routes packets to `224.0.0.251` and `ff02::fb:5353` because of `mDNS`.

_Managed by Artur._
