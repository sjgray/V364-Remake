Commodore V364 Prototype Remake Project   Steve J. Gray
=======================================

This is a project to remake the V364 prototype computer from Commodore.
This would have been the flagship model in the TED/264 series, and
would feature a larger case with numeric keypad and built-in speech
synthesis using a more integrated version of the Magic Voice cartridge
that was released for the C64.

This project will involve several different tasks:

1) Create a PCB that matches the existing prototype layout as close as possible.
2) Create a functional equivalent to the custom speech gate array chip.
3) Create a MX-switch compatible keyboard with numeric pad OR just the numeric
   pad that can be added along side a standard Plus/4 keyboard.
4) Create cherry MX keycaps.
5) Create 3D modelled cursor arrow keys and function keys.
6) Create a 3D modelled case of the V364 case to match the V36 motherboard
7) Create a 3D modelled case that will accept a Plus/4 motherboard and keyboard
   for those just wanting the look. Use addon numeric keypad.
8) Create a "Magic Voice" cartridge for existing 264-series computers.
9) Create an internal add-on speech board for Plus/4 or C16.
10) Create replica case badge.


Status Overview  **** This project is not complete!!!! ***
---------------

* V364 MX Keyboard has been completed and tested working. May need updating.
* V364 3D case is in development. Almost complete.
* V364 replica PCB is in development. Layout almost complete. No routing.


Keyboard
--------

A mechanical keyboard PCB has been produced with numeric pad. Custom cherry keycaps
were ordered from Maxkeyboard.com. These were tested on a real Plus/4 computer and
are working. A standalone MX numeric keypad PCB will be created for those wanting to
use a Plus/4 keyboard (feasibility to be determined).


Stand-alone Numeric Keypad
---------------------------

This has not been started, but will be just the numeric pad section of the full design.
The method of connecting a normal Plus/4 keyboard and addon numeric section needs to
be determined. Keycaps for the numeric pad are complete.


Keycaps
-------

Keycaps have been completed for the normal cherry type keys. The non-standard
function keys and arrow cursor keys have not been started. These will have to wait
for the 3D case to be completed.


Keycap Labels
-------------

 Custom colour printed keycaps were made by Maxkeyboard.com. A SVG file was submitted
in order to make the dyesub printed keycaps. This SVG file can also be used to make water-slide or vinyl sheet for using on blank keycaps.


Case
----

Initially I took 2 Plus/4 cases and modded them to resemble a V364 case. Of course
the function key area was wrong but it allowed me to test a Plus/4 motherboard and
the MX keyboard. The Plus/4 keyboard ribbon connector was replaced with a normal
pin header (like the C64) for testing.

A 3D replica case is being designed using the free version of Sketchup. It is mostly
complete but has not been printed. Final design will depend on the motherboard PCB
design to match port locations and mounting holes etc.

Badge
-----

I want to duplicate the real V364 badge. This was done in the same style as the Plus/4
badge. It uses raised silver logo, letters, and model# as well as the same multi-coloured
rainbow stripes. I think this will have to be done with separate printed components.
The base can be made of plastic with colour-laser printed sticker applied over top. The
rest will need to be resin-printed in order to get the proper detail and spray-painted
silver. Each will need to be glued on top of the sticker sheet. Currently only the silver
parts have been 3D modelled.


Motherboard PCB
---------------

A replica PCB is in progress using Kicad. The board dimensions and layout are mostly
done by underlaying a photo of a real V364 motherboard for alignment. The Plus/4 schematic was used as a base and the speech section was derived by work done by
Bo Zimmerman and Richard Atkinson. The Magic Voice schematic was used to obtain the
Toshiba T6721 chip pinout and audio output circuit.


Custom Gate Array
-----------------

This has not started. Since the V364 has been emulated it should be possible to
duplicate the functionality on some type of programmable logic chip and turned into
a pin-compatible plug-in board.


Speech Cartridge
----------------

This will be just the speech chips with an audio output jack. It will also need a
connection to the "F0" pin on the PLA inside the computer.


Project notes
-------------

I will release work-in-progress for anyone interested in following along. Anyone that
wishes to help is encourage to contact me.

Steve

