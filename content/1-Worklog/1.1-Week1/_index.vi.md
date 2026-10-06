---
title: "Worklog Tuần 1"
date: 2026-10-06
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:

* Hiểu các dịch vụ AWS cơ bản, cách sử dụng AWS Console, AWS CLI & Docker Floci local.
* Cấu hình an toàn ngân sách tài khoản **AWS Budgets** chống phát sinh chi phí ngoài ý muốn.
* Thực hành quản lý danh tính **AWS IAM**: Tạo IAM Users, IAM Groups và phân quyền theo tiêu chuẩn DevSecOps.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Làm quen với chương trình FCAJ Buildrathon 2026 <br> - Đọc và lưu ý các quy định thực tập và tiêu chí đánh giá mộc thực tập (&ge;7.0/10) | 06/10/2026 | 06/10/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Tìm hiểu tổng quan AWS & các nhóm dịch vụ cốt lõi: <br>&emsp; + Compute (EC2) <br>&emsp; + Storage (S3, EBS) <br>&emsp; + Networking (VPC) <br>&emsp; + Database (RDS, DynamoDB) <br>&emsp; + Security & IAM | 06/10/2026 | 06/10/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Cấu hình môi trường thực hành Local (Docker Floci) & AWS CLI <br> - **Thực hành Ngày 1 (Bài 2 & Bài 4):** <br>&emsp; + [Bài 2] Cấu hình **AWS Budgets** cảnh báo tự động $1.00 USD <br>&emsp; + [Bài 4] Cấu hình **AWS IAM**: Tạo `Developers-Group`, tạo user `dev-khang` và gán vào nhóm | 06/10/2026 | 06/10/2026 | <https://cloudjourney.awsstudygroup.com/1-explore/> |
| 5 | - **Thực hành Ngày 2 (Bài 5 & Bài 6 - Kế hoạch):** <br>&emsp; + [Bài 5] Phân quyền IAM Role & `sts assume-role` <br>&emsp; + [Bài 6] Thiết kế hạ tầng mạng Amazon VPC cơ bản | 07/10/2026 | | <https://cloudjourney.awsstudygroup.com/1-explore/> |
| 6 | - **Thực hành Ngày 3 (Bài 7, 8 & 10 - Kế hoạch):** <br>&emsp; + [Bài 7 & 8] Khởi tạo máy chủ EC2 Linux & thao tác CLI <br>&emsp; + [Bài 10] Deploy Static Website với Amazon S3 | 08/10/2026 | | <https://cloudjourney.awsstudygroup.com/1-explore/> |


### Kết quả đạt được tuần 1:

* Hiểu tổng quan AWS là gì và nắm vững các nhóm dịch vụ cốt lõi cho Kỹ sư DevSecOps:
  * Compute (EC2)
  * Storage (S3, EBS)
  * Networking (VPC)
  * Database (RDS, DynamoDB)
  * Security & IAM

* Cấu hình thành công AWS Budgets mức cảnh báo $1.00 USD gửi email tự động khi phát sinh chi phí.

* Thực hành thành công bài Lab 1 (IAM Users & Groups):
  * Tạo thành công nhóm `Developers-Group`
  * Tạo user `dev-khang` và gán vào nhóm phân quyền
  * Nắm vững nguyên tắc phân quyền tối thiểu (Least Privilege), không dùng tài khoản Root hàng ngày.

* Thiết lập thành công môi trường thực hành Local an toàn với Docker Floci (`localhost:4566`) và kết nối AWS CLI thành thạo.
