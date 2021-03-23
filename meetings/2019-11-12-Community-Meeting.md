# Gluster Community Meeting -  12 Nov 2019


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting - https://bluejeans.com/s/klEr1
    

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 12 November 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/441850968
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Sheetal Pamecha (spamecha) - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Rishubh Jain (risjain) - Red Hat
* Vishal Pandey - Red Hat
* Hari Gowtham - Red Hat.
* Sanju Rakonde
* Rinku Kothiya (rkothiya) - Red Hat.

### User stories
* Reduce locking Contention - patch posted upstream by chengwai - https://review.gluster.org/#/c/glusterfs/+/23685/


### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 54   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9% |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 4 <br> 6 <br> 1 <br>  1  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |     50     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    353   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    419   |


* Any release updates? 
Hari - release blocker for release 7 - planning to mark centos 6 issue as known issue(to be fixed in 7.1) and  proceed with release
     
* Blocker issues across the project?
Nil

* Notable thread form mailing list
Nil     
  

### Conferences / Meetups

* [Developers' Conference -](https://docs.google.com/spreadsheets/d/12QJMf0C59wnRUZXWDzNzswloofYe3uLF_8vEsWanOE0/edit#gid=0)

1. [Devconf.cz](https://www.devconf.info/cz/)
Important dates: 
CFP Closes- closed 
Schedule Announcement- TBA
Event Open for Registration- Dec 9, 2019
Last Date of Registration- TBA
Event dates- January 24-26, 2020
Venue- Brno, Czech Republic

2. [FOSDEM'20](https://fosdem.org/2020/)
Important dates: 
CFP Closed- closed for main track, for storage dev room - 24 Nov, 2019
Schedule Announcement- TBA
Event Open for Registration- 
Last Date of Registration- 
Event dates: 1 & 2 February 2020
Venue: Brussels (Belgium)

Talks related to gluster:
* [Name] [Topic] - [Conference]
    

### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (Blocked) -  Stability, Automation - Only
  - GlusterFS-8.0 (Feb 1st, 2020) - <Open for discussion> - Plan for Fedora 32/RHEL8.2
  - GlusterFS-9.0 (June 1st, 2020) Reflink, io_uring, and similar improvements.
  - Gluster X (December 2020)


### Developer focus

* Any design specs to discuss?



### Component status
* Arbiter - Nil
* AFR - Nil
* DHT - Nil
* EC - Nil
* FUSE - Nil
* POSIX - Nil
* DOC - Nit fixes
* Geo Replication - Backports to be merged
* libglusterfs - Nil
* Glusterd - Nil
* Snapshot - Nil
* NFS - Nil
* thin-arbiter - Nil

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions


### Recent Blog posts / Document updates
* https://severalnines.com/database-blog/deploying-highly-available-nextcloud-mysql-galera-cluster-and-glusterfs
* https://itnext.io/oracle-always-free-cloud-instances-in-ha-configuration-e1d3dd59d3b1
* https://medium.com/@harigowtham/glusterfs-quota-fix-accounting-840df33fcd3a
* https://medium.com/star-systems-labs/finding-gluster-volumes-in-kubernetes-d5552b495665

### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting? - Hari
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting

   

### RoundTable
* Status update on moving from gerrit to github.
* Reducing Regression time in upstream - Deepshikha and Barak

### Action Items on host
* Check-in Minutes of meeting for this meeting

