Gluster Community Meeting - 2019-07-23
===

### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 2019-07-23, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
* Ashish Pandey (_apandey) - Redhat
* Rishubh Jain  (risjain)  - Redhat
* Susant Palai (spalai) - Redhat
* hari gowtham (hgowtham) - Red Hat
* Sheetal Pamecha (spamecha) - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Amar Tumballi (amarts/@tumballi)
* Sunny Kumar (sunnyk) - Red Hat
* Rinku Kothya (rinku) - Red Hat
* Hamza
* Khalid
* Sanju Rakonde (srakonde) - RedHat
* Deepshikha (dkhandel) - Red Hat
* Pranith Kumar (pranithk) - Red Hat
* Sunil Kumar (skumar) - Red Hat
* Kotresh HR (kotreshhr) - RedHat
* David Spisla - Gluster User
* Rafi KC - Red Hat
* Prasanna Kumar Kalever (pkalever) - RedHat
* Karthik Subrahmanya (ksubrahm) - Red Hat
* Arjun Sharma - Red Hat
* Kaustav Majumder - Red Hat


### User stories

Felix, is trying to setup a production server. asked for ideas to set it up.
storing large media and research files using replica/disperse vol.

a users issue was addressed with a patch. duplicate entry in volfile. [bug which talks about issue](https://bugzilla.redhat.com/1730953)

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  71   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |    59   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    69.7 (13-07-2019) |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 12 <br> 2<br> 5 <br>  0  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |     17      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    335   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    380   |


* Any release updates?
    * 4.1.10, 5.8 and 6.4's packaging is nearly done. will release it in a day or two.
    * 4.1.10 will be EOLed
    * Release 7, merged some patches and some are pending due to centos regression failing.
  
* Blocker issues across the project?
    * we have fixed the python issue with 5.7 and are working on 5.8 

* Notable thread form mailing list
    * webhook for geo rep by Aravinda
  

### Conferences / Meetups

* [Developers' Conference -  August 2-3, 2019](https://devconf.info/in) -

Important dates: 
CFP Closed 
Schedule Announcement: https://devconfin19.sched.com/ 
Event Open for Registration : https://devconfin19.eventbrite.com 
Last Date of Registration: 31st July, 2019 
Event dates: Aug 2nd, 3rd 
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


### Developer focus

* Any design specs to discuss?
nothing


### Component status
* Arbiter - nothing 
* AFR - metadata split brain has been fixed. gfid split brain is being worked on.
* DHT - nothing
* EC - data corruption worked by Xavi and Pranith.
* FUSE - Nithya sent a few patches to invalidate inode. mail to discuss this
* POSIX - nothing 
* DOC - Man page bugs are open need to be looked into. glusterfs-8 doc has to be looked into(RDMA has to be removed) Gluster v status has RDMA which has to be looked into as well . tier has to be removed from man page.
* Geo Replication - The mount broker blocker issue is fixed. The [patch](https://review.gluster.org/#/c/glusterfs/+/23089/) is merged. Needs backport to release branches.
* libglusterfs - nothing
* Management Daemon : glusterd1 -  nothing new. glusterd_volinfo_find() optimization
* Snapshot - nothing
* NFS - 
* thin-arbiter - performance improvements.

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions
* For this meeting lets talk about Roadmap suggestions.
   - https://hackmd.io/JtfYZr49QeGaNIlTvQNsaA



### Recent Blog posts / Document updates
* https://medium.com/@sheetal.pamecha08/https-medium-com-sheetal-pamecha08-one-good-way-to-start-contributing-to-open-source-static-analysers-16543eeeb138
* https://pkalever.wordpress.com/2019/07/02/expanding-gluster-block-volume/
* https://medium.com/@tumballi/glusters-management-in-k8s-13020a561962
* https://aravindavk.in/blog/gluster-and-k8s-portmap/


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  
  Sunny will host the next meeting.

### Notetaker

* Who will take notes from the next meeting?
   

### RoundTable
[Amar] Road map has to be worked on for the next 6 months to be sent by Maintainers.

### Action Items on host
* Check-in Minutes of meeting for this meeting
