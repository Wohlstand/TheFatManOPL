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


# Content of repository
- **showcase** - Music examples to show how these banks sounds.
- **wopl** - The copy of the C program to read and write WOPL files, dump their content and the full specification of WOPL format.
- **fatman-2op.wopl** - The Fat Man's 2-operator tone library, targeted to OPL2 chips that supports only the 2-operator mode. Can be used with OPL3 chip too having 18 voices instead of OPL2's 9.
- **fatman-2op-dump.txt** - The full description of The Fat Man's 2-operator tone library's content.
- **fatman-4op.wopl** - The Fat Man's 4-operator tone library, targeted to OPL3 chips that supports the 4-operator mode. This bank will don't work on OPL2 chip.
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
