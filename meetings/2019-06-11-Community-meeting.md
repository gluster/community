Gluster Community Meeting - 2019-06-11
===

### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC friendly hours
  - Tuesday 11th June 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
    * Hari Gowtham (hgowtham) - Red Hat
    * Ashish Pandey (apandey_) - Red Hat
    * Sudheer Singh (sudheerit11) - Paypal
    * Kotresh HR (kotreshhr) - RedHat
    * Sheetal Pamecha - Red Hat


### User stories

Sudheer from paypal, is trying a few pocs for some work related to container storage. He is interested into looking at gluster for container storage.
He has tried fuse and NFS on distributed replicated volume and finds the performance to be low on FUSE.

When are we completely removing gnfs?

Doc and the blogs are scattered. have asked him to update the topics which need more coverage.

David Cunningham from New Zealand is interested in thin arbiter support with gd1. Is looking for the tentative release date of gluster with thin arbiter.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  78   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   66   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|   70.1  |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>14<br>8<br>3   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |    14      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   475   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   380   |


* Any release updates?
    6.2 was tagged and annouced.
    5.7 facing issues with smoke and is hindering the build
    4.1.9 and 6.3 are in the process of tagging.


* Blocker issues across the project?

* Notable thread form mailing list


### Conferences / Meetups

* [Developers' Conference -  August 2-3, 2019](https://devconf.info/in) -
Important dates:
CFP Opens: March 15, 2019
CFP Closes: May 01, 2019
CFP Status Notifications: June 1, 2019
Schedule Announcement: July 1, 2019
Event Opens for Registration : July 1, 2019
Event dates: Saturday, August 2 to Sunday, August 3, 2019
Venue: Christ University - Bengaluru, India


### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.

### Developer focus

* Any design specs to discuss?

### Component status
* Arbiter
* AFR
* DHT
* EC
* FUSE
* POSIX
* DOC
* Geo Replication
increased code coverage and looking into newer ways of syncing the slave volume.
* libglusterfs
* Management Daemon - glusterd1
* Snapshot
* NFS
* thin-arbiter

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions
* For this meeting


### Recent Blog posts / Document updates
* https://gluster.home.blog/2019/05/06/why-brick-multiplexing/
* https://ravispeaks.wordpress.com/2019/05/14/gluster-afr-the-complete-guide-part-3/
* https://ashishpandeyblogs.home.blog/2019/06/08/gluster-scale-disperse-volume-by-one-node-part-2/

### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
    https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host
* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
Hari

### Notetaker

* Who will take notes from the next meeting?

### RoundTable
*

