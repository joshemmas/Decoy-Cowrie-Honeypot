# 🛡️ Cowrie SSH Honeypot Setup & Troubleshooting Guide

This repository documents my journey of setting up, running, and troubleshooting a **Cowrie SSH honeypot** on Kali Linux. It includes all the steps I followed, the problems I encountered, and the solutions applied.

---

## 📌 Table of Contents
1. [Introduction](#introduction)
2. [System Setup](#system-setup)
3. [Installing Cowrie](#installing-cowrie)
4. [Running the Honeypot](#running-the-honeypot)
5. [Troubleshooting & Fixes](#troubleshooting--fixes)
6. [Systemd Service Setup](#systemd-service-setup)
7. [Testing with SSH](#testing-with-ssh)
8. [Scanning with Nmap](#scanning-with-nmap)
9. [Lessons Learned](#lessons-learned)
10. [Future Improvements](#future-improvements)

---

## 📖 Introduction
Cowrie is a medium-interaction SSH and Telnet honeypot designed to log brute-force attacks and the commands issued by attackers.  

The purpose of this project:
- Practice **honeypot deployment**  
- Understand how attackers interact with exposed services  
- Build practical cybersecurity skills  

---

## 🖥️ System Setup
- **OS**: Kali Linux (VM)  
- **User**: `cowrie` (non-root for security)  

---

## ⚙️ Installing Cowrie
1. Clone repository:
   ```bash
   git clone https://github.com/cowrie/cowrie.git
   cd cowrie
