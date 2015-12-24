     # M-Editor-For-Eclipse-Original-Version
        Joel L. Ivey (jivey@jiveysoft.com)
        
The original version of the M-Editor for Eclipse including an embedded Java version it runs with.

Added to provide access to the main file (since it is too large to put on GitHub at over 200 Mbytes) but is available for download from my DropBox account (you do not need a DropBox account) using the link 

https://www.dropbox.com/s/vyvegej1055g1io/Eclipse3_5_1M-full%20versionIncludesJava.zip?oref=e

Sorry for the extra work.


The Department of Veteran Affairs information system is called VistA (Veterans Health Information Systems and Technology Architecture), and even with a name change has been used since 1984 or so for information storage and processing.  It is based on the language M (or MUMPS) which although it is not that widely used or known has been used for many years (it was originally created in 1967 and was one of the earliest ANSI Standard Languages in 1977) for handling large databases (it was Non-SQL long before SQL appeared).  As a developer for the Department of Veteran Affairs and working with several other languages besides M as well, I thought that the Eclipse Integrated Development Environment might provide a good editing system for working with the M routines.  Across a period of time, I did generate the "M-Editor for Eclipse" which was used by myself and some other developers.  It had tied into it the capabilities for creating or loading a routine from the server, performing editing, saving the routine back into the server, and as it was saved it ran routines already available to determine whether there were any errors or warnings, and built into the ability to run any related unit tests for the routine within the M environment  (I also originally wrote the XTMUNIT routines for running M-Unit tests, and after retirement from the VA have continued that development with certification by OSEHRA (the Open Source Electronic Health Record Alliance) of the %ut* routines for M-Unit tests also available on my GitHub account).  More recently, other developers working for OSEHRA reworked the M-Editor for Eclipse so that it would work with the most recent versions of Eclipse.  In doing so, there were several parts that seemed to have gotten lost.  The original version that I am making available here has included with it an earlier version of Eclipse and Java that it works with.  Simply unzipping the zip file into a directory name Eclipse or something like that will provide the full client side functionality of the original version.  It already includes all of the necessary plug-ins, etc., as well as a version of java that it runs with.  On the server side, the user will need a MUMPS installation (Cache on windows or GT.M on Linux), with at least the Basic VA (Kernel and FileManager) software installed, and running the VistALink listener.  It will also need at the three included KIDs patches installed (XT73P81V10.KID, XT73P101V7.KID and XT73P107V4.KID).

I have included two documents that were presented at the VistA Community Meeting in January, 2015 which provide comparisons between the new and original versions (the version here being the latter) of the M-Editor in Eclipse.  In addition, there is an earlier presentation from 2008 that focuses on the original version.  

Included with the M-Editor functionality, and mentioned in some of the included documentation, is an M-Debugger for Eclipse plug-in.  This functionality has not been that well tested by others, and while parts of it function well, it definitely should not be thought of as a finished product.

Work to improve the M-Editor for Eclipse continues.

