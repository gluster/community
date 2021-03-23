020# Gluster Community Meeting -  24-03-2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 24-03-2020, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968


-------

### Attendance
Name (#gluster-dev alias) - company
* Amar Tumballi (Kadalu.io)
* Aravinda (Kadalu.io)
* sankarshan (Kadalu.io)
* Sunny Kumar - Red Hat
* Hari Gowtham - Red Hat
* Sheetal pamecha - Red Hat
* Ravi(#itisravi) - Red Hat
* Deepshikha - Red Hat
* Rafi - Red Hat
### User stories
* [Amar] what happens when sharding is disabled was a question raised by an user on the mailing list.
* [sankarshan] oVirt+Gluster continuing effort highlighted in the same email about OKD+Gluster
* [ravishankar] responding to user (Strahil) who complained about VM not booting up (Amar opines it is the missing patch)
* [hari] announcing the Gluster release on announce list too. User provided feedback about this being required

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 59 |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   0  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|  71.1   |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                | couldn't track because of the movement to github.  <br> {value} <br> {value} <br> {value} <br>  {value}  |
|[Gluster User Queries in last month](https://lists.gluster.org/pipermail/gluster-users/2020-March/thread.html)        |     37     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    2   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    720   |

 - [hari] Clang count needs to be reviewed if the reported output is correct.
 - [hari] Discrepancy in total bugs reported in last meeting and the current state. Did the automation impact and bring this change?
 - [amar] The project-infrastructure bugs which are in a separate repo are likely the reason https://github.com/gluster/project-infrastructure


* Any release updates?
  * 7.4 is out and users are asking for https://review.gluster.org/#/c/glusterfs/+/24200/

[sheetal] Builds are in progress. ubuntu's launchpad has been updated. the rest will also be done.

* Blocker issues across the project?
  - Someone need to have a look at [#884](https://github.com/gluster/glusterfs/issues/884)
  - https://review.gluster.org/#/c/glusterfs/+/22492/ is the reason to suspect Shard feature. I suspect the issue still fails.

* Notable thread form mailing list
  - Deepshika's email on Bugzilla => Github migration.
  - the Github migration is being done in phases. Phase 1 is BZ --> Github; Phase 2 would be utilizing the entire range of Github workflow and actions


### Conferences / Meetups

COVID-19 impact is likely for events!

* Storage Developer Conference

Important dates:
CFP Closed : No (May 15, 2020)
Schedule Announcement :
Event Open for Registration : Yes (early bird registeration till 8/24/2020)
Last Date of Registration :
Event dates: September 21-24, 2020
Venue: Santa Clara, CA

Talks related to gluster:

* Devconf.us

Important dates:
CFP Closed : 27th April
Schedule Announcement : July 3, 2020
Event Open for Registration : July 3 2020
Last Date of Registration :
Event dates: September 23rd to 25th 2020
Venue:Framingham, MA.

Talks related to gluster:



### GlusterFS - v8.0 and beyond
* When is the good time to make release? branch?
  - [name=Amar Tumballi] prefers to have https://review.gluster.org/24163 reviewed and merged before, so by release 9, we can achieve lesser logs, and more accurate reasoning for errors.
    - https://kadalu.io/rfcs/0004-gluster-error-codes.html
    - https://github.com/gluster/glusterfs/issues/280



### Developer focus

* Any design specs to discuss?
  - Not sure if people saw this [Kadalu RFC](https://kadalu.io/rfcs/0005-external-control-plane-gluster.html), which would impact future Gluster management.
    - Feedback welcome!



### Component status
* Arbiter - nil
* AFR - nil
* DHT - email from Barak about changing stuff in DHT
* EC - Nil
* DOC - github work flow changes
* Geo Replication - SElinux related issues.
* Glusterd - Nil
* thin-arbiter - Nil


### Flash Talk Gluster
* Nil

### Recent Blog posts / Document updates
* Nil


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA
  - [name=Amar Tumballi] Can we revive this? Specially considering most people are at home, podcasts (and videos too) would work better to spread the word. - sankarshan will look into this and see what can be done

### Host

* Who will host next meeting? -rafi
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* We need to come up with a solid way on how to clone, set the release version, needinfo and so on with the github issues.
* Release management needs changes as it was done around bugzilla, and that has to be looked into and documented as well
* [Amar] Github migration - [Next Steps](https://docs.google.com/document/d/1SOPr56naVXXtkOmRu48xqKsefxM435UuN1Zoja2UhFE/edit?usp=sharing)


### Action Items on host
* Check-in Minutes of meeting for this meeting


