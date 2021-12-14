# Gluster Community Meeting -  14/12/2021


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
* Amar Tumballi (kadalu.io)
* Rakshitha Kamath (Red Hat)
* Sheetal Pamecha (Red Hat)
* Sunil Kumar Acharya (Red Hat)
* Karthik (Red Hat)
* Chetan More(Red Hat)
* Tamar Shacked (Red Hat)
* Shwetha Acharya (Red Hat)



### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 21 (19)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   87 (87)  |
|[Line coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     70.7 (70.9) |
|[Function coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     84.9 (85.2) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-December/thread.html)        |     8      |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |  259     |


* Any release updates?
      
    * Minor Versions of 9.x and 10.x will be happening on JAN 2022
        * FUSE Crash issue to be fixed in 9.5

* Blocker issues across the project?
    * None

* User stories / Notable thread from the mailing list
    * https://github.com/gluster/glusterfs/issues/3025
        * If the performance improves we may want to make directory healing multi threaded at the cost of some wasted cycles when the heals are not succeeding. At this time this probably fine since granular entry healing is the default. This only happens when a disk is replaced and speed of the heal is more important.


### Conferences / Meetups
*  [FOSDEM 2022 -  5 & 6 February 2022](https://fosdem.org/2022/)
     Important dates:
    - Jan  7th 2022:  submission deadline for talk proposals
    - Jan 14th 2022:  announcement of the final schedule
    - Feb  6th 2022:  Software Defined Storage dev room


### GlusterFS - v11 and beyond
*   Please add planned feature list to below issue
    *   https://github.com/gluster/glusterfs/issues/3023


### Developer focus
* Regressions tests - Failing frequently
  * First test itself is failing
  * Example: https://build.gluster.org/job/gh_centos7-regression/1918/consoleFull 

* 


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
* Should we add Developer Session links here?
  - May not be required, its present in github README itself.




### Host

* Who will host the next meeting? 
* [SAJU]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? 



### RoundTable



### Action Items on host
* Check-in Minutes of meeting for this meeting
