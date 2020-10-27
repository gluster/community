# Gluster Community Meeting -  27/10/2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Details of this meeting

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 13/10/2020, 02:30PM IST
  - Bridge: https://bluejeans.com/441850968
* NA
  - Every 1st and 3rd Tuesday at 01:00 PM EDT
  - Bridge: https://bluejeans.com/118564314


-------

### Attendance
Name (#gluster-dev alias) - company
* Nikhil Ladha - Red Hat
* sankarshan - Kadalu.IO
* Pranith Kumar Karampuri - PhonePe
* Vinayak Hariharmath - RedHat
* Ravi - Red Hat
* Sunil Kumar - Red Hat
* Amar Tumballi - Kadalu.IO
* Saju Mohammed - RedHat
* Shwetha Acharya - RedHat
* Aravinda Vishwanathapura (aravindavk) - Kadalu.io
* Csaba Henk - Red Hat
* Rinku Kothiya - Red Hat
* Barak Sason Rofman - Red Hat
* Deepshikha - Red Hat
* Srijan Sivakumar - Red Hat

### User stories
* No new stories.

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 61  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   87  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-October/thread.html)        |     13     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    401   |


* Any release updates?
    * [Rinku] We do not have enough patches tagged for Release7 and Release8 hence I propose to delay the release to next month, in case we get enough patches tagged for release-8 and release-7 we can consider releasing a build.  
    

* Blocker / Severe issues across the project?
    * [Amar] https://github.com/gluster/glusterfs/issues/1699
    * [Deepshika] [Document](https://docs.google.com/document/d/1Vxf24dLPSCmVBfJ7PfO5bN28r9slfyoJufZX2GOzlTc/edit?usp=sharing) mentioning the criterias to be a member of gluster org   [Under review]


* Notable thread from mailing list
    * None


### Conferences / Meetups

* [Hacktoberfest](https://hacktoberfest.digitalocean.com/)
    * Event dates: The whole month of October.
    * Venue: Online

### GlusterFS - v9.0 and beyond
* Gluster release 9 roadmap [tracker](https://github.com/gluster/glusterfs/issues/1465)
    * Everything is on track. Good progress on the issues.


### Developer focus

* Any design specs to discuss?
    * Updated permissions for running regression tests
    * Stale bot
        * Topic raised by Pranith around https://github.com/gluster/glusterfs/issues/910#issuecomment-706451616 with discussion around the [stalebot](https://github.com/gluster/glusterfs/blob/devel/.github/stale.yml) workflow. Pranith to raise an issue track proposed changes to kick in stalebot earlier than the 7 month cycle
        * https://github.com/gluster/glusterfs/issues/910 (look at the comment on stalebot)
        * We can choose to use a 'label'.
    * Quota - What next?
        * Check the RFC - https://kadalu.io/rfcs/0006-optimized-quota-feature-with-namespace.html
        * There is a need for the feature.

### Component status
* Arbiter - Stable / Maintained
* AFR - Update on granular self-heal entry
* DHT - [Barak] Will send out an invite for a session regarding Global Layout and Rebalance enhancments
* EC - Satble / Maintained
* DOC - [Pranith] Will be sending out a PR for updates.
* Geo Replication - Stable
* Glusterd - Stable / Maintained


### Recent Blog posts / Document updates
* None


### Host

* Who will host next meeting? [Nikhil]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting? [Nikhil]


### RoundTable

* No concerns


### Action Items on host
* Check-in Minutes of meeting for this meeting

