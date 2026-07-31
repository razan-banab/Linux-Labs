# Lab 04 – SSH (Secure Shell)

## Objective

Learn how to configure, manage, and test the SSH service on Ubuntu Linux to enable secure remote administration between two Linux systems.

---
## Scenario

A company has two Linux machines on the same network: one acts as a server and the other as a client. The system administrator must configure the server to allow secure remote access using SSH, verify that the service is operating correctly, and confirm that users can remotely log in and manage the server.

---
## Implementation

- Identified the server's IP address and verified network connectivity from the client.
- Verified the OpenSSH Server and Client packages.
- Verified and managed the SSH service using `systemctl`.
- Configured the SSH service to start automatically at boot.
- Verified that the SSH server was listening on the default port.
- Established a secure SSH connection between the client and server.
- Executed remote commands through the SSH session.

---
## Commands Used

- `ip a`
- `ping`
- `apt update`
- `apt install`
- `systemctl status`
- `systemctl enable --now`
- `ss -tuln`
- `ssh`

---
## Screenshots

### Server IP Address

![Server IP Address](screenshots/server-ip.png)

### Network Connectivity Test

![Network Connectivity Test](screenshots/ping-server.png)

### OpenSSH Client Package Verification

![OpenSSH Client Package Verification](screenshots/client.png)

### OpenSSH Server Package Verification

![OpenSSH Server Package Verification](screenshots/server.png)

### SSH Service Status and Boot Configuration

![SSH Service Status and Boot Configuration](screenshots/ssh-service-status.png)

### SSH Server Listening on Port 22

![SSH Server Listening on Port 22](screenshots/ssh-listening-port.png)

### SSH Connection and Remote Command Verification

![SSH Connection and Remote Command Verification](screenshots/ssh-remote-command.png)

---
## Skills Covered

- Linux package management
- Linux service management
- Secure remote administration
- Network connectivity verification
- SSH configuration and authentication
- Remote command execution
- Basic Linux server administration

---
## What I Learned

- Configuring secure remote access using SSH.
- Verifying the OpenSSH Server and Client packages.
- Managing the SSH service using `systemctl`.
- Enabling services to start automatically during system boot.
- Verifying that the SSH server is listening for incoming connections.
- Establishing secure remote connections between Linux systems.
- Executing commands remotely through an SSH session.

---
## Real-World Relevance

SSH is one of the most essential tools used by Linux system administrators, cloud engineers, and DevOps engineers. It provides a secure method for remotely managing servers, virtual machines, and network devices over a network. Whether administering cloud infrastructure, automating deployment tasks, or maintaining production systems, SSH is a fundamental technology used in professional IT environments.

---
## Result

Successfully configured an Ubuntu server for secure remote administration using SSH, verified that the SSH service was operating correctly and configured to start automatically at boot, confirmed network connectivity, and established a secure remote connection to execute commands on the server.
