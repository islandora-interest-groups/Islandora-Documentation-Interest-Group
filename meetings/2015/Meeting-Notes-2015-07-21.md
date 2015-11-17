# Documentation Interest Group Minutes - July 21, 2015 2:00 ET

## Attending:
* Gabriela Mircea (Chair)
* Robin Dean (Notes)
* Jaime Pinto
* Becky Yoose
* Kelli Babcock
* Melissa Anez

## 1) Approve last meeting minutes

Notes from last meeting:
https://github.com/Islandora/Islandora-Documentation-Interest-Group/wiki/Meeting-Notes-2015-06-16

* Gabriela will not be attending the conference. Kelli and Bryan are attending and can help facilitate the Docs IG meeting. Kelli will also be presenting a 10-minute overview of the Docs IG during the conference sessions.

## 2) Accountability time

Status of action items from last meeting.

* Robin will post meeting minutes. - Done!
* Robin will make deduplication spreadsheet and send to group. - Done!
  * https://docs.google.com/spreadsheets/d/1a58tGCj1XR41I15Gic6Ey1Hwphgr5gphFKTkpofJwEI/edit?usp=sharing
  * Discussed that we should make JIRA tickets for these instead, since no one signed up on the spreadsheet.
* Michael will contact Melissa to suggest how islandora.ca can help guide people to the wiki when the wiki is more current. - Done!
  * Melissa will look at Google Analytics data.
  * Melissa will unpublish outdated tutorials so they aren't confusing to new users.
  * Please email Melissa if you find any other outdated information on islandora.ca.
* Becky and Bryan will work together on the Contribute page. - In progress
  * There is an active discussion on the docs list about how to merge various contribution pages.
  * Will have a landing page that emphasizes interest groups as a way to figure out how to contribute to Islandora.
  * This wiki page will be a clearinghouse for ways to contribute.
  * Documentation on code contributions and development should be maintained by the developers/committers and linked to from the documentation wiki.
  * Docs IG should have a representative in charge of attending the committers' calls. Kelli has volunteered.
* Lingling completed a table of what versions of Fedora were tested with what versions of Islandora for the upgrade/migration page. - In progress
   * https://wiki.duraspace.org/pages/viewpage.action?pageId=68063509
   * Group will review and comment on discussion list.

## 3) Style guide
Need to assign this to someone to make a draft, and make a deadline so there's a draft by Sept 15 meeting.
* Gabriela will make a first attempt of this.

## 4) Documenting our processes & how we work as a group
(would like to share with Hydra and other communities)
* Review terms of reference and see if it needs updating. Robin will make a Google doc and suggest some edits/updates.
* Add more information to the wiki landing page.
* Active vs. inactive membership list
  *  How do we accurately reflect how many people are available to assign work to and participate in meetings? We want to be able to acknowledge those who have made contributions in the past without making our membership seem larger than it actually is.  
  *  The group will try making a "Former Members" list on the terms of reference, and will move formerly active members to that list if they miss 3 consecutive meetings without notifying the group or responding to emails from the group, or if they resign from the group.

## 5) Look at having permanent links to documentation
(rather than a version for each release) > reason behind this: some links hard coded in Islandora (see https://jira.duraspace.org/browse/ISLANDORA-1343 - discussed at 2015.07.10 Committer's Call)
* The Docs group agrees that hard-coding links in Islandora code to a docs page is not best practice, because the structure of documentation sometimes changes radically (beyond the version number). Instead, include the necessary information in the interface whenever possible.
* Docs IG did generally like the idea of having the current copy of the documentation that is always called "Current" while still maintaining the older, numbered release versions for reference. There was a long discussion about the process and workflow for managing a "current" version of documentation along with the existing workflow for making new copies of the documentation for each release.
* Workflow for making each new release version of docs the "current" one:
  1. Minor edits are made on Current until the documentation freeze date before the next version release.
  2. On the freeze date (about a month before the release), the wiki admin will create a clone of the "Current" space and name the new space "Release." Release will become the working copy of the next version of documentation. Release will be a hidden space while it is being worked on.
  3. When the next version of the software is released, the "Current" wiki is cloned to a version named with its version number and made available for reference.
  4. The "Release" version of the documentation is then published and replaces the contents of the "Current" version.

## 6) Where do users submit documentation changes?
* The group agreed to make JIRA the officially preferred location for submitting documentation issues. All issues should be tagged "Documentation."
* There isn't a way to get JIRA to email the Docs IG mailing list, so the group will need to check JIRA periodically. Use this filter to see only the Documentation issues: https://jira.duraspace.org/issues/?filter=13130
* Users with accounts can also make comments on the wiki, and we are leaving this functionality intact. Melissa will figure out if there is a way for the Docs IG list to get notifications when people make comments on the wiki. (Currently, only the creators/editors of wiki pages get notifications if there are comments.)
* If people comment on the wiki, we should acknowledge their feedback with a public comment and make minor corrections right away. If the correction is major or needs to be discussed or assigned to someone else, create a JIRA ticket. Because you can comment on the wiki only if you have an account, you can also go to the people's profiles in the wiki and email them directly. To reply to a comment, log in and go to the page the other person commented on.

## 7) Other topics
* Kelli will send an email to the group asking for suggestions for what she should present about at the Islandora conference.

## 8) Next Meeting, August 18, 2015, 2 PM ET

https://docs.google.com/spreadsheets/d/1TShQBPszHfjr5qUDUDT_jOhoGMcqj6isV1cyEbw3in0/edit?pli=1#gid=0

Chair: Robin

Notes: Kelli

### Agenda items for next meeting:
* Approve minutes from last time
* Accountability time!
  1. Robin: Post notes from last time
  2. Becky & Bryan: Finalize contribute page
  3. Melissa: Islandora.ca cleanup and Google Analytics
  4. Gabriela: Draft style guide (by Sept 15)
  5. Robin: Make document to review Terms of reference
  6. Robin: Update membership list in GitHub
* Discuss how we will assign and review JIRA tickets. A monthly review may not be enough.
* Discuss feedback from Islandora Conference.
