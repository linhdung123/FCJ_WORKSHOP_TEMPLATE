---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Tìm hiểu các dịch vụ lưu trữ và sao lưu dữ liệu trên AWS.
* Thực hành triển khai các dịch vụ Storage và Backup thông qua các bài lab.
* Hiểu cách bảo vệ dữ liệu, phục hồi sau sự cố và lựa chọn giải pháp lưu trữ phù hợp với từng nhu cầu.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | --------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Tìm hiểu Amazon S3 <br> - Tìm hiểu AWS Storage Gateway <br> - Tìm hiểu AWS Backup                 | 11/05/2026   | 11/05/2026      | https://cloudjourney.awsstudygroup.com/ |
| 3   | - **Thực hành:** <br> + Tạo S3 Bucket <br> + Upload/Download Object <br> + Quản lý Bucket và Object | 12/05/2026   | 12/05/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - **Thực hành:** <br> + AWS Backup <br> + AWS Import/Export <br> + Quản lý và khôi phục dữ liệu     | 13/05/2026   | 13/05/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - **Thực hành:** <br> + AWS Storage Gateway <br> + Kết nối hệ thống On-premises với AWS Storage     | 14/05/2026   | 14/05/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - **Thực hành:** <br> + Amazon FSx <br> + Tạo và quản lý File System                                | 15/05/2026   | 15/05/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 4:

* Hiểu được vai trò của các dịch vụ lưu trữ trên AWS và biết cách lựa chọn dịch vụ phù hợp với từng nhu cầu sử dụng.

* Nắm được cách sử dụng **Amazon S3** để:

  * Tạo Bucket và quản lý Object.
  * Phân quyền truy cập thông qua Bucket Policy và IAM.
  * Hiểu các Storage Class và trường hợp sử dụng của từng loại.

* Thực hành **AWS Backup**, bao gồm:

  * Tạo Backup Vault.
  * Xây dựng Backup Plan.
  * Tạo và quản lý Recovery Point.
  * Khôi phục dữ liệu từ bản sao lưu khi cần.

* Tìm hiểu **AWS Import/Export** và các phương án di chuyển dữ liệu lớn lên AWS, giúp giảm thời gian truyền tải đối với khối lượng dữ liệu lớn.

* Thực hành **AWS Storage Gateway**:

  * Hiểu mô hình Hybrid Cloud.
  * Kết nối hệ thống lưu trữ tại chỗ với AWS.
  * Phân biệt File Gateway, Volume Gateway và Tape Gateway cùng các trường hợp sử dụng.

* Thực hành **Amazon FSx**:

  * Tạo File System.
  * Hiểu các lựa chọn triển khai như Windows File Server và Lustre.
  * Biết cách cung cấp hệ thống lưu trữ hiệu năng cao cho ứng dụng.

* Hiểu được các khái niệm về:

  * Sao lưu (Backup).
  * Phục hồi sau sự cố (Disaster Recovery).
  * Khả năng sẵn sàng và độ bền của dữ liệu (Availability & Durability).
  * Quản lý vòng đời dữ liệu và tối ưu chi phí lưu trữ.

### Kiến thức học được:

* Hiểu nguyên lý hoạt động của Amazon S3 và mô hình lưu trữ Object Storage.
* Biết cách lựa chọn Storage Class để tối ưu chi phí và hiệu năng.
* Hiểu quy trình sao lưu và khôi phục dữ liệu bằng AWS Backup.
* Nắm được mô hình Hybrid Storage với AWS Storage Gateway.
* Hiểu các giải pháp File Storage trên AWS thông qua Amazon FSx.
* Biết các phương án di chuyển dữ liệu từ hệ thống On-premises lên AWS.
* Nhận thức được tầm quan trọng của chiến lược Backup và Disaster Recovery trong việc đảm bảo tính liên tục của hệ thống.

### Khó khăn gặp phải:

* Gặp khó khăn trong quá trình cấu hình đường kết nối giữa EC2 và AWS Storage Gateway do yêu cầu về VPC, Route Table và Security Group.
* Mất thời gian để kiểm tra các thiết lập mạng nhằm đảm bảo EC2 có thể giao tiếp với Storage Gateway đúng cách.

### Mục tiêu tuần tiếp theo:

* Tìm hiểu **AWS Shared Responsibility Model**.
* Hiểu rõ trách nhiệm giữa AWS và khách hàng trong việc bảo mật hạ tầng Cloud.
* Thực hành các nội dung liên quan đến Identity & Access Management (IAM) và Security Best Practices.
