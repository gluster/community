# Gluster Community Meeting -  08/09/2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Recording of this meeting-

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday {Date}, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968
* NA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Sheetal Pamecha (spamecha) - Red Hat
* Sunil - Red Hat
* Rinku Kothiya - Red Hat
* Shwetha Acharya (sacharya) - Red Hat
* Rafi KC (rafi) - iTernity
* Nikhil Ladha - Red Hat

### User stories
* [Rafi] Using worm xlators and other xlators for our use case at iTernity.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 76  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   82  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9% |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-September/thread.html)        |     25     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    529   |


* Any release updates?
    - Release 6 is EOL
    - minor release 7.8 is scheduled to release on - 30th Sep 2020
    - minor release 8.3 is scheduled to release on - 20th Sep 2020
        - [rinku]Following [https://www.gluster.org/release-schedule/]
    - Issue for release-9 RFEs is open, please update.
    - Important point : glusterfs-selinux dependency has been added to the spec file, so from now on we will have to ship glusterfs-selinux rpm for fedora/RHEL/centos.
    - Request the team to tag the Features so that we can include it in the release notes in the appropriate section.

* Blocker issues across the project?
    - Migration from gerrit to github


### Conferences / Meetups
* Ovirt Conference
Talk by Gobinda - Introduction to Ovirt Hyperconvergence
https://www.youtube.com/watch?v=ydaymbXUWd4&feature=youtu.be

*  COVID-19 has impacted the events!



### GlusterFS - v9.0 and beyond
* https://github.com/gluster/glusterfs/issues/1465
- [Sheetal] Feel free to add more items

### Developer focus

* Any design specs to discuss?


### Component status
* Arbiter - Nil
* AFR - coverity and log related patches
* EC - patches to take care of stale entries from indices/xattrop folder
* Sharding -  in fallocate path which is moved to 8.1 
    * https://github.com/gluster/glusterfs/issues/1425
* Geo Replication -  patch on sensitive languge is in WIP, also we have patch to address automount failures basically discovered on rhel 8
* thin-arbiter - Targetting add-brick, remove-brick and replace-brick support for glusterfs-9
   [Slack] - Many requests for providing add-brick, and also allowing distributed replicate configs for thin-arbiter.


### Recent Blog posts / Document updates
* https://medium.com/dev-genius/eventing-feature-in-glusterfs-e842d5f9bc5
* https://medium.com/@stevenyuan/staking-keep-on-a-raspberry-pi-cluster-with-ansible-kubernetes-k3s-glusterfs-and-more-10efe30539d4
* https://medium.com/dev-genius/distribute-volume-in-glusterfs-de167af1d518
* https://medium.com/dev-genius/replica-volume-in-glusterfs-b05324ce1b6f
* https://medium.com/dev-genius/rsync-5fd794e8c377
* https://medium.com/@sivakumarsrijan/the-glusterfs-journey-3439bd971c5ehttps://medium.com/dev-genius/using-gluster-setting-up-the-environment-and-installation-ef00122ab854


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA


### Host

* Who will host next meeting? Shwetha
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* [Sunil] upstream regression failures on centos 8
* [Saju] As per discussion with Deepshika, some issue was seen with respect to path spec.
* [Rinku] Release-7 branch centos regression failing, unable to merge those patches to the branch. 


### Action Items on host
* Check-in Minutes of meeting for this meeting


