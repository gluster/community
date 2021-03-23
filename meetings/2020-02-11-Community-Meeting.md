# Gluster Community Meeting -  2020-02-11



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


### Attendance
Name (#gluster-dev alias) - company

* Amar Tumballi - Kadalu.IO
* Sunil Kumar  - Red Hat
* Aravinda (aravindavk) - Kadalu.io
* Hari Gowtham (#hgowtham) - Red Hat
* Ravi (itisravi) -Red Hat
* Sunny Kumar(sunnyk) -Red Hat
* Sankarshan - kadalu.io
* Yati Padia - Red Hat
* Rinku Kothiya - Red Hat 
* Shwetha Acharya (sacharya) - Red Hat
* Bala Konda Reddy - Red Hat
* Kotresh HR - RedHat

### User stories
* user tried it on mac mini. It was container based. Initially he faced issues with  peer probe and now he has moved on from that and is facing issues with mount. 


### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 55  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[7.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&list_id=10353290&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=7)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br> 04 <br> 02 <br> 04 <br>  00  |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-January/thread.html)        |     127     |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |    343   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    428  |

* State of OPEN/NEW bugs across components
  Updates (requires maintainers)

* Any release updates?
  - [Release 8] Enhancement Proposal window for features is over.
  - [Release 8] Let's focus on this release as a more stable, debug friendly release.
  
* Blocker issues across the project? Nothing here.

* [sankarshan] Project software pipeline health items
  - Gluster Infrastructure topics (smoke, regression): how is the regression?
  - Deepshika: around 8 to 9 tests are failing. Deepshika is looking into it. Smoke tests are fine.
  - fstat data (https://fstat.gluster.org/summary) discussion: Do take a look if its spurious or not. As per Deepshika observation, it's spurious.
  - Self heal, quorum validation failure are things that had failed.

* [sankarshan] State and updates on Gluster Test Framework
  Updates on Glusto (requires maintainers)  : Where are the tests run?
  Bala: Requires 8 node cluster (dedicated if possible). Need to sort it out with centos CI.
  restarts are another thing to be sorted out with the CI. We are covering deep dir and untar as a part of the Glusto test run. We have triggered it for Gluster-6. 700 test cases in place. can take 24 hours to finish.
  Deepshika: please do open an issue to track and fix this. Should be mostly permission issues. To get 8 machines we have to talk to centos CI. Can help bala in sorting out the permission issues and stuff.
  Sankarshan: would be nice to run it once on release-7

* [sankarshan] Gluster Documentation updates: Looking into What can be refreshed. Its substantial and outdated. Would need restructuring.
Ravi: docs related to thin arbiter need to be updated. Planing to send out an email regarding the same.

* [Rinku] Unable to run performance test for NFS Ganesha, even manual configuration is failing. Have been blocked on this. Unable to mount the shared volume. BZ#1785531

* [Amar] Github Migration - Sooner rather than later.
* 2 steps. 
* Bugzilla to github: straight forward. Labels required for workflow can be done.
* Reviews: split view is nearly the same as gerrit. Considering the other projects its good to move to github.
 
* [Sunny] Upstream health status:
* Sunny- 81/252 bugs. 81 bugs in is POST state Closed almost 20 to 30 bugs. a good number of patches are in abandoned state. please do take a look into it. 135 is in the NEW state . triaging will help us reduce it.

* [Rinku] In fosdem I met two people who complained about gluster performance drops from Release5 to Release7 about 90% when used with Samba. 
we have never run perf test on samba that is one more task we are planning to add to our perfromance test suit. Once tested will raise a bug for this.

* Notable thread form mailing list
  - Release-8 mailing thread
  - community meeting agenda and time: Timing is yet to be decided. Would be great to discuss with more people and come to a conclusion. 
  - EMEA has lesser participation. Need to find a common slot. 
  - Can think of just having EMEA and APAC. Once we get to see how this works we can extend it to US. Post lunch of Bangalore suits both EMEA and APAC (2:30/ 3 pm IST from next meeting.)
  - Sunny joined a meetup Scottish linux user group and there were almost 100 people there basically unawre of gluster so has asked moderator to give a timeslot for gluster presentation. He will talk about gluster in 2-3 months.


### Conferences / Meetups

* Gophercon India

Important dates: 
CFP Closed : 1st Feb 2020
Schedule Announcement : 
Event Open for Registration : open now
Last Date of Registration : 15th Feb 2020
Event dates: March 28th, 29th 2020
Venue: Goa

Talks related to gluster:
    
        

### GlusterFS - v8.0 and beyond
Need to have gluster-8 well tested. So the work that has gone in so far will be validated. Need to find the sweet spot between what each individual wants to do with gluster. Need to have a conversation with devs to understand what patch is worked for which release, what is supported and so on. Content planning has to be done. 



### Developer focus

* Any design specs to discuss?
* Nothing

### Infra
Nil


### Component status
* Arbiter - Nothing
* AFR - Ravi: saw a bug with splitbrain. working on what is happening. will send a fix soon
* DHT - nil
* EC - nil
* DOC - Sankarshan is looking into restructing and have sent a few fixes. Few github bugs opened by an user regarding outdated docs
* Geo Replication - Aravinda will send out doc changes to have non root as default.
* Glusterd - nil
* thin-arbiter - Amar working on an easy way to use thin arbiter. 
        (docker run --privileged -p 24007:24007 -v ${hostbrickdir}:/mnt/brick http://docker.io/kadalu/kadalu-tiebreaker')

### Flash Talk Gluster
nil

### Recent Blog posts / Document updates
* http://hrkscribbles.blogspot.com/2020/02/throttling-of-signing-process-in-bitrot.html


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA
  

  Sheetal and Shwetha are looking into it.
 

### Host

* Who will host next meeting? - Hari will host the next one.
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.
  

### Notetaker

* Who will take notes from the next meeting?
   

### RoundTable
Gluster devs aren't much active on Slack, better to be more active on slack. 
IRC? We do see a good amount of people joining IRC.

Any questions regarding thin arbiter during fosdem talk. Thin arbiter using Kadalu was mentioned. 
  We have to change the footer of the gluster-dev and user mailing list.
  Sunny joined a meetup and they didnt have any idea about Gluster. within a month or 2 Sunny should be giving a talk to the interested once.
  We need to look into K8 meetups and other such meetups which people would be interested and convey about gluster using that rather than having a specific gluster meetup.
  Users asked about georep and halo. more interested towards gluster-halo. Can it replace georep use cases.


### Action Items on host
* Check-in Minutes of meeting for this meeting

