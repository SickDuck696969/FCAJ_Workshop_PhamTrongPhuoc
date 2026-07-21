---
title: "Event 4"
date: 2026-06-20
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

# Bài thu hoạch sự kiện "FCAJ Community Day - Tháng 62026"

| Thông tin | Chi tiết |
|------|---------|
| Ngày | 27/06/2026 |
| Địa điểm | Tầng 36 Tòa nhà Bitexco, 02 Hải Triều, Phường Bến Nghé, Quận 1, TP Hồ Chí Minh |
| Vai trò | Người tham dự |

### Mục Đích Của Sự Kiện
- Tích hợp AI vào vận hành hệ thống.
- Tối ưu hóa hạ tầng đám mây.
- Bảo mật dữ liệu ở quy mô doanh nghiệp.

### Danh Sách Diễn Giả
- **Mr.  Steve Trần** (Cloud Thinker) - Vận hành Hạ tầng Đám mây và Kỷ nguyên Agentic Platform.
- **Mr. Hiếu Nghị, Mr. Kiệt, Mr. Trung** - Xây dựng Trợ lý AI Giọng nói cho Doanh nghiệp.
- **Ms. Bảo & Mr. Nguyên Nguyễn** (Cloud Kinetics) - Triển khai DevOps AI Agent trên AWS.
- **Mr. Trường & Ms. Minh Anh** (Noventic) - Tự động hóa Quy trình Nhân sự với Amazon Q.
- **Mr. Toàn Nguyễn & Mr. Hiếu Nghị** (Renova Cloud) - Mô hình Bảo mật Private cho Amazon Q và MCP Server.

### Nội Dung Nổi Bật

#### 1. Vận hành Hạ tầng Đám mây và Kỷ nguyên Agentic Platform
- **Agentic Platform giải quyết 4 vấn đề cốt lõi:** Điều tra sự cố, Đánh giá Code (Code Reviews), FinOps, và Bảo mật (Security).
- **Single Agent vs Multi-Agent:**
  - Single Agent có thể xử lý mượt mà hơn 95% các tác vụ khi được thiết kế tốt.
  - Multi-Agent tối ưu hóa dung lượng ngữ cảnh và phân quyền bằng cách phân rã tác vụ cho các Agent chuyên biệt.
- Giúp các kỹ sư Senior giải quyết sự cố nhanh hơn, giảm thiểu thời gian gián đoạn hệ thống.

#### 2. Từng bước Xây dựng Trợ lý AI Giọng nói cho Doanh nghiệp
- **STT + LLM + TTS:** Là giải pháp tối ưu cho tiếng Việt, trong đó Speech-to-Text chuyển giọng nói thành văn bản, LLM xử lý ngữ cảnh và Text-to-Speech phản hồi.
- **Ưu điểm cho doanh nghiệp:** Định dạng văn bản trung gian giúp kiểm soát nội dung (Guardrails) giảm thiểu sai lệch, và hệ thống có thể tự động gọi API (Tool calling) theo thời gian thực.
- **Thách thức trên Production:** Sử dụng Streaming để giảm độ trễ, bổ sung dữ liệu giọng nói vùng miền, nhận diện giới tính, xử lý ngắt lời ngẫu nhiên và tự động chuyển cuộc gọi cho nhân viên khi cần.

#### 3. Triển khai DevOps AI Agent trên AWS
- **Tự động hóa điều tra sự cố:** Giải pháp DevOps AI Agent tự động hóa quá trình điều tra ngay khi nhận được cảnh báo lỗi (ví dụ: CloudWatch).
- **6 trụ cột của hệ thống:** Context Learning (lập bản đồ Topology), Control (phân quyền), Integration (mở rộng qua MCP), Collaboration (Slack, Jira), Convenient (kích hoạt trên Console), và Cost Effective (trả phí theo giây).
- **Quy trình xử lý:** Phân loại lỗi, điều tra RCA, đề xuất khắc phục nhanh và đề xuất cải tiến dài hạn. (Agent chỉ đề xuất chứ không can thiệp trực tiếp).

#### 4. Tự động hóa Quy trình Nhân sự với Amazon Q
- **Tuyển dụng tự động:** Amazon Q hoạt động như một nền tảng trợ lý nội bộ bảo mật, khắc phục rủi ro rò rỉ dữ liệu khi dùng AI công cộng.
- **Khả năng tích hợp:** Kết nối qua MCP với Google/Microsoft Workspace, Jira, Salesforce, GitHub.
- **Quy trình:** Tạo trợ lý đánh giá chuyên biệt từ file hướng dẫn, tự động quét CV (cả OCR), phân loại ứng viên theo mức độ phù hợp và xuất báo cáo/gợi ý lương qua no-code app.

#### 5. Mô hình Bảo mật Private cho Amazon Q và MCP Server
- **Bảo mật Zero Trust:** Ngăn chặn rủi ro DDoS và tấn công trung gian (Man-in-the-middle) khi AI tương tác với MCP Server nội bộ.
- **Giải pháp kiến trúc:**
  - Cách ly MCP Server trong Private Subnet của VPC.
  - Amazon Q dùng Interface Endpoint qua VPC Connection.
  - Mã hóa lưu lượng TLS qua ALB nội bộ, dùng ACM và Cognito để xác thực.
  - Dùng Route 53 Resolver ẩn giấu DNS nội bộ khỏi internet bên ngoài.

### Ứng Dụng Vào Công Việc
- **Hiểu đúng về vai trò của AI:** Xem AI là một công cụ hỗ trợ và khuếch đại sức mạnh, không hoàn toàn thay thế vai trò của con người trong các công việc kỹ thuật.
- **Triển khai AI an toàn:** Đảm bảo thực hiện Quản trị Dữ liệu (Data Governance), thiết lập Guardrails và kiến trúc Bảo mật Private trước khi đưa AI lên Production.
- **Tối ưu Vận hành:** Áp dụng tư duy Agentic Platform và Multi-Agent vào các quy trình giám sát hệ thống để điều tra sự cố và tối ưu chi phí.

![Ảnh sự kiện](/images/4-EventParticipated/4.4-event4/evt41.jpg)

![Ảnh sự kiện](/images/4-EventParticipated/4.4-event4/evt42.jpg)