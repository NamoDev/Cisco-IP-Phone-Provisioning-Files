# Cisco-IP-Phone-Provisioning-Files
Samples of Cisco IP phone configuration/XML files for use with Asterisk!

### Usage
Rename the files to `SEP<mac>.cnf.xml`, then customize as required.

### Coverage & Compatibility
* Cisco 7821 IP phones (tested with sip78xx.12-1-1-12)
* Cisco 6921 IP phones (tested with SIP69xx.9-4-1-3)
* Cisco 9971 IP phones (tested with sip9971.9-4-2SR4-1)
* Cisco 7911 IP phones (tested with SIP11.8-5-3S)
* Cisco 7942 IP phones (tested with SIP42.8-5-4S)
* Cisco 7960 IP phones (tested with SIP P0S3-8-12-00. Note: configuration file name for this series of phones is `SIP<mac>.cnf`)

### Other Options (that you might want to customize)
* The `<webAccess>` key enables or disables the phone's web UI (mostly used for debugging). A value of `0` enables it while `1` disables it.
* There's a nice guide [here](http://usecallmanager.nz/sepmac-cnf-xml.html) which goes into detail of each and possibly every config key that you could set on these phones.
