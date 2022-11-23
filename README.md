#### Practicing Network skills, admin tasks and inspecting the network to achieve better connectivity and deploying projects its very repetitive, this version will be mmore portable by taking into account input from the user, will collect important data and inspect the network for a continuos improvement.

### System utilities

#### The sys utils are the base packagaing tools that comes out of the box on all unix like OS's, almost all of the one used in this script come preinstalled on all distros. Only the "arp-scan" util needs to be installed as dependency in case your main driver is an Ubuntu base OS:

* nmap
* arp
* awk

### NMAP or the Network Mapper

#### Nmap is by far the most known Recon/Scanner tool known to all system admins, ethical hackers, pentesters and HomeLab geeks. is an open source tool for network exploration and security auditing.It was designed to rapidly scan large networks, although it works fine against single hosts. Nmap uses raw IP packets in novel ways to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics. While Nmap is commonly used for security audits, many systems and network administrators find it useful for routine tasks such as network inventory, managing service upgrade schedules, and monitoring host or service uptime.

### ARP

#### Arp manipulates or displays the kernel's IPv4 network neighbour cache. It can add entries to the table, delete one or display the current content. ARP stands for Address Resolution Protocol, which is used to find the media access control address of a network neighbour for a given IPv4 Address.

### AWK

#### The awk utility shall interpret each input record as a sequence of fields where, by default, a field is a string of non-<blank> non-<newline> characters. This default <blank> and  <newline> field  delimiter  can be changed by using the FS built-in variable or the -F sepstring option. The awk utility shall denote the first field in a record $1, the second $2,  and  so  on. The symbol  $0  shall refer to the entire record; setting any other field causes the re-evaluation of $0. Assigning to $0 shall reset the values of all other fields and the  NF  built-in  variable.
