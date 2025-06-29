# 🌐 Smart Static Website (AWS Project)

A secure, scalable, and cost-effective static website hosted entirely on **AWS Free Tier services**. Designed and implemented by **Bharat Surya Jithuga** to showcase cloud skills with real-world infrastructure.

🔗 **Live Demo:** [Smart Static Website](https://dr48176xbcono.cloudfront.net/)

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

| Tool / Service         | Purpose                                |
|------------------------|-----------------------------------------|
| **Amazon S3**          | Static website file storage and hosting |
| **CloudFront**         | CDN and SSL (HTTPS) distribution        |
| **IAM**                | Access and bucket policy management     |
| **AWS CLI**            | Command-line deployment automation      |
| **Route 53** *(optional)* | Custom domain + DNS management     |

---

## 📸 Demo Screenshot

![Demo Screenshot](assets/demo.png)

---

## 📂 Folder Structure

```bash
Smart-Static-Website/
├── assets/
│   ├── demo-screenshot.png
│   └── architecture.png
├── portfolio.pdf
├── src/                     # Actual static website files
├── README.md
└── .gitignore

---
```



🔐 Sample S3 Bucket Policy
json
Copy code
```bash
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::nice-school-smart-website-bharat/*"
    }
  ]
}

```


## 🎓 What I Learned from This Project

✅ Hosting a real website using **Amazon S3** and **CloudFront**  
✅ How to configure and apply **IAM policies** and **S3 bucket policies**  
✅ Using **AWS CLI** to manage and automate deployments  
✅ **DNS concepts** and how **Route 53** integrates with CloudFront  
✅ Setting **cache behavior**, **HTTPS enforcement**, and **static error pages**  
✅ Making a **production-ready static website** — at **zero cost** (AWS Free Tier)

---

> 💡 Tip: This approach gives you full control over your website’s deployment pipeline with minimal infrastructure and zero recurring cost — perfect for personal projects and portfolios.
