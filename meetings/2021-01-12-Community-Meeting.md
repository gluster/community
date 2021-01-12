# Gluster Community Meeting -  12/01/2021


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/blob/master/meetings/2020-12-08-Community-Meeting.md)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Pranith Kumar K - PhonePe.com
* Rinku Kothiya - Red Hat
* Ravi (itisravi) - Red Hat
* Saju Mohammed - Red Hat
* Amar Tumballi (kadalu.io)
* Aravinda (kadalu.io)
* Sheetal pamecha - Red Hat
* Csaba Henk - Red Hat
* Sunil Kumar - Red Hat
* Nikhil Ladha - Red Hat
* Srijan Sivakumar - Red Hat

### User stories
* Interesting stories over slack
    * An user using glusterfs with bitrot.
* [Amar] GlusterFS being used over 400 nodes.
    * (Volume type Replica3). Some issues seen with number of connections open.
    * Some issues with locks and layout holes and overlaps found.
* Loading of external xlators into the volfile.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 67  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   88  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 % |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-January/thread.html)        |    24      |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    365   |


* Any release updates?
  - Test day planned on 15-Jan-2021. Reference doc for people interested to contribute towards the effort [Upgrade testing for Release 9](https://docs.google.com/spreadsheets/d/1NudwDLOaeYXkr_0yPkQMnVM0RqJQR54-w4ptX4IFMgk/edit?usp=sharing)
  - Planing to release 9.0 in last week of Jan 2021

* Blocker issues across the project?
  - Regression Test failures
      - Ideally no spurious tests should be present in tests/. If one notices a test which is spurious, please move the test to '000-flaky/' directory.
  - Nightly test failures (NFS bug)

* Notable thread from mailing list
    - [Multiple Geo Rep issues due to SELINUX on CentOS 8.3](https://lists.gluster.org/pipermail/gluster-users/2021-January/039066.html)

### Conferences / Meetups

* [Devconf.cz 2021](https://hopin.com/events/devconf-cz-2021)
    * Registration is open and [schedule](https://devconfcz2021.sched.com/) is live


* Talks related to gluster:
    - None.


### GlusterFS - v9 and beyond
* Roadmap to be taken up into focus in coming days.

### Developer focus

* Any design specs to discuss?



### Component status
* Arbiter - Stable
* AFR - Stable
* DHT - Stable
* EC - Stable
* DOC - Conscious language change being undertaken.
* Geo Replication - Conscious language change merged with devel.
* Glusterd - Stable
* thin-arbiter - Stable



### Recent Blog posts / Document updates
* No new blog posts in the recent times ( People we need to experiment and spread the word ! )


### Host

* Who will host next meeting? [ Srijan ]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [ Srijan ]


### RoundTable
* [sheetal] - For glusterdocs not able to add reviewers to PR 
    * Added @sheetal to Documentation group
    * https://github.com/orgs/gluster/teams/documentation/members

Able to add reviewers now. Successfully added to groups

* [Csaba] - devel branch and tagging

* [Amar] - Moana project is ready to 'try' - https://github.com/kadalu/moana
   * Happy to hear feedback, and get contributions :D


### Action Items on host
* Check-in Minutes of meeting for this meeting
