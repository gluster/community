# Gluster Community Meeting - 2019-04-16
===

### Attendance

* Ravi, Red Hat
* Poornima, Red Hat
* Sheetal, Red Hat
* Sunny, Red Hat
* Ashish, Red Hat
* Amar, Red Hat
* Kotresh, Red Hat
* Deepshikha, Red Hat
* Xavier Hernandez, Red Hat


### Host

Current meeting host: [Amar Tumballi](mailto:amarts@gmail.com)
Next APAC meeting host: [AshishPandey](mailto:aspandey@redhat.com)

### User stories

* We didn't had any user joining us today.
* Agreed to discuss on specific usecase a particular feature was designed for, if there are only developers.

### Community

* Metrics
Project metrics:

|    Metrics                |   Value  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |   94   |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |   89   |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|  65.3%   |
|New Bugs in last 14 days<br>[master](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=mainline)<br>[ 6.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=6)<br>[ 5.x](https://bugzilla.redhat.com/buglist.cgi?bug_status=NEW&bug_status=ASSIGNED&bug_status=POST&f1=creation_ts&o1=greaterthan&product=GlusterFS&query_format=advanced&v1=-14d&version=5)                |   <br>20<br>20<br>7   |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2019-April/thread.html)        |    40      |
|[Total Bugs](https://bugzilla.redhat.com/report.cgi?x_axis_field=bug_status&y_axis_field=component&z_axis_field=&no_redirect=1&query_format=report-table&short_desc_type=allwordssubstr&short_desc=&bug_status=__open__&longdesc_type=allwordssubstr&longdesc=&bug_file_loc_type=allwordssubstr&bug_file_loc=&status_whiteboard_type=allwordssubstr&status_whiteboard=&keywords_type=allwords&keywords=&deadlinefrom=&deadlineto=&bug_id=&bug_id_type=anyexact&votes=&votes_type=greaterthaneq&emailtype1=substring&email1=&emailtype2=substring&email2=&emailtype3=substring&email3=&chfieldvalue=&chfieldfrom=&chfieldto=Now&j_top=AND&f1=noop&o1=noop&v1=&format=table&action=wrap&product=GlusterFS)       |   632   |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |   369   |

* Any release updates?
  - 6.1 pending
  - Need packaging volunteers.
  - Need a team to automate most of the release activities.
  - 5.6 tagging is done, testing of reduced n/w load shows good results. But seems to still have some issues with quick-read module.

* Blocker issues across the project?
  - None known at the time.

* Communication Update
  - Currently Gluster uses IRC, but the proposal is to move to Slack - https://gluster.slack.com
  - Need Archiver setup properly as there would be 10k lines backup only.
    - Expert help requested.
  - Also need proper invite bot, as the 'link' would get void after every 30days.
  - For those who want to join now, please join using [this link before 25th April, 2019](https://join.slack.com/t/gluster/shared_invite/enQtNTg5MTg1NDg5NzgyLWMwMGU5MzFkZjExNmQwOWE5YTNiODczOWFhMTk1ZmUyN2I3Y2EzNzNiMWMwMTgyMzYwMTU5NmI2MmFhNTAzZjU)

### Conferences / Meetups

* Amar Tumballi and Sahina Bose would be present @ Red Hat Summit, Boston (May 7-9). Specially at GlusterFS community booth.
* Ravishankar N would be present at SDC India, Bengaluru, on May 23rd and 24th.


### GlusterFS - v7.0 and beyond

* Proposal - https://docs.google.com/presentation/d/1rtn38S4YBe77KK5IjczWmoAR-ZSO-i3tNHg9pAH8Wt8/edit?usp=sharing
* Proposed Plan:
  - GlusterFS-7.0 (July 1st) -  Stability, Automation - Only
  - GlusterFS-8.0 (Nov 1st) - <Open for discussion> - Plan for Fedora 31/RHEL8.2
  - GlusterFS-9.0 (March 1st, 2020) Reflink, io_uring, path based geo-replication and similar improvements.


### Developer focus

* Any design specs to discuss?
  - [Xavi's shared thread discussion](https://lists.gluster.org/pipermail/gluster-devel/2019-April/056106.html)
  - [Dict hash changes Yaniv proposed.](https://review.gluster.org/22416/)

* Metrics
  - Number of patches from new developers.
    - Need a script to get this info.
  - Frequent test failures in the CI
    - What can be done to fix it properly ?


### Recent Blog posts in April
* [Gluster AFR: The Complete Guide (Part-1):](https://wp.me/peiBB-3Q) - Ravi
* [Gluster AFR: The Complete Guide (Part-2):](https://wp.me/peiBB-51) - Ravi
* [GlusterD volume scalability improvements in the next Gluster release:](https://atinmu.wordpress.com/2019/04/03/glusterd-volume-scalability-improvements-in-glusterfs-7/) - Atin
* [Improving Geo-replication Status:](https://gluster.github.io/devblog/improving-geo-replication-status) - Aravinda

### RoundTable

* Ashish: Can we invite 'users' we work with in email threads to this meeting?
  - Please do. The idea is to discuss more, make people aware of the things happening, and developers aware of usecases, issues.
* Ashish: Can we add a link to Blogs and major documentation added in the week?
  - Sure. (And is done in this notes itself)
* Poornima: What is the plan for upgrade testing? How can we automate it?
* Kotresh: Can the website reflect the details of this meeting, and also details of Slack channel?
* Kotresh: Where to find what tests we run during upgrade? How to contribute for the 'upgrade', multiple machine test cases? Mainly because I found .t tests, and glusto tests both are not enough for this at present.
  - This needs to be thought about and discussed. This should be treated as one of the major item for glusterfs-7.


