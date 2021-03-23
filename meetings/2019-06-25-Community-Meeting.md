Gluster Community Meeting - 2019-06-25
===

### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC friendly hours
  - Tuesday 25th June 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
    Hari Gowtham (hgowtham) - Red Hat
    Ashish Pandey - Red Hat (apandey_)
    Amar Tumballi - (amarts)
    Anoop C S (anoopcs) - Red Hat
    David Spisla - Gluster User
    Rinku Kothiya - Red Hat (rkothiya)
    Sanju Rakonde - Red Hat (srakonde)
    Pranith Kumar K - Red Hat (pranithk)
    Sheetal Pamecha - Red Hat (spamecha)
    Kotresh HR - RedHat (kotreshhr)
    Karthik Subrahmanya - Red Hat (ksubrahm)
    Shwetha K Acharya - Red Hat (sacharya)
    Rafi KC - Red Hat (rafi)
    Atin Mukherjee - Red Hat (atinmu/atinm)
    Krutika Dhananjay - Red Hat (kdhananjay)
    Vinayak - Red Hat
    Kshithij - Red Hat
    Deepshikha - Red Hat.


### User stories
David Spisla:
I use Gluster v5.5 together with Samba (SMB) and CTDB (HA Setup).
2-Node Replica2 Setup with WORM file level enabled.
I use Gluster for longterm archiving most of the time.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  71   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   61   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|   70.0  |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>19<br>9<br>5   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |    14      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   441   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   377   |


* Any release updates?
    5.7 was facing a smoke issue which has delayed it a lot.
    6.3 and 4.1.9 packages are ready and being tested. Once done we will mark them for release.
    7.0  we want to do this post nighly build passing
    4.1.9 is the last release in release 4

* Blocker issues across the project?
    smoke and regression have been failing for a few reasons.

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

Talks related to gluster:
Ashish: Thin Arbiter volume
Aravinda: Rethinking Gluster Management using k8s
Ravi: Strategies for Replication in Distributed systems
Mugdha: selenium for automation in RHHI

### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.
  The maintainers have to file a github issue about what they want to work on for release 8. the planning has to be started.


### Developer focus

* Any design specs to discuss?


### Component status
* Arbiter all green
* AFR - gfid split brain
* DHT - memory leak is suspected introduced as a regression
* EC - heal not happening
* FUSE - recent [patch](https://review.gluster.org/c/glusterfs/+/21147) broke Samba's get_real_filename implementation. See [bug #1722977](https://bugzilla.redhat.com/show_bug.cgi?id=1722977) for details
* POSIX - all fine
* DOC - there are plans on updating them. we are working on it.
* Geo Replication - Mount broker seems to be broken in upstream. Sunny has sent the [patch](https://review.gluster.org/#/c/glusterfs/+/22920/) to fix the same.
self heal + geo rep issue with syncing.
release 5 and 6 arent passing regression. because of python version.
* libglusterfs
* Management Daemon - glusterd1 - one regression being worked on regarding brick mux.
shd mux will make it into release 7. its being made stable.
thin arbiter integration is almost done. last round of review happening.
* Snapshot test case failing with brick mux. being worked on.
* NFS
* thin-arbiter - As updated in glusterd: thin arbiter integration is almost done. last round of review happening.

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions


### Recent Blog posts / Document updates
* https://medium.com/@tumballi/24007-choosing-the-right-port-for-project-77bdc88f59d2
* https://medium.com/@harigowtham/glusterfs-quotas-accounting-6ee60c78bb1f?postPublishedType=repub
* https://gluster.github.io/devblog/gluster-3-12-vs-6-a-performance-oriented-overview

planet gluster issues have to be worked on so blogs can be made available.
As of 10th its fixed.

### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
    https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - The [readme](https://github.com/gluster/community) gives detailed steps for the host to follow.

  Ashish came forward to be the host for the next meeting.

### Notetaker

* Who will take notes from the next meeting?

### RoundTable

Glusto - CIFs mount had some issue in automation.
Bala has been contacted about this.
Deepshikha has provided the machines to run the test cases.

### Action Items on host
* Check-in Minutes of meeting for this meeting

