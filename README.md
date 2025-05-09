# Homelab Project

**Overview:**
This project contains all files to configure homelab k8s cluster and infrastructure in it.

Installed Talos Linux, as secure and minimal OS, will be used to manage Kubernetes clusters, providing a streamlined and secure foundation for container orchestration. 

The setup will serve as an environment for learning and experimenting with virtualization, Kubernetes, and enterprise-grade security practices.

## Tech Stack

**Hypervisor:** Proxmox

**Container Orchestration:** Kubernetes

**CI:** Github Actions

**CD:** ArgoCD

**Monitoring:** Grafana, Prometheus

**Networking:** Cilium

**DNS:** Bind9 or Pihole

**Secure reverse proxy:** Cloudflare zero trust tunnel

**ingress controler:** traefik

**Secure Vault:** HashiCorp Vault

**Managing certificates:** cert-manager

**Storage:** Longhorn


## Hardware

I'm using two mini pc and proxmox isnstalled on it to maximalize possibilities.

Dell OptiPlex 7050 i5-6400T 12 Gb 512Gb ( 1 x masternode )

Dell OptiPlex 7040 i5-6400T 24 Gb 1Tb ( 3 workernodes )

Router Ubiquiti X-sfp router/firewall
