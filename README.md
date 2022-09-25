# simcheck
A simple python script to search for similar files within sub directories.

TN: This program only supports files inside your user's home directory.

Please provide feedbacks and pull requests for imporvements.

Usage: simchk [OPTION]... [DIRECTORY]

-m  --method <sha:compare:icmp>  method to use sha or compare
-h  --help                  display this help and exit
--version                   output version information and exit

METHODS

cmp: Uses the python filecmp module to compare files.

sha: Compares the SHA-1 hash files.

icmp: Same as cmp but only compares files with same file extensions.
