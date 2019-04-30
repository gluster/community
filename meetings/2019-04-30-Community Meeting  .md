Gluster Community Meeting : 2019-04-30
===

### Previous Meeting minutes:

- http://github.com/gluster/community

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 14th May 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Tuesday 7th May 2019, 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655

-------

### Attendance
Name (#gluster-dev alias)
* Ashish Pandey (aspandey_) - Redhat
* Pranith Kumar K (pranithk) - Red Hat
* Ravishankar N (itisravi) -Red Hat
* Sheetal Pamecha (spamecha) - Red Hat
* Sunny Kumar (sunny) - Red Hat
* Rafi KC (rafi) - Red Hat
* Kotresh (kotreshhr) - Redhat
* Susant Palai (spalai) - Red Hat
* David Spisla
* Yi Wang
* Poornima G
* Rafi (rafi_kc)
* Nithya (nbalacha)

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community

### User stories

* User Name:
  SETUP: distributed Disperse volume 
  GlusterFS - 
  
  ISSUE: User renamed a directory when one of the node, on which some
  bricks were hosted, was rebooted. This lead to a situation where
  directory entries were not visible on mount point even after node was
  up and all the bricks were running.
  
  RECOMMENDATION:
  We are trying to come up with some workaround to get the data back on
  mount point.
  At the same time we have started design discussion to fix this issue in
  gluster code.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |   103   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   88   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|  67.2%   |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>12<br>8<br>1   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |    26      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   581   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   370   |


* Any release updates?
gluster-block 0.4 will be released this week 
  
  
  
* Blocker issues across the project?
  
  

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
*  [SDC India, Bengaluru, on May 23rd and 24th](https://www.snia.org/events/sdcindia) - 
  

### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.


### Developer focus

* Any design specs to discuss?
Sent first version of gluster plus one scale 
https://github.com/gluster/gluster-plus-one-scale
It is still work in progress, however, feedback and comments are welcome.

* Metrics of the week?
  - Number of patches from new developers.
     - Need a script to get this info.
  - Frequent test failures in the CI
     - What can be done to fix it properly ?


### Recent Blog posts / Document updates
[[Gluster, Scale Disperse Volume by One Node – (Part-1) :- Ashish](https://ashishpandeyblogs.home.blog/2019/04/16/gluster-scale-disperse-volume-by-one-node/)]

### RoundTable
* David S: Gluster documents are not updated. Struggled to set some option
using old document. Information about options are not updated.

* Poornima : We are restructuring documentation of glusterfs. Probably this will be done by glusterfs 7.0.

* David S: What will be the medium of communication in the future? Focus on one platform or fragmented over slack, IRC and mailing list.

* Poornima: Mailing list will always be there. Slack is the platform where we want to go, however, during the transition phase we would continue using IRC.


