# cPanel-IP-whitelister
cPanel plugin for cPanel users to whitelist their own IP's


Installation:

1) Download all files to /root directory (wget https://github.com/DowayneB/cPanel-IP-whitelister/archive/master.zip)
2) Move all files in cPanel-IP-whitelister to root
3) run #> ./ip_whitelist init


Whitelisting, and removing from the whitelist, is dependent on ho your company handles this regularly, the whitelisting function in this script adds to the cphulk whitelis, and the remove whitelist function does nothing, you can add your own scripts in there if you wish to use ipsets/iptables.
