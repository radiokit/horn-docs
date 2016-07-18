Getting Started
===============

RadioKit Horn is a web-based playout, automation and a switch in one system.
You can prepare there content for a Christmas time, or have a backup stream
for times of electrical surges or your internet downtime. Or you can just
schedule exact playlist or programmes repeats for a nightime time or a weeekend,
when you want to have the live studio empty.
It can work as an event studio letting journalist switch between streaming live
and playing music, jingles or commercials from the cloud.


Library - Depot
^^^^^^^^^^^^^^^

To be able to schedule files  you need to have a library first -
if you want to know how it works - please see http://depot-docs.radiokit.org
If in this docs you'll encounter some unclear terms like tag or repository -
it may mean you should refer there as well.


Auto-scheduling
***************

Heart of the Horn is automatic scheduler. It works in week cycle, which means you
can define rules, that are going to be repeated each week. (I.e. Sunday morning selection,
late Friday night selection etc).

This is the feature that is going to be developed in future to satisfy most fastidious needs.
For now it can shuffle from the group of chosen tags or shuffle from the newest files that were
uploaded into your repository.


To set-up weekly rule you should go to Broadcast/Auto and click Add Automatic Scheduler.
This will open a modal, where you need to choose type of shuffling. Next you need
to pick tags from your repositories from where system will take files to schedule.
You can pick multiple tags from different repositories. If you choose more than one tag -
you can set percentage of the tag presence in the scheduled playlist.
After that just need to pick the days of the week and exact time, which is going to be
filled with that rule. Optionally you can name your rule, to easily distinguish it later on.

If you have more then one content type - you will have to choose to which content type the rule belongs.


(note: you won't see instant changes in the Broadcast/Schedule as the systems is planning the schedule
each minute just for a 30 minutes ahead, allowing you to plan things manually as well)


Adding single file
******************

If you want to schedule particular file at exact time of a concrete date - you need to go to
Broadcast/Schedule and click the button Add Track. It will open for you a window with a live search
engine that is going through all your repositories. Auto-suggestion will pop-up to you with last files uploaded.
After you will have done searching - you can specify the time when the files should start. For obvious reasons
you can't amend the end of the files, as its define by the file duration.
Optionally - you can change the name under which the file is going to show up in the playlist (it doesn't changes
the filename itself - just the name of this one execution).


If you have more then one content type - you will have to choose to which content type the rule belongs.




Content Types
*************

Content types are made for the purpose of clear browsing and tracking past or planned
broadcasts.

If you plan your schedule in blocks, like news, commercials, music, repeats etc. -
you can create for each of them a content type. After you done that - you can assign
the type at the end of both modal for automatic scheduling, and modal for adding
particular files to the schedule.

Why should you do that? It will make your searches through the schedule a lot easier,
and it will be more comfortable to track past broadcasts.

(note: You need to have at least one content type)


Workflow
********

To have an auto-generated playlist with rule defined by you, you need:
- have uploaded files, that has assigned tags;
- move the files to Ready stage;
- create at least one content type (i.e. music)
- add an Automatic Scheduler for period of the week.

(note: system is planning the schedule for just a half an hour ahead, so probably you won't
see your changes instantly - they'll show up when its time come)






.. toctree::
   :maxdepth: 2
