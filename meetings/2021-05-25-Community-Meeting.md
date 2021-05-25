# Gluster Community Meeting -  25/05/2021


### Previous Meeting minutes:

- [Meeting Minutes](http://github.com/gluster/community/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Ayush Ujjwal - Red Hat
* Nishith Vihar - Red Hat
* Pranith Kumar K - PhonePe.com
* srijan-sivakumar - Red Hat
* sankarshan - Kadalu.IO
* Sunil Kumar - Red Hat
* Shwetha Acharya - Red Hat
* Csaba Henk - Red Hat
* Saju Mohammed - Red Hat
* Nikhil Ladha - Red Hat


### User stories
* None

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 38  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   89  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-May/thread.html#start)        |     27     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    315   |


* Any release updates?
    * None

* Blocker issues across the project?
    * It looks like the lock-recovery changes introduced with https://review.gluster.org/#/c/glusterfs/+/22712/ has issues. We already fixed https://github.com/gluster/glusterfs/pull/2456 and https://github.com/gluster/glusterfs/issues/2337 but looks like the code is buggy. Need someone to take a look at the difference between posix-locks and client xlators in how the locks are maintained to fix the issue completely.


* Notable thread form mailing list
    * Not exactly from mailing list. Slack user pinged me and asked me if it is possible to let the users know of any known issues in the latest releases so that they can make a decision about which version to use. For example: 9.0 and 9.1 had protocol issue.
    * Along the same lines, I wanted to ask one more question. Should we release beta-releases for major releases so that we get feedback about any issues that happen in their particular environment to address the issues even before the stable releases are made?


### Conferences / Meetups

* [SYSTOR 21](https://www.systor.org/2021/cfp.html)
    * June 14 - June 16,2021
* [SDC India 2021](https://www.snia.org/events/sdcindia)
    * Submission of presentations is OPEN

* Talks related to gluster:
    - None.




### GlusterFS - v10 and beyond
* No new updates

### Developer focus

* Any design specs to discuss?
    * None



### Component status
* Arbiter - stable/maintained
* AFR - stable/maintained (Release 9 is affected by https://github.com/gluster/glusterfs/issues/2462)
* DHT - stable/maintained
* EC - stable/maintained
* DOC - stable/maintained
* Geo Replication - stable/maintained
* Glusterd - stable/maintained
* thin-arbiter - stable/maintained



### Recent Blog posts / Document updates
* No new blog posts recently.


### Host

* Who will host next meeting? [Ayush]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Ayush]


### RoundTable

* None


### Action Items on host
* Check-in Minutes of meeting for this meeting

