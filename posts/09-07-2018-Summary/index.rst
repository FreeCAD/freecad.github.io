.. title: Summary of FreeCAD Development so far
.. slug: 09-07-2018-Summary
.. date: 2018-09-07 19:41:57 UTC
.. tags:
.. category:
.. link:
.. description:
.. type: text

Greetings to all FreeCADers, this post is created by a FreeCAD volunteer to keep the community up to date about how 0.18 development is progressing. Since FreeCAD has a pretty long release cycle (the team has decided on a yearly cycle)
this blog then will come in handy for folks that are really wanting to use the vibrant and prolific bleeding-edge of FreeCAD (AKA 'HEAD' or the master branch) where many bugs are being removed (Hopefully! :wink:) and new features being woven in for testing and refinement.

It is the intention that there will be a post at the end of each month of FreeCAD development updates. Though that may seem a little ambitious, it may not be far from reality. For example, one of the core developers, Yorik Van Havre, creates a blog post on his `website <http://yorik.uncreated.net/guestblog.php?tag=freecad>`_ for his supporters every month with an update regarding his monthly FreeCAD hacking activities. So at the very least we'll figure out a way to link to his blog posts.

The main goal of the 0.18dev cycle is to iron out all Python3 and Qt5 incompatibilities.

Summary
-------

* Tracking Python3 and Qt5 compatibility is ongoing. Ways to track progress: `Python3 and Qt5 Compatible Addon Workbenches (in preparation for 0.18) <https://forum.freecadweb.org/viewtopic.php?f=10&t=30624>`_. Many fixes provided by @looooo and @wmayer and others.
* An upgrade to the Start Page Workbench was `merged <https://github.com/FreeCAD/FreeCAD/pull/1617>`_. The UI has been modernized and updated with a Notepad that persists between FreeCAD sessions.
* Arch Stair was improved see `FreeCAD forum thread <https://forum.freecadweb.org/viewtopic.php?f=23&t=29358>`_
* Assembly3 port continues to receive a lot of attention and care for `@realthunder <https://github.com/realthunder>`_ and a lot of interest from the rest of the FreeCAD community. Progress of As3 can be followed on the `git repo <https://github.com/realthunder/FreeCAD_assembly3/>`_
* Several Sketcher Solver refinements made it in to master, thanks to `@abdullahtahiriyo <https://github.com/abdullahtahiriyo>`_
* New Workbenches added to FreeCAD Addon Manager: `SlopedPlanes <https://github.com/caceres/SlopedPlanesMacro>`_, `Lithopane <https://github.com/furti/FreeCAD-Lithophane/>`_, and `AirPlaneDesign <https://github.com/FredsFactory/FreeCAD_AirPlaneDesign/>`_
* GSOC 2018 participant, @kkremitzki, completed his assignment of heroically maneuvering through the dependency hell that FreeCAD requires. Many upstream dependencies have been updated and are either pending or part of the upstream Debian package repositories which will make compiling FreeCAD more uniform across most \*nix-based platforms.
