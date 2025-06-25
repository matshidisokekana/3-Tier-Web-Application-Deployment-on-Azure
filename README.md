# 🌐 3-Tier Web Application Deployment on Azure with GitHub Actions

This project demonstrates how to deploy a complete **3-tier web application** (Frontend, Backend, and MySQL Database) on **Azure**, using **GitHub Actions for CI/CD** and Azure App Services for cloud hosting.

---

## 🛠️ Tools & Technologies

- Azure App Service (Linux)
- Azure MySQL Database
- GitHub Actions (CI/CD)
- Deployment Center (Azure Portal)
- GitHub Source Control

---

## 🧱 Architecture Overview

- **Frontend & Backend**: Deployed together using Azure App Service
- **Database**: Azure-hosted MySQL with custom schema (`myschema`)
- **Authentication**: Secure connection between App Service and DB
- **CI/CD Pipeline**: GitHub Actions integrated through Deployment Center

---

## 🔄 Deployment Workflow

1. **Create Resource Group** (Canada Central)
2. **Deploy App Service** with Linux OS
3. **Connect GitHub Repository** using Deployment Center
4. **Set up MySQL Server** and configure schema
5. **Configure Environment Variables** for DB connection
6. **Trigger Deployment** via GitHub Push → Azure Web App auto-updated
7. **Application Live**: Deployed website accessible via Azure URL

---

## ✅ What I Learned

- Implemented full-stack application deployment using **Azure services**
- Built a **CI/CD pipeline** using **GitHub Actions**, enabling fast and automated cloud deployments
- Gained practical experience in **secure DB connection setup** and **cloud-native DevOps**
- Learned how to orchestrate multiple Azure resources for **production-like cloud architecture**

---

### 🌐 Why Hosting a Website on Azure Cloud is Easy and Important

**Ease of Hosting on Azure:**

* **User-Friendly Interface:** Azure Portal provides an intuitive, web-based interface that lets you create and manage resources like web apps quickly—no deep infrastructure knowledge needed initially.
* **Managed Services:** Azure App Service handles the underlying infrastructure, OS patching, scaling, and availability, so you focus only on your app code.
* **Quick Deployment:** You can deploy websites directly from code repositories like GitHub, with built-in CI/CD support for fast, automated updates.
* **Built-In Security & Compliance:** Azure offers pre-configured security features and compliance certifications, helping protect your website and data without extra setup.
* **Scalability:** Easily scale your website up or down to handle changes in traffic, ensuring consistent performance without manual server management.

---

**Importance of Hosting Websites on Azure:**

* **Reliability & Uptime:** Azure’s global data centers and redundant infrastructure ensure your website is always available to users worldwide.
* **Cost Efficiency:** Pay-as-you-go pricing helps optimize costs—you only pay for the resources you use.
* **Global Reach:** With data centers around the world, you can deploy websites close to your users to reduce latency.
* **Integration with Other Services:** Azure websites can easily connect with databases, AI services, storage, and monitoring tools, enabling rich, modern applications.
* **Supports Modern DevOps:** Azure’s integration with GitHub, Azure DevOps, and other tools facilitates continuous deployment, testing, and monitoring workflows.

---

Hosting a website on Azure transforms complex infrastructure management into a simple, scalable, and secure process — empowering developers to focus on building great applications and delivering value quickly.

---
## 🙋🏽‍♂️ Author

**Matshidiso M. Kekana**  
[GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourprofile)

---

