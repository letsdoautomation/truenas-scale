# TrueNAS Scale: Configure RAIDZ1 layout vdev disk pool

<b>Description:</b>

Uses one disk for parity while all other disks store data. RAIDZ1 requires at least three disks. RAIDZ is a traditional ZFS data protection scheme.

<b>Requirements:</b>

* Atleast 3 disks

<b>Provides:</b>

* Least redundancy per vdev compared to other RAIDZ layouts
* Most capacity per vdev compared to other RAIDZ layouts

<b>Example 1:</b>

<img src="img/raidz1_1vdev_3wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 1
* Total drives: 3
* Drive capacity: 8 GB
* Total capacity: 16 GB
* Redundancy: 1 drive

<b>Example 2:</b>

<img src="img/raidz1_1vdev_4wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 4
* Number of VDEVs: 1
* Total drives: 4
* Drive capacity: 8 GB
* Total capacity: 24 GB
* Redundancy: 1 drive

<b>Example 3:</b>

<img src="img/raidz1_2vdev_3wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 2
* Total drives: 6
* Drive capacity: 8 GB
* Total capacity: 32 GB
* Redundancy: 2 drives total, 1 drive per vdev

<b>Example 4:</b>

<img src="img/raidz1_3vdev_3wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 3
* Total drives: 9
* Drive capacity: 8 GB
* Total capacity: 48 GB
* Redundancy: 3 drives total, 1 drive per vdev

<b>Example 5:</b>

<img src="img/raidz1_3vdev_4wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 4
* Number of VDEVs: 3
* Total drives: 12
* Drive capacity: 8 GB
* Total capacity: 72 GB
* Redundancy: 3 drives total, 1 drive per vdev

# Related videos:

* [TrueNAS Scale playlist](https://www.youtube.com/playlist?list=PLVncjTDMNQ4RKprjwzLtGYUwVLZe6INiH)