# ad-blocklist for pihole/adguard

### How:


Presently i use my Kreisklasse blocklists (see below) and the list from [Steven Black](https://github.com/StevenBlack/hosts) on a odroid N2, running 
* [HassOS](https://www.home-assistant.io/hassio/installation/) with
* [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home) addon, with my blocklists, and
* [Wireguard VPN](https://github.com/hassio-addons/addon-wireguard) addon.

As DNS-Server i use the following DoT servers:
* [NextDNS.io](https://nextdns.io) (with some blocklists and logging active)
* [Freifunk München](https://ffmuc.net/wiki/doku.php?id=knb:dohdot) - dot.ffmuc.net - (no blocklist, no logging)
* [UncensoredDNS.dk](https://blog.uncensoreddns.org/dns-servers/) - unicast.uncensoreddns.org - (no blocklist, no logging)
* [sinodun.com](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Test+Servers) - dnsovertls.sinodun.com - (no blocklist, no logging)
* [getdnsapi.net](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Test+Servers) - getdnsapi.net - (no blocklist, no logging)





### Links of my block/allow lists here on codeberg for use in adguard/pihole:
BlockList Main:
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_main.txt

Test list, wait and see if it breaks anything:
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_test.txt

Special list for blocking Google, Facebook, Amazon,Apple, Microsoft:
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_gafam.txt

List with urls that annoy me:
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_privat.txt


List in Adblock syntax, not usable with pihole, but good usable in AdGuard:
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_adblock_syntax.txt


AllowList
* https://codeberg.org/kreisklasse/adblock/raw/branch/master/kreisklasse_allow.txt
