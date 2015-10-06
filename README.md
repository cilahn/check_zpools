check_zpools
============

A Nagios/Icinga plugin to monitor ZFS Pools (zpools).
It is based on "Check Solaris ZFS Pools" but is completely rewritten.

For my environment with different OS using ZFS (Solaris, OpenSolaris, SmartOS, FreeBSD) I needed a Nagios plugin which is running on all OS. 

Added some more features after fork:

- support for non-root users running the script like (ncap/nrpe/nagios)
- simplified check flow

TODO:
- make script posix conform for ncpa agent which uses posix shell in default for checks

Based on the orignial Skript of Claudio Kuenzler @ http://www.claudiokuenzler.com

You may find a full documentation with examples on the original script:
http://www.claudiokuenzler.com/nagios-plugins/check_zpools.php
