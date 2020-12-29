# Recovery

Planning for recovery with BlockCaptain.

## File Modification or Deletion

* Identify changes with diffing btwen snapshots.
* Restore files from earlier snapshosts on data or backup disks.
* or Swap back to old snapshot.

## Data Filesystem Degraded

Insert new disk. Btrfs replace.

## Backup Disk Failures

Init new. Btrfs send/rcv from main to backup.

## Data Filesystem Failure

Init new. Btrfs send/rcv from backup to main.

## Operating System Filesystem Failure

* Reinstall fresh. Run OS restore cmd.
* or.. restore full os backup from live media

## NAS Burst in to Flames

Full Reinstall. Pull from cloud backups.