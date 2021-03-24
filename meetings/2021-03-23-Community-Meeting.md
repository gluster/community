# Gluster Community Meeting -  23/03/2021


### Previous Meeting details:

- [Meeting Minutes](https://github.com/gluster/community/blob/master/meetings/2021-03-09-Community-Meeting.md)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Ravishankar - Red Hat
* Sankarshan - Kadalu.IO
* Amar Tumballi - Kadalu.IO
* Rinku Kothiya - Red Hat
* Saju Mohammed - Red Hat
* Pranith Kumar K - PhonePe
* Vinayak hariharmath - Redhat
* Sheetal Pamecha - RedHat
* Ayush Ujjwal - RedHat
* Csaba Henk - Red Hat
* Aravinda Vishwanathapura - Kadalu.IO
* Srijan Sivakumar - Red Hat

### User stories

* [Interesting thread](https://lists.gluster.org/pipermail/gluster-users/2021-March/039210.html) about gluster for HPC use case. 

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 58  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   89  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.8 % |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-March/thread.html)        |    73      |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    371   |

* Any release updates?
  - For Release-9.1 patches have been merged we will be tagging the branch shortly. 
      - today would be a good day to complete all activities around patches for 9.1

* Blocker issues across the project?
     - [Pranith] not exactly a blocker; crash reported around FUSE (Github issue 2286) 

* Notable thread from mailing list
    * See above for gluster-users@ thread on HPC - [Link](https://lists.gluster.org/pipermail/gluster-users/2021-March/039210.html)


### Conferences / Meetups

* [SYSTOR 21](https://www.systor.org/2021/cfp.html)
    * June 14th - June 16th

* Talks related to gluster:
    - None.

* [SDC India 2021](https://www.snia.org/events/sdcindia)
    * Announcements regarding plans and dates for SDC India 2021 will be made in March; event slated for September 28 - 29, 2021



### GlusterFS - v10 and beyond

* Gluster X Backlog - A Github tracker added to track the issues.
    * monitoring with Prometheus is one of the major items to be added/considered
    
### Developer focus
* Developer Session 1 on Disk filesystem. [Youtube Link](https://youtu.be/kD3A_vpVfNk)
    * ~ 10 participants ; covered the foundational set of knowledge required to start working on Gluster
    * next session coming up on Tuesday - a total of 6 foundational sessions planned to be followed by replication and related topics. Geo-replication, FUSE, DHT etc sessions would be useful to have
    * [PR Link](https://github.com/gluster/glusterfs/pull/2291)


### Component status
* Arbiter - Stable
* AFR - Stable
* DHT - Stable
* EC - Stable
* DOC - Stable
* Geo Replication - Stable
* Glusterd - Stable
* thin-arbiter - Stable


### Recent Blog posts / Document updates

* [How to fix the Hyperconverged Cluster backed by gluster when the thinpool is filled 100%](https://medium.com/dev-genius/the-curious-case-of-duplicate-certificate-entries-34ae161160af?source=rss------glusterfs-5)
* [Gluster--Geo-replication](https://medium.com/swlh/gluster-geo-replication-83dab508a9de?source=rss------glusterfs-5)
* [Gluster: Geo-replication Fixes-#1](https://medium.com/@ujjwal-msrit/gluster-geo-replication-fixes-1-e85d3510ed19?source=rss------glusterfs-5)
* [The curious case of duplicate certificate entries](https://medium.com/dev-genius/the-curious-case-of-duplicate-certificate-entries-34ae161160af?source=rss------glusterfs-5)
* [Home Lab Chronicles](https://medium.com/@galenkdavis/home-lab-chronicles-93574d5cccfb?source=rss------glusterfs-5)


### Host

* Who will host next meeting? - Srijan
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* [Pranith] Increased number of lookups. PR Link -


### Action Items on host
* Check-in Minutes of the previous meeting

