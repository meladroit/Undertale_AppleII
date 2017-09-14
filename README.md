# Undertale for the Apple II
## or rather, an Undertale music/graphics demo for Apple IIe/IIc computers
The basic idea here is to build software capable of running the UnderTale intro (and a few extra songs) on the Apple IIe/IIc, without any expansion cards or extra memory!

There are four files here:
* this readme;
* a PDF with some barely annotated 6502 assembly source code for selected routines;
* UnderTale.do, which is the DOS-ordered sector image for side A of the diskette;
* and UnderTale jukebox.do, which is the image for side B.

To try it for yourself, transfer both sides to a diskette using ADTPro or similar software. Insert side A and start up your Apple II, which should then boot into Beagle Bros' Pronto-DOS and automatically move DOS up in memory. Then, RUN UnderTale. (RUN IT BY LEGAL to view some legally advisable acknowledgements.)

There is a JUKEBOX program on side B, which should not depend on anything in the UnderTale program. However, you must boot from side A and then turn to side B, or the JUKEBOX program will break down due to DOS not being where the JUKEBOX expects it to be (i.e. not in its way).

UnderTale belongs, of course, now and forever to Toby Fox; Temmie drew the prologue artwork. Said artwork was colour-reduced and dithered in the GIMP, reprocessed via a custom Python script to fit the hi-res page, and compressed using faddenSoft's fhpack. The production made heavy use of CiderPress and Virtual ][, which are both excellent pieces of software.
