# INTRO-TO-ASSEMBLY-MAINFRAME-PROJ
A mainframe program used as an introduction to compiling and running Assembly
For 25 points, create and edit the new member of your Assignments PDSE.  
You should have named the new member ASSIGN1.
When you're ready to begin editing that member, type or copy and paste the JCL (Job Control Language) and Assembly language program below that begins with the line

//KC03nnnA JOB ,'your name here',MSGCLASS=H

and ends with the line with only two forward slashes ( // ) into your PDSE member named ASSIGN1.  

When you've finished and made the editing change to it described in red in the "doc box" below, you will have what's known as a "job" that can be submitted for execution remotely on the Marist University mainframe.  By the way, you can delete the lines with the red text from your PDSE member if you choose to do so.  
 
It's important that you begin in column 1 for lines 1 through the line with MAIN on it and be sure that the final two lines begin in column 1.  In Assembler, columns make a difference so don't change the position of anything in this code.

Once you have the JCL and program typed or copy and pasted into the PDSE member named ASSIGN1, make changes to it as described in the doc box in red below.

//KC03nnnA JOB ,'your name here',MSGCLASS=H
//JSTEP01  EXEC PGM=ASSIST
//STEPLIB  DD DSN=KC00NIU.ASSIST.LOADLIB,DISP=SHR
//SYSPRINT DD SYSOUT=*
//SYSIN    DD *
