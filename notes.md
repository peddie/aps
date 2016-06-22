Areo-Positioning System
=======================

Value
-----

Has to be incidental to existing missions.

Value to be had in running multiple services from one cheap
constellation.
  - positioning
  - timing
  - communications
  - weather observations?

OD
--

Constellation Design
--------------------

Single groundstation, mainly for referencing positions to the surface

Timing
------

MP: Absolute time (as opposed to globally consistent time) may be
useful for astromony and geodesy tasks, possibly common in a colony.

Positioning
-----------

Chipping faster for better accuracy -- no problem with modern electronics

Longer code -- better gain

Mars has an ionosphere -- 2 frequencies at least

Could send signals without nav messages on some bands -- integrate as
long as you want (good for surveying)

Define user algorithm and error models

Comms
-----

Bandwidth requirements: ~100Mbps capacity per-sat; "This is the
future; we need to be streaming Martian porn from one end of the
planet to the other." -- HH

"How are we going to serve them ads?"  -- BM

Link design for ground users.  Toughest constraints:
  - power budget
  - sat size

HH proposes: fixed spot areas with satellite handover.
