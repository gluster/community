# Gluster Community Meeting -  10/05/2022


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
* Pranith Kumar - PhonePe
* Shwetha Acharya - Red Hat
* Sunil Kumar Acharya - Red Hat


### Community

* Project metrics:

|    Metrics                |   Value (Last meeting)  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 13 (18)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   61 (64)  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.3 (71.1) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2022-February/thread.html)        |     1     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    201   |


* Any release updates?
    * 9.x will receive updates once in 6 month
        * Next release is planned around the week of 20th August
    * 10.x will receive update once in 3 month
        * Next release is planned around the week of 15th May


* Blocker issues across the project?
    * oVirt breaking becasue of stripe count removal
        * Plan is to revert the change in 10.2. [PR link](https://github.com/gluster/glusterfs/pull/3511)


* Notable thread from mailing list
    * None


### Conferences / Meetups

* Storage Developer Conference Global(SDC)
    * Date: September 19-22, 2022
    * Deadline to submit proposals: June 17th
    * Submit your proposal [here](https://storagedeveloper.org/events/sdc-2022/speakers/call-for-presentations)

* Storage Developer Conference EMEA
    * Date: June 14,2022
    * Registeration for attendees will open in May.
    * Checkout the [SDC website](https://www.snia.org/events/sdcemea) for more information


### GlusterFS - v11.0 and beyond
*   Please add the planned feature list to the [tracker](https://github.com/gluster/glusterfs/issues/3023)


### Developer focus

* Any design specs to discuss?
    * None



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

* Who will host next meeting? [Nikhil]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Nikhil]


### RoundTable
* [Pranith] What exactly is the issue that oVirt is facing due to stripe count removal?
    * We need to check the upgrade scenarios, so that nothing breaks due to backport. From 9.x to 10.2 and 10.1 to 10.2


### Action Items on host
* Check-in Minutes of meeting for this meeting
