# Tone libraries for OPL2 and OPL3 chips produced by The Fat Man.

Developed by K. Weston Phelan and George Alistair Sanger

Copyright (c) 1993-2025 The Fat Man (TM)

Author's Homepage: https://www.fatman.com/


# Description
There are original tone libraries for Yamaha OPL2 and OPL3 sound generator chips
developed by K. Weston Phelan and George Alistair Sanger who is known as "The Fat Man".
These banks were been widely used in various MIDI drivers and audio libraries
that played music via Yamaha OPL2 or OPL3 sound generator chips notable by
vintage PC sound cards such as AdLib, Creative Sound Blaster, Pro Audio Spectrum,
and many others. The 2-operator bank is notable by wide usage in sound card drivers
for the Windows 95/98/ME.

This is a preservation repository made by me (Vitaliy Novichkov) after direct
email conversation between me and the George Alistair Sanger who explicitly
granted the release of these banks under terms of the MIT license.

These banks can be freely used, redistributed, modified under terms of the MIT license.

# History
These banks were created by American composers Kevin Weston Phelan and George
Alistair Sanger using the Adlib Instrument Maker utility from the AdLib SDK and
included with the Miles Sound System (initially called IBM Audio Interfaces
Library). The Instrument Maker utility was given by John Miles to George and
Kevin with the set of the Miles Sound System toolkit.

These banks were made to simplify the music composing for developing
"The 7'th Guest" game with the goal to use the same MIDI file per melody
designed for all the supported sound cards. Initial variant of the bank
developed to match the instruments layout of the MT-32 until the General MIDI
standard released and applied to the musical instruments industry. Then, the
bank was reworked to use the General MIDI layout, and additionally, Geroge and
Kevin developed the bank for the Roland MT-32 to simulate the General MIDI layout.

Then, they gave their banks to John Miles to ship with his drivers so people
can use these banks for the credits and the one dollar given to George. Later,
these banks has been licensed from George's team by Yamaha and then by Microsoft,
and later, these banks introduced in the Windows drivers (primarily in drivers
for OPL2/OPL3-based sound cards using in Windows 9x).

During November of 2025, I (Vitaliy Novichkov) contacted to Gerge through his
email to request the MIT license, and now, these banks are officially licensed
under terms of the MIT license and preserved in this repository here for
everybody's usage.


# Content of repository
- **showcase** - Music examples to show how these banks sounds.
- **wopl** - The copy of the C program to read and write WOPL files, dump their content and the full specifications of WOPL and WOPLX formats.
- The Fat Man's 2-operator tone library (MT-32 variant), targeted to OPL2 chips that supports only the 2-operator mode. Can be used with OPL3 chip too having 18 voices instead of OPL2's 9.
  - **fatman-2op-mt32.wopl** - Binary WOPL variant.
  - **fatman-2op-mt32.woplx** - Text-based WOPLX variant.
- The Fat Man's 2-operator tone library (General MIDI variant), targeted to OPL2 chips that supports only the 2-operator mode. Can be used with OPL3 chip too having 18 voices instead of OPL2's 9.
  - **fatman-2op.wopl** - Binary WOPL variant.
  - **fatman-2op.woplx** - Text-based WOPLX variant.
  - **fatman-2op-dump.txt** - The full description of The Fat Man's 2-operator tone library's content.
- The Fat Man's 4-operator tone library, targeted to OPL3 chips that supports the 4-operator mode. This bank will don't work on OPL2 chip.
  - **fatman-4op.wopl** - Binary WOPL variant.
  - **fatman-4op.wopl** - Text-based WOPLX variant.
  - **fatman-4op-dump.txt** - The full description of The Fat Man's 4-operator tone library's content.
- **LICENSE.txt** - The MIT license, it must be included with the copied, modified, and/or re-converted into other formats bank files.


# License
  MIT License

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in all
  copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  SOFTWARE.
