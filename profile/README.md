<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dark.svg">
    <img src="logo-light.svg" alt="Nebla" height="56">
  </picture>
</p>

<p align="center">
  An open-source cloud console for Proxmox VE.
</p>

Nebla lets you create, resize and rebuild VMs from a clean panel or the `nebla` CLI. It runs as one Docker container next
to Proxmox, talks only to the Proxmox API, and installs nothing on the host. Projects, quotas and tenant isolation are
built in, so it works for a single homelab box and for hosting customers on your own clusters.

The core is AGPL-3.0, free, with no limit on nodes.

| Repository | What's in it |
| --- | --- |
| [nebla](https://github.com/nebla-cloud/nebla) | The panel, REST API and CLI |
| [nebla-site](https://github.com/nebla-cloud/nebla-site) | The source of [nebla.dev](https://nebla.dev) |

Start with the [install guide](https://nebla.dev/install), read the [docs](https://nebla.dev/docs), or ask in
[Discussions](https://github.com/nebla-cloud/nebla/discussions). Contributions are welcome: see
[CONTRIBUTING.md](https://github.com/nebla-cloud/nebla/blob/main/CONTRIBUTING.md).
