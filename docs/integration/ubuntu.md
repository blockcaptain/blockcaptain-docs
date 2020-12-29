Ubuntu provides an ideal foundation for a do-it-yourself NAS setup. Ubuntu LTS can run securely with low maintenance for many years. 
[Ubuntu 20.04](https://ubuntu.com/about/release-cycle) will receive security updates via [ESM](https://ubuntu.com/esm) until April 2030. 
ESM is available [free for personal use](https://ubuntu.com/advantage) or for a nominal fee for commerical use. Ubuntu also has kernel 
[Livepatch Service](https://ubuntu.com/livepatch) to address security issues without reboots, also free for personal use.

## BlockCaptain NAS

The [BlockCaptain NAS Media Creator](https://github.com/blockcaptain/blockcaptain-nas) can be used to seed a Ubuntu-based NAS. The media 
can be pre-configured to fully install a system with no user interaction.

## ZSys

In the future, when there is ZFS support, BlockCaptain will complement [ZSys](https://github.com/ubuntu/zsys).

## LXD

LXD on Ubuntu a good complement to application (OCI/Docker) containers. LXD runs system (LXD) containers and full virtual machines (QEMU).

*TODO* backing up with blkcapt.
