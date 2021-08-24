# Gluster Community Meeting -  10/08/2021


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
*    Shwetha Acharya - Red Hat
*    Saju Mohammed - Red Hat
*    Pranith Kumar K - PhonePe
*    Ravishankar - Red Hat
*    Sunil Kumar Acharya - Red Hat
*    Srijan Sivakumar - Red Hat
*    Aravinda Vishwanathapura - Kadalu.io
*    Karthik - Red Hat
*    Sheetal Pamecha - Red Hat
### User stories
* None

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 21  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |  87  |
|[Line coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     70.7 |
|[Function coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     84.9 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-July/thread.html)        |     4     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |  292    |


* Any release updates?
    * Minor release in August.
    * Please backport all the relevant fixes to release-8 branch and mark the PR with the `release-8` label
  
* Blocker issues across the project?
    * Smoke, Regression was failing on release-8 branch but resolved now by PR [#2698](https://github.com/gluster/glusterfs/pull/2698), [#2699](https://github.com/gluster/glusterfs/pull/2699)


* Notable thread from the mailing list
    * None


### Conferences / Meetups



### GlusterFS - v10 and beyond
   * Gluster 10 release might be delayed by 4 wks, possible ETA OCT 11th 
   * Planning to change the  Gluster Release cycle
   * What that means:
         1. Next 1 yr we will maintain 10 with minor releases
             a) Every alternate month a minor release
         2. Gluster 9.x will also be maintained 
             b) Every 3 months a minor release
         3. Gluster 8.x series will not have further releases after 10 release


### Developer focus

Any design specs to discuss?

* Plugin support for Snapshots feature. Need Review https://github.com/gluster/glusterfs/pull/2642
* Tiering PR needs design overview for reviewers https://github.com/gluster/glusterfs/pull/2681
A detailed explaination about tiering PR can be expected next meeting.

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
* https://blog.devgenius.io/preparing-bricks-for-glusterfs-5602bdf8191c
* Upcoming release of Gluster Metrics Exporter https://github.com/kadalu/gluster-metrics-exporter/milestone/1

### Host

* Who will host the next meeting?
Srijan

### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* Current testing is taking place on CentOS 7. Is it the right time to switch to CentOS 8?
* Rakshitha to cleanup and retrigger the test


### Action Items on host
* Check-in Minutes of meeting for this meeting
