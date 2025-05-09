# 🌐 Visitor Counter with AWS Lambda, DynamoDB & Function URL

Track visits to your website in real time using a fully serverless architecture powered by AWS Lambda, DynamoDB, and a direct Lambda Function URL endpoint.

![Architecture Diagram](https://user-images.githubusercontent.com/your-diagram.png) <!-- Optional: Add your own diagram -->

---

## 🚀 Live Demo

Try it live: [https://pedroaragoncloud.com](https://pedroaragoncloud.com)

---

## 📦 Stack

- **Frontend**: Static website hosted with visitor count logic in JavaScript
- **Backend**: AWS Lambda 
- **Database**: Amazon DynamoDB 
- **API**: AWS Lambda Function URL with CORS support
- **Infrastructure as Code**: Terraform

---

## 📊 Features

- ✅ Real-time visitor count
- ✅ Serverless & scalable
- ✅ CORS-enabled Function URL (secure to your domain)
- ✅ Fully managed infrastructure with Terraform
- ✅ Cost-efficient (no idle compute charges)

---

## 🧠 Architecture

1. User visits the website.
2. JavaScript code sends a POST request to the AWS Lambda Function URL.
3. Lambda securely updates the `viewer-count` item in DynamoDB.
4. Response returns updated visitor count.
5. All resources are provisioned and managed using Terraform.
