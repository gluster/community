# Gluster Community Meeting -  26/04/2022


### Previous Meeting minutes:

- [Meeting Minutes](https://github.com/gluster/community/tree/master/meetings)

### Date/Time: Check the [community calendar](https://calendar.google.com/event?action=TEMPLATE&tmeid=MDQ0YmRydTllMXYzdWFoMmpsbjdqNXJlYmNfMjAyMDEwMjdUMDkwMDAwWiBzYWptb2hhbUByZWRoYXQuY29t&tmsrc=sajmoham%40redhat.com&scp=ALL)

### Bridge
  - 2nd / 4th Tuesday's, 02:30PM IST
  - Bridge: https://meet.google.com/cpu-eiue-hvk


-------


### Attendance
Name (#gluster-dev alias) - company
* Chetan More - Red Hat
* Pranith Kumar K - PhonePe
* Nikhil Ladha - Red Hat
* Amar Tumballi - Kadalu
* Rakshitha Kamath - Red Hat
* Harshita Shree - Red Hat

### Community

* Project metrics:

|    Metrics                |   Value (Last meeting)  |
| ------------------------- | -------- |
|[Coverity](https://scan.coverity.com/projects/gluster-glusterfs)  |  18(27)  |
|[Clang Scan](https://build.gluster.org/job/clang-scan/lastBuild/) |    64(80)  |
|[Test coverage](https://build.gluster.org/job/line-coverage/lastCompletedBuild/Line_20Coverage_20Report/)|     71.1(71.1) |
|[Gluster User Queries in last 14 days](https://lists.gluster.org/pipermail/gluster-users/2022-March/thread.html)        |     4    |
|[Total Github issues](https://github.com/gluster/glusterfs/issues)       |     198(203)  |


* Any release updates?
    * Release updates
         * 9.x will receive updates once in 6 month
         * 10.x will receive update once in 3 month
         
         [Shwetha] Next tentative dates:
         * 9.x   : Week of 20th Aug
         * 10.x  : Week of 15th May 
 
   - [Amar] Can the community agree to make a immediate release if we fix a CVE/Crash bug? The release can just have tarball from glusterfs community, and users who are impacted can work on getting their own rpm/deb packages if needed in that cases (if release team feels its too much of work). But not making a release (of at least a tarball) for CVEs and crash fixes is not a good thing for the project IMO.

* Blocker issues across the project?
    * None


* Notable thread from mailing list / User stories
    * None



### Conferences / Meetups

#####  Storage Developer Conference Global(SDC)
   - Date: September 19-22, 2022
   - [Call for proposals of presentations](https://storagedeveloper.org/events/sdc-2022/speakers/call-for-presentations)
   - Deadline to submit proposals: June 17th


#####  Storage Developer Conference EMEA
   - Date: June 14,2022
   - check [link](https://www.snia.org/events/sdcemea) for more information
   - Registeration will open at end of April 2022.
   
#####  Red Hat Summit 2022
   - Date: May 10-11,2022
   - check [link](https://www.redhat.com/en/blog/save-date-red-hat-summit-2022) for more information   


### GlusterFS - v11.0 and beyond
*   Please add the planned feature list to the [tracker](https://github.com/gluster/glusterfs/issues/3023)
*   Amar - [O_PATH support](https://github.com/gluster/glusterfs/issues/2717)




### Developer focus

* Any design specs to discuss?
  - simple-quota: PR Is merged now. Pranith had some questions.
  - One of them was why changes in DHT for simple-quota. 
    - This helped reduce the complexity of Quota feature by reducing the challenge of running a separate daemon process (like quotad). Some 10 lines saved the whole aggregation process as a separate one, thus making management and maintenance simple.



### Component status
* Arbiter - stable/maintained
* AFR - stable/maintained
* DHT - stable/maintained
* EC - stable/maintained
* DOC - stable/maintained
* Geo Replication - stable/maintained
* Glusterd - stable/maintained
* thin-arbiter - stable/maintained
  - Who is maintaining this? Can we make sure docs are up-to-date for thin-arbiter?

### Recent Blog posts / Document updates
* None


### Host

* Who will host next meeting? Chetan.
  - Host will need to send out the agenda 24hr - 12hrs in advance to mailing list, and also make sure to send the meeting minutes.
  - Host will need to reach out to one user at least who can talk about their usecase, their experience, and their needs.
  - Host needs to send meeting minutes as PR to http://github.com/gluster/community
  - Host has to send the meeting minutes as a mail to the gluster-devel and gluster-users list.


### Notetaker

* Who will take notes from the next meeting?


### RoundTable
* [Amar] Was the training videos/sessions helpful?
   - Yes (answer from few)


### Action Items on host
* Check-in Minutes of meeting for this meeting
