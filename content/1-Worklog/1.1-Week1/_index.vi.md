---
title: "Worklog Tuần 1"
date: 2026-10-06
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### 🎯 Mục tiêu tuần 1:
* Hoàn thành các bài học nền tảng trong **Section 1 - Explore AWS Services**.
* Cấu hình an toàn tài khoản **AWS Budgets** chống phát sinh chi phí ngoài ý muốn.
* Thực hành quản lý danh tính **AWS IAM**: Tạo IAM Users, IAM Groups và phân quyền chuẩn DevSecOps.

---

### 📋 Tiến độ công việc tuần 1:

| Buổi | Bài học & Nội dung thực hành chi tiết | Trạng thái | Nguồn tài liệu |
| :--- | :--- | :---: | :--- |
| **Buổi 1** | **[Bài 2] Manage usage costs with AWS Budgets**<br>• Tìm hiểu cơ chế tính phí AWS Free Tier.<br>• Cấu hình AWS Budgets gửi cảnh báo tự động về Email khi chi phí vượt quá $1.00 USD.<br>• Nắm rõ các quy tắc an toàn bảo mật tài khoản. | <span style="color:green; font-weight:bold;">[ĐÃ HOÀN THÀNH]</span> | [AWS Budgets](https://cloudjourney.awsstudygroup.com/1-explore/1.2-budgets/) |
| **Buổi 1** | **[Bài 4] Access Management with AWS IAM**<br>• Tìm hiểu khái niệm IAM User, IAM Group & Policy.<br>• Thực hành tạo nhóm `Developers-Group`, tạo user `dev-khang` và gán vào nhóm.<br>• Kiểm tra phân quyền truy cập danh tính chuẩn DevSecOps. | <span style="color:green; font-weight:bold;">[ĐÃ HOÀN THÀNH]</span> | [AWS IAM](https://cloudjourney.awsstudygroup.com/1-explore/1.4-iam/) |
| **Buổi 2** | **[Bài 5] Grant permissions through IAM Role**<br>• Tìm hiểu cơ chế mượn mũ IAM Role & Token tạm thời tự hủy (`sts assume-role`).<br>• Thực hành tạo `S3-Admin-Role` & `AdminGroup`. | <span style="color:orange; font-weight:bold;">[BÀI HỌC TIẾP THEO]</span> | [IAM Role](https://cloudjourney.awsstudygroup.com/1-explore/1.5-iamrole/) |
| **Buổi 3** | **[Bài 6] Deploy network with Amazon VPC**<br>• Thiết kế Public/Private Subnet, Internet Gateway & Security Groups. | ⏳ Chờ thực hành | [Amazon VPC](https://cloudjourney.awsstudygroup.com/1-explore/1.6-vpc/) |
| **Buổi 4** | **[Bài 7 & 8] Amazon EC2 & AWS CLI**<br>• Khởi chạy EC2 Linux Server, kết nối SSH & quản lý qua AWS CLI. | ⏳ Chờ thực hành | [Amazon EC2](https://cloudjourney.awsstudygroup.com/1-explore/1.7-ec2/) |
| **Buổi 5** | **[Bài 10] Hosting static website with Amazon S3**<br>• Khởi tạo S3 Bucket, cấu hình Public Bucket Policy & Deploy web tĩnh HTML/CSS. | ⏳ Chờ thực hành | [Amazon S3](https://cloudjourney.awsstudygroup.com/1-explore/1.10-s3staticweb/) |

---

### 🏆 Kết quả đạt được trong Buổi 1:

#### 1. Quản lý Chi phí (AWS Budgets):
* Đã cấu hình thành công **AWS Budgets** với hạn mức cảnh báo **$1.00 USD**.
* Nắm rõ danh mục tài nguyên Free Tier (750h EC2/RDS, 5GB S3, 1M Lambda requests/tháng).
* Nắm rõ nguyên tắc tuyệt đối **không commit Access Key / Secret Key lên GitHub**.

#### 2. Quản lý Danh tính & Phân quyền (AWS IAM):
* Đã khởi tạo thành công nhóm người dùng `Developers-Group` và user `dev-khang`.
* Gán quyền thành công và kiểm tra truy cập tài khoản IAM.
* Hiểu nguyên lý phân quyền tối thiểu (Least Privilege), không sử dụng tài khoản Root cho công việc hàng ngày.
