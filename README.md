# linux-system-administration-project
Hands-on Linux System Administration project using Oracle Linux, LVM, XFS, Nginx, networking, permissions, and security.
# Linux System Administration Project

## 📌 Project Overview

This project is a hands-on Linux System Administration lab built using Oracle Linux and VirtualBox. It focuses on Linux user management, storage administration, networking, service management, security, monitoring, and troubleshooting.

## 🖥️ Lab Environment

* **Operating System:** Oracle Linux Server 8.10
* **Virtualization:** Oracle VirtualBox
* **Web Server:** Nginx
* **Storage Management:** LVM and XFS
* **Service Management:** systemd
* **Security:** Firewalld and SELinux

## 🛠️ Skills Practiced

### 1. User and Permission Management

* User and group administration
* File and directory permissions
* Access Control Lists (ACL)
* SUID, SGID, and Sticky Bit

### 2. Storage Administration

* Physical volumes, volume groups, and logical volumes
* XFS filesystem verification
* Persistent mounts using `/etc/fstab`
* Disk usage and storage troubleshooting

### 3. Networking and Remote Administration

* IP address and routing verification
* DNS troubleshooting
* SSH service administration
* Network connectivity testing

### 4. Service Management and Monitoring

* systemd service management
* Nginx configuration and verification
* System logs using `journalctl`
* Memory, disk, and server health checks

### 5. Security and Troubleshooting

* Firewalld configuration verification
* SELinux status and policy awareness
* Permission and access troubleshooting
* Linux service and connectivity diagnostics

### 6. Automation

* Bash scripting fundamentals
* Scheduled tasks using cron
* Command-line administration

## 🔍 Verification Commands

```bash
uptime
free -h
df -hT
lsblk -f
ip -br addr
ip route
systemctl --failed
sudo nginx -t
getenforce
```

These commands help inspect server health, storage, networking, services, and security settings.

## 🎯 Project Objectives

* Develop practical Linux administration skills.
* Understand storage and access control.
* Practice service monitoring and troubleshooting.
* Build a foundation for Linux System Administrator and System Engineer roles.

## 👨‍💻 Author

Harshit Singh

---

**Note:** This repository documents a hands-on learning project. Configurations and results should be verified against the actual lab environment.

