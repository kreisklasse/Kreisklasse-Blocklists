# ad etc blacklist

### How:


Presently i only use my Kreisklasse blocklists on a Raspberry Pi2 running 
* [HassOS](https://www.home-assistant.io/hassio/installation/) with
* [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home) addon, with my blocklists, and
* [Wireguard VPN](https://github.com/hassio-addons/addon-wireguard) addon

and as DNS-Server the servers (DoT & DoH) from 
[NextDNS.io](https://nextdns.io) with some blocklist active.





### My block lists:
Main blocklist:
https://codeberg.org/kreisklasse/pihole-blocklists/raw/branch/master/kkblacklist.txt

Test list, wait and see if it breaks anything:
https://codeberg.org/kreisklasse/pihole-blocklists/raw/branch/master/kkblacklisttest.txt

Special list for blocking Google, Facebook, Amazon,Apple, Microsoft:
https://codeberg.org/kreisklasse/pihole-blocklists/raw/branch/master/kkblacklist-gafam.txt

List with urls that annoy me:
https://codeberg.org/kreisklasse/pihole-blocklists/raw/branch/master/kkblacklist-privat.txt
