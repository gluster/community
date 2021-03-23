Gluster Community Meeting - 2019-04-23
===

### Previous Meeting minutes:

- http://github.com/gluster/community

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge 
* APAC friendly hours
  - Tuesday 30th April 2019, 11:30AM IST
  - Bridge: https://bluejeans.com/836554017
* NA/EMEA
  - Tuesday 23th April 2019, 01:00 PM EDT
  - Bridge: https://bluejeans.com/486278655

-------

### Attendance

* Raghavendra Bhat, Red Hat
* Amar Tumballi, Red Hat
* Raghavendra Talur, Red Hat
* David S, 
* Vijay Bellur, Red Hat
* Csaba Henk, Red Hat

### User stories

* David S:
  SETUP:
  GlusterFS - 5.5
  replica 3 volume
  SMB access (Samba + CTDB)
  Both big files (around 700MB) and small files (Around 1-10 MB)
  
  ISSUE:
  Write operations did not continue when failover happened
  Did not happen around a year ago

  RECOMMENDATION:
  Please send an email to gluster-users about the issue with
  /var/log/samba/ contents (they contain the log files of samba
  server and the gluster's plugin for samba)

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |   94   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   89   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|  65.3%   |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>14<br>10<br>4   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |    40      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   584   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   370   |


* Any release updates?
  
  GlusterFS-6.1 released
  
* Blocker issues across the project?
  
  performance changes by Xavi?

### Conferences / Meetups

* Amar Tumballi and Sahina Bose would be present @ Red Hat Summit, Boston (May 7-9). Specially at GlusterFS community booth.
*  Ravishankar N would be present at SDC India, Bengaluru, on May 23rd and 24th.
  

### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, and similar improvements.


### Developer focus

* Metrics of the week?
  - Number of patches from new developers.
     - Need a script to get this info.
  - Frequent test failures in the CI
     - What can be done to fix it properly ?


### Recent Blog posts / Document updates

### RoundTable


*  David S: Which release are the Permormance changes by Xavi targeted for?
         - Not in the near term (i.e. not GlusterFS-7.0) as it is ongoing effort
* David S: Any additional xlators to be cleaned up for GlusterFS-7.0?
         - Not currently planned for GlusterFS-7.0 as some cleanup happened
           for GlusterFS-6.x
* David S: What automation improvements are being done for GlusterFS-7.0?
         - Stricter Smoke tests
         - Reduced time for running automation 
         (https://review.gluster.org/#/c/glusterfs/+/19254/)
         - More .t files (tests) are being added to improve code coverage
