# Gluster Community Meeting -  24 Dec 2019


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday {Date}, 11:30AM IST
  - Bridge: https://bluejeans.com/441850968
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Yati Padia (ypadia) - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Hari Gowtham (hgowtham) - Red Hat
* Sunil Kumar Acharya - Red Hat
* Sheetal Pamecha (spamecha) - Red Hat
* Aravinda Vishwanathapura (aravindavk) - Kadalu.io
* sankarshan - Kadalu.io
* Rinku Kothiya (rkothiya) - Red Hat
* Karthik Subrahmanya (ksubrahm) - Red Hat


### User stories
* 


### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 53  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9% |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 11 <br> 3 <br> 2 <br>  2  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-December/thread.html)        |     57     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    355   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    432   |


* Any release updates?
  - done with 5.11
  - waiting  on build for 7.1
  - debian machines are slow
  
* Blocker issues across the project?
  

* Notable thread form mailing list
    - gluster volume heal info sometimes takes long time to run, it has been solved by Ravi- will be available for next release.
        - https://review.gluster.org/#/c/glusterfs/+/23883/

  

### Conferences / Meetups
* [Developers conference - {Dates}]({https://docs.google.com/spreadsheets/d/12QJMf0C59wnRUZXWDzNzswloofYe3uLF_8vEsWanOE0/edit#gid=0})

**[Devconf -  January 24-26, 2020](https://www.devconf.info/cz/)** -

Important dates: 
CFP Closed : Nov 1, 2019
Schedule Announcement : Dec 9, 2019
Event Open for Registration : Dec 9, 2019
Last Date of Registration : 
Event dates: Jan 24-26,2020
Venue:Brno, Czech Republic

**[Fosdem -  February 1-2, 2020](https://fosdem.org/2020/)**-
Important dates:
CFP Closed- closed for main track, for storage dev room - 24 Nov, 2019 Schedule Announcement- TBA
Event dates: 1 & 2 February 2020
Venue: Brussels (Belgium)

**[The Vault 2020 - February 24-25, 2020](https://www.usenix.org/conference/vault20)**

Important dates:
Talk proposals due:December 3, 2019, 11:59 pm 
Notification to accepted speakers:December 9, 2019
Early Bird Registration Deadline:February 3, 2019
Venue: SANTA CLARA, CA, USA


Talks related to gluster:


 Identifying performance bottlenecks in a cloud environment - Rinku Kothiya.
Evolution of Geo-replication in Gluster - Hari Gowtham
Blockchain for decentralized storage with gluster - Prajith Prasad
Thin Arbiter’ for glusterfs replication - Ravishankar Narayanankutty

    

### GlusterFS - v8.0 and beyond

  - GlusterFS-8.0 (March 18th, 2020) - <Open for discussion> - Plan for Fedora 31/RHEL8.2 
  tracker for release 8
          -  https://github.com/gluster/glusterfs/projects/1 
          - https://github.com/gluster/glusterfs/issues? q=is%3Aopen+is%3Aissue+milestone%3A%22Release+8%22
          - Sankarshan to work with amar
- GlusterFS-9.0 (August 1st, 2020) Reflink, io_uring, and similar improvements.


### Developer focus

* Any design specs to discuss?



### Component status
* Arbiter - nothing
* AFR - healinfo taking long time({https://review.gluster.org/c/glusterfs/+/23883/})
* DHT - nothing
* EC - nothing
* DOC - Had a patch from Kshithij. and have merged it.
* Geo Replication - old set of bugs, minor changes(waiting of the review)
* Glusterd - nothing
* thin-arbiter - nothing

### Flash Talk Gluster
* Typical 5 min talk about Gluster with up to 5 more minutes for questions


### Recent Blog posts / Document updates
*


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting?
  

### RoundTable
* Sankarshan: how to track untriaged bugs? Who will be looking into it?link to untracked bugs({https://lists.gluster.org/pipermail/gluster-devel/2019-December/056733.html})
* Hari: component owners?
* changes to be made on the agenda


### Action Items on host
* Check-in Minutes of meeting for this meeting

