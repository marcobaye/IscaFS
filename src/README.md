
* !IscaFS

This is the IscaFS application directory, but without the module.

* iscafs

This contains the source code to build the IscaFS module.

* !PNAsm

This is Phil Norman's assembler used to assemble the IscaFS module.

* !PCFNLib

This application holds Phil Norman's library files needed for assembling.

* PartTool

This program creates image files for IscaFS. It is written in C and it is
meant to replace the older programs "GetPartns" and "ReadPart" (see below).

* lsattr-isc

This is a little utility to display ext2 access mode bits on the RISC OS
command line. It is written in BBC BASIC.

* GetPartns

This is a little C program which will create pseudo-images so you can access
your ext2 partition(s) with IscaFS.  You need a C compiler if you want to
change this program. This program is now superseded by PartTool.

* ReadPart

This is a little program written in BBC BASIC which allows you to dump
entire ext2 partitions into ext2 image files.  It only works for the ADFS
'partitioning' system though. This program is now superseded by PartTool.
