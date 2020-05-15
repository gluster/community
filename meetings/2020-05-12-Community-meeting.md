# Gluster Community Meeting -  12-05-2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 12-05-2020, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968



-------

### Attendance
Name (#gluster-dev alias) - company
* Sunny (sunny) - Red Hat
* Hari Gowtham (hgowtham) - Red Hat
* Rinku Kothiya (rinku) - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Sunil Kumar Acharya - Red Hat
* Csaba Henk - Red Hat
* Amar - Kadalu.IO [Joined late]
* Aravinda - Kadalu.IO [Joined late]
* sankarshan - Kadalu.IO [Joined late]

### User stories
* [Hari] users are hesitant to upgrade. A good number of issues in release-7 (crashes, flooding of logs, self heal) Need to look into this.
* [Sunil] Increase in inode size https://lists.gluster.org/pipermail/gluster-users/2020-May/038196.html Looks like it can have perf benefit.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 59  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.0 |
|New Issues in last 14 days<br>[master](https://github.com/gluster/glusterfs/issues?q=is%3Aissue+created%3A%3E%3D2020-03-28) |<br>  53  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-January/thread.html)        |      14    |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    756   |

[Sunil] how to improve
[Sunny] Clang is running on gcc9. expect it to upgrade to gcc10. Most of these are false positives. With gcc10 expecting this to go down.
[Sunil] can we have an issue to track this?
[Sunny] Coverity is the same. When a new issue is raised, Sunny is reaching out to the owner of the concern patch owner to take a look. 30 to 40 are false positives. Reached out to coverity devs and they said they will look into false positive but no update from them.
[Sunil] rest 50%'s status
[Sunny] few are assigned and around 10 or 15 will be genuine issues. This is a good number for a ope source project.
[Sunil]test coverage
[Sunny] have sent out a mail. A few test cases for snapshot, glusterfind(might not contribute as its in python), afr from pranith are sent.
[hari] raising questions as issues with users has to be taken care of.
[sunny] send out a mail for the same.

* Any release updates?
    * 6.9 is done and announced
    * [Sunil]can we take this in for release-8: https://review.gluster.org/#/c/glusterfs/+/24396/
    * [Rinku]Yes, we need to ask the patch owners to port this to release8 post merging it to master. Till the time we tag release8 this is possible post this it will be difficult, after which we can put it in release8.1
    * [Csaba] This is necessary as well https://review.gluster.org/#/c/glusterfs/+/24415/
    * [Rinku] We need release notes to be reviewed and merged release8 is blocked due to this. https://review.gluster.org/#/c/glusterfs/+/24372/
    *

* Blocker issues across the project?
    * There is a crash with open-behind. First patch has missed a corner case, Xavi is looking into it.


* Notable thread form mailing list
    * same as in user stories

### Conferences / Meetups

* COVID-19 has impacted the events!


### GlusterFS - v8.0 and beyond
* discussed above

### Developer focus

* Any design specs to discuss?
    * Ravi working on IOuring (https://docs.google.com/document/d/1vbvY0eBpElpNNlTaWyFGSj2ZRpPqBTW4gTSYiHYan70/edit)
    * [sunny] Reach out to ravi for the permission. or send out a mail
    * [Hari] ask Rafi to take the performance discussion upstream.
    * To help debugging please do review https://review.gluster.org/#/c/glusterfs/+/24163. Big patch needs more people to review it.

### Component status
* Arbiter - Nil
* AFR - Nil
* DHT - Nil
* EC - Nil
* DOC - backporting docs need to be worked on
* Geo Replication - [Sunny] nothing major, issues with SElinux being enabled has resulted in few issues and Have sent a few patches to fix it. [Aravinda] updating doc on non-root geo rep.
* Glusterd - Nil
* thin-arbiter - Nil


### Flash Talk Gluster
* Nil


### Recent Blog posts / Document updates
* Need to update the how to backport part.
* Need to check with infra team about planet gluster not reflecting the blogs about gluster.


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA


### Host

* Who will host next meeting?
* Sunny has volunteered.
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* [Sunil] Do we support cento8 and gluster?
    * [sankarshan] Please highlight the concerns on the mailing list. The developers who do the manual testing can review and provide their assessment on where the project stands
    * We do have packages, how are we testing it?
* [Sunil] Centos8 regression is having issues and are not being used for regression testing.
* [Hari] For packages, Shwetha and Sheetal are manually testing the bits with centos8. Basics works fine. But this testing isn't enough
* send out a mail to sort this out
* [Amar] Kadalu 0.7 release based on GlusterFS 7.5 has been recently released (Release Blog: https://kadalu.io/blog/kadalu-storage-0.7)
    * [Rinku] How to test
        * [Aravinda] https://kadalu.io/docs/k8s-storage/latest/quick-start


### Action Items on host
* Check-in Minutes of meeting for this meeting

