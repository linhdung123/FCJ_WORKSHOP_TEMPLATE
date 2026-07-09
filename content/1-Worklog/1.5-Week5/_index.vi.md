---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Tìm hiểu các dịch vụ bảo mật và quản lý danh tính trên AWS.
* Nâng cao kỹ năng quản lý quyền truy cập và bảo vệ tài nguyên AWS.
* Thực hành mã hóa dữ liệu và giám sát bảo mật trong môi trường AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Tìm hiểu các dịch vụ bảo mật của AWS.<br>&emsp;+ AWS Shared Responsibility Model.<br>&emsp;+ Identity & Access Management.<br>&emsp;+ Data Protection. | 18/05/2026 | 18/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Thực hành lab **AWS Identity and Access Management (IAM)**.<br>&emsp;+ IAM Policies.<br>&emsp;+ IAM Roles.<br>&emsp;+ IAM Conditions.<br>&emsp;+ IAM cho ứng dụng. | 19/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Thực hành quản lý quyền truy cập bằng **AWS Tags**.<br>&emsp;+ Gắn Tag cho Amazon EC2.<br>&emsp;+ Kiểm soát quyền truy cập dựa trên Tags (ABAC). | 20/05/2026 | 20/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Thực hành **AWS Security Hub**.<br>&emsp;+ Tìm hiểu **AWS IAM Identity Center**.<br>&emsp;+ Quản lý danh tính và truy cập tập trung. | 21/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - Thực hành mã hóa dữ liệu bằng **AWS Key Management Service (AWS KMS)**.<br>&emsp;+ Encrypt at Rest.<br>&emsp;+ Customer Managed Keys (CMKs). | 22/05/2026 | 22/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - Tham dự sự kiện Community Day của FCJ. | 23/05/2026 | 23/05/2026 | |

### Kết quả đạt được tuần 5:

* Hiểu được mô hình **AWS Shared Responsibility Model** và vai trò của các dịch vụ bảo mật trong việc bảo vệ hạ tầng và dữ liệu trên AWS.

* Thành thạo hơn trong việc sử dụng **AWS Identity and Access Management (IAM)**:
  * Tạo và quản lý IAM Users, Groups và Roles.
  * Xây dựng IAM Policies theo nguyên tắc **Least Privilege**.
  * Sử dụng **IAM Conditions** để giới hạn quyền truy cập theo điều kiện cụ thể.
  * Cấu hình IAM Roles cho ứng dụng nhằm truy cập tài nguyên AWS một cách an toàn mà không cần sử dụng Access Keys.

* Hiểu và áp dụng **AWS Tags** để:
  * Phân loại tài nguyên AWS.
  * Quản lý tài nguyên hiệu quả.
  * Kiểm soát quyền truy cập dựa trên thuộc tính (**Attribute-Based Access Control - ABAC**).

* Thực hành với **AWS Security Hub**, hiểu cách:
  * Tổng hợp các phát hiện bảo mật từ nhiều dịch vụ AWS.
  * Giám sát trạng thái bảo mật của tài khoản AWS.
  * Phát hiện các cấu hình chưa đáp ứng các tiêu chuẩn bảo mật.

* Làm quen với **AWS IAM Identity Center**, hiểu cách quản lý danh tính tập trung và triển khai cơ chế **Single Sign-On (SSO)** cho nhiều tài khoản AWS.

* Thực hành **Encrypt at Rest** bằng **AWS Key Management Service (AWS KMS)**:
  * Tạo và quản lý khóa mã hóa.
  * Hiểu cơ chế mã hóa dữ liệu khi lưu trữ.
  * Áp dụng AWS KMS để tăng cường bảo mật dữ liệu trên các dịch vụ AWS.

### Mục tiêu tuần sau:

* Tìm hiểu các dịch vụ cơ sở dữ liệu trên AWS.
* Thực hành với Amazon RDS, Amazon DynamoDB và các giải pháp quản lý cơ sở dữ liệu trên nền tảng AWS.