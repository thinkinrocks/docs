_The Thinkin' Rocks* documentation repository!_

This is the documentation of how things are set up at TR: services, bots, networks, tech and everything related.

## Changelog

- *2026-02-06*. **Changed docs.thinkin-rocks.local to serve from a static directory**. Now there isn't an extra webserver running for serving static files.
- *2026-02-06.* **Added a changelog to the docs page!**
- *2026-02-05.* **Changed the IP address of Kanboard**, now moved from `133.7.0.69:8080` to `133.7.0.69:8084`.
- *2026-02-05.* **Added DNS query support to the VPN.** There is a DNS proxy running on 192.168.0.2. It forwards the requests to the actual DNS server at 133.7.0.1 with stripped [eDNS](https://en.wikipedia.org/wiki/Extension_Mechanisms_for_DNS) since Windows Server 2008 doesn't support it. You can add `DNS = 192.168.0.2` to the Wireguard configuration.
