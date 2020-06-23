# Gluster Community Meeting -  09-06-2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 09-06-2020, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968


-------

### Attendance
* Hari Gowtham (hgowtham) - Red Hat 
* Aravinda Vishwanathapura (aravindavk) - Kadalu.io
* Sunil Kumar  - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Rinku Kothiya (rinku) - Red Hat 
* Sanju Rakonde (srakonde) - Redhat
* Csaba - RedHat
* Federic stratic - A3Cube
* Naran
* Sankarshan - kadalu.io
* Deepshikha (dkhandel) - Red Hat
* Anandhu
* Sheetal Pamecha (spamecha) - Red Hat

### User stories
* Naren- using gluster as a backup filesystem. (Distributed-replicated)
* [Federico] I work for a company A3Cube and we are looking into gluster and ways to improve it. Looking for improvements to zero copy write in glusterfs.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  59 |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |  79 |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastStableBuild/Line_20Coverage_20Report/)|  70.9%   |
|New Issues in last 14 days<br>[master](https://github.com/gluster/glusterfs/issues?q=is%3Aissue+created%3A%3E%3D2020-05-26+)<br> |  18 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-June/thread.html#start)        |    19    |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    483 |

Clang issues have increased significantly and need to be looked at



* Any release updates?


    - Update on Release 8?
    - Rinku: Patches merged and tagged and waiting for the build. 

[Shwetha] Saw a few issues in debian and have resolved it. Few more issues to be addressed.


* Blocker issues across the project?
 Nil

* Notable thread form mailing list
 Nil


### Conferences / Meetups

COVID-19 impact is likely for events!

* Kadalu Community Conversations https://hackmd.io/MgF4KE6wT3iFaOZ-t0ivwQ
  June 16, 2020 1415 IST(UTC+0530)

### GlusterFS - v8.0 and beyond
Nil

### Developer focus

* Any design specs to discuss?
    * Please review https://review.gluster.org/#/c/glusterfs/+/24163 
    * Rafi's effort on Readdirp Performance Improvement (https://docs.google.com/document/d/10z4T5Sd_-wCFrmDrzyQtlWOGLang1_g17wO8VUxSiJ8)
    * Ravi working on Io-uring (https://docs.google.com/document/d/1vbvY0eBpElpNNlTaWyFGSj2ZRpPqBTW4gTSYiHYan70/edit)

### Component status
* Arbiter - Nil
* AFR - NIl
* DHT - Nil
* EC - Nil
* DOC - Nil
* Geo Replication - Working on user queries
* Glusterd - working on reducing writes - https://review.gluster.org/24524
* thin-arbiter - Nil
* Snapshot - Nil


### Flash Talk Gluster


### Recent Blog posts / Document updates
* [Sharing files across kubernetes clusters — the easy way](https://medium.com/russmediaequitypartners/sharing-files-across-kubernetes-clusters-the-easy-way-d1ea8f6e5149)
* [Docker Swarm Persistent Storage Using GlusterFS](https://medium.com/cloudnesil/docker-swarm-with-persistent-storage-using-glusterfs-48d8cdb84e7c)


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA


### Host
 Shwetha
* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* Infra team has worked and fixed planet gluster not taking up the blogs
* Gerrit to Github Migration
    * [Deepshika] Gluster related regression have to be moved. Looking into mergify.
* NetBSD and gluster
    * [Hari] Gluster is not tested with NetBSD for a long time  are we planning to support it. If not having it getting built for gluster might cause an inconvience for users. 
* [Aravinda] Look into the projects under gluster and update if its not being maintained. A good amount of questions are being asked about it.
* [Deepshika] Can get the list of projects and send out a mail and archive it based on the response.

### Action Items on host
* Check-in Minutes of meeting for this meeting
