# Home-Lab
Collection of scripts, services and configs I am using and running on my ASUS Tinkerboard.

## [update-dns](update-dns)
Some ISPs change the IPv6 prefix from time to time making it hard to maintain the DNS records. In such cases, DDNS(Dynamic DNS) is used to keep the DNS records up-to-date. This script is my version of DDNS. I am using Cloudflare as my NS. Whenever the wlan0 interface is turned up or a dhcp6 lease renewal or rebinding happens, the script runs and updates the DNS records with the latest IPv6 address.
