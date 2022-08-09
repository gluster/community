# Gluster Community Meeting -  09/08/2022


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd Tuesday, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company

* Niraj Yadav - Red Hat
* Sunil Kumar Acharya - Red Hat
* Sanju Rakonde - PhonePe

### Community

* Project metrics:

|    Metrics                |   Value (Last meeting)  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 16 (16)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   62 (62)  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.2 (71.4) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2022-July/thread.html)        |     04     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    206   |


* Any release updates?
    * Backport your patches for subsequent releases of 9.x and 10.x( **probable next release will be around 15th-Aug-2022** )
        * Add the label `release-9` and `release-10` accordingly.

* Blocker issues across the project?
    * None


* Notable thread from mailing list / User stories
    * None


### Conferences / Meetups

*  None


### GlusterFS - v11.0 and beyond
*   Please add the planned feature list to the [tracker](https://github.com/gluster/glusterfs/issues/3023)

### Developer focus

* [Mohit]
    * ~ 33% performance improvement to rmdir. Patch links:
        * [Part One](https://github.com/gluster/glusterfs/pull/3684)
        * [Part Two](https://github.com/gluster/glusterfs/pull/3686)



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

* None


### Host

* Who will host next meeting? [Niraj]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Niraj]


### RoundTable
* [Shwetha]
    * Not enough patches for release-10
    * Planning to postpone it for 2-3 months
    * We have sufficient patches for release-9

### Action Items on host
* Check-in Minutes of meeting for this meeting
