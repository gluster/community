# Gluster Community Meeting -  2020-02-25


### Previous Meeting minutes:

- http://github.com/gluster/community/meetings/
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 2020-02-25, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968


-------

### Attendance
Name (#gluster-dev alias) - company
* Team from Kadalu.IO (Amar, Aravinda, Sankarshan)
* Team from Red Hat (Hari, Sunil, Karthik, Yati, Ravi, Sunny, Sheetal, sanju, Rinku, Shwetha)
* David Spisla - Gluster Community

### User stories
* issue with worm xlator. David will send out a patch.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  57 |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|  70.9   |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 8 <br> 4 <br> 6 <br>  14  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-January/thread.html)        |     25     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    317   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    438   |


* Any release updates?
  - The 7.3 release's [fedora package](https://download.gluster.org/pub/gluster/glusterfs/LATEST/Fedora/glusterfs-fedora.repo) has issue. Path in server is 'f30', and this has 'fedora-30'.
  - scripts to migrate are ready (permission to close is unavailable. someone from redhat has to do it for now)

* Blocker issues across the project?
  - [Amar] Please check bugzilla -> github migration topic.
  - More on it @ [github issue](https://github.com/gluster/glusterfs/issues/824)


* Notable thread form mailing list
  - [Alternative option for GlusterFS](https://lists.gluster.org/pipermail/gluster-users/2020-February/037702.html)
      - user opinion matters, is project active, how stable is it and other such questions. How to make others know that there are happy users as well.
      - How many downloads are done is a way to show how active it is.
      - Who is using page on Gluster and let users fill that for us.
      - We can think more on this.
  - [netdata gluster plugin](https://lists.gluster.org/pipermail/gluster-devel/2020-February/056826.html)
      - expectation from many users. Devs can consider this as one of the AI and work on it.

### Conferences / Meetups

* Devconf.us
    * September 23rd to 25th 2020 in Framingham, MA.

Important dates:
CFP Closed : 27th April
Schedule Announcement : July 3, 2020
Event Open for Registration : July 3 2020
Last Date of Registration :
Event dates:
Venue:

Talks related to gluster:



### GlusterFS - v8.0 and beyond
* nil

### Developer focus

* Any design specs to discuss?
nil


### Component status
* Arbiter - Nil
* AFR - corner case of gfid split brain fixed
* DHT - nil
* EC - nil
* DOC - release notes, small changes then and there
* Geo Replication - nil
* Glusterd - bricks mux issue of multiple bricks being spawned is merged in master
* thin-arbiter - Ashish set a patch for client connection. merged on master.


### Flash Talk Gluster
* nil


### Recent Blog posts / Document updates
* please do submit it as per the steps [here](https://docs.gluster.org/en/latest/Contributors-Guide/Adding-your-blog/)


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA

  nil

### Host

* Who will host next meeting?
* Rafi?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
*
release - 7 has a lot of issues.
Better to test and then release.
the particular one announced has to be built and made available.
Ravi - bugs are raised on various components. One user encountered a crash on power pc architecture but I was not reproducible on x86_64. Just wanted to point out that there are folks using gluster on non-conventional archs.
Sunny - Use the order as per agenda.

### Action Items on host
* Check-in Minutes of meeting for this meeting

