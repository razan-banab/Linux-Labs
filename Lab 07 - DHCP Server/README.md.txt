# Lab 07 - DHCP Server

## Objective

Configure an ISC DHCP Server on Ubuntu Server to automatically assign IP addresses and network settings to client devices.

---

## Scenario

A small company wants to automate IP address assignment for employee devices instead of configuring each device manually. A DHCP server is deployed to provide IP addresses, the default gateway, and DNS server information automatically.

---

## Implementation

- Installed the ISC DHCP Server package.
- Configured the DHCP scope and network settings.
- Configured the DHCP listening interface.
- Validated and started the DHCP service.
- Verified the DHCP listening port.
- Tested automatic client configuration.
- Verified client connectivity and DNS resolution.

---

## Commands Used

- `ip a`
- `apt install isc-dhcp-server`
- `apt list --installed`
- `nano /etc/dhcp/dhcpd.conf`
- `nano /etc/default/isc-dhcp-server`
- `dhcpd -t`
- `systemctl restart isc-dhcp-server`
- `systemctl status isc-dhcp-server`
- `ss -tuln | grep :67`
- `ping`
- `nslookup`

---

## Screenshots

![DHCP Package Installation](screenshots/dhcp-package-installation.png)

![DHCP Configuration](screenshots/dhcp-configuration.png)

![DHCP Configuration Validation](screenshots/dhcp-config-validation.png)

![DHCP Service Status](screenshots/dhcp-service-status.png)

![DHCP Listening Port](screenshots/dhcp-listening-port.png)

![Client IP Configuration and Connectivity](screenshots/client-ip-connectivity.png)

![Client DNS Resolution](screenshots/Client-DNS-Resolution.png)

---

## Skills Covered

- DHCP Server Configuration
- Linux Network Configuration
- Service Management
- Network Troubleshooting
- Client Configuration

---

## What I Learned

- How to deploy and configure an ISC DHCP Server.
- How to configure a DHCP scope, gateway, and DNS settings.
- How to validate a DHCP configuration before starting the service.
- How to verify automatic IP assignment and client connectivity.

---

## Real-World Relevance

DHCP automates IP address management by assigning network settings to client devices automatically, reducing manual configuration and improving network efficiency.

---

## Result

Successfully deployed and configured an ISC DHCP Server that automatically assigned IP addresses and network settings to client devices.