# FAMS - Flix App Management System

**FAMS** is a robust, centralized platform designed to streamline the lifecycle of mobile and web applications. It provides a comprehensive suite of tools for release management, OTA updates (CodePush), and team collaboration.

## 🚀 Key Features

- **App Management:** Centralized dashboard to track multiple applications across various environments.
- **CodePush (OTA Updates):** Deploy dynamic patches to your applications without requiring a full store re-submission.
- **Release Distribution:** Securely store and distribute build artifacts (binaries, bundles, and assets).
- **Organization & Collaboration:** Multi-tenant support allowing teams to manage apps, invitations, and permissions.
- **Unified CLI:** Powerful command-line interface for CI/CD integration and developer workflows.
- **Modern Dashboard:** A sleek, high-performance web interface built with React and Rsbuild.

## 📦 Components

This repository serves as the public distribution channel for the following components:

- **Backend:** A high-performance Go-based API handling authentication, storage, and logic.
- **CLI:** A cross-platform tool for developers to manage releases and CodePush patches from the terminal.
- **Frontend:** A responsive, interactive dashboard for visual management.

## 📦 Distribution & Installation

### 1. Web Dashboard
The web interface is hosted live at:  
👉 **[https://flixyudh.github.io/fams_public/](https://flixyudh.github.io/fams_public/)**

### 2. Binaries & Releases
For the Backend and CLI tools, navigate to the **[Releases](https://github.com/flixyudh/fams_public/releases)** section. We provide pre-compiled binaries for:
- **Linux** (amd64, arm64)
- **macOS** (Intel, Apple Silicon M1/M2/M3)
- **Windows** (amd64)

---

## 🛠 Tech Stack

- **Backend:** Go (Golang)
- **Frontend:** React, Rsbuild, Tailwind CSS
- **CLI:** Go (Cobra/TUI)
- **Database:** PostgreSQL / SQLite

---
*FAMS is an automated release system. For internal source code access or security inquiries, please email flixy121@gmail.com or open an issue.*
