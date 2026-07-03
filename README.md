# ☁️ AWS CloudOps Project: Static Website Hosting (Amazon S3 + CloudFront)

## 🚀 Overview

This project demonstrates how to deploy a production-ready static website on **Amazon Web Services (AWS)** using **Amazon S3** for website hosting and **Amazon CloudFront** as a Content Delivery Network (CDN). It showcases a real-world cloud deployment workflow, from local development to globally accessible website hosting.

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Amazon S3 (Static Website Hosting)
    │
    ▼
Amazon CloudFront (CDN)
    │
    ▼
Global Users
```

---

## 🌐 Live Deployment

* **Hosting:** Amazon S3 Static Website Hosting
* **Content Delivery:** Amazon CloudFront
* **Access:** Public Web Access

---

## 🧰 Tech Stack

* Amazon Web Services (AWS)

  * Amazon S3
  * Amazon CloudFront
* Git
* GitHub
* HTML5
* CSS3
* JavaScript

---

## ✨ Features

* Hosted a static website using Amazon S3.
* Configured bucket policies to enable secure public access.
* Integrated Amazon CloudFront for faster global content delivery.
* Improved website performance, scalability, and availability through CDN caching.
* Managed source code using Git and GitHub.

---

## 🧠 What I Learned

Throughout this project, I gained hands-on experience with:

* Creating and configuring Amazon S3 buckets
* Enabling Static Website Hosting
* Managing bucket policies and public access permissions
* Configuring Amazon CloudFront distributions
* Troubleshooting deployment issues and CDN configuration
* Using Git and GitHub for version control and project management

---

## 🔧 Challenges & Solutions

### CloudFront 403 Forbidden Error

* Identified incorrect origin configuration.
* Updated the origin to use the correct S3 website endpoint.

### S3 Public Access Issues

* Configured bucket policies correctly.
* Adjusted Block Public Access settings where appropriate.

### CloudFront Origin Misconfiguration

* Differentiated between the S3 bucket endpoint and the S3 static website endpoint.
* Reconfigured the distribution to use the appropriate endpoint.

### GitHub Authentication Problems

* Resolved authentication issues using SSH keys and Personal Access Tokens (PATs).

---

## 📈 Future Enhancements

* Implement a CI/CD pipeline using AWS CodePipeline
* Automate deployments from GitHub to Amazon S3
* Configure a custom domain using Amazon Route 53
* Secure the website with HTTPS using AWS Certificate Manager (ACM)
* Add monitoring and logging using Amazon CloudWatch

---

## 📌 Skills Demonstrated

* AWS Cloud Fundamentals
* Amazon S3
* Amazon CloudFront
* Static Website Hosting
* CDN Configuration
* Git & GitHub
* Troubleshooting Cloud Deployments
* Basic DevOps Practices

---

## 👩‍💻 Author

**Ipshita Chaudhuri**

Aspiring **CloudOps / DevOps Engineer**

Passionate about building scalable cloud infrastructure, automating deployments, and continuously learning modern cloud technologies.
