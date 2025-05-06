# TrueNAS Scale: Configure mirror layout vdev disk pool

<b>Description:</b>

Data is identical in each disk. A mirror requires at least two disks, provides the most redundancy, and has the least capacity

<b>Requirements:</b>

* Atleast 2 disks

<b>Provides:</b>

* Most redundancy
* Least capacity

<b>Example 1:</b>

<img src="img/mirror_1vdev_2wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 1
* Total drives: 2
* Drive capacity: 8 GB
* Total capacity: 8 GB
* Redundancy: 1 drive

<b>Example 2:</b>

<img src="img/mirror_1vdev_3wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 1
* Total drives: 3
* Drive capacity: 8 GB
* Total capacity: 8 GB
* Redundancy: 2 drives

<b>Example 3:</b>

<img src="img/mirror_2vdev_2wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 2
* Total drives: 4
* Drive capacity: 8 GB
* Total capacity: 16 GB
* Redundancy: 2 drives 1 in each vdev

<b>Example 4:</b>

<img src="img/mirror_3vdev_2wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 2
* Number of VDEVs: 3
* Total drives: 6
* Drive capacity: 8 GB
* Total capacity: 24 GB
* Redundancy: 3 drives 1 in each vdev

<b>Example 5:</b>

<img src="img/mirror_3vdev_3wide.png" width=30% height=30%>

<b>Configuration:</b>

* Width: 3
* Number of VDEVs: 3
* Total drives: 9
* Drive capacity: 8 GB
* Total capacity: 24 GB
* Redundancy: 6 drives 2 in each vdev

# Related videos:

* [TrueNAS Scale playlist](https://www.youtube.com/playlist?list=PLVncjTDMNQ4RKprjwzLtGYUwVLZe6INiH)