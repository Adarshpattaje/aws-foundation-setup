# AWS Foundation Setup – Secure Account Baseline

## 📌 Project Objective
This repository documents the secure foundational setup of an AWS account following DevOps and security best practices. The goal is to establish a hardened baseline before provisioning infrastructure.

This simulates real-world cloud onboarding in enterprise environments.

---

## 🏗 Scope of Implementation

- Root account secured with MFA
- IAM Admin user created (no root usage)
- Least privilege access model introduced
- Custom IAM policy created
- AWS CLI configured
- Standardized tagging strategy defined
- Billing alert configured

---

## 🔐 Security Controls Implemented

### 1. Root Account Hardening
- MFA enabled
- Root access restricted (no daily usage)
- Billing alerts configured

### 2. IAM Governance
- Created IAM group: `DevOps-Lab-Group`
- Created custom policy: `DevOpsLabPolicy`
- Attached policy to group
- Assigned user to group

### 3. AWS CLI Configuration
Configured AWS CLI for programmatic access using secure credentials.

Command used:
aws sts get-caller-identity


---

## 🏷 Tagging Strategy
All future resources will follow standardized tagging for cost tracking and governance.

See `tagging-strategy.md`

---

## 📁 Repository Structure

aws-foundation-setup/
│
├── README.md
├── iam-policies/
│ └── DevOpsLabPolicy.json
└── tagging-strategy.md


---

## 🚀 Next Steps

- VPC architecture creation
- EC2 provisioning
- Security Group design
- Infrastructure as Code (Terraform)

---

## 👤 Owner
Adarsha  
DevOps / Cloud Engineering Practice
