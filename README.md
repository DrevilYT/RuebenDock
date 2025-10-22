<p align="center"><a href="https://browser.rueben.xyz"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=52C2BE&center=true&vCenter=true&width=435&lines=RuebenDock" alt="RuebenDock" /></a>
<h1 align="center">your browser in the cloud</h1>

<p align="center">Each session runs in its own secure Docker container, giving you a private, isolated browsing environment every time. All servers are hosted by myself.</p>
<hr>

## ⚙️ How to Set It Up Yourself?

## Prerequisites

-  A Debian based Linux server (Ubuntu or Debian) with Docker and Docker Compose installed
-  4 GB RAM and 10 GB storage minimum
-  A domain or subdomain (e.g. browser.rueben.xyz)
-  Optional: Nginx, Caddy, or Cloudflare Tunnel for HTTPS and routing

### Method 1 - Using Portainer (Recommended)

-   Install Portainer.
-   Open Portainer at https://your-ip:9443 and complete the setup wizard.
-   Go to Containers → Add Container, and enter:

Image: ksm-chrome:latest or another browser image (e.g. browserless/chrome)

Ports: 3000 → 3000

Restart policy: Always
-   You will see the activation options. Select your option.

### Method 2 - Windows Run Installer (Discontinued)
-   Discontinued (new versions will no longer receive the run installer method as of v5).
-   [Click here for the older versions code](https://github.com/DrevilYT/ActivationScript/tree/main/installer/readme.md)

</br>

```
Latest Version: 1.2-beta
Release date: 21-Oct-2025
```
