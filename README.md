## Computer go brrrrrr
## DoorOS


NOTE: Big Update is not the newest version, it is the first version. It's just named that because I forgot to change it.


DoorOS is a 64-bit operating system built from scratch.

It’s written in C and Assembly.

Features

64-bit long mode kernel

Custom bootloader / boot process

Paging and virtual memory management

Interrupt handling

Syscall interface

Basic scheduler

Virtual file system

Disk support

Graphics / framebuffer / GUI

Input drivers (keyboard and mouse)

Networking stack

Build

You will need:

GCC (or cross-compiler for x86_64)

NASM

GNU Make

QEMU (recommended)

GNU binutils

Build with:

make
Run
make run

Or manually:

qemu-system-x86_64 -drive format=raw,file=build/disk.img
Status

Active development. Expect bugs and crashes.


License
DoorOS License v1.2

Copyright (c) 2026 <Your Name>

Permission is hereby granted to any person obtaining a copy of this software and
associated documentation files (the "Software") to use, copy, modify, and distribute
the Software for personal, educational, and internal business purposes, subject to
the following conditions:

1. No Sale or Commercial Distribution
   The Software may not be sold, sublicensed, or distributed as part of a product,
   service, or offering for which a fee is charged.

2. Internal and Work Use Allowed
   The Software may be used within companies, organizations, or workplaces,
   including for development, research, testing, and internal tools.

3. Attribution
   Redistributions of the Software or substantial portions of it must retain this
   copyright notice and license.

4. No Warranty
   THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
   INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
   PARTICULAR PURPOSE AND NONINFRINGEMENT.

5. Limitation of Liability and No Legal Claims
   IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
   DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE,
   ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
   DEALINGS IN THE SOFTWARE.

   BY USING THE SOFTWARE, YOU AGREE NOT TO BRING ANY LEGAL CLAIM OR LAWSUIT AGAINST
   THE AUTHORS OR COPYRIGHT HOLDERS RELATED TO THE SOFTWARE.

6. Termination
   This license automatically terminates if you fail to comply with its terms.

7. Right to Modify License for Future Versions
   The copyright holder reserves the right to modify, replace, or release future
   versions of the Software under different license terms at any time.


8. Right to Discontinue
   The copyright holder reserves the right to discontinue distribution of the
   Software at any time.

9. Existing Copies
   Copies already obtained under this license may continue to be used under these
   terms unless the user violates the license.
