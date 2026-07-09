---
title: "Các bài blogs đã dịch"
date: 2026-07-09
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Tại đây là phần tổng hợp các bài blog đã tìm hiểu và dịch trong quá trình thực tập tại AWS. Các bài viết tập trung vào những công nghệ và dịch vụ mới trên nền tảng AWS, dưới đang là tóm tắt các bài blog đã dịch.

### [Blog 1 - Bảo Mật Đám Mây Với Amazon VPC Encryption Controls](3.1-Blog1/)

Blog giới thiệu **Amazon VPC Encryption Controls**, một tính năng bảo mật mới của AWS giúp doanh nghiệp giám sát và thực thi việc mã hóa dữ liệu khi truyền tải (*encryption in transit*) giữa các tài nguyên trong Amazon VPC. Nội dung trình bày cách sử dụng **Monitor Mode** để đánh giá trạng thái mã hóa của hệ thống trước khi chuyển sang **Enforce Mode** nhằm bắt buộc tất cả lưu lượng mạng phải được mã hóa. Bài viết cũng phân tích vai trò của **AWS Nitro System**, các dịch vụ được hỗ trợ, những trường hợp ngoại lệ và lợi ích của tính năng này trong việc tăng cường bảo mật, đơn giản hóa quá trình kiểm toán và đáp ứng các tiêu chuẩn tuân thủ như **HIPAA**, **PCI DSS** và **FedRAMP**.

### [Blog 2 - Web Search Trên Amazon Bedrock AgentCore](3.2-Blog2/)

Blog giới thiệu tính năng **Web Search trên Amazon Bedrock AgentCore**, cho phép AI Agent truy cập và tìm kiếm thông tin mới nhất trên Internet ngay trong môi trường AWS mà không làm dữ liệu truy vấn rời khỏi hạ tầng của khách hàng. Bài viết giải thích kiến trúc hoạt động của AgentCore, cách tích hợp khả năng tìm kiếm thông qua **Model Context Protocol (MCP)**, cũng như cơ chế kết hợp dữ liệu từ Internet và **Amazon Knowledge Graph** để tạo ra các câu trả lời có căn cứ và trích dẫn nguồn rõ ràng. Ngoài ra, blog còn phân tích những lợi ích về bảo mật, khả năng mở rộng, các trường hợp ứng dụng trong doanh nghiệp và những lưu ý khi triển khai AI Agent trên môi trường production.

### [Blog 3 - Bảo Vệ Dữ Liệu Trên AWS Với AWS Backup](3.3-Blog3/)

Blog giới thiệu **AWS Backup**, dịch vụ quản lý sao lưu tập trung của AWS giúp tự động hóa quá trình backup và khôi phục dữ liệu cho nhiều dịch vụ khác nhau trên nền tảng đám mây. Nội dung trình bày các thành phần quan trọng như **Backup Plan**, **Backup Vault**, khả năng sao lưu **Cross-Region** và **Cross-Account**, cùng những lợi ích trong việc giảm thiểu rủi ro mất dữ liệu và xây dựng chiến lược **Disaster Recovery** hiệu quả. Bài viết cũng chia sẻ các khuyến nghị khi triển khai AWS Backup nhằm tối ưu chi phí, đảm bảo khả năng khôi phục dữ liệu và đáp ứng các yêu cầu về bảo mật, kiểm toán cũng như tuân thủ trong môi trường doanh nghiệp.