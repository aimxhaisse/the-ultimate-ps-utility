The *ps* utility designed to work with systemd
==============================================

*ps* has always be a complicated tool. Do you want to list only your process?
Do you want to display session leaders? Processes with a tty? Maybe those
associated with the current terminal?

Seriously, who the fuck knows all the options you can give to *ps*?


Thanks to the great *systemd*, there's no need to such complexity anymore.
*systemd* intends to provide everything you need on your system. Need a DHCP client?
*systemd* has one. An HTTP server? Wait a bit, *systemd* will have one.

This version of the *ps* utility only displays what really matters: info about
**the** process running on your machine.
