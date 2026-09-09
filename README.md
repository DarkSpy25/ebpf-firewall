# ML-Based eBPF Firewall

An eBPF-based network firewall that uses machine learning to identify and block suspicious IP addresses.

## Overview

This project combines **eBPF-based packet filtering** with **machine learning** to provide a lightweight and efficient approach to network security.

The machine learning component analyzes network traffic and identifies potentially suspicious IP addresses, while the eBPF component enforces the resulting blocking decisions at the Linux kernel level.

## Features

* Machine learning-based identification of suspicious IP addresses
* eBPF-based network packet filtering
* Automated blocking of potentially malicious traffic
* Kernel-level packet processing for efficient filtering
* Separation of ML-based detection and eBPF-based enforcement

## Architecture

```text
Network Traffic
      ↓
Machine Learning Model
      ↓
Suspicious IP Detection
      ↓
eBPF Firewall
      ↓
Allow / Block Traffic
```

## Technologies

* Python
* Machine Learning
* eBPF
* Linux
* Network Security
* Firewall
