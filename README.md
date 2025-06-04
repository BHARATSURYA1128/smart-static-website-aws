# 🌐 Smart Static Website (AWS Project)

A secure, scalable, and cost-effective static website hosted entirely on **AWS Free Tier services**. Designed and implemented by **Bharat Surya Jithuga** to showcase cloud skills with real-world infrastructure.

🔗 **Live Demo:** [Smart Static Website](https://d1axzls1oymsy2.cloudfront.net)

---

## 📌 Project Overview

This project demonstrates how to host a static website using **Amazon S3**, distributed securely through **CloudFront**, and optionally integrated with a **custom domain using Route 53**. It's ideal for personal portfolios, product pages, or blog hosting — with near-zero running costs on AWS Free Tier.

---

## 🧠 Learning Goals

✅ Understand AWS S3 static hosting  
✅ Configure CloudFront for secure, cached delivery  
✅ Use IAM to manage access securely  
✅ Automate deployments using AWS CLI  
✅ (Optional) Integrate custom domains via Route 53

---

## 🏗️ Architecture Diagram

![Architecture Diagram](assets/architecture.png)

---

## 🛠️ Tools & AWS Services Used

| Tool / Service | Purpose                                |
|----------------|-----------------------------------------|
| **Amazon S3**   | Static website file storage and hosting |
| **CloudFront**  | CDN and SSL (HTTPS) distribution        |
| **IAM**         | Access and bucket policy management     |
| **AWS CLI**     | Command-line deployment automation      |
| **Route 53** *(optional)* | Custom domain + DNS management    |

---

## 📸 Demo Screenshot

![Demo Screenshot](assets/demo.png)

---

## 📂 Folder Structure

```bash
Smart-Static-Website/
├── assets/                  # Images and demo screenshots
│   └── demo-screenshot.png
├── architecture.png         # AWS infrastructure diagram
├── portfolio.pdf            # Project overview (PDF format)
├── src/                     # Your actual static site files
├── README.md
└── .gitignore
