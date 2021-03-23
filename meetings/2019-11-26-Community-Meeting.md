# Gluster Community Meeting -  26th Nov, 2019


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    - https://bluejeans.com/s/s1Zma

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 26th Nov, 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/441850968
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Ravi (itisravi)- Red Hat
* Sheetal Pamecha(spamecha) - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Amar Tumballi - Consultant
* Vishal Pandey - RedHat
* Sunil Kumar - RedHat
* Aravinda VK (aravindavk) - Red Hat
* Rishubh Jain (risjain) - Red Hat
* Rinku Kothiya (rkothiya) - Red Hat
* Ashish Pandey (apandey) - Red Hat
* Kotresh (kotreshhr) - RedHat

### User stories
* 


### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  49   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9% |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 10 <br> 7 <br> 6 <br>  2  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |     48     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    343   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    428   |


* Any release updates?
     
* Blocker issues across the project?

* Notable thread form mailing list
     
  

### Conferences / Meetups

Devconf.cz
Important dates:
CFP Closes- closed
Schedule Announcement- TBA
Event Open for Registration- Dec 9, 2019
Last Date of Registration- TBA
Event dates- January 24-26, 2020
Venue- Brno, Czech Republic

[FOSDEM'20](https://fosdem.org/2020/)
Important dates:
CFP Closed- closed for main track, for storage dev room - 24 Nov, 2019
Schedule Announcement- TBA
Event Open for Registration-
Last Date of Registration-
Event dates: 1 & 2 February 2020
Venue: Brussels (Belgium)

Talks related to gluster:
* Evolution of Geo-replication in Gluster - Hari Gowtham
* Blockchain for decentralized storage with gluster - Prajith Prasad


    

### GlusterFS - v8.0 and beyond

* Proposal - 
* Proposed Plan:
  - 


### Developer focus

* Any design specs to discuss?



### Component status
* Arbiter - No update
* AFR - No update except lock healing patch got merged and lock-less heal-info work in progress.
* DHT - memory corruption patch to be pushed in release 7 branch
* EC - rename issue design in progress
* FUSE - no update
* POSIX -  no update
* DOC - no update
* Geo Replication - changelog update (Patch: https://review.gluster.org/#/c/glusterfs/+/23733/ Issue: https://github.com/gluster/glusterfs/issues/154 )
* libglusterfs - no update
* Glusterd - sanju working on lockless gluster volume info , vishal working on issue when brick fails when brick-mux on and a user case dealing with
* Snapshot - no update
* NFS - Proposal to change gNFS status - mail thread
* thin-arbiter - (Issue #763), support for add-brick, remove-brick

### Flash Talk Gluster
*


### Recent Blog posts / Document updates
* https://severalnines.com/database-blog/deploying-highly-available-nextcloud-mysql-galera-cluster-and-glusterfs
* https://itnext.io/oracle-always-free-cloud-instances-in-ha-configuration-e1d3dd59d3b1
* https://medium.com/@tumballi/gluster-a-proposal-for-better-future-6bd92ebf3cfc


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting?
    Rishubh will host the next meeting

  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting?
   

### RoundTable
* Gluster 8 plan
* use Github actions for easy ci/cd integration on github
* Developers to attend community meeting more often
* thin arbiter release details on release 7 update notes
* moving to centos 8 for upstream CI
* upgrading gerrit or moving to github to handle issues like merge conflict - deepshikha

### Action Items on host
* Check-in Minutes of meeting for this meeting
