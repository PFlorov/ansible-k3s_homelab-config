Ansible Homelab Configuration


This repository houses the Ansible playbooks and inventory for managing my personal K3s homelab cluster. It follows an Infrastructure as Code (IaC) approach to automate setup, configuration, and maintenance tasks across my nodes.

---

🎯 Purpose

The primary goals for this repository are:

- Automated K3s Management: Automate the installation, configuration, and lifecycle management of my K3s cluster.

- Reproducible Environment: Ensure a consistent and reproducible setup for all homelab nodes.

- Configuration Management: Define and maintain the desired state of system configurations and application deployments.

- Disaster Recovery: Facilitate quick recovery or re-provisioning of the entire homelab infrastructure.

- Skill Development: Deepen practical experience with Ansible and IaC principles.

---

⚙️ How It Works

Ansible is run from my local machine (the control node) and connects to the homelab servers via SSH. Playbooks define the desired state, and Ansible ensures that state is applied to the target machines.

Prerequisites

- Ansible: Installed on your local machine (ansible-core or ansible package).

- SSH Access: SSH keys configured for passwordless access from your local machine to all target homelab nodes.

- Privilege Escalation: sudo access configured for the ansible_user on all target nodes.

---

🛠️ Key Automations

This repository aims to automate tasks such as:

- Operating System package updates and common utility installation.

- Initial K3s master and worker node provisioning.

- Deployment of essential cluster services (e.g., FluxCD bootstrap).

- Regular maintenance and health checks.

---

🤝 Contributing & Support

This is a personal learning repository. However, suggestions, issues, or pull requests are welcome.

---
