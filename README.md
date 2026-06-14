# Python-Environment-Bootstrapper

# Python Environment Bootstrapper with Ansible

## Project Overview

Developed an automated Python environment provisioning solution using Ansible to eliminate dependency conflicts and ensure consistent application deployments across environments. The project demonstrates Configuration Management and Infrastructure Automation best practices by creating isolated Python virtual environments and installing application dependencies from a centralized requirements file.

The solution targets the staging environment and leverages Ansible's native `pip` module to automate virtual environment creation and package installation. By isolating application dependencies from the system-wide Python installation, the automation prevents version conflicts, improves deployment reliability, and supports reproducible development and testing workflows.

## Responsibilities

* Designed and implemented an automated Python environment bootstrap process.
* Created isolated Python virtual environments using Python's built-in `venv` module.
* Automated dependency installation from a centralized `requirements.txt` file.
* Ensured staging environment readiness through automated directory management.
* Applied Infrastructure as Code (IaC) principles for repeatable environment provisioning.
* Reduced manual setup effort and dependency-related deployment failures.
* Maintained environment consistency across application deployment cycles.

## Technologies Used

* Ansible
* YAML
* Python
* Virtual Environments (venv)
* Pip Package Manager
* Linux System Administration
* Configuration Management
* Infrastructure Automation

## Key Features

* Automated virtual environment creation.
* Dependency installation from version-controlled requirements files.
* Isolated application runtime environment.
* Idempotent deployment process using native Ansible modules.
* Staging environment provisioning and validation.
* Prevention of dependency conflicts and version mismatches.
* Agentless automation architecture.

## Business Value

This project demonstrates how automated environment provisioning improves software deployment stability and operational efficiency. By isolating dependencies and enforcing consistent package versions, organizations can reduce application failures, accelerate onboarding, streamline deployments, and ensure predictable execution across environments.

## Outcome

Successfully automated the creation of a Python virtual environment and installation of required dependencies on the staging server using Ansible, improving deployment consistency, reducing configuration drift, and eliminating dependency-related issues.

## Run
source .env/bin/activate
ansible-playbook main.yml

