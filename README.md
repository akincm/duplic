# duplic
A python script to search for duplicate files within sub directories.
Please note that this script comes with no warranty whatsoever, use at your own risk.

Usage: duplic [OPTION]... [DIRECTORY]

-m  --method {compare,icmp,compare_then_delete,compare_dirs}  method to use

-h  --help                  display this help and exit

--version                   output version information and exit

METHODS

cmp: Uses the python filecmp module to compare duplicate files.

icmp: Only compares files with same file extensions.

compare_then_delete: Deletes redundant files (The file which is outermost in filesystem are kept).

compare_dirs: Checks for redundant directories and moves them to a directory named MOVED inside the main directory

[Please not that you need to mention compare_then_delete or compare_dirs explicitly to run them]
