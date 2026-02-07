_The Thinkin' Rocks* documentation repository!_

## Pages

- [`kanboard.thinkin-rocks.local`](https://kanboard.thinkin-rocks.local), a [Kanban](https://en.wikipedia.org/wiki/Kanban) board for tracking our tasks and progress.
- [`git.thinkin-rocks.local`](https://git.thinkin-rocks.local), a Gitea instance for hosting our runners and git repositories.
- [`secrets.thinkin-rocks.local`](https://git.thinkin-rocks.local), our Vaultwarden instance where we keep all our secrets.
- [`docs.thinkin-rocks.local`](https://docs.thinkin-rocks.local), the central point where we try to document everything.
- [`files.thinkin-rocks.local`](https://files.thinkin-rocks.local), a small shared file services for any general-purpose files that need to be accessible from all devices.


## Changelog

- *2026-02-07*. **Added a local Gitea instance.** Now hosted at `git.thinkin-rocks.local`.
- *2026-02-06*. **Changed docs.thinkin-rocks.local to serve from a static directory**. Now there isn't an extra webserver running for serving static files.
- *2026-02-06.* **Added a changelog to the docs page!**
- *2026-02-05.* **Changed the IP address of Kanboard**, now moved from `133.7.0.69:8080` to `133.7.0.69:8084`.
- *2026-02-05.* **Added DNS query support to the VPN.** There is a DNS proxy running on 192.168.0.2. It forwards the requests to the actual DNS server at 133.7.0.1 with stripped [eDNS](https://en.wikipedia.org/wiki/Extension_Mechanisms_for_DNS) since Windows Server 2008 doesn't support it. You can add `DNS = 192.168.0.2` to the Wireguard configuration.
- *2026-02-04.* Now tracking the Changelog!
