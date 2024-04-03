# Bypassing a CGNAT with Wireguard

## Overview
I'm behind a CGNAT, found a useful guide from [mochman](https://github.com/mochman/Bypass_CGNAT/wiki) and decided to created a fork with my own changes

The main things I wanted to do with my setup were:
* Create a self-hosted PaaS with Docker, Dokku, and Shokku
* Forward only specific traffic from the internet to my services
* Provide my PaaS Server with clients real IPs and 
* Use a domain with subdomains to redirect traffic to the appropiated services in my PaaS

## Tested with:
* Oracle Cloud ([link](https://www.oracle.com/cloud/))

## If this is something you would like to try out, please go to the [wiki section](https://github.com/jusemon/homeserver/wiki) to start the tutorial.

# Other ways to bypass a CGNAT
[Wireguard Installer for Gaming](https://github.com/xiahualiu/wg_gaming_installer) - Can be used to bypass a CGNAT so you can have a **Full Clone NAT**

[Cloudflared Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/install-and-setup/tunnel-guide/)

[BoringProxy](https://boringproxy.io/)

[ZeroTier](https://www.zerotier.com/) [(u/RedKyet's Tutorial)](https://www.reddit.com/r/selfhosted/comments/u8n5hz/how_to_bypass_cgnat_and_expose_your_server_to_the/)

[Awesome-Tunnel](https://github.com/anderspitman/awesome-tunneling) - List of many open/closed source tunneling solutions.
