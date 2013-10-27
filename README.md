2ndRoboCopy
===========

Description
-----------

VBScript for creating a mirror copy of your Data Drive on an external Drive using Microsoft [Robocopy](http://en.wikipedia.org/wiki/Robocopy)

After successful operation your computer is shut down. If there were errors a message box appears telling you what caused the error.

A logfile "2ndRoboCopy.log" is generated right beside the script file. If there where errors look for "(0x" in the log file to find the errors.


How to use
----------

1. Copy the script to your Backup-Drive.
2. If your Data Drive is not D:\ edit header of script and change the variable `targetDrive`.
3. run script.
