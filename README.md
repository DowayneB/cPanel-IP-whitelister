# cPanel-IP-whitelister
cPanel plugin for cPanel users to whitelist their own IP's


Installation:

1) Download all files to /root directory (wget https://github.com/DowayneB/cPanel-IP-whitelister/archive/master.zip)
2) Move all files in cPanel-IP-whitelister to root
3) run #> ./ip_whitelist init


Whitelisting, and removing from the whitelist, is dependent on how your company handles the IP whitelisting process.

The whitelisting function in this script adds an IP to the cphulk whitelist. The remove whitelist function does nothing at the moment, which will allow you
to add your own scripts in the function (for example: if you wish to use ipsets/iptables.)

