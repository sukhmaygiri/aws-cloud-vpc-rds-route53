# AWS Cloud Project: VPC, RDS & Route 53

## 📌 Overview
This project demonstrates a secure AWS cloud architecture with:
- Custom VPC (public + private subnets)
- EC2 instance hosting a sample portfolio website
- RDS (MySQL/PostgreSQL) in private subnet
- AWS Client VPN for secure database access
- Route 53 domain + subdomain mapping

## 🏗 Architecture
![VPC Architecture](architecture.png)

- **Public Subnet** → EC2 instance (website)
- **Private Subnet** → RDS instance (MySQL/PostgreSQL)
- **Client VPN Endpoint** → secure access to private subnet
- **Route 53 Hosted Zone** → domain + subdomain (`sukhmay.sukhmaygiridevops.site`) pointing to EC2 website

## 🚀 Steps Implemented
1. Created custom VPC with public/private subnets.
2. Deployed EC2 instance in public subnet with sample website.
3. Launched RDS instance in private subnet (no public access).
4. Configured AWS Client VPN Endpoint for secure RDS access.
5. Registered domain & created Route 53 hosted zone.
6. Configured subdomain `sukhmaygiridevops.site → points to EC2 website.
7. Documented setup with screenshots & architecture diagram.

## 🔗 Subdomain URL
[http://sukhmay.sukhmaygiridevops.site]

## 📂 Repository Contents
- `/screenshots` → setup screenshots
- `/code` → website source code (HTML/CSS)
- `architecture.png` → VPC diagram
- `README.md` → documentation

