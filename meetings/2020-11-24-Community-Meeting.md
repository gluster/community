# Gluster Community Meeting -  24/11/2020


### Previous Meeting minutes:

- http://github.com/gluster/community
- Details of this meeting

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
* APAC/EMEA friendly hours
  - Tuesday 24/11/2020, 02:30PM IST
  - https://meet.google.com/cpu-eiue-hvk



-------

### Attendance
Name (#gluster-dev alias) - company
* Sheetal Pamecha - Red Hat
* srijan-sivakumar - Red Hat
* Vinayakswami Hariharmath - Red Hat
* Sankarshan - Kadalu.IO
* Amar Tumballi - Kadalu.IO
* Rinku Kothiya - Red Hat
* Barak Sason Rofman - Red Hat
* Shwetha Acharya - Red Hat
* Csaba Henk - Red Hat
* Sunil Kumar - Red Hat
* Nikhil Ladha - Red Hat
* Pranith Kumar Karampuri - PhonePe


### User stories
* nil

### Community

* Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  | 62  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   87  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|    70.9 |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2020-October/thread.html)        |     12     |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |    407  |
|[Pending PRs](https://github.com/gluster/glusterfs/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc) | 63 |



* Any release updates?
    * Planning the release of Release 7 and 8 early next week.

* Blocker / Severe issues across the project?
  - Is it possible for everyone to be available on ['Slack'](https://join.slack.com/t/gluster/shared_invite/enQtODMwMDU5MTI0OTQ3LTNjMTA4NTJmMDY3OGM4YTA0ZDlhOGM5ZWYzNjRkYmQ0Mjg3NDUxODRjZGI4ZjQxNDczNTYxZWZjMmY5NDMyNzM)
  - Currently 326 users are there.
  - #development channel has 46 members.


* Notable thread from mailing list
    - [Docs on gluster volume options](https://lists.gluster.org/pipermail/gluster-users/2020-November/038949.html)

### Conferences / Meetups

* [Dec.Conf India](https://www.devconf.info/in/)
    * Event dates: December 17-19, 2020
    * Venue: Online

### GlusterFS - v9.0 and beyond
* Gluster release 9 roadmap [tracker](https://github.com/gluster/glusterfs/issues/1465)
    * Everything is on track. Good progress on the issues.

* When is the release? Are we planning to have enough features and then release? or is it based on time?

* Release Owner
  - Rinku, Saju and others

* Dates:
  - 11th Dec, 2020 is the plan



### Developer focus

* Any design specs to discuss?
  - [Amar] Has anyone tried Cloudsync translator before?


### Component status
* Arbiter - Stable/Maintained
* AFR - Stable/Maintained
* DHT - Stable/Maintained
* EC - Stable/Maintained
* DOC - Stable/Maintained
* Geo Replication - Stable/Maintained
* Glusterd - Stable/Maintained


### Recent Blog posts / Document updates
* https://vinayak-hariharmath.medium.com/glusterfs-get-core-dump-on-a-customer-set-up-without-killing-the-process-3e35e54de612



### Host

* Who will host next meeting? [shwetha]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable

* [Pranith] -  Can we focus more on milliseconds / seconds optimizations instead of nanosecond improvements?
  - The focus should be more on latency in network layer, system calls, Locks etc.
  - It is not bad, but is it worth the effort?
  - For introduction into glusterfs, best things that have impact are cleanups in fini().

* [Amar] -  Review request on Simple-Quota patches [PR #1750](https://github.com/gluster/glusterfs/pull/1750) and [PR #1763](https://github.com/gluster/glusterfs/pull/1763)


* [Nikhil] - github-updates stopped on slack


### Action Items on host
* Check-in Minutes of meeting for this meeting
