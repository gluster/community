# Gluster Community Meeting -  09/03/2021


### Previous Meeting details:

- [Meeting Minutes](https://github.com/gluster/community/blob/master/meetings/2021-02-23-Community-Meeting.md)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------

### Attendance
Name (#gluster-dev alias) - company
* Nikhil - Red Hat
* Pranith Kumar K - PhonePe
* Nishith Vihar S - Red Hat
* Sunil Kumar - Red Hat
* Amar Tumballi - kadalu.io
* Shwetha Acharya - Red Hat
* SajuMohammed - Red Hat
* Srijan Sivakumar - Red Hat
* Rinku Kothiya - Red Hat
* Aravinda - kadalu.io


### User stories

* rebalance: 
  - when we had 'readdir + stat' was way slower (~200x), compared to only readdir.
  - fsync cost - some fsyncs took upto 25second in few cases! Fails meet SLA. Can we do O_DIRECT writes, so we can avoid fsync?
  - rebalance start & rebalance stop was costly (doesn't serve any purpose!)
  - data movement - layout overlap is a costly operation!
  - Work around was to get the filelist in separate input files, and pass it to rebalance script, so we avoid crawling.



### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 64  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   89  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.6 % |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2021-January/thread.html)        |    8      |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    358   |

* Any release updates?
  - Request team to tag the patches that need to go in Release-9.1 

* Blocker issues across the project?
    * None
* Notable thread from mailing list
    * None

### Conferences / Meetups

* [SYSTOR 21](https://www.systor.org/2021/cfp.html)
    * June 14th - June 16th

* Talks related to gluster:
    - None.

* [SDC India 2021](https://www.snia.org/events/sdcindia)
    * Announcements regarding plans and dates for SDC India 2021 will be made in March.


### GlusterFS - v10 and beyond

* Gluster X Backlog - Under planning, a Github tracker will soon be added to track the issues.
    
### Developer focus

* Can we have a real-time check for coverity scan on each PR as a Github action? 
* Any design specs to discuss?
    * readdir through file [#2197](https://github.com/gluster/glusterfs/issues/2197)
    * Option dependency [#2019](https://github.com/gluster/glusterfs/pull/2019)
    * Simple-Quota is being deployed by kadalu.io team, and is working smoothly. Would be great to get it merged by GlusterFS X [#1750](https://github.com/gluster/glusterfs/pull/1750)


* How do we get to the internal faster? for a developer?
  - How can we help onboarding faster?
  - No Design docs, no overviews etc
  - Makes hard for external developer!
  - Transfer of knowledge is key for project's progress!
  - README.md in each directory!
  - The flow of how to go about the code understanding!
  - Videos are key!
  - Very very important for project's success!


* Why one Self-Heal daemon per node? instead of 1 per volume? 1 per brick etc?
  - Ideally we thought number of self-healing required is less, so one per node, for all volumes would be good enough.


### Component status
* Arbiter - Syntax update for volume creation [#2207](https://github.com/gluster/glusterfs/pull/2207)
* AFR - Stable
* DHT - Stable
* EC - Stable
* DOC - Stable
* Geo Replication - Stable
* Glusterd - Stable
* thin-arbiter - Stable


### Recent Blog posts / Document updates

* No new blog posts in the recent times.


### Host

* Who will host next meeting? - Srijan
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? - Srijan


### RoundTable

* Blog posts which have been written post Dec 2020 not reflecting in planet.gluster.org.
    * Infra issue : [118](https://github.com/gluster/project-infrastructure/issues/118)
* Plan to have video sessions on alternate tuesdays to discuss more on the in-depth working of different features/components of Gluster

### Action Items on host
* Check-in Minutes of the previous meeting
