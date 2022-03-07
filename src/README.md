# Cloudflare Cheat Sheet

rbl-2022-03-06

Eats their own dog food

## Connectivity

* The Cloudflare global network **runs every service in every data center** so users have a consistent experience everywhere. *Customer* traffic is processed at the data center closest to them, with no backhauling or performance tradeoffs

## Edge Network

* Collects own and uses vendor antivirus
* Bare metal builds
* Commodity hardware tested and sourced from multiple vendors who build the servers to our specifications.
* ARM
* Network dual-port 25G
* Linux
* Open source firmware

## Teams

* Cloudflare Teams Access
  * Identity federation across multiple identity providers
  * Authentication and Authorization 
  * Active Directory IPsec / GRE connection
* modern VPN
* WARP access
  * Configure with Device Management Platform 
* Cloudflare Gateway
	* next generation Firewall
	* Replace onsite firewalls

## Warp 1.1.1.1

* Team gateway access
* Wireguard protocol
* Not a VPN to access restricted content

## Zero Trust Network Access

* Secure Remote Workforces
* Deliver Zero Trust Network Access
* Replace Virtual Private Networks (VPNs)
* Protect Employees on the Internet
* Stop Ransomware, Phishing & Data Loss
* Manage Access for Contractors


## Splunk

[More products, more partners, and a new look for Cloudflare Logs](https://blog.cloudflare.com/logpush-ui-update/)

* Gateway logs provide visibility into internet and web traffic, across all users, devices, and locations
* Direct  Splunk integration
* >“Organizations are in a state of digital transformation on a journey to the cloud. Most of our customers deploy services in multiple clouds and have legacy systems on premise. Splunk provides visibility across all of this, and more importantly, with SOAR we can automate remediation. We are excited about the Cloudflare partnership, and adding their data into Splunk drives the outcomes customers need to modernize their security operations.” 
— Jane Wong, Vice President, Product Management, Security at Splunk
