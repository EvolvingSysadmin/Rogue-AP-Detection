# Rogue AP Detection

## Techniques

<em>NMAP Network Discovery</em>

* nmap -sV --allports -T4 192.168.1.0/24
    * Find service and version of all ports at fast execution on target network

<em>NMAP DHCP Discovery</em>

* nmap --script broadcast-dhcp-discover -e bond0
    * Use broadcast-dhcp-discover script on bond0 interface

<em>NMAP UPnP Discovery</em>

* nmap -sV --script=broadcast-upnp-info -T4 192.168.1.0/24
    * Use broadcast-upnp-info plugin to get universal plug and play devices

<em>Kismet Wireless Sniffer</em>
* Kismet README: https://www.kismetwireless.net/docs/readme_group.html

<em>Aircrack-ng</em>
* Aircrack README: https://github.com/aircrack-ng/aircrack-ng

<em>Arpwatch</em>
* Arpwatch Man Page: https://linux.die.net/man/8/arpwatch


## Software

* NMAP: https://github.com/nmap/nmap
* Kismet: https://github.com/kismetwireless/kismet 
* Aircrack-NG: https://github.com/aircrack-ng/aircrack-ng

## Resources

* https://www.redhat.com/sysadmin/finding-rogue-devices
* https://www.interfacett.com/blogs/finding-rogue-wireless-access-points-kali-linux/
* https://www.cyberithub.com/how-to-install-arpwatch-tool-on-rhel-centos-7-8-simple-and-effective-steps/