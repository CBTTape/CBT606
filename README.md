# CBT606
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 606 is from Reed Petty and contains a version of his      *   FILE 606
//*           AWSSL program which can produce HET (Hercules         *   FILE 606
//*           Emulated Tape) format tapes on an MVS system, as      *   FILE 606
//*           well as AWS format tape files.  Since this version    *   FILE 606
//*           of AWSSL produces tapes that are only readable on     *   FILE 606
//*           Hercules-based systems and not on P/390 systems,      *   FILE 606
//*           I am placing this version on a separate file from     *   FILE 606
//*           the previous versions of AWSSL, which do not produce  *   FILE 606
//*           HET format tapes.  HET format is a superset of AWS    *   FILE 606
//*           format, where the tape blocks might be compressed.    *   FILE 606
//*           If the tape blocks are not compressed, the format     *   FILE 606
//*           of the tape file is compatible with AWS.              *   FILE 606
//*                                                                 *   FILE 606
//*   A few fixes from David Cartwright (marked *agco*).  I think   *   FILE 606
//*   this allows the creation of 64K blocked tapes (SBG).  See     *   FILE 606
//*   member $$NOTE1.                                               *   FILE 606
//*                                                                 *   FILE 606
//*           email:  DaveCartwright@uk.agcocorp.com                *   FILE 606
//*                                                                 *   FILE 606
//*   Explanation of HET and AWS tape formats.                      *   FILE 606
//*                                                                 *   FILE 606
//*      AWS tapes contain six-byte headers, which tell you when    *   FILE 606
//*      a tape block begins, and where a tape mark is.  AWS tapes  *   FILE 606
//*      contain the tape blocks as uncompressed bytes, whereas     *   FILE 606
//*      HET tapes contain the tape blocks as compressed data,      *   FILE 606
//*      using either the ZLIB compression program or the BZLIB     *   FILE 606
//*      compression program.                                       *   FILE 606
//*                                                                 *   FILE 606
//*      HET format was invented by Leland Lucius.                  *   FILE 606
//*                                                                 *   FILE 606
//*           email:  rhp@draper.net                                *   FILE 606
//*                                                                 *   FILE 606
```
