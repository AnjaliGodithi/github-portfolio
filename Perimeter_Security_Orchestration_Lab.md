# Lab 01: Perimeter Security Orchestration & Ingress Control

**Name:** Anjali Godithi  
**Course:** IT 335  
**Date:** January 2026  
**Status:** Completed  

---

## 🎯 Objective
To implement a default-deny ingress firewall policy, allow only required services, and verify enforcement through controlled connectivity testing.

---

## 🛠️ Tools Used
- UFW (Host-based firewall)
- Linux terminal commands (`ss`, `ip`, `ufw`)
- netcat (`nc`) for testing

---

## 🔍 Implementation Summary
1. Verified baseline firewall status
2. Enabled firewall and applied default ingress deny
3. Allowed approved ports only
4. Performed block test and allow test to validate enforcement

---

## ✅ Commands Executed
```bash
sudo ufw status verbose
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 22/tcp
sudo ufw status numbered
```
