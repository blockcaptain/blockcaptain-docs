About the design.

## Principles

Rigerously evaluate and mitigate failures modes which may lead to data loss. The probability of major data loss should be close to 0%. Every risk that can be reasonably mitigated should be: e.g. silent data corruption ([bitrot](https://en.wikipedia.org/wiki/Data_degradation)), malicious data corruption, complete failure of 1, 2 or all physical disks, an unrecoverable data bug in the cloud backup tool, or forgetting to pay the bill on your cloud storage. 

## Alternative Tools

BlockCaptain has some intersecting functionality with the following tools. These tools are not full alternatives to BlockCaptain, nor is BlockCaptain a superset of these tools.

### Btrfs

* [btrbk](https://github.com/digint/btrbk) (Perl) - Snapshot management and send/receive snapshots.
* [Btrfs Maintenance](https://github.com/kdave/btrfsmaintenance) (Bash) - Automate btrfs filesystem maintenance.
* [btrfs-sxbackup](https://github.com/masc3d/btrfs-sxbackup) (Python) - Send/receive snapshots.
* [buttermanager](https://github.com/egara/buttermanager) (Python) - Snapshot management and filesystem maintenance.
* [Snapper](http://snapper.io/) (C++) - Snapshot management.

### ZFS

There is no ZFS support in BlockCaptain today. The following tools support ZFS snapshot management.

* [pyznap](https://github.com/yboetz/pyznap) (Python) - ZFS Snapshot management and send/receive snapshots.
* [Sanoid](https://github.com/jimsalterjrs/sanoid) (Perl) - ZFS Snapshot management and send/receive snapshots.
* [ZnapZend](https://www.znapzend.org/) (Perl) - ZFS Snapshot management and send/receive snapshots.
* [zrepl](https://zrepl.github.io/) (Go) - ZFS Snapshot management and send/receive snapshots.
