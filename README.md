# Terraform Azure Resource Group

## Overview

This project provisions an Azure Resource Group using Terraform Infrastructure as Code (IaC).

The solution demonstrates how to automate Azure infrastructure deployment using reusable Terraform configuration files and variables.

---

## Architecture

Developer → Terraform → Azure Provider → Azure Resource Group

---

## Project Structure

terraform-azure-rg/

├── main.tf

├── variables.tf

├── terraform.tfvars

└── README.md

---

## Resources Created

* Azure Resource Group

---

## Variables

| Variable | Description         |
| -------- | ------------------- |
| rg_name  | Resource Group Name |
| location | Azure Region        |

---

## Execution Steps

terraform init

terraform plan

terraform apply

---

## Benefits

* Infrastructure as Code
* Reusable Configuration
* Faster Deployment
* Consistent Environment Provisioning

---

## Author

Kumar Manglam

DevOps Engineer
