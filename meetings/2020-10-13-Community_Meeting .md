# Gluster Community Meeting -  13/10/2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Details of this meeting

### Date/Time: Check the [community calendar](https://calendar.google.com/calendar/b/1?cid=dmViajVibDBrbnNiOWQwY205ZWg5cGJsaTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

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
* Saju Mohammed - Red Hat
* Pranith Kumar Karampuri - PhonePe
* Ravi (itisravi) -Red Hat
* Rinku Kothiya - Red Hat
* Rafi KC - iTernity
* Barak Sason Rofman - Red Hat
* Srijan Sivakumar - Red Hat
* Sunil Kumar - Red Hat
* Aravinda Vishwanathapura (aravindavk) - Kadalu.io
* Shwetha Acharya - Red Hat
* Csaba Henk (Red Hat)
* Sheetal Pamecha (spamecha) - Red Hat
* Vinayakswami Hariharmath - RedHat
 
### User stories
* None

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 62  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   83  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-October/thread.html)        |     9     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    574   |


* Any release updates?
    * Gluster release 7.8 announced on 30-09-2020
    * [Rinku] Release-8: I am not seeing pull requests in Release-8 branch 
        * Might get Delay Because of geo-rep regression failure

* Blocker issues across the project?
    * [Pranith] Regression test crashing in Github after migration
        * https://github.com/gluster/glusterfs/issues/1539
        * https://github.com/gluster/glusterfs/issues/1529
        * https://github.com/gluster/glusterfs/issues/1525


* Notable thread from mailing list
    * None


### Conferences / Meetups

* [Hacktoberfest](https://hacktoberfest.digitalocean.com/)
    * Event dates: The whole month of October.
    * Venue: Online


### GlusterFS - v9.0 and beyond
* Gluster release 9 roadmap [tracker](https://github.com/gluster/glusterfs/issues/1465)
    * [Saju] No major updates, will be updating the tracker.

### Developer focus

* Any design specs to discuss?
    * [Pranith] Design specs for DHT-rebalance
    * [Rinku] Tagging the PR with appropiate tags, will help in not missing out any of the important updates in the branch.



### Component status
* Arbiter - None
* AFR - [Ravi] Will be working on the patch, as per the comments.
* DHT - [Barak] Global layout update
* EC - None
* DOC - None
* Geo Replication - [Ravi] Problematic language update
    * [Shwetha] rsync config with verbose support, make passive worker sync self-heal traffic- request for review
* Glusterd - [Nikhil] enhancements to port mapper, 
    * [Srijan] cleaning up the code and improving the 5k vol with Brick Mux.


### Recent Blog posts / Document updates
* None


### Gluster Friday Five
* Every friday we release this, which basically covers highlight of week in gluster. Also, you can find more videos in youtube link.
  https://www.youtube.com/channel/UCfilWh0JA5NfCjbqq1vsBVA
  * No more updates are coming on this channel, so it can be removed from the agenda from next meeting onwards. 

### Host

* Who will host next meeting?
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* I notice that some people are tagging the pull request with appropriate tag. I would request everybody to tag it with correct branch so that none of the patches get missed for merging.
* Slack invitaion [link](https://gluster.slack.com/join/shared_invite/enQtODMwMDU5MTI0OTQ3LTNjMTA4NTJmMDY3OGM4YTA0ZDlhOGM5ZWYzNjRkYmQ0Mjg3NDUxODRjZGI4ZjQxNDczNTYxZWZjMmY5NDMyNzM#/)
* [Barak] Patch for rebalance update in DHT
    * [Issue](https://github.com/gluster/glusto-tests/issues/33) opened to improve glusto-test's framework, data correctness verification.
    * [Csaba] Updated the above issue with his findings on rsync.


### Action Items on host
* Check-in Minutes of meeting for this meeting
