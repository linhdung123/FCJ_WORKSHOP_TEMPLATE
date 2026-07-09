---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7

* Tìm hiểu AWS Database Migration Service (AWS DMS) và AWS Schema Conversion Tool (AWS SCT).
* Thực hành di chuyển cơ sở dữ liệu và tìm hiểu kiến trúc Data Lake trên AWS.
* Kiểm tra và tối ưu tài nguyên AWS để tránh phát sinh chi phí không cần thiết.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Xem hướng dẫn Lab 000043 (tài liệu gặp lỗi nên không thể truy cập) | 01/06/2026 | 01/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - **Thực hành:** <br>&emsp;+ Di chuyển dữ liệu bằng AWS DMS và AWS SCT | 02/06/2026 | 02/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Học và thực hành Data Lake on AWS | 03/06/2026 | 03/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Kiểm tra AWS Billing <br>&emsp;+ Xóa Snapshot không sử dụng <br>&emsp;+ Giải phóng Elastic IP chưa sử dụng <br>&emsp;+ Kiểm tra tài nguyên Amazon EC2 | 04/06/2026 | 04/06/2026 | AWS Management Console |
| 6 | Nghỉ | 05/06/2026 | 05/06/2026 | |

### Kết quả đạt được tuần 7

* Hoàn thành bài lab về AWS DMS và AWS SCT.
* Hiểu quy trình di chuyển cơ sở dữ liệu lên AWS.
* Làm quen với kiến trúc Data Lake trên AWS.
* Kiểm tra và dọn dẹp các tài nguyên không sử dụng nhằm tránh phát sinh chi phí.

### Kiến thức học được

* Học cách theo dõi **AWS DMS Migration Tasks** và giám sát quá trình di chuyển dữ liệu.
* Tìm hiểu cách xử lý các lỗi thường gặp trong AWS DMS và quy trình **Environment Cleanup**.
* Hiểu mục đích của AWS DMS trong việc di chuyển cơ sở dữ liệu với thời gian gián đoạn tối thiểu.
* Biết cách cấu hình **Source Endpoint**, **Target Endpoint** và **Replication Instance**.
* Hiểu các chế độ **Full Load**, **Change Data Capture (CDC)** và **Full Load + CDC**.
* Tìm hiểu kiến trúc cơ bản của **Data Lake on AWS** và vai trò của Amazon S3 trong lưu trữ dữ liệu.

### Khó khăn gặp phải

* Gặp lỗi tài liệu Lab 000043 nên mất thời gian tìm nguồn tham khảo khác.
* Gặp khó khăn khi cấu hình Source Endpoint, Target Endpoint và Replication Instance.
* Mất thời gian xử lý lỗi Migration Task và kiểm tra kết nối giữa các cơ sở dữ liệu.
* Phát sinh chi phí AWS do còn tồn tại Amazon EC2 Snapshot và Elastic IP chưa được giải phóng, cần rà soát và dọn dẹp tài nguyên.

### Mục tiêu tuần tiếp theo

* Theo dõi AWS Billing để đảm bảo không phát sinh chi phí ngoài mong muốn.
* Viết blog tổng kết các kiến thức đã học và các bài lab đã thực hiện.