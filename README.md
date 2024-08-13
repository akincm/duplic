# duplic
A python script to search for duplicate files within sub directories.
Please note that this script comes with no warranty whatsoever, use at your own risk.

Usage: duplic [OPTION]... [DIRECTORY]

Example `duplic -m cmp -a move /home/user/Documents`

-m  --method                method to use See METHODS

-a  --action                action to take after finding redundant files <move,delete,print>

-h  --help                  display this help and exit

-v  --version               output version information and exit


METHODS
cmp: Uses the python filecmp module to compare duplicate files.

icmp: Only compares files with same file extensions. (Time efficient)

dirs: Checks for redundant directories and moves them to a directory named `MOVED` inside the main directory
