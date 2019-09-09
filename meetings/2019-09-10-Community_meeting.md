Gluster Community Meeting - 10/09/2019
===

### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting - No recording available for this meeting due to technical issues
    

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 10th September 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/9461957313
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
Sheetal Pamecha (spamecha) - Red Hat
Sunny Kumar (sunny) - Red Hat
Rishubh Jain (risjain) - Red Hat
Ravi (@itisravi) Red Hat    
Sanju Rakonde (srakonde) - RedHat    
Rinku Kothiya (rinku) - RedHat
Ashhadul Islam (aislam) - Redhat
Vishal Pandey (vpandey) - RedHat
Ashish Pandey (_apandey) -RedHat
Sunil Kumar Acharya - RedHat
Shwetha Acharya (sacharya) - RedHat
Hari Gowtham (hgowtham) -Red Hat
### User stories
* None

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  65   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   59   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|   70.9  |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>6<br>2<br>7<br>3   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-August/thread.html)        |    52      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   350   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   399   |


* Any release updates?
  
    - We are yet to merge some patches which are present in release6 but not in release7. We are waiting for it to pass centos regression. 
  
* Blocker issues across the project?
  nil

* Notable thread form mailing list
  nil

### Conferences / Meetups

* Gluster Meetup on September 25th
Register here: https://www.meetup.com/glusterfs-India/events/264366771/* 
* [Developers' Conference -  {Date}]({Link}) -
Important dates:
CFP Opens: 
CFP Closes: 
CFP Status Notifications: 
Schedule Announcement: 
Event Opens for Registration : 
Event dates: 
Venue: 


### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.
  The maintainers have to file a github issue about what they want to work on for release 8. the planning has to be started.


### Developer focus

* Any design specs to discuss?
  - nil

### Component status
* Arbiter - no updates
* AFR - no updates
* DHT - no updates
* EC - fixed new data corruption issues and working on some scripts for automation for handling edge cases
* FUSE - no updates
* POSIX - no updates
* DOC - no updates
* Geo Replication - no updates
* libglusterfs - no updates
* glusterd - no updates
* Snapshot - no updates
* NFS - no updates
* thin-arbiter - 

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions


### Recent Blog posts / Document updates
* https://medium.com/@tumballi/fixing-glusters-git-history-6031096f6120
* https://medium.com/@rune.henriksen.skat/hey-wilson-wilson-3540521ecfc0
* https://shwetha174.blogspot.com/search/label/Gluster


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
    https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host
  Sanju will host next meeting
* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - The [readme](https://github.com/gluster/community) gives detailed steps for the host to follow.
  

### Notetaker

* Who will take notes from the next meeting?
   


### RoundTable
Sunny - Please RSVP to gluster meet up
        Yaniv will talk about Gluster X and Aravinda will talk about kaDalu
        
Sunny - Should we start using hangouts for video calls than using bluejens?
Ravi - Hangouts may have some limitations on no of people that can join meeting, which should be checked
Deepshika - Hangounts video is not integrated with Red Hat conference calling system
 * Gluster X


### Action Items on host
* Check-in Minutes of meeting for this meeting

