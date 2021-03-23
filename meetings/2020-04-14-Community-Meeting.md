# Gluster Community Meeting -  14-04-2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 14-04-2020, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968


-------

### Attendance
Name (#gluster-dev alias) - company
* Rafi (#rafi) - Red Hat
* Hari Gowtham (#hgowtham) - Red Hat
* Sheetal Pamecha (#spamecha) - Red Hat
* Aravinda (Kadalu.IO)
* Amar Tumballi (Kadalu.IO)
* Rinku Kothiya - (#rinku) - Red Hat
* Sunny(#sunny) - Red Hat
* Ravi (@itisravi) - Red Hat
* Sunil Kumar - Red Hat
* Sanju - Red Hat
* Deepshikha - Red Hat
* Barak - Red Hat

### User stories
* https://lists.gluster.org/pipermail/gluster-users/2020-April/038026.html
* https://twitter.com/gluster/status/1247990943602495488

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 61  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   58  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    71.1 |
|New Issues in last 14 days<br>[master](https://github.com/gluster/glusterfs/issues?q=is%3Aissue+created%3A%3E%3D2020-03-24+)<br> |   <br> 28|
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-April/thread.html#start)        |     79     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    738   |


* Any release updates?

    - Release-5.13, tagging is done, Sheetal and shwetha are looking into building packages. Once that is done, we will announce the release.
    - 5.13 will be last release in branch 5.

    - Unlike the previous process, currently for both release 7 and 5, the same issue is being used, so I have tagged the issue with appropriate release while merging. 
https://review.gluster.org/#/c/glusterfs/+/24231/
https://review.gluster.org/#/c/glusterfs/+/24233/
discussion about how we are going to backport the patches. 

Xavi clarified earlier that we can use the same issue.
Rinku proposed to use labels to know that an issue is used for various branches as well

Template for tracker : 
https://review.gluster.org/#/c/glusterfs/+/24285/

Sanju : make changes in template to ask the reported to get the labels right from the maintainer atleast and would be better if we can give others the permission to assign labels.Amar: the reporter needs write permission in the repo.
Deepshikha:  created a team of dev. for this team, they will have permissions to add labels and other necessary values.


* Blocker issues across the project?
https://github.com/gluster/glusterfs/issues/884. has been merged in master

*Reduce number of release cycles - Announcement to user ML[hari]
*reach out to Amar and take the release-8 work forward to packaging.
*Tentative date for release 8 - end of April start branching
*https://www.gluster.org/release-schedule/ - update the release schedule in gluster.org [Rinku]. Hari will let him know the other issues in the website

* Notable thread form mailing list
    
    - glfs_fallocate() looks completely broken on disperse volumes with sharding enabled. tests/bugs/shard/zero-flag.t failed when changing the volume type to disperse.
    - Impressive boot times for big clusters: NFS, Image Objects, and Sharding
Rafi will ping the dev offline.
Ravi has a fix for the split-brain issue reported by user, needs to reach out to the reporter to see if it fixed the actual issue.


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

* https://sambaxp.org/

Important dates: 
CFP Closed : Closed 
Event Open for Registration : Open 
Event dates: 26th - 28th of May 2020
Venue: Online

Talks related to gluster:



### GlusterFS - v8.0 and beyond
*Have the release dates updated. Hari, Rinku and Amar will discuss about what is left for release 8 and get the dates right. and will take release-8 to a conclusion.

### Developer focus

* Any design specs to discuss?
Any effort done in the perf side of gluster? gluster vs other storage? any design change[sunil]
* [Ravi] I am working on a patch that adds io_uring functionality to posix xlator. Will create a github issue and share details once ready.
* while backporting please do add the release-branch label.
* 
### Component status
* Arbiter - Nil
* AFR - patch being worked on for spurious split brain
* DHT - Nil
* EC -Nil
* DOC -a few patches have been merged. One is how to run regression, move how to build rpm into dev side. the whole how to build RPM is yet to be updated with newer values
* Geo Replication - New test case for glusterfind is merged.
* Glusterd -remove brick operation is moved from opsm to mgmt v3 framework(because of a race in volfile creation and notify of clients) patch needs review.
* thin-arbiter - Nil
* Snapshot - snap scheduler was failing. Sunny has fixed the issue and added a testcase as well.


### Flash Talk Gluster
*nil 


### Recent Blog posts / Document updates
* Planet gluster needs fix [hari] it was fixed by misc[deepshikha]


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA
yet to be worked on.

### Host
Sunny has volunteered
* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* Permission to set labels for all dev[hari]
* Newly created group gives these permissions. please request to be added to it (https://github.com/orgs/gluster/teams/gluster-dev) [Deepshikha]
* Hackathon update https://github.com/gluster/glusterfs/issues/1154 https://docs.google.com/spreadsheets/d/1_j_JfJw1YjEziVT1pe8I_8-kMf7LVVmlleaukEikHw0/edit#gid=0

After release 6 we moved from n-3 to n-2.
We can send a mail out to know which one we can stop and when.
We will have a capping saying, we will support a release for 1 year or until n-2 support. which ever happens first.

Are the blogs in gluster related to gluster or other stuff such as kubernetes as well[Ravi]

code and test coverage needs some contribution. Maintainers please do take the right measures[Sunny]

### Action Items on host
* Check-in Minutes of meeting for this meeting
Please do add the gluster spurious test failure in the metrics. Sunny volunteered to do it.
