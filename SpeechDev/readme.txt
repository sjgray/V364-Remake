Commodore V364 Prototype Remake Project   Steve J. Gray
=======================================

This is a project to remake the V364 prototype computer from Commodore.
This would have been the flagship model in the TED/264 series, and
would feature a larger case with numeric keypad and built-in speech
synthesis using a more integrated version of the Magic Voice ("MV")
cartridge that was released for the C64.


SPEECH DEV BOARD
================

This is a development board that lets you experiment with adding speech to
any 264-series machine. It contains sockets for developing either type of
speech method:

* V364 - Uses V364 custom Gate Array and the Toshiba T6721A chips
* Magic Voice - Uses 6525 TPI, GI Logic Array and T6721A chips.

**** IMPORTANT!!! Install only the chips in the correct set!


CONNECTIONS
===========

The board is connected to one ROM socket of the 264 machine via a ribbon cable,
or using a header under the board (depending on computer and clearance).
The ROM from the computer is installed on the Dev board and the V364 Speech ROM
or modified speech ROM are installed in the other socket.

There are a bunch of flyouts to connect to various places on the computer pcb.

PLA F0 - The PLA F0 pin controls the 6525 or Custom Gate Array
CS_SPEECH - Connects to ROM control C2_HI.
R/W - Connect to Read/Write line.
PHI0 - Connect to PHI0 line.
IRQ - Connect to IRQ line.
AUDIO_IN - Normally not used but can connect to a SID board etc
AUDIO_OUT - Connects to EXT_AUDIO line (cartridge connector)

