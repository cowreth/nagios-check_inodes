# NRPE Plugin : check_inodes 

This simple Nagios NRPE plugin will check inodes on all filesystems.
It's based on the output from "df -i", parsed with awk to get the
percentage of used inodes. It then echo the results as requested per NRPE.
