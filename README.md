# duplic
A python script to search for duplicate files within sub directories.
Please note that this script comes with no warranty whatsoever, use at your own risk.

Usage: duplic [OPTION]... [DIRECTORY]

-m  --method <compare:icmp>  method to use 
-h  --help                   display this help and exit
--version                    output version information and exit

METHODS

cmp: Uses the python filecmp module to compare files.

icmp: Same as cmp but only compares files with same file extensions. (Fast but will skip check for redundant files with different file extensions, though resulting in lower runtimes)
