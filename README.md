nas-backup
==========

Quick and dirty backup from Web server to a NAS box in my home.

 * Create a new backup user which has no password and only logs in with a key.
 * Create a new MySQL user which can dump the whole DB
 * Setup the webserver script to run at ~04:00
 * Setup the NAS script to run at ~04:30

You of course need to setup and test the ability for the NAS box to login to the Webserver with Public/Private Key Pair

