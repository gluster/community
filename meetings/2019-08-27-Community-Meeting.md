# Gluster Community Meeting -  27th Aug 2019


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 27th August 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655


-------

### Attendance
Name (#gluster-dev alias) - company
* Hari Gowtham (hgowtham) - Red Hat
* Ravishankar (itisravi) Red Hat
* Sheetal Pamecha (spamecha) - Red Hat
* David Spisla - Gluster User
* Sunny Kumar (sunny) - Red hat
* Rinku Kothiya (rkothiya) - Red Hat
* Ashish Pandey (_apandey) Red Hat
* Sunil Kumar Acharya - Red Hat
* Arjun Sharma - Red Hat
* Sanju Rakonde(srakonde) - Red Hat
* Kotresh (kotreshhr) - Redhat
* Karthik Subrahmanya (ksubrahm) - Red Hat

### User stories
* Ravi - timeout of self heal crawl to be automatically updated. (Bug ID: 1743988)
* Hari - user asked for project: user quota. Had to reply that we are running out of bandwidth. contribution will be helpful here.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  65   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |    59  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.8% |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 6 <br> 2 <br> 10 <br>  1  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |     232     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    345   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    393   |


* Any release updates?
  Rinku - We have released Release-7 rc0 on 26-August-2019, request users to report any problems seen. 
   
* Blocker issues across the project?
  Atin - infra issue related to a bunch of tests are failing. A fix to do retry was done. Nightly is running an old code base. 

* Notable thread from mailing list
     Amar - Moving to Github from gerrit.
     Atin - It will be good to move to github completely. We can discuss it with large audiance.
     
     
  

### Conferences / Meetups

* [Developers' Conference -  {Date}]({Link}) -
No conferences to talk about this week.
Important dates: 
CFP Closed 
Schedule Announcement: 
Event Open for Registration :  
Last Date of Registration:  
Event dates:  
Venue: 

Talks related to gluster:

    

### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.


### Developer focus

* Any design specs to discuss?
nil


### Component status
* Arbiter - no new updates.
* AFR - nil
* DHT - nil
* EC - new data corruption corner cases. Pranith has found the code path.
* FUSE - nil
* POSIX -  nil
* DOC - changes related to afr was posted by Ravi and Karthik
* Geo Replication - nil
* libglusterfs - nil
* Glusterd
 - Glusto automation run is blocked because of https://bugzilla.redhat.com/show_bug.cgi?id=1744420 , team is working on it.
* Snapshot - nil
* NFS - nil
* thin-arbiter - nil

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions


### Recent Blog posts / Document updates
* https://shwetha174.blogspot.com/search/label/Gluster
* https://medium.com/@ntkumar/running-alluxio-on-hashicorp-nomad-ef78130727ef
* https://medium.com/@tumballi/kadalu-ocean-of-potential-in-k8s-storage-a07be1b8b961



### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

Sheetal will host next meeting.
* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting?
   

### RoundTable
* 

### Action Items on host
* Check-in Minutes of meeting for this meeting
