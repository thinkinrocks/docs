# Backups

Backups are hosted using `restic` on 2 ZFS raid drives. Restic encrypts all the data so the individual backups are not accessible without a password. The partition is called `/mnt/tank`.

The backups job is set up to run regularly at night using `root`'s `cron`.

## Maintenance 

- `cron
