# Gluster Community Meeting - 09/11/2021


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Saju Mohammed (Red Hat)
* Pranith Kumar K (PhonePe)
* Nikhil Ladha - Red Hat
* Rakshitha Kamath (Red Hat)
* Ravishankar (Pavilion Data)
* Sheetal pamecha (Red Hat)
* Sunil Kumar (Red Hat)
* Shwetha Acharya (Red Hat)

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 19 (19)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   87 (87)  |
|[Line coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     70.7% (70.9 %) |
|[Function coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     84.8 (85.1%) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-October/thread.html)        |     6      |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |  266     |


* Any release updates?
      
    * Gluster 10 - Tcmalloc has build issues with other architectures
        * We will be enabling tcmalloc with x86_64 architecture only. Release will be happening this week.

* Blocker issues across the project?
    * https://github.com/gluster/glusterfs/pull/2931

* User stories / Notable thread from the mailing list
    * 


### Conferences / Meetups
* None


### GlusterFS - v11 and beyond
*   Please tag new improvements/issues to Gluster 11 milestone in github.


### Developer focus
* Glusterd hangs on updating the max-port range after updating port-mapper logic in Gluster-X
    * Issue link: https://github.com/gluster/glusterfs/issues/2910


### Component status
* Arbiter - stable/maintained
* AFR - stable/maintained
* DHT - stable/maintained
* EC - stable/maintained
* DOC - stable/maintained
* Geo Replication - stable/maintained
* Glusterd - stable/maintained
* thin-arbiter - stable/maintained



### Recent Blog posts / Document updates

* Scaling a read-intensive, low-latency file system to 10M+ IOPs https://www.hpcwire.com/solution_content/aws/scaling-a-read-intensive-low-latency-file-system-to-10m-iops/
* scale-out file/block/object HCI software https://blocksandfiles.com/2021/10/28/ixsystems-open-sourcery-scale-out-file-block-object-hci-software/
* 


### Host

* Who will host the next meeting? [Nikhil]
* 
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Nikhil]



### RoundTable
* Geo-rep help on upstream
* Fuse Sessions next week


### Action Items on host
* Check-in Minutes of meeting for this meeting
