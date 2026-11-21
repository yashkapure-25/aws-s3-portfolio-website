** ☁️ Amazon S3 & Cloud Storage — Portfolio Website**

## 📌 Project Overview

This project demonstrates how to host a static portfolio website using **Amazon Simple Storage Service (Amazon S3)**.

The project covers S3 bucket creation, object management, storage classes, access permissions, and static website hosting.

## 🎯 Objectives

- Understand Amazon S3 buckets, objects, permissions, and storage classes.
- Create and configure an S3 bucket.
- Upload and manage website files using Amazon S3.
- Understand S3 access control and bucket policies.
- Deploy a static portfolio website using S3 Static Website Hosting.

## 🛠️ Technologies Used

- Amazon Web Services (AWS)
- Amazon S3
- AWS IAM
- S3 Bucket Policies
- HTML5
- CSS3
- Git & GitHub

## 🏗️ Project Architecture

User Browser → Amazon S3 Static Website Endpoint → S3 Bucket → HTML/CSS Files

## 🚀 Implementation Steps

### 1. Created an S3 Bucket
- Created a general-purpose Amazon S3 bucket.
- Selected an AWS Region.
- Configured bucket settings and object ownership.

### 2. Uploaded Website Files
- Developed a static portfolio website using HTML and CSS.
- Uploaded website files to the S3 bucket.
- Used the S3 Standard storage class.

### 3. Configured Bucket Permissions
- Reviewed S3 Block Public Access settings.
- Configured a bucket policy to allow public read access to website objects.
- Applied permissions required for static website hosting.

### 4. Enabled Static Website Hosting
- Opened the S3 bucket Properties tab.
- Enabled static website hosting.
- Configured `index.html` as the index document.
- Obtained the S3 website endpoint.

### 5. Tested Website Deployment
- Accessed the website using its S3 endpoint.
- Verified that the portfolio loads successfully in a web browser.

## 🔐 Security Considerations

- Public read access was configured only for website files.
- Sensitive information and credentials were not uploaded.
- Bucket permissions were reviewed to avoid unnecessary access.
- For production deployments, CloudFront with a private S3 bucket is recommended.

## 📂 Repository Structure

```text
aws-s3-portfolio-website/
├── index.html
├── README.md
└── screenshots/
    ├── s3-bucket.png
    ├── s3-objects.png
    ├── bucket-policy.png
    ├── static-hosting.png
    └── live-website.png
```

## 🌐 Live Website

**Website URL:** http://yash-aws-s3-portfolio-2026.s3-website-ap-southeast-2.amazonaws.com/

## 📸 Screenshots

The `screenshots` directory contains evidence of the S3 configuration and website deployment.

## 📚 Key Learnings

- Amazon S3 bucket and object management
- S3 storage classes
- Bucket policies and access permissions
- Static website hosting
- AWS cloud storage fundamentals
- Deploying static websites without managing servers

## ✅ Conclusion

Successfully deployed a static portfolio website using Amazon S3 and gained practical experience in AWS cloud storage, permissions, and serverless static website hosting.

---

**Project:** Amazon S3 & Cloud Storage  
**Learning Program:** Codomax Digital Solutions
