# TrueNAS Scale: Configure RAIDZ2 layout vdev disk pool

<b>Description:</b>

Uses two disks for parity while all other disks store data. RAIDZ2 requires at least four disks. RAIDZ is a traditional ZFS data protection scheme.

<b>Requirements:</b>

* Atleast 4 disks

<b>Provides:</b>

* Medium redundancy per vdev compared to other RAIDZ layouts
* Medium capacity per vdev compared to other RAIDZ layouts