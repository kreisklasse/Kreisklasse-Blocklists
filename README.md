# PiHole Blacklist

### Blocklists in use:


Presently i only use my Kreisklasse blocklists on a Raspberry Pi2 running 
* [HassOS](https://www.home-assistant.io/hassio/installation/) with
* [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home) addon, with my blocklists, and
* [Wireguard VPN](https://github.com/hassio-addons/addon-wireguard) addon

and as DNS-Server the servers (DoT & DoH) from 
[NextDNS.io](https://nextdns.io) with some blocklist active.





### Not used anymore:
i also tried this one,  
https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/CombinedBlacklists/CombinedBlackLists.txt  
update frequency: acc. to file, daily  
but it blocks about 2.5 Million URLs. For me it blocks to much. But you can try it.

https://github.com/notracking/hosts-blocklists :  
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt  
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/domains.txt 

https://raw.githubusercontent.com/EnergizedProtection/block/master/unified/formats/hosts.txt  
this gave me now 1.2 Million blocked URLs


https://github.com/AdroitAdorKhan/Energized :  
https://raw.githubusercontent.com/EnergizedProtection/block/master/basic/formats/hosts  
update frequency: bi-weekly on fridays

https://github.com/anudeepND/blacklist :  
https://raw.githubusercontent.com/anudeepND/blacklist/master/facebook.txt  
update frequency: unknown
 
this gives me about 500.000 blocked urls

now added the following lists to my Test-piHole:  
from https://github.com/crazy-max/WindowsSpyBlocker the WindowsSpyBlocker list:  
https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/spy.txt  