# Linux Infrastructure & Security Home Lab

Personal Linux home lab built using VMware and Ubuntu Server for practicing Linux system administration, networking, security hardening, automation, and infrastructure management.

---

# Project Goals

This project was created to build hands-on experience in:

- Linux System Administration
- Networking Fundamentals
- Linux Security
- Bash Automation
- Web Server Management
- Infrastructure Troubleshooting

The lab is continuously updated with new services, configurations, scripts, and security improvements.

---

# Lab Architecture

```text
VMware Workstation
│
├── Ubuntu Server VM
│   ├── Apache2
│   ├── OpenSSH
│   ├── UFW Firewall
│   └── Bash Scripts
│
└── Client VM
```

---

# Technologies Used

- Ubuntu Server
- VMware Workstation
- Apache2
- OpenSSH
- UFW Firewall
- Bash Scripting
- Linux Networking
- Git & GitHub

---

# Project Structure

```text
linux-home-lab/
│
├── networking/     -> networking notes and configurations
├── services/       -> Linux services documentation
├── security/       -> security hardening and firewall
├── scripts/        -> Bash automation scripts
├── monitoring/     -> monitoring and logs
├── screenshots/    -> lab screenshots
├── diagrams/       -> network and lab diagrams
└── progress-log/   -> learning journey and updates
```

---

# Implemented Features

## Linux Administration

- Linux service management
- User and permissions management
- System troubleshooting
- File system navigation

## Networking

- Static IP configuration
- Network troubleshooting
- DNS configuration
- Connectivity testing

## Security

- SSH configuration
- UFW Firewall setup
- SSH hardening
- Linux user security

## Web Services

- Apache web server
- Service management with systemctl

## Automation

- Bash scripts
- System information scripts
- Service monitoring scripts

---

# Screenshots

## Ubuntu Server

# Linux Infrastructure & Security Home Lab

Personal Linux home lab built using VMware and Ubuntu Server for practicing Linux system administration, networking, security hardening, automation, and infrastructure management.

---

# Project Goals

This project was created to build hands-on experience in:

- Linux System Administration
- Networking Fundamentals
- Linux Security
- Bash Automation
- Web Server Management
- Infrastructure Troubleshooting

The lab is continuously updated with new services, configurations, scripts, and security improvements.

---

# Lab Architecture

```text
VMware Workstation
│
├── Ubuntu Server VM
│   ├── Apache2
│   ├── OpenSSH
│   ├── UFW Firewall
│   └── Bash Scripts
│
└── Client VM
```

---

# Technologies Used

- Ubuntu Server
- VMware Workstation
- Apache2
- OpenSSH
- UFW Firewall
- Git & GitHub
---

# Project Structure

```text
linux-home-lab/
├── networking/     -> networking notes and configurations
├── services/       -> Linux services documentation
├── scripts/        -> Bash automation scripts
├── monitoring/     -> monitoring and logs
├── screenshots/    -> lab screenshots
├── diagrams/       -> network and lab diagrams
└── progress-log/   -> learning journey and updates
```

---

# Implemented Features


- Linux service management
- System troubleshooting
- File system navigation

## Networking

- Network troubleshooting
- DNS configuration
- Connectivity testing

## Security
- SSH configuration
- UFW Firewall setup
- SSH hardening
- Linux user security
## Web Services

- Apache web server
- Service management with systemctl

## Automation
- Bash scripts
- System information scripts
- Service monitoring scripts
---

# Screenshots

## Ubuntu Server

![Ubuntu Server](screenshots/ubuntu-terminal.png)

## Apache Web Server

![Apache](screenshots/apache-running.png)

## Network Configuration
![Network](screenshots/ip-config.png)

---

# Troubleshooting

## Apache Service Issue

Problem:
Apache service failed to start after configuration changes.
Solution:

```bash
journalctl -xe
systemctl status apache2
```

The issue was fixed by correcting the Apache configuration file.


# Lessons Learned

- Linux system administration basics
- Linux networking concepts
- Service management using systemctl
- SSH remote access configuration
- Linux troubleshooting techniques
- Bash scripting fundamentals

---

# Future Improvements

- Docker containers
- Nginx reverse proxy
- Fail2Ban
- Grafana dashboards
- Log analysis
- Reverse proxy configuration

---

# Author

Mohamad Farivar

Linux • Networking • Security • Infrastructure- Monitoring stack
---






- Static IP configuration
- User and permissions management
## Linux Administration
├── security/       -> security hardening and firewall
│

- Bash Scripting

