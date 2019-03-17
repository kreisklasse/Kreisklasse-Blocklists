# PiHole Blacklist

My personal Blacklists.


Beside my Kreisklasse-blocklists,  
i use also the following blacklists on my pihole:

https://github.com/AdroitAdorKhan/Energized :  
https://raw.githubusercontent.com/EnergizedProtection/block/master/basic/formats/hosts  
update frequency: every friday

https://github.com/anudeepND/blacklist :  
https://raw.githubusercontent.com/anudeepND/blacklist/master/facebook.txt  
update frequency: unknown


https://github.com/notracking/hosts-blocklists :  
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt  
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/domains.txt  
  
this gives me about 500.000 blocked urls


i also tried this one,  
https://raw.githubusercontent.com/deathbybandaid/piholeparser/master/Subscribable-Lists/CombinedBlacklists/CombinedBlackLists.txt  
update frequency: acc. to file, daily  
but it blocks about 2.5 Million URLs. For me it blocks to much. But you can try it.

##Testing
now added the following lists to my Test-piHole:  
from https://github.com/crazy-max/WindowsSpyBlocker the WindowsSpyBlocker list:  
https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/spy.txt  

https://raw.githubusercontent.com/EnergizedProtection/block/master/unified/formats/hosts.txt  
here paused the Energized Basic-list  
this gives me 1.2 Million blocked URLs



