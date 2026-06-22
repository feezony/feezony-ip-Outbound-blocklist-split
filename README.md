**IP Outbound Blocklist**

This project provides split IP blocklists for outbound traffic, updated hourly, with built-in exclusions for major public DNS resolvers to ensure uninterrupted access to essential services.

The architecture addresses the 131,072-entry limit imposed on FortiGate firewall external connectors. By segmenting the blocklists into smaller, manageable files, this project ensures that all data can be successfully imported without exceeding the device's capacity threshold.


**Acknowledgements**

1. ipblocklist : https://github.com/bitwire-it/ipblocklist?tab=readme-ov-file#ip-blocklist
2. Johan Borestad (foundational blocklists) : https://github.com/borestad
3. Grok (Code contributions) : https://grok.com/


**Data Source**

1. ipblocklist : https://raw.githubusercontent.com/bitwire-it/ipblocklist/refs/heads/main/outbound.txt
2. borestad/blocklist-abuseipdb : https://github.com/borestad/blocklist-abuseipdb
3. borestad/firehol-mirror : https://github.com/borestad/firehol-mirror
4. stamparm/ipsum : https://github.com/stamparm/ipsum
5. ShadowWhisperer/IPs : https://github.com/ShadowWhisperer/IPs
6. romainmarcoux/malicious-ip : https://github.com/romainmarcoux/malicious-ip
7. romainmarcoux/malicious-outgoing-ip : https://github.com/romainmarcoux/malicious-outgoing-ip
8. elliotwutingfeng/ThreatFox-IOC-IPs : https://github.com/elliotwutingfeng/ThreatFox-IOC-IPs
9. binarydefense.com : https://binarydefense.com/banlist.txt
10. bruteforceblocker.com : https://danger.rulez.sk/projects/bruteforceblocker/blist.php
11. darklist.de : https://www.darklist.de/raw.php
12. dan.me.uk Tor List : https://www.dan.me.uk/torlist/
13. Emerging Threats : http://rules.emergingthreats.net/blockrules/compromised-ips.txt
14. Spamhaus EDROP : https://www.spamhaus.org/drop/edrop.txt
15. Spamhaus DROP : https://www.spamhaus.org/drop/drop.txt
16. Abuse.ch SSLBL : https://sslbl.abuse.ch/blacklist/sslipblacklist.txt
17. Abuse.ch Feodo : https://feodotracker.abuse.ch/downloads/ipblocklist_recommended.txt
18. CINSscore : https://cinsscore.com/list/ci-badguys.txt
19. Talos Intelligence : https://talosintelligence.com/documents/ip-blacklist
20. DigitalSide Threat-Intel : https://osint.digitalside.it/Threat-Intel/lists/latestips.txt
21. CriticalPathSecurity : https://github.com/CriticalPathSecurity/Public-Intelligence-Feeds
22. C2 Tracker : https://github.com/montysecurity/C2-Tracker
