# Gluster Community Meeting -  08/12/20


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/blob/master/meetings/2020-11-24-Community-Meeting.md)
- Details of this meeting

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 08/12/20, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968
* NA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Nikhil Ladha - Red Hat
* Pranith Kumar K - PhonePe
* Sankarshan - Kadalu.IO
* Amar - Kadalu.IO
* Vinayak Hariharmath - RedHat
* Ravi (itisravi) -Red Hat
* Saju Mohammed - Red Hat
* Srijan Sivakumar - Red Hat
* Sunil Kumar - Red Hat
* Patric Uebele - Red Hat
* Karthik Subrahmanya - Red Hat

### User stories
* [Pranith] - PerryNzohu 
    * Some options which are harmful over releases
    * Like 'trash' xlator
    * 'Readdir-ahead' which has issues!
    * 'read-ahead' and 'io-cache' causing more perf regression than helping.
    * Needs an issue to be raised
* How to join the gluster.org team?
  - https://github.com/gluster/glusterfs/pull/1895 
  - Thanks to Deepshika. Need reviews.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 73  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   88  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.0 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-September/thread.html)        |     9     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    391   |
|[Pending PRs](https://github.com/gluster/glusterfs/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc) | 60 |


* Any release updates?
    * Gluster-7.9 and Gluster8.3 will be rolling out on 08/12/2020
* Blocker issues across the project?
    * None

* Notable thread from mailing list
    * [Poor performance on a server-class system vs. desktop](https://lists.gluster.org/pipermail/gluster-users/2020-November/038971.html)


### Conferences / Meetups

* DevConf.in
    * Event dates: 17-18 December, 2020
    * Venue: Online
    * Link: https://www.devconf.info/in/


### GlusterFS - v9.0 and beyond
*   Gluster release 9 roadmap [tracker](https://github.com/gluster/glusterfs/issues/1465)
    *   Release date postponed or on-track?
        *   Postponed by a week to 18th December, 2020

### Developer focus

* Any design specs to discuss?
  - [Nikhil] GitHub app not working for Slack
    - Can someone setup github App to Slack?
        - [Nikhil] I can have a look into it.



### Component status
* Arbiter - Stable
* AFR - Stable
* DHT - Fixing corner cases in the lookup-optimize
* EC - Stable
* DOC - Stable
* Geo Replication - Stable
* Glusterd - Stable
* thin-arbiter - Stable


### Recent Blog posts / Document updates
* https://www.gluster.org/looking-back-at-2020-with-gratitude-and-thanks/


### Host

* Who will host next meeting? [Srijan]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Srijan]


### RoundTable
*  [Ravi] Open Pr for updates in the problematic language in glusterfs repo.
    *  Request from maintainers for working on the same in in other repos of gluster as well.
*  [Sankarshan] Note of thanks to the community for working through the challenges in this year and continuing the contrbution to Gluster.
*  The meeting on 22/12/2020 is cancelled because of shutdown/end of year holidays.


### Action Items on host
* Check-in Minutes of meeting for this meeting

