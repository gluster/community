Gluster Community Meeting - 2019-07-09
===

### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Every 2nd and 4th Tuesday at 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
Hari Gowtham (#hgowtham) - Red Hat
Rafi KC (#rafi) - Red Hat   
Sunny (#sunny) - Red Hat
Ravi (itisravi) - Red Hat    
Ashish (apandey) - Red Hat
David Spisla - Gluster User
Rinku Kothiya (rinku) - Red Hat
Aravinda (aravindavk) - Red Hat
Sheetal Pamecha (spamecha) - Red Hat
Amar Tumballi (@tumballi)
Sunil Kumar - Red Hat
Rishubh Jain(risjain) - Red Hat
Sanju Rakonde(srakonde) - Red Hat
Shwetha Acharya (sacharya) - Red Hat
Kotresh (@kotreshhr) - Red Hat
Deepshikha Khandelwal (dkhandel) - Red Hat
Vishal Pandey (@vpandey) - Red Hat
Atin Mukherjee (@atinmu) - Red Hat
Strahil Nikolov - Community

### User stories
None for this week


### Community

Amar: Go through the bugs for gluster and see if its reproducible and take it to completion. A update to the bug would be great.


* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  69   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   59   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.3 (2019-07-03)  |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 25<br> 4<br> 1   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-June/thread.html)        |     125      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    374   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    378   |


* Any release updates?
    * Release 7 branched.
    * 5.7 packaging issue's fix has been decided to prioritize python2 over python3. This should fix it. 
  
* Blocker issues across the project?
    * tests/basic/afr/tarissue.t is failing frequently. Has to be addressed.
    * There's a comment on /tests/bugs/nfs/bug-904065.t in the end which might be related to the nfs failures we are facing in regression runs.
    * a samba user was facing issue, it was fixed and the user is happy.


  

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
- Ashish: Thin Arbiter volume
- Aravinda: Rethinking Gluster Management using k8s
- Ravi: Strategies for Replication in Distributed systems
- Mugdha: selenium for automation in RHHI
 
### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.


### Developer focus

* Any design specs to discuss?



### Component status
* Arbiter - nothing to update
* AFR - working on Heal info
* DHT - nothing
* EC - after shd multiplex, we are seeing issues (crash as well). Might be common to AFR and EC
* FUSE - nothing
* POSIX - nothing
* DOC - community meetings' hosting steps have been posted and merged
* Geo Replication - mount broker issue's patch posted. has to be backported.
* libglusterfs - issues with header files, Amar sent a patch to modularize it. https://review.gluster.org/23015
* Management Daemon - glusterd1 - Thin arbiter integration is done with GD1.
Vol info find function optimization is being worked by Mohit.
shd mux needs more work to be done.
* Snapshot - nothing
* NFS - no update.
* thin-arbiter - Integration with GD1 done. Initial testing is done.
Release 7 has the patch. 

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions
* For this meeting
https://lists.gluster.org/pipermail/gluster-devel/2019-July/056404.html
Amar: Code has been removed to improve stablility. 6 and 7 have improved stability. we are aiming for more. not focusing on feature.
performance improvements (io perf and reboot and other management perf). Scale improvements (RIO). Containers. Path based Georep. Testing (automate the upgrade testing, reduce spurious failures)
Add your points in the hachmd.

   https://hackmd.io/JtfYZr49QeGaNIlTvQNsaA?both
QUESTIONS: Rinku had a question about perf values varying on the same machine and same configuration.


### Recent Blog posts / Document updates
*  https://ashishpandeyblogs.home.blog/2019/07/03/gluster-disperse-volume-troubleshooting-heal/ - Ashish Pandey
* https://medium.com/@tumballi/glusters-management-in-k8s-13020a561962 - Amar Tumballi


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
    https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  
 Hari will host the next community meeting


### RoundTable

Hari - Have started the work for automating the packaging of Gluster for various distributions.
The latest should be available only when the packages are made available.

### Notetaker

* Who will take notes from the next meeting?
Ashish will help taking the notes.
   

### Action Items on host
* Check-in Minutes of meeting for this meeting
