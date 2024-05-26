# Ansible Setup Playbook

This Ansible playbook automates the setup and configuration of a development environment on a local machine. It performs tasks such as updating the system, installing essential packages, and configuring services.

## Requirements

- Ansible installed on your local machine.
- A compatible operating system (the playbook is designed for systems using `dnf` package manager, such as Fedora).

## Playbook Tasks

The playbook performs the following tasks:

1. **System Update**: Updates all installed packages to their latest versions.
2. **Installing Git**: Installs Git, a version control system.
3. **Installing Fish Shell**: Installs Fish, a user-friendly command line shell.
4. **Changing Default Shell to Fish**: Changes the default shell to Fish for the root user.
5. **Installing Curl**: Ensures Curl is installed, a tool for transferring data with URLs.
6. **Installing Node.js**: Installs Node.js, a JavaScript runtime.
7. **Verifying Node.js Installation**: Verifies the installation of Node.js and displays the installed version.
8. **Installing Docker**: Installs Docker and related packages.
9. **Starting Docker Service**: Starts and enables the Docker service.
10. **Installing npm**: Installs npm, the Node.js package manager.
11. **Installing pnpm**: Installs pnpm, an alternative package manager for Node.js.

## Usage

To use this playbook, follow these steps:

1. Ensure you have Ansible installed.
2. Clone the repository containing this playbook to your local machine.
   ```bash

   git clone https://github.com/shubhendra3/ansible.git
   cd ansible
   ansible-playbook code.yaml
   ```
