# Gluster Community Meeting - 14/02/2023

### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge

- Monthly, 2nd Tuesday, 02:30PM IST
- Bridge: https://meet.google.com/cpu-eiue-hvk

---

### Attendance

Name (#gluster-dev alias) - company

- Niraj Yadav - IBM
- Sanju Rakonde - PhonePe
- Rakshitha Kamath - IBM

### Community

- Project metrics:

| Metrics                                                                                                            | Value (Last meeting) |
| ------------------------------------------------------------------------------------------------------------------ | -------------------- |
| [Coverity](https://scan.coverity.com/projects/gluster-glusterfs)                                                   | 87 (94)              |
| [Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/)                                                  | 64 (64)              |
| [Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)          | NA* (71.2)          |
| [Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2023-January/thread.html) | 6                    |
| [Total Github issues](https://github.com/gluster/glusterfs/issues)                                                 | 166                 |

- Any release updates?

  - RC under testing

- Blocker issues across the project?

  - None

- Notable thread from mailing list / User stories
  - None

### Conferences / Meetups

- None

### GlusterFS - v11.0 and beyond

- RC for release 11 is under upgrade testing
- Found a small bug while upgrading on Debian. Patch backported to release-11.

### Developer focus

- The jobs which builds and upload [rpms](https://artifacts.ci.centos.org/gluster/nightly/devel/8-stream/x86_64/?C=M;O=D) for devel branch has been migrated to a [new OCP cluster](https://console-openshift-console.apps.ocp.cloud.ci.centos.org/topology/ns/gluster) and the jenkins instance can be found [here](https://jenkins-gluster.apps.ocp.cloud.ci.centos.org).

### Component status

- Arbiter - stable/maintained
- AFR - stable/maintained
- DHT - stable/maintained
- EC - stable/maintained
- DOC - stable/maintained
- Geo Replication - stable/maintained
- Glusterd - stable/maintained
- thin-arbiter - stable/maintained

### Recent Blog posts / Document updates

- None

### Host

- Who will host next meeting? [Niraj]
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.

### Notetaker

- Who will take notes from the next meeting? [Niraj]

### RoundTable

- Recording of the talk from Pranith(PhonePe) and Sanju(PhonePe) at Fosdem can be seen at https://fosdem.org/2023/schedule/event/sds_lessons_learnt_glusterfs/

### Action Items on host

- Check-in Minutes of meeting for this meeting
