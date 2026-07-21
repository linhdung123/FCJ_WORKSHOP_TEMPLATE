---
title: "Event 4"
date: 2026-06-27
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---


# Bài thu hoạch “FCAJ Community Day”

### Mục Đích Của Sự Kiện
- Hành trình sự nghiệp IT, sự tác động của AI đến công việc kỹ sư và các giải pháp vận hành hệ thống đám mây (Cloud Infrastructure) của Cloud Thinker.
- Xây dựng Voice AI (Trợ lý AI bằng giọng nói), ứng dụng thực tiễn và cách xử lý giọng nói tiếng Việt.
- Giới thiệu giải pháp AWS DevOps Agent giúp tự động hóa quá trình xử lý sự cố hệ thống.
- Giải quyết các bài toán của ngành Nhân sự (HR) bằng công cụ trí tuệ nhân tạo Amazon Qick.
- Cách thiết lập kết nối bảo mật nội bộ giữa Amazon Qick và các hệ thống bên thứ ba thông qua MCP Server.
### Danh Sách Diễn Giả
- **Steve Tran** - Founder của Cloud Thinker
- **Hieu Nghi** - AI Renova Cloud
- **Kiet Tran** - AI Engineer AWS Student Builder Group
- **Trung Vu** - CEO Revve AI
- **Bao Phan và Nguyen Nguyen** - Cloud Engineers từ Cloud Kinetic
- **Truong Tran và Anh Dang** - Solution Architect-Cloud Kinetics
- **Toan Nguyen và Hieu Nghi** - Senior Business Systems Analyst-VPBank

### Nội Dung Nổi Bật

### Thị trường việc làm IT
- AI đang làm thay đổi tốc độ viết mã nguồn, khiến nhu cầu tuyển dụng lập trình viên ở các công ty thay đổi, tuy nhiên các kỹ sư vận hành hạ tầng (Cloud Engineering) thật sự giỏi để xử lý sự cố hệ thống lớn vẫn rất được săn đón.
### Kiến trúc AI Agent
- Đánh giá sự khác biệt giữa Single Agent và Multi-Agent, trong đó kiến trúc Multi-Agent (với các agent chuyên biệt) giúp giới hạn phạm vi ngữ cảnh (context window), kiểm soát quyền truy cập (Role-Based Access Control) và tối ưu hóa chi phí tốt hơn.
### Cấu trúc Voice AI
- Hệ thống Voice AI thường trải qua quá trình chuyển âm thanh thành văn bản (Speech-to-Text), đưa qua mô hình ngôn ngữ lớn (LLM) để xử lý logic, và chuyển đổi văn bản đó thành giọng nói phản hồi (Text-to-Speech).
### Xử lý ngôn ngữ ít tài nguyên Tiếng Việt
- Vì tiếng Việt thiếu hụt dữ liệu để huấn luyện các mô hình biến đổi giọng nói trực tiếp (Speech-to-Speech), phương pháp kết hợp LLM với văn bản giúp xử lý ngữ cảnh tiếng Việt tốt hơn và quản lý chính xác việc gọi công cụ (tool calling) như khóa thẻ ngân hàng.
### Trải nghiệm hội thoại tự nhiên
- Để trợ lý AI giao tiếp tự nhiên giống con người, hệ thống cần được huấn luyện để phân biệt giới tính người dùng (gọi "anh/chị" chính xác), biết lúc nào nên ngắt lời khi người dùng ngừng nói, và nhận diện một phần giọng vùng miền.
### Quy trình xử lý sự cố tự động
- Agent sẽ phân loại lỗi, điều tra nguyên nhân gốc rễ bằng cách đưa ra giả thuyết, đề xuất giải pháp xử lý (Mitigation Plan) và gợi ý cải thiện hệ thống trong tương lai. Ví dụ qua demo: Agent tự động nhận diện hệ thống bị quá tải do tấn công DDoS và sinh ra lệnh terminal chặn các tác vụ gây lỗi.
### Thách thức của bộ phận HR
- HR đối mặt với khó khăn khi lọc CV thủ công dễ làm bỏ lỡ người tài, đánh giá ứng viên dựa vào cảm tính, và nguy cơ rò rỉ dữ liệu khi đẩy thông tin ứng viên lên các AI công cộng.
### Ứng dụng thực tiễn trong tuyển dụng
- Amazon Q giúp tự động hóa quy trình phân tích CV, trích xuất điểm mạnh/yếu của ứng viên, tự động thiết lập thang điểm đối chiếu với JD (Job Description), qua đó giúp tăng tốc độ tuyển dụng và giảm tải các tác vụ thủ công.
### Yêu cầu bảo mật của doanh nghiệp
- Để Amazon Q tương tác với các ứng dụng bên thứ ba (như Jira, WhatsApp, Zalo), cần đi qua MCP Server, nhưng các doanh nghiệp yêu cầu dữ liệu không được đi qua Internet công cộng.

### Những Gì Học Được
- Nếu có ý tưởng hãy bắt tay vào làm ngay lập tức không để ngâm lâu.
- Nên ra đời trải nghiệm từ sớm để có kinh nghiệm.
- Lựa chọn kiến trúc linh hoạt cho ngôn ngữ ít tài nguyên: Tiếng Việt là ngôn ngữ thiếu hụt dữ liệu huấn luyện. Do đó, thay vì dùng mô hình biến đổi giọng nói trực tiếp (Speech-to-Speech) vốn gặp nhiều hạn chế, bài học rút ra là nên dùng kiến trúc 3 bước: chuyển âm thanh thành văn bản (STT), đưa qua LLM xử lý logic, và chuyển văn bản thành giọng nói (TTS).
- Con người là quyết định cuối cùng, công cụ AI khuếch đại kỹ năng của kỹ sư chứ không thay thế họ.
### Bài học rút ra
- **Bảo vệ luồng giao tiếp AI**: Khi kết nối AI nội bộ (như Amazon Q) với các ứng dụng của bên thứ ba qua máy chủ MCP, bài học xương máu là không được sử dụng kết nối mạng Internet công cộng (public). Phải đặt các hệ thống này trong mạng riêng tư (Private Subnet) và định tuyến thông qua kết nối VPC để ngăn chặn các rủi ro bị tấn công DDoS hoặc tấn công nghe lén (Man-in-the-middle)

#### Một số hình ảnh khi tham gia sự kiện
* Thêm các hình ảnh của các bạn tại đây
![overview] (/FCJ_WORKSHOP_TEMPLATE/images/4-EventParticipadted/4.4-Event4/image.png)
![overview] (/FCJ_WORKSHOP_TEMPLATE/images/4-EventParticipadted/4.4-Event4/image1.png)
> Tổng thể, sự kiện không chỉ cung cấp kiến thức kỹ thuật mà còn giúp tôi thay đổi cách tư duy về thiết kế ứng dụng, hiện đại hóa hệ thống và phối hợp hiệu quả hơn giữa các team.
