# Linux / Infrastructure Automation Portfolio

I build Linux-based infrastructure automation labs using Ansible, Proxmox VE, Docker, Zabbix, Pacemaker/DRBD, LINSTOR, Kubernetes, and secure bastion/hardening designs.

My focus is on practical infrastructure operations: server provisioning, monitoring, high availability, secure remote access, backup/NAS, and automation for repeatable deployments.

データセンター勤務を通じてサーバー・ネットワーク運用に関わりながら、Linux / Ansible / Proxmox VE / Zabbix / DRBD / Kubernetes / Security Hardening などを用いたインフラ自動化ポートフォリオを作成しています。  
実運用を想定した構成、冗長化、監視、障害時復旧、踏み台アクセス制御、セキュリティベースラインを重視しています。

## Focus Areas

- Linux server operations and automation
- Infrastructure as Code with Ansible
- Proxmox VE VM provisioning and lab automation
- Monitoring and observability with Zabbix
- High availability with Pacemaker, DRBD, LINSTOR, and QDevice
- Secure remote access using bastion/proxy designs
- Linux security hardening with SSH restrictions, firewall, fail2ban, auditd
- Docker / Kubernetes based application and infrastructure labs
- Network fundamentals based on CCNA knowledge

## Featured Projects

### [Ansible Zabbix HA](https://github.com/2hasimasqqsan-commits/ansible-zabbix-ha)
Ansible portfolio project for deploying a Zabbix HA cluster with Pacemaker, DRBD, MariaDB, Apache, and STONITH fencing.

### [Proxmox LINSTOR Ansible](https://github.com/2hasimasqqsan-commits/pve-linstor-ansible)
Ansible portfolio project for building a Proxmox VE two-node HA lab with LINSTOR, DRBD-backed storage, QDevice quorum, and VM failover verification.

### [Bastion Ansible Lab](https://github.com/2hasimasqqsan-commits/bastion-ansible)
Ansible automation for building an LXC-based bastion and proxy lab environment on Ubuntu Server.

### [Kubernetes Lab Ansible](https://github.com/2hasimasqqsan-commits/k8s-lab-ansible)
Ansible portfolio project for building a Kubernetes cluster on Proxmox VE with kubeadm, Flannel, MetalLB, and nginx Deployment verification.

### [Raspberry Pi Samba NAS Ansible](https://github.com/2hasimasqqsan-commits/raspi-samba-nas-ansible)
Ansible project for building a Raspberry Pi Samba NAS with external SSD and Tailscale remote access.

### [Simple Chat Ansible](https://github.com/2hasimasqqsan-commits/simple-chat-ansible)
Lightweight self-hosted group chat app deployed with Ansible, Docker, Flask, nginx, MariaDB, MinIO, Cloudflare Tunnel, and Brevo SMTP.

### [Zabbix phpIPAM Ansible](https://github.com/2hasimasqqsan-commits/zbx-ipam-ansible)
Ansible automation for deploying a Zabbix and phpIPAM lab environment on Ubuntu Server.

### [Ansible Asset Ledger](https://github.com/2hasimasqqsan-commits/ansible-asset-ledger)
Ansible portfolio project for deploying a Docker-based Flask, Nginx, MariaDB asset ledger with Proxmox VE API integration.

### [Linux Hardening Lab](https://github.com/2hasimasqqsan-commits/ansible-proxmox-hardening-lab)
Ansible project for provisioning a Linux VM on Proxmox VE and applying security hardening with SSH restrictions, firewall, fail2ban, auditd, automatic updates, disk resizing, and verification tasks.

## Skills / Tools

- **Linux:** Ubuntu Server, AlmaLinux
- **Automation:** Ansible, cloud-init, shell scripting
- **Virtualization:** Proxmox VE, KVM, LXC
- **Monitoring:** Zabbix, SNMP, logs
- **High Availability:** Pacemaker, Corosync, DRBD, LINSTOR, QDevice
- **Containers:** Docker, Docker Compose, Kubernetes
- **Networking:** VLAN, routing, LACP, SSH, firewall, CCNA fundamentals
- **Security:** SSH hardening, UFW, fail2ban, auditd, bastion/proxy access control
- **Application / Web:** Flask, nginx, MariaDB, MinIO

## Certification

- Cisco Certified Network Associate (CCNA)

## Notes

These projects are built as practical infrastructure labs for learning, verification, and portfolio purposes.  
Each repository includes Ansible roles, configuration examples, verification steps, and screenshots where applicable.
