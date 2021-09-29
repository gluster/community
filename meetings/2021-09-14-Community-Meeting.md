# Gluster Community Meeting -  14/09/2021


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Nikhil Ladha - Red Hat
* Saju Mohammed - Red Hat
* Karthik - Red Hat
* Ravishankar - Pavilion Data
* Sheetal Pamecha - Red Hat
* Mohit Agrawal - Red Hat
* Sunil Kumar Acharya - Red Hat
* Tamar Shacked - Red Hat
* Pranith Kumar K - PhonePe

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 23  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   87  |
|[Line coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     70.9 |
|[Function coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     85.1 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-August/thread.html)        |     9     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |  273     |


* Any release updates?
    * Next Major Release is Gluster-X
        * Please tag appropiate Issues/PRs with "release-10" label

* Blocker issues across the project?
    * None

* User stories / Notable thread from the mailing list
    * None

### Conferences / Meetups
* None


### GlusterFS - v10 and beyond
* Gluster-X release is planned for 11th October, 2021

### Developer focus
 * [Pranith] why IO thread is loaded below iostats?
     * [Ravi] Client IO threads disabled of all the volume except EC
     * [Pranith] dd with block size to 8k with write-behind is seeing performance regression(aggregate size is 128k)

 * [Mohit] We are getting good performance improvement in case of smallfile with tcmalloc and mempool disabled, along with use standard allocation for iobuf - [GitHub Issue](https://github.com/gluster/glusterfs/issues/2771)



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

* Who will host the next meeting? [Nikhil]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Nikhil]


### RoundTable
* None

### Action Items on host
* Check-in Minutes of meeting for this meeting



