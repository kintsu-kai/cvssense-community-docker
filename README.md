# 🛡️ CVSSense - Community Edition

**Optimize and accelerate your security assessment workflow with precision CVSS 4.0 scoring.**

**CVSSense** is a private initiative developed to streamline the workflow of professional security assessments. This Community Edition serves as a first insight into the core logic of the tool, designed to provide immediate value to the security community.



## 📸 Demo

<img src="https://github.com/user-attachments/assets/f4775260-0ecd-4088-86cb-8e1d2a58417d" width="100%" alt="CVSSense Dashboard Preview">
*A look at the CVSS 4.0 scoring interface.*



## 📦 Installation

CVSSense is delivered as a **containerized image** via Docker. This ensures a zero-dependency setup and consistent performance across Windows, macOS, and Linux.

### Prerequisites
* **Docker Desktop** (or Docker Engine for Linux) must be installed and active. [Download Docker here](https://www.docker.com/).

### Setup Steps
1. **Download** the `docker-compose.yml` file from this repository.
2. **Place** the file in a dedicated directory on your system.
3. **Initialize** the service by running the following command in your terminal:

```bash
docker compose up -d
```

## 🛠 Usage

Once the container is successfully initialized, you can access the application through your web browser.

**Access URL:** `http://localhost:8080` *(Note: If you modified the port in your docker-compose.yml, use that port instead).*

### Recommended Workflow:
1. **Analyze Vulnerability:** Input the specific characteristics of the security flaw.
2. **Select Metrics:** Choose the appropriate values based on the **CVSS 4.0 Standard**.
3. **Utilize Decision Support:** If unsure about a metric, refer to the built-in **Standard Decision Assistant** for guidance.
4. **Save Configuration:** Store your result as one of your 5 available session presets for quick reference.



## ✨ Features

* **Native CVSS 4.0 Logic:** Stay up to date with the latest industry standard for vulnerability scoring.
* **Decision Assistant:** Reduces subjectivity by providing logic-based guidance during the scoring process.
* **Containerized Stability:** Runs in an isolated environment, ensuring that host system updates don't break the tool.
* **Visual Insights:** Includes a basic vulnerability graph to help visualize the impact of the score.



## 🧰 Tech Stack

* **Deployment:** Docker & Docker Compose
* **Standardization:** CVSS v4.0 Framework
* **Architecture:** Secure Containerized Microservice



## 🤝 Feedback & Collaboration

We value input from the security community to help refine CVSSense.

* **Bug Reports & Suggestions:** Please email us at **CVSSsense@hotmail.com**.
* **Professional Inquiries:** Contact us for details regarding the upcoming **Professional Edition**, featuring AI-assisted scoring and enterprise reporting.

> [!IMPORTANT]
> **Community Guidelines:** To maintain a productive exchange, we only respond to constructive and professional feedback.



## ⚖️ License & Terms

CVSSense is proprietary software. By installing or using this application, you acknowledge that you have read and agree to be bound by the terms in the provided license documentation.

### License Summary:
* **Proprietary License:** CVSSense is owned exclusively by **K3res**. All rights, including source code, logic, and the "Decision Assistant" workflows, are reserved.
* **Usage Tier (Community Edition):** You are granted a non-exclusive license for internal, non-commercial assessment purposes.
* **Technical Limitations:** In this version, usage is limited to **five (5) saved presets**. Access to the AI Engine and OWASP Top 10 Integration is strictly prohibited and technically disabled.
* **Restrictions:** Redistribution, modification, reverse engineering, or incorporating this logic into other products is strictly prohibited without prior written consent.

### Third-Party Components:
This product contains software components (including `cvss40.js`) developed by **FIRST.ORG, Inc., Red Hat, and contributors**, licensed under the **BSD 2-Clause License**.

Detailed legal documents can be found in the `license` folder of this repository:
* `license/EULA.md` – End User License Agreement
* `license/CVSSense_licenses.md` – Proprietary License Details
* `license/cvss40.js_licenses.txt` – Third-Party Notices & BSD License

## 🙌 Credits & Acknowledgments

* **Inspiration:** Developed to support the tireless work of penetration testers and security analysts worldwide.
* **Frameworks:** Built upon the standards provided by **FIRST.org** for CVSS 4.0.
* **Special Thanks:** To the early testers who provided the initial data to calibrate the decision assistant.

---
© 2026 K3res | CVSSense Initiative. All rights reserved.
