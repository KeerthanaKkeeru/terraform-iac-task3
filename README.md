# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker Desktop
- Visual Studio Code
- Git and GitHub

## Project Description
This project demonstrates Infrastructure as Code (IaC) using Terraform. The Terraform Docker provider downloads an Nginx image and provisions a Docker container named `terraform-nginx`.

The container exposes port 80 internally and maps it to port 8080 on the local computer.

## Implementation Steps
1. Installed and verified Terraform and Docker.
2. Created the Terraform configuration in `main.tf`.
3. Initialized Terraform using `terraform init`.
4. Formatted and validated the configuration.
5. Reviewed planned changes using `terraform plan`.
6. Created resources using `terraform apply`.
7. Verified the container using Docker commands and a browser.
8. Inspected resources using Terraform state commands.
9. Removed the infrastructure using `terraform destroy`.

## Files Included
- `main.tf` — Terraform configuration.
- `logs/execution-logs.txt` — Terminal execution log.
- `screenshots/` — Screenshots showing execution and verification.
- `.gitignore` — Excludes Terraform-generated and local state files.

## Result
Successfully provisioned and verified a local Docker container using Terraform, inspected its state, and destroyed the managed infrastructure.

## Learning Outcome
Understood Infrastructure as Code, Terraform providers, resources, planning, applying, state management, and infrastructure destruction.