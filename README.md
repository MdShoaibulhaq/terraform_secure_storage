# Task 4: Create and Configure Secure File Storage on AWS using Terraform

## 🔒 Objective

Provision a **secure AWS S3 bucket** using Terraform with the following:
- Random bucket name
- Server-side encryption (AES256)
- Versioning enabled
- Block all public access

---

## 📁 Files

| File Name                               | Description                    |
|----------------------------------------|--------------------------------|
| YourName_SecureStorage_2025-05-12.tf   | Terraform file                 |
| output_screenshot.png                  | Output screenshot              |

---

## ✅ Prerequisites

- AWS Account & Access Key
- Terraform installed
- AWS CLI configured
- Git & GitHub setup

---

## 🚀 Deployment Steps

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/secure-file-storage.git
cd secure-file-storage
# terraform_secure_storage
2. Initialize Terraform
bash
Copy
Edit
terraform init
3. Preview Terraform Plan
bash
Copy
Edit
terraform plan
4. Apply the Terraform Configuration
bash
Copy
Edit
terraform apply
Confirm with yes

🧼 To Destroy Resources
bash
Copy
Edit
terraform destroy
