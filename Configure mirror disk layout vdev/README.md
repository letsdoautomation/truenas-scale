# TrueNAS Scale: Configure mirror disk layout vdev

<b>Description:</b>

Data is identical in each disk. A mirror requires at least two disks, provides the most redundancy, and has the least capacity

<b>Requirements</b>

* Atleast 2 disks

<b>Provides:</b>

* Most redundancy
* Least capacity

<b>Sample 1:</b>

<img src="img/mirror_2_drives_1_vdev.png" width=25% height=25%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 1
* Capacity: 8 GB
* Redundancy: 1 drive

<b>Sample 1:</b>

<img src="img/mirror_6_drives_3_vdev.png" width=25% height=25%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 3
* Capacity: 24 GB
* Redundancy: 3 drive