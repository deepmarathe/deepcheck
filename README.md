# DeepCheck

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

---

## DeepCheck: A Comprehensive System Audit Tool for Linux and Cloud Instances

DeepCheck is a powerful and easy-to-use bash script packaged as a `.deb` file to perform an extensive system health audit. It gathers detailed information about your Linux or cloud instance environment, including OS details, CPU/memory usage, disk health, network status, running services, security checks, cloud metadata, and more.

---

## Table of Contents

- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Report Output](#report-output)  
- [Requirements](#requirements)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)  

---

## Features

- OS and kernel information  
- Uptime and logged-in users  
- Memory and CPU details  
- Disk usage and health checks (including smartctl if installed)  
- Network interfaces and routing table  
- Open ports and firewall status  
- Running system services  
- Security configuration checks (password policies, ssh root login, auditd status)  
- Cloud metadata detection (AWS)  
- Docker container status  
- Pending system updates (apt/yum supported)  
- Top memory-consuming processes  
- Log file size overview  
- Swap usage statistics  
- Disk I/O statistics  
- Scheduled cron jobs  
- Local firewall (iptables) rules  

---

## Installation

You can install DeepCheck by downloading the pre-built Debian package (`.deb`) from the GitHub Releases page.

### Steps to install:

1. Download the latest `.deb` package from the [Releases](https://github.com/<your-username>/<repo-name>/releases) page:

```bash
wget https://github.com/<your-username>/<repo-name>/releases/download/v1.1.0/deepcheck_1.1.0_amd64.deb
