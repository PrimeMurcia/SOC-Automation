# SOC Automation Installation Guide

Welcome to the SOC Automation Installation Guide. This guide will walk you through the steps to install and configure various components essential for setting up a Security Operations Center (SOC). The components covered in this guide are:

1. [Wazuh](https://github.com/PrimeMurcia/Wazuh-Installation-Guide)
2. [TheHive](https://github.com/PrimeMurcia/TheHive-Installation)
3. [Wazuh Vulnerability Scanning](https://github.com/PrimeMurcia/Wazuh-Vulnerability-Scanning/blob/main/README.md)
4. [Basic Securing NGINX](https://github.com/PrimeMurcia/Basic-securing-NGINX)
5. [NGINX Reverse Proxy WAF](https://github.com/PrimeMurcia/nginx-reverse-proxy-WAF/tree/main)
6. [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](https://github.com/PrimeMurcia/Wazuh-nginx-monitoring-and-Virus-total)
7. [Integration of Wazuh and TheHive](https://github.com/PrimeMurcia/Wazuh-SIEM-The-Hive-Integration/tree/main)
8. [Wazuh, TheHive, and Shuffle Integration](https://github.com/PrimeMurcia/Wazuh-TheHive-and-Shuffle-integration)
9. [Wazuh Email Alert and Active Response](https://github.com/PrimeMurcia/Wazuh-Email-Alert-and-Active-respond)

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation Guide](#installation-guide)
   - [Wazuh](#wazuh)
   - [TheHive](#thehive)
   - [Wazuh Vulnerability Scanning](#wazuh-vulnerability-scanning)
   - [Basic Securing NGINX](#basic-securing-nginx)
   - [NGINX Reverse Proxy WAF](#nginx-reverse-proxy-waf)
   - [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](#wazuh-nginx-monitoring-and-virustotal-integration-for-xdr)
   - [Integration of Wazuh and TheHive](#integration-of-wazuh-and-thehive)
   - [Wazuh, TheHive, and Shuffle Integration](#wazuh-thehive-and-shuffle-integration)
   - [Wazuh Email Alert and Active Response](#wazuh-email-alert-and-active-response)
4. [Configuration](#configuration)
5. [Support](#support)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This guide provides comprehensive instructions to install and configure essential tools for SOC automation. Follow the steps carefully to set up your SOC environment efficiently.

**Note:** All installations and configurations in this guide are based on Ubuntu 22.04.

## Prerequisites

Before starting the installation, ensure you have the following prerequisites:

- A Linux-based operating system (Ubuntu 22.04)
- Root or sudo access to the system
- Internet connectivity
- Basic knowledge of Linux commands

## Installation Guide

### Wazuh

Wazuh is a free, open-source security monitoring platform. It provides threat detection, integrity monitoring, incident response, and compliance management. Follow the detailed installation guide provided in the link below:

- [Wazuh Installation Guide](https://github.com/PrimeMurcia/Wazuh-Installation-Guide)

### TheHive

TheHive is a scalable, open-source, and free Security Incident Response Platform. It helps in managing and resolving security incidents efficiently. To install TheHive, refer to the guide linked below:

- [TheHive Installation Guide](https://github.com/PrimeMurcia/TheHive-Installation)

### Wazuh Vulnerability Scanning

Wazuh's vulnerability scanning feature helps identify vulnerabilities in your system, ensuring your environment is secure. Follow the guide below to set up and configure vulnerability scanning with Wazuh:

- [Wazuh Vulnerability Scanning](https://github.com/PrimeMurcia/Wazuh-Vulnerability-Scanning/blob/main/README.md)

### Basic Securing NGINX

Securing NGINX involves configuring several security measures to protect your web server. This includes setting secure headers, implementing basic authentication, and using allow/deny directives to control access. Follow the guide below for detailed steps:

- [Basic Securing NGINX](https://github.com/PrimeMurcia/Basic-securing-NGINX)

### NGINX Reverse Proxy WAF

Setting up an NGINX Reverse Proxy with a Web Application Firewall (WAF) enhances the security of your web applications by filtering and monitoring HTTP traffic. This setup uses the open-source ModSecurity and the latest OWASP Core Rule Set (CRS). Follow the guide below to set up NGINX as a reverse proxy with WAF capabilities:

- [NGINX Reverse Proxy WAF](https://github.com/PrimeMurcia/nginx-reverse-proxy-WAF/tree/main)

### Wazuh NGINX Monitoring and VirusTotal Integration for XDR

This integration allows you to monitor NGINX logs using Wazuh and enhance your security operations with VirusTotal's intelligence. It provides extended detection and response (XDR) capabilities. Follow the guide below to set it up:

- [Wazuh NGINX Monitoring and VirusTotal Integration for XDR](https://github.com/PrimeMurcia/Wazuh-nginx-monitoring-and-Virus-total)

### Integration of Wazuh and TheHive

Integrating Wazuh with TheHive allows you to automate the creation of security incidents and streamline incident response processes. Follow the guide below to integrate Wazuh with TheHive:

- [Integration of Wazuh and TheHive](https://github.com/PrimeMurcia/Wazuh-SIEM-The-Hive-Integration/tree/main)

### Wazuh, TheHive, and Shuffle Integration

Integrating Wazuh, TheHive, and Shuffle provides enhanced automation for incident response workflows. Shuffle is a workflow automation tool that further improves incident handling efficiency. Follow the guide below to set up this integration:

- [Wazuh, TheHive, and Shuffle Integration](https://github.com/PrimeMurcia/Wazuh-TheHive-and-Shuffle-integration)

### Wazuh Email Alert and Active Response

Configuring Wazuh for email alerts and active response helps in promptly addressing security incidents by sending alerts and taking predefined actions automatically. Follow the guide below to set up Wazuh for email alerts and active response:

- [Wazuh Email Alert and Active Response](https://github.com/PrimeMurcia/Wazuh-Email-Alert-and-Active-respond)

## Configuration

After installing the components, follow the configuration steps outlined in each respective guide to ensure proper integration and functionality. Make sure to:

- Configure Wazuh agents and manager.
- Set up TheHive connectors and users.
- Integrate VirusTotal with Wazuh for extended detection and response.
- Configure the integration between Wazuh and TheHive to automate incident management.
- Set up and configure the NGINX reverse proxy and WAF with ModSecurity and the latest OWASP Core Rule Set.
- Configure basic security measures in NGINX, including secure headers, basic authentication, and allow/deny directives.
- Configure vulnerability scanning in Wazuh.
- Set up and configure the integration between Wazuh, TheHive, and Shuffle.
- Configure Wazuh for email alerts and active response.

## Support

If you encounter any issues during installation or configuration, please refer to the respective guide's troubleshooting section. For further assistance, you can open an issue on the corresponding GitHub repository.

## Contributing

We welcome contributions to improve the guides and the installation process. If you have suggestions or improvements, please fork the repositories and submit a pull request.

## License

This guide and the associated repositories are licensed under the MIT License. For more details, refer to the LICENSE file in each repository.

---

Thank you for using the SOC Automation Installation Guide. We hope this helps you set up a robust SOC environment. For any questions or feedback, please reach out through the respective GitHub repositories.
