# Gluster Community Meeting -  08/03/2022


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------


### Attendance
Name (#gluster-dev alias) - company
* Rakshitha Kamath - Red Hat
* Ravishankar - pavilion.io
* Sunil Kumar Acharya - Red Hat
* Chetan More - Red Hat
* Saju Mohammed - Red Hat
* Sheetal Pamecha - Red Hat
* Nikhil Ladha - Red Hat
* Harshita Shree - Red Hat


### Community

* Project metrics:

|    Metrics                |   Value (Last meeting)  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 15 (18)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   84 (85)  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.1 (70.7) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2022-March/thread.html)        |     6    |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    210 (210)  |


* Any release updates?
[Saju]

* Blocker issues across the project?
    * None


* Notable thread from mailing list / User stories
    * None



### Conferences / Meetups

#####  Storage Developer Conference Global(SDC)
   - Date: September 19-22, 2022
   - [Call for proposals of presentations](https://storagedeveloper.org/events/sdc-2022/speakers/call-for-presentations)
   - Deadline to submit proposals: June 17th


#####  Storage Developer Conference EMEA
   - check [link](https://www.snia.org/events/sdcemea) for more information



### GlusterFS - v11.0 and beyond
*   Please add the planned feature list to the [tracker](https://github.com/gluster/glusterfs/issues/3023)



### Developer focus

* Any design specs to discuss?
    * No



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

* Who will host next meeting? Preet
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* https://www.gluster.org/release-schedule/
    * [Sunil] Looks like release data  is not updated
* [Saju] Release updates
    * 9.x will receive updates once in 6 month
    * 10.x will receive update once in 3 month
* [Saju] Custom Builds for Glusterfs
    * https://github.com/gluster/Gluster-Builds/actions/workflows/custom-branch-builds.yml
    * Anyone who joins the Gluster project should be able to do the custom build.
    * Demo completed.
* [Rakshita] https://build.gluster.org/job/nightly-devel/
    * Centos8, regression-with-multiplex and line-coverage jobs are failing
    * Please help resolve the test failures.


### Action Items on host
* Check-in Minutes of meeting for this meeting
