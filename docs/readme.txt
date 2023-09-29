﻿Finnish Trainset Fix 0.2 README
===============================

----------
0 Contents
----------

1   About
2   General information
    2.1  Requirements
    2.2  Installation
    2.3  Parameter settings
    2.4  Usage
3   Known issues
4   Background information
5   Frequently Asked Questions
6   Credits
7   Contact information
    7.1  Bug reports
    7.2  Other problems
    7.3  General enquiries
8   License
9   Obtaining the source


-------
1 About
-------

The Finnish Trainset is a NewGRF featuring Finnish Rolling stock from
1870 to present day. This trainset has been created by Finnish Trainset
team. See credits.


---------------------
2 General information
---------------------

2.1 Requirements
----------------
- OpenTTD 1.2.0 or nightly r23842, or higher
- Not compatible with TTDPatch


2.2 Installation
----------------
OpenTTD:
  see http://wiki.openttd.org/NewGRF
  This NewGRF is available from the ingame Online Content


2.3 Parameter settings
----------------------

Local, express and sleeper passenger MU/coach loading speeds can be 
defined using NewGRF parametres. Default values are:

Local: 40
Express: 25
Sleeper: 15

Purchase and running costs can be defined using NewGRF parametres.
Default parametres are:

Purchase cost setting: Medium
Running cost setting: Medium

Wagon and coach running costs can be turned on and off using
NewGRF parameter (Enable wagon and coach running costs)

Default setting for wagon and coach running costs is on.


2.4 Usage
---------
Everything in this set is Finnish rolling stock, in addition of several
wagon types from Eastern (Russian) and Western (Sweden, SeaRail)
interconnections.

Locomotives and multiple units featuring refitting are for deciding the
speed and traction effort suitable for freight or passenger operations
and/or livery refitting.

When livery refitting is available, the default setting is
year-dependent livery. That means when the livery is scheduled be
changed between specific years, locomotive, multiple unit or coach will
automatically update to the next livery.

The next option is build year livery, which means that locomotive,
multiple unit or coach will remain on the livery scheme as built. It
overrides the automatic update of livery, enabling former livery being
usable on the time when it's not otherwise available anymore.

The third option is to manually choose a livery from liveries already
introduced.

Speed and traction effort can be choosed at the same time (if locomotive
or multiple unit has one) with year-dependent, build year or manual
livery.

Wagon refitting behaves as in normal OpenTTD, there is cargo-specific
graphics on major part of wagons.

--------------
3 Known issues
--------------

Some wagons will appear too "tubeous" on consist. If you do notice too
tubeous wagons on consist, please report them to the Finnish Trainset
DevZone.



------------------------
4 Background information
------------------------

Information regarding rolling stock is provided from realiable sources.
Errors may exist, do report them when encountered.

Some locomotives and multiple units feature idling, accelerating and
running sound effects. They are used with permissions from several
parties:

Oskari Kvist, Ville Saarelainen, Suomen Rautatiemuseo (Finnish Railway
Museum), Lari Nylund, Juhana Konttinen, Niklas Savinsaari, 
Pietu Tuovinen, Mikael Sarhervo, Timo Keski-Pitäjä and others.

----------------------------
5 Frequently Asked Questions
----------------------------

Q: Why can't I use this in older versions of OpenTTD or TTDPatch?
A: This NewGRF uses some features only available to OpenTTD r23842 and
   newer. Furthermore, the most recent version of NML used to build this
   NewGRF, produces GRF version 8. This is only supported by OpenTTD
   r23166 and newer anyways.



---------
6 Credits
---------

Founder:
- Villem

Project leading and management:
- DanMacK (Dan MacKellar)
- Kyosuke1989 (Oskari Kvist)

Information basis:
- DanMacK (Dan MacKellar)
- as
- Lakie (Nathaniel Lake)
- Kyosuke1989 (Oskari Kvist)
- juzza1 (Jussi Virtanen)

Graphics (see individual graphic files in the source for details):
- DanMacK (Dan MacKellar)
- Purno
- Hairysteed
- jpl (Juhani Pirttilahti)
- Kyosuke1989 (Oskari Kvist)
- juzza1 (Jussi Virtanen)
- Emperor Jake
- alluke

Sound effects (see individual sound files in the source for details):
- Kyosuke1989 (Oskari Kvist)

Code:
- FooBar (Jasper Vries), initial DevZone-implementation
- juzza1 (Jussi Virtanen), NML-based coding on DevZone
- Lakie (Nathaniel Lake), earlier NFO-based coding

Translations:
- Finnish:  Kyosuke1989 (Oskari Kvist)

Makefile system:
- planetmaker (Ingo von Borstel)


Special thanks to everyone whom thanks is due.



---------------------
7 Contact information
---------------------

7.1 Bug reports
---------------
Please report any bugs you find at
  bug tracker: http://dev.openttdcoop.org/projects/finnishtrainset/issues
  or forum topic: http://www.tt-forums.net/viewtopic.php?f=26&t=21457

Always included a detailed description of the bug, preferrably with
screenshot and savegame. Also state the exact game version you're using,
as well as the version of this NewGRF.

If you have a savegame that includes NewGRFs not available on OpenTTD's
Online Content, then please try to reproduce the bug in a new game
which has all NewGRFs easily accessible.

If you're using a patched version of the game, please try to reproduce
the bug on an official game build. If you can't reproduce the bug, then
don't report it here but in the forum topic of the patch(pack) instead.


7.2 Other problems
------------------
If you have any problems using this NewGRF that are not covered in the
Frequently Asked Questions above, then you can ask your questions in the
forum topic: http://www.tt-forums.net/viewtopic.php?f=26&t=21457


7.3 General enquiries
---------------------

If you have any queries that cannot be asked in the forum topic, then
contact kyosuke1989 via Private Message at www.tt-forums.net.



---------
8 License
---------

FTS - Finnish Train Set
Copyright (C) 2013 Finnish Trainset Team

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.



----------------------
9 Obtaining the source
----------------------

The source code can be obtained from the #openttdcoop DevZone
via source browser:
    http://dev.openttdcoop.org/projects/finnishtrainset/repository
or via mercurial checkout:
    hg clone http://hg.openttdcoop.org/finnishtrainset
or via a source bundle download (releases only):
    http://bundles.openttdcoop.org/finnishtrainset/

How to build from source and the requirements for that are included
with the source in the file /docs/building_from_source.txt.
