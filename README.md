# Unix-and-Shell-Programming-16CS33

Command
NAME
       ss - another utility to investigate sockets

SYNOPSIS
       ss [options] [ FILTER ]

DESCRIPTION
       ss  is  used  to  dump socket statistics. It allows showing information similar to netstat.  It can display more TCP and state informations
       than other tools.

OPTIONS
       When no option is used ss displays a list of open non-listening sockets (e.g. TCP/UNIX/UDP) that have established connection.
       
-f FAMILY, --family=FAMILY
              Display sockets of type FAMILY.  Currently the following families are supported: unix, inet, inet6, link, netlink.
-d, --dccp
              Display DCCP sockets.
-u, --udp
              Display UDP sockets.
-x, --unix
              Display Unix domain sockets (alias for -f unix).
-w, --raw
              Display RAW sockets.
