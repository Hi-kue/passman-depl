# Passman Deployment

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

Passman is a secure and user-friendly password management tool designed to help users store, manage, and retrieve their passwords efficiently. This repository contains the deployment configuration and scripts for deploying Passman to various environments.

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Features

- **Secure Password Storage**: Encrypts and stores passwords securely.
- **Cross-Platform**: Deployable on multiple environments (e.g., Docker, Kubernetes, Cloud).
- **User-Friendly Interface**: Easy-to-use interface for managing passwords.
- **Automated Deployment**: Streamlined deployment process using CI/CD pipelines.

---

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Kubernetes](https://kubernetes.io/docs/setup/) (optional, for Kubernetes deployment)
- [Terraform](https://www.terraform.io/downloads.html) (optional, for cloud deployment)
- [Helm](https://helm.sh/docs/intro/install/) (optional, for Helm-based deployments)

---

## Installation

To set up Passman locally or in your environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Hi-kue/passman-depl.git
   cd passman-depl
  ```
2. Setup fly.io with auth login:
    ```bash
    flyctl auth login | fly auth login
    ```
3. Visit Fly.io, head to your dashboard, and click on the newly created pocketbase application.

## Usage

Once deployed, access the URL provided by Fly.io and start using your instance of Pocketbase.
Note you should make sure that you create a superuser account first to access the
application. Pocketbase should provide you a route to create a superuser account.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
