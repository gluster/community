# Gluster Community Meeting -  23rd June, 2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-
    

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 23rd June, 2020, 11:30AM IST
  - Bridge: https://bluejeans.com/441850968
* NA/EMEA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
* Shwetha Acharya - (RHT)
* Adrian Quintero - 
* Amar Tumballi (Kadalu.IO)
* Rinku Kothiya (Red Hat)
* Aravinda Vishwanathapura (Kadalu.io)
* Srijan Sivakumar (Red Hat)
* Karthik Subrahmanya (Red Hat)
* Sheetal Pamecha (Red Hat)
* Hari Gowtham (Red Hat)
* Rafi (iTernity)
* Nikhil Ladha (Red Hat)
* Deepshikha (Red Hat)
* Sunil Kumar (Red Hat)
* Anandhu Manoj - 

### User stories
* gluster status
* [Adrian] uses gluster for storage in VMs
    * using gluster 6. 
    * Concerned about recovery
    * [Adrian]  concern is actually about production impact and which version is more stable i.e. I had issues with 6.6, 6.8 due to permission denied (ACL related) so I downgraded to 6.5


### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  54   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/)| 78   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)| 70.9%    |
|[New Issues in last 14 days<br>master](https://github.com/gluster/glusterfs/issues?q=is%3Aissue+created%3A%3E%3D2020-06-08)|   <br> 36 <br> 
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-June/thread.html)        |  16 -116msgs       |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |  4    |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |  508     |


* Any release updates?
  [Hari]
  - The published upgrade guide refers to upgrade gude of 4.x working on       creating a generic upgrade guide which can be used in its palce  

  - Did not hear any complains about the Release-8rc0 will make that the 
    final release comming week. 
    
  - This will be the last release for Release-6
  [Hari] Inhouse testing is needed before release
  [Amar] Upgrade from different versions and for different volumes by maintainers
  [Rinku] will test day be a good idea? - agreed
  
* Blocker issues across the project?
  [Amar] ACL issues from mailing list - having look on the Acl usses will be useful
         No of logs can be reduced
  [Aravinda] Amar's error code patch
  [Amar] Cant be promised release8 - need to be worked on certain issues 

* Notable thread form mailing list
    [Gluster-users] State of Gluster project
    [Aravinda] a good thread, can have a maintainers meeting to prioritise things
    - Learnings: 
      - Debug Tools: Need of the hour
      - NFS use cases with Gluster (many people mentioning about it)
      - Performance is a major issue
      
  

### Conferences / Meetups
COVID-19 impact is likely for events!

### Github Migration

* Infra team is ready with the possible steps
* @amarts opened https://github.com/gluster/project-infrastructure/issues/62
  - glusterfs issue is - https://github.com/gluster/glusterfs/issues/1330
  - Request you to have your opinion recorded if not in favour
  - Last day to consider that would be 30th June, 2020.
  - We plan to start the migration process By July 1st.

    

### GlusterFS - v8.0 and beyond

* Should we reduce days of inactivity to 4 months from current 7 months (210 days) ?
  - [Aravinda] Should we keep it alive for the life-cycle of release?

 


### Developer focus

* Any design specs to discuss?
[Rafi] have been working on Readdirp Performance Improvement (https://docs.google.com/document/d/10z4T5Sd_-wCFrmDrzyQtlWOGLang1_g17wO8VUxSiJ8)
Have sent out a mail regarding the same


### Component status
* Arbiter - Fixed a problem with the quorum logic in arbiter volumes
* AFR - Fixed an issue with migration failures in case of add-brick & rebalance scenario
      - Delayed post-op of fsync to improve the performance of fsync heavy workloads
* DHT - [amar]good amount of patches from team 
* DOC - Upgrade guide contributed by Rinku
* Geo Replication- user queries have been addressed
* Glusterd - add-brick command failing. The patch is merged and command works successfully
* Snapshot - Nil
* thin-arbiter - Nil

### Flash Talk Gluster
*


### Recent Blog posts / Document updates
* GlusterFS quota accounting mismatch(https://medium.com/@harigowtham/glusterfs-quota-accounting-mismatch-9478bc2eaf0a)
* Debian and ubuntu packaging from the same machine(https://medium.com/@harigowtham/debian-and-ubuntu-packaging-from-the-same-machine-5a0ee4e74e07)


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster.Also you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

### Host

* Who will host next meeting? - Amar

  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting?
   

### RoundTable
* [Aravinda] close the stale projects from gluster repo
* [Deepshikha] 4-5 issues failing on centos8 regression
* [Aravinda] initiate the mail thread for maintainers meeting

### Action Items on host
* Check-in Minutes of meeting for this meeting

