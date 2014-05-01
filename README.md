uretest
=======

This test script reads data from a hard disk
to check for Unrecoverable Read Errors and log them.

The goal of this script is to determine the frequency
of UREs

Syntax:

uretest <logdir> <disk device>

example:

uretest /log sdc

Log output format:

date/time,MD5 test result,SYSLOG error messages,total data read

