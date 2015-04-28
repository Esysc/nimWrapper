###nimWrapper
===

Script wrapper to instanciate a nim mksysb restore, boot the client  and produce the postinstall script for further customisation.
This script can be executed from command line but the main puprose is to be executed in background .

The script is stored in a mysql table and parsed by the nim server. Whena user throw the GUI web app insert the script for execution filling all script arguments, it'll be automatically executed.

It contains  some expect code to boot nim client and set the nim network address in sms menu.


