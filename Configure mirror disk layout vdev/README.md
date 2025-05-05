# TrueNAS Scale: Configure mirror disk layout vdev

<b>Description:</b>

Data is identical in each disk. A mirror requires at least two disks, provides the most redundancy, and has the least capacity

<b>Requirements</b>

* Atleast 2 disks

<b>Provides:</b>

* Most redundancy
* Least capacity

<b>Example 1:</b>

<img src="img/mirror_2_drives_1_vdev.png" width=25% height=25%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 1
* Total drives: 9
* Capacity: 8 GB
* Redundancy: 1 drive

<b>Example 2:</b>

<img src="img/mirror_6_drives_3_vdev.png" width=50% height=50%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 3
* Total drives: 6
* Capacity: 24 GB
* Redundancy: 1 drive in each vdev, 3 total

<b>Example 3:</b>

<img src="img/mirror_9_drives_3_vdev.png" width=50% height=50%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 3
* Total drives: 9
* Capacity: 24 GB
* Redundancy: 2 drives in each vdev, 6 total

<b>Example 3:</b>

<img src="img/mirror_8_drives_4_vdev.png" width=50% height=50%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 4
* Total drives: 8
* Capacity: 32 GB
* Redundancy: 1 drive in each vdev, 4 total