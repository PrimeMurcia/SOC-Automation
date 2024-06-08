# SOC Automation Installation Guide

Welcome to the SOC Automation Installation Guide. This guide will walk you through the steps to install and configure various components essential for setting up a Security Operations Center (SOC). The components covered in this guide are:

1. [Wazuh](https://github.com/PrimeMurcia/Wazuh-Installation-Guide)
2. [TheHive](https://github.com/PrimeMurcia/TheHive-Installation)
3. [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](https://github.com/PrimeMurcia/Wazuh-nginx-monitoring-and-Virus-total)
4. [Integration of Wazuh and TheHive](https://github.com/PrimeMurcia/Wazuh-SIEM-The-Hive-Integration/tree/main)
5. [NGINX Reverse Proxy WAF](https://github.com/PrimeMurcia/nginx-reverse-proxy-WAF/edit/main/README.md)
6. [Wazuh Vulnerability Scanning](https://github.com/PrimeMurcia/Wazuh-Vulnerability-Scanning/blob/main/README.md)

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation Guide](#installation-guide)
   - [Wazuh](#wazuh)
   - [TheHive](#thehive)
   - [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](#wazuh-nginx-monitoring-and-virustotal-integration-for-xdr)
   - [Integration of Wazuh and TheHive](#integration-of-wazuh-and-thehive)
   - [NGINX Reverse Proxy WAF](#nginx-reverse-proxy-waf)
   - [Wazuh Vulnerability Scanning](#wazuh-vulnerability-scanning)
4. [Configuration](#configuration)
5. [Support](#support)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This guide provides comprehensive instructions to install and configure essential tools for SOC automation. Follow the steps carefully to set up your SOC environment efficiently.

## Prerequisites

Before starting the installation, ensure you have the following prerequisites:

- A Linux-based operating system (Ubuntu recommended)
- Root or sudo access to the system
- Internet connectivity
- Basic knowledge of Linux commands

## Installation Guide

### Wazuh

Wazuh is a free, open-source security monitoring platform. Follow the detailed installation guide provided in the link below:

- [Wazuh Installation Guide](https://github.com/PrimeMurcia/Wazuh-Installation-Guide)

### TheHive

TheHive is a scalable, open-source, and free Security Incident Response Platform. To install TheHive, refer to the guide linked below:

- [TheHive Installation Guide](https://github.com/PrimeMurcia/TheHive-Installation)

### Wazuh NGINX Monitoring and VirusTotal Integration for XDR

This integration allows you to monitor NGINX logs using Wazuh and enhance your security operations with VirusTotal's intelligence. Follow the guide below to set it up:

- [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](https://github.com/PrimeMurcia/Wazuh-nginx-monitoring-and-Virus-total)

### Integration of Wazuh and TheHive

Integrating Wazuh with TheHive allows you to automate the creation of security incidents and streamline incident response processes. Follow the guide below to integrate Wazuh with TheHive:

- [Integration of Wazuh and TheHive](https://github.com/PrimeMurcia/Wazuh-SIEM-The-Hive-Integration/tree/main)

### NGINX Reverse Proxy WAF

Setting up an NGINX Reverse Proxy with a Web Application Firewall (WAF) enhances the security of your web applications. Follow the guide below to set up NGINX as a reverse proxy with WAF capabilities:

- [NGINX Reverse Proxy WAF](https://github.com/PrimeMurcia/nginx-reverse-proxy-WAF/edit/main/README.md)

### Wazuh Vulnerability Scanning

Wazuh's vulnerability scanning feature helps identify vulnerabilities in your system. Follow the guide below to set up and configure vulnerability scanning with Wazuh:

- [Wazuh Vulnerability Scanning](https://github.com/PrimeMurcia/Wazuh-Vulnerability-Scanning/blob/main/README.md)

## Configuration

After installing the components, follow the configuration steps outlined in each respective guide to ensure proper integration and functionality. Make sure to:

- Configure Wazuh agents and manager.
- Set up TheHive connectors and users.
- Integrate VirusTotal with Wazuh for extended detection and response.
- Configure the integration between Wazuh and TheHive to automate incident management.
- Set up and configure the NGINX reverse proxy and WAF.
- Configure vulnerability scanning in Wazuh.

## Support

If you encounter any issues during installation or configuration, please refer to the respective guide's troubleshooting section. For further assistance, you can open an issue on the corresponding GitHub repository.

## Contributing

We welcome contributions to improve the guides and the installation process. If you have suggestions or improvements, please fork the repositories and submit a pull request.

## License

This guide and the associated repositories are licensed under the MIT License. For more details, refer to the LICENSE file in each repository.

---

Thank you for using the SOC Automation Installation Guide. We hope this helps you set up a robust SOC environment. For any questions or feedback, please reach out through the respective GitHub repositories.
