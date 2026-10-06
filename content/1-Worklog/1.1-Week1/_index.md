---
title: "Week 1 Worklog"
date: 2026-10-06
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### 🎯 Week 1 Objectives:
* Complete foundation lessons in **Section 1 - Explore AWS Services**.
* Configure **AWS Budgets** to prevent unexpected cloud costs.
* Practice identity management with **AWS IAM**: Create IAM Users, IAM Groups, and enforce DevSecOps Least Privilege permissions.

---

### 📋 Week 1 Task Progress:

| Session | Lesson & Detailed Practice Content | Status | Reference Material |
| :--- | :--- | :---: | :--- |
| **Session 1** | **[Lesson 2] Manage usage costs with AWS Budgets**<br>• Understand AWS Free Tier allocation.<br>• Configure AWS Budgets to auto-send email alerts if cost exceeds $1.00 USD.<br>• Master account security rules against credential leaks. | <span style="color:green; font-weight:bold;">[COMPLETED]</span> | [AWS Budgets](https://cloudjourney.awsstudygroup.com/1-explore/1.2-budgets/) |
| **Session 1** | **[Lesson 4] Access Management with AWS IAM**<br>• Understand IAM Users, IAM Groups & Policies.<br>• Practice creating `Developers-Group`, user `dev-khang`, and assign membership.<br>• Verify identity access control following DevSecOps standards. | <span style="color:green; font-weight:bold;">[COMPLETED]</span> | [AWS IAM](https://cloudjourney.awsstudygroup.com/1-explore/1.4-iam/) |
| **Session 2** | **[Lesson 5] Grant permissions through IAM Role**<br>• Learn temporary credential assumption (`sts assume-role`).<br>• Practice creating `S3-Admin-Role` & `AdminGroup`. | <span style="color:orange; font-weight:bold;">[NEXT LESSON]</span> | [IAM Role](https://cloudjourney.awsstudygroup.com/1-explore/1.5-iamrole/) |
| **Session 3** | **[Lesson 6] Deploy network with Amazon VPC**<br>• Design Public/Private Subnets, Internet Gateway & Security Groups. | ⏳ Pending | [Amazon VPC](https://cloudjourney.awsstudygroup.com/1-explore/1.6-vpc/) |
| **Session 4** | **[Lesson 7 & 8] Amazon EC2 & AWS CLI**<br>• Launch EC2 Linux Server, SSH connection & manage via AWS CLI. | ⏳ Pending | [Amazon EC2](https://cloudjourney.awsstudygroup.com/1-explore/1.7-ec2/) |
| **Session 5** | **[Lesson 10] Hosting static website with Amazon S3**<br>• Create S3 Bucket, configure Public Bucket Policy & Deploy static HTML/CSS site. | ⏳ Pending | [Amazon S3](https://cloudjourney.awsstudygroup.com/1-explore/1.10-s3staticweb/) |

---

### 🏆 Session 1 Key Achievements:

#### 1. Cost Management (AWS Budgets):
* Successfully configured **AWS Budgets** with an alert threshold of **$1.00 USD**.
* Mastered Free Tier limits (750h EC2/RDS, 5GB S3, 1M Lambda requests/month).
* Enforced strict security practices: **never commit Access Keys / Secret Keys to GitHub**.

#### 2. Identity & Access Management (AWS IAM):
* Successfully created `Developers-Group` and user `dev-khang`.
* Assigned group permissions and tested IAM access policies.
* Understood Least Privilege principle, avoiding Root Account usage for daily operations.
