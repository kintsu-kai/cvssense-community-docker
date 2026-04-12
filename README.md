# CVSSense - Community Edition

This guide provides the necessary instructions to deploy **CVSSense Community Edition** using Docker. This distribution method ensures a streamlined setup while maintaining the integrity and security of the application.



## 💡 Project Background & Vision

**CVSSense** is a private initiative developed to optimize and accelerate the workflow of professional security assessments. This Community Edition serves as a first insight into the core logic of the tool, designed to provide immediate value to the security community.

While this version is free to use, a **Professional Edition** is currently in development. The Pro version will expand upon this foundation with advanced features designed for enterprise-grade vulnerability management and complex reporting requirements.

> **Feedback & Collaboration:** > Your insights are invaluable. For feedback, bug reports, or inquiries regarding the upcoming Professional Edition, please reach out to:  
> 📧 **[Your Email Address Here]**
>Note on Quality: To ensure a productive environment, we only process constructive feedback. Unprofessional messages or personal attacks will be ignored.


## 📊 Feature Comparison: Community vs. Professional

| Feature | 🟢 Community Edition (Current) | 🔵 Professional Edition (Upcoming) |
| :--- | :--- | :--- |
| **Primary Goal** | Trial & Basic Assessment | Full Lifecycle Security Management |
| **Scoring Logic** | CVSS 4.0 Standard Scoring | Advanced AI-assisted Scoring Helper |
| **Decision Support** | Standard Decision Assistant | Pro Decision Assistant |
| **Presets** | 5 Saved Configurations | 20 Saved Configurations |
| **Visualization** | Basic Vulnerability Graph (Limited) | Advanced Graph & OWASP Top 10 Mapping |
| **Data Export** | No Export | SVG, PNG, JPEG Chart Reports |
| **Management** | Standalone Session | History, Editing & 5 Role Permissions |
| **AI Integration** | None | Internal AI Scoring Helper |



## 📌 Architectural Overview

Unlike traditional software distributions, **CVSSense** is delivered as a containerized image. This approach offers several technical advantages:

* **Encapsulation:** The source code and execution environment are securely packaged, preventing accidental modification and ensuring long-term stability.
* **Consistency:** The application operates identically across different operating systems (Windows, macOS, Linux).
* **Zero-Dependency Setup:** No manual installation of underlying runtimes (e.g., Python, Node.js) is required on the host system.



## 🚀 Deployment Instructions

Follow these steps to initialize the application on your local system.

### 1. Prerequisites
Ensure that **Docker Desktop** (or Docker Engine for Linux) is installed and active on your machine. If not yet installed, obtain it at [docker.com](https://www.docker.com/).

### 2. Configuration File
The deployment is managed via a single configuration file: `docker-compose.yml`.
* Download the `docker-compose.yml` file from this repository.
* Place the file in a dedicated directory on your system.

### 3. Service Initialization
Open your terminal or command prompt, navigate to the directory containing the file, and execute the following command:

```bash
docker compose up -d
