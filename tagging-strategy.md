# AWS Tagging Strategy

## 📌 Objective
To enforce standardized tagging across all AWS resources for cost tracking, governance, and operational clarity.

---

## 🏷 Mandatory Tags

| Key | Description | Example |
|------|------------|----------|
| Environment | Deployment stage | Dev |
| Project | Project name | DevOps-30Day |
| Owner | Resource owner | Adarsha |
| CostCenter | Budget allocation group | Learning |
| ManagedBy | Tool managing resource | Manual / Terraform |

---

## 📊 Why Tagging Matters

- Enables cost allocation reports
- Helps identify unused resources
- Supports automation
- Improves compliance visibility

---

## 🔒 Governance Rule

All AWS resources must include mandatory tags during creation.

Resources without tags should be considered non-compliant.
