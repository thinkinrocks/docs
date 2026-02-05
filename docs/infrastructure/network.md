Our on-site network is `133.7.0/24`, so all of the physical machines reside within it. All of the relevant devices are available under `*.thinkin-rocks.local`.

The TLD of the network is `.local` which _technically_ is only inteded for mDNS, but we use it for all machines and route it on our DNS server. Yes, it is intentional.

We also have a piece of network available over WAN at `wg.thinkinrocks.com`. It lets the users into the overlay network `192.168.0.0/24`. It consists of a WAN server and a LAN server. The Wireguard client connects to the WAN server and all of their data is proxied to the LAN.

Also, it is accessible via [Wireguard](./services/wireguard.md).
