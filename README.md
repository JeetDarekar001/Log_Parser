Log Parser-Regex

Robocopy is a populor file transfer tool on windows.
It logs the status of file when transfering from one location to another location.

Objective : Parse the log and convert to JSON format.


ROboCopy_success.txt log contains log entry after successfull transfer.
Robocopy_invalid.txt contains log entry after failure.

success log contains:

header section, start time, end time and source and desstination path.
at the bottom of log file we see it has bytes transfered.


faliure log contains : keyword error, with error message and time stamp.
