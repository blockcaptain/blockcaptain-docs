## Features

* **Custom Installation Media Creator** - Boot from USB media to a fully installed system with no user interaction.

### Why use BlockCaptain?

You agree with the principles above. You enjoy learning and using Linux. You want a general purpose server to easily run VMs and/or containers. 
You want to have a deep understanding and closeness to the software that is protecting your precious data.

### Why not use BlockCaptain?

You don't want to use Ubuntu[^1]. You want to use ZFS. You want a simple appliance with a web interface and you don't care how it works underneath.

## Principles

BlockCaptain NAS is not an appliance. Some things are automated, but very little effort
is made to hide or "abstract away" the system. The interface is the CLI via SSH. 

The system must be low maintenance and run securely for many years. [Ubuntu 20.04](https://ubuntu.com/about/release-cycle) will receive security updates
via [ESM](https://ubuntu.com/esm) until April 2030. ESM is available [free for personal use](https://ubuntu.com/advantage) or for a nominal fee for commerical use. 
Ubuntu also has kernel [Livepatch Service](https://ubuntu.com/livepatch) to address security issues without reboots, also free for personal use.

## Related Tools

In the future, when there is ZFS support, BlockCaptain should complement [ZSys](https://github.com/ubuntu/zsys).

## Inspirations

* Regolith Linux
* Arch Wiki

## Alternative Servers

BlockCaptain NAS has some intersecting functionality with the following servers. BlockCaptain NAS has significantly less out-of-the-box functionality. 
However, because its foundation is Ubuntu, it's very easy to build upon. And because its core componenent is BlockCaptain it does have strong data integrity capabilities.

* [FreeNAS](https://www.freenas.org/) (Python/FreeBSD)
* [Rockstor](http://rockstor.com/) (Python/OpenSUSE)
* [OpenMediaVault](https://www.openmediavault.org/) (PHP/Python/Debian)

[^1]: Changes to support Debian are welcome. See [Contributing](/development/contributing.md).
