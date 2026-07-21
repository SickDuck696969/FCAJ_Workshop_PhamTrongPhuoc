---
title: "Event 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch sự kiện "FCAJ Community Day"

| Thông tin | Chi tiết |
|------|---------|
| Ngày | 09/05/2026 |
| Địa điểm | Tầng 26 Tòa nhà Bitexco, 02 Hải Triều, Phường Bến Nghé, Quận 1, TP Hồ Chí Minh |
| Vai trò | Người tham dự |

### Mục Đích Của Sự Kiện
- Chia sẻ các kỹ thuật tâm lý giúp tạo động lực học tập và duy trì thói quen bền vững.
- Cung cấp kiến thức chuyên sâu về Prompt Engineering để tối ưu hóa output của LLM.
- Giới thiệu các System Architecture thực tế ứng dụng AWS Serverless.
- Định hướng tư duy nghề nghiệp, nhấn mạnh tầm quan trọng của Foundation và Mindset cho sinh viên IT.
- Trình bày phương pháp BMAD giúp tích hợp hiệu quả AI Agent vào quy trình SDLC.

### Danh Sách Diễn Giả
- **Mr. Huỳnh Hoàng Long** - Chia sẻ về cơ chế điều hướng Dopamine và Gamification trong học tập.
- **Mr. Thịnh Nguyễn** - Trình bày chuyên đề Prompt Engineering và kiến trúc hạ tầng AWS Cloud.
- **Mr. Khang** - Solutions Architect tại Cloud Kinetics.
- **Ms. Thảo** - Software Developer tại VIB.

### Nội Dung Nổi Bật

#### 1. Quản trị động lực học tập qua cơ chế tâm lý
- **Cơ chế Dopamine:** Dopamine được giải phóng khi kỳ vọng một phần thưởng chứ không chỉ khi nhận được nó. Việc đưa yếu tố bất ngờ vào quá trình học sẽ kích thích sự tập trung.
- **Gamification:** Áp dụng các cơ chế trò chơi như duy trì streak (chuỗi ngày học liên tục) và tận dụng tâm lý sợ mất mát (fear of loss) để hình thành kỷ luật.
- **Task Chunking:** Chia nhỏ khối lượng kiến thức đồ sộ (ví dụ: học một dịch vụ AWS mỗi ngày) để giảm thiểu rào cản tâm lý.
- **Quy tắc 2 phút (2-Minute Rule):** Xử lý ngay lập tức các task tốn ít hơn hai phút để tránh tình trạng trì hoãn.

#### 2. Tối ưu hóa Prompt Engineering và AWS Serverless Architecture
- **Cấu trúc Prompt chuẩn:** Một prompt chất lượng cần định nghĩa rõ Role, Task, Context, Input, Output format và Examples. Cần tránh các chỉ thị phủ định để giảm thiểu rủi ro Hallucination của LLM.
- **Kỹ thuật nâng cao:** Sử dụng các phương pháp luận như Chain of Thought và Tree of Thoughts để dẫn dắt LLM xử lý các logic phức tạp.
- **Serverless Ecosystem:** Trình bày mô hình ứng dụng AI có khả năng mở rộng cao, sử dụng:
  - **Frontend & CDN:** Amazon S3 và Amazon CloudFront.
  - **Authentication:** Amazon Cognito.
  - **Backend Compute:** Amazon API Gateway và AWS Lambda.
  - **AI & Data Storage:** Amazon Bedrock để tích hợp Foundation Models, Amazon DynamoDB cho lưu trữ NoSQL và Amazon CloudWatch để monitoring hệ thống.

#### 3. Tư duy nghề nghiệp và Core Foundation
- **Foundation quan trọng hơn Tools:** AI hoạt động như một công cụ amplify (khuếch đại). Cần nắm vững Foundation và tuyệt đối không outsource quá trình critical thinking của bản thân cho AI.
- **Tư duy "Why":** Cần liên tục đặt câu hỏi về bản chất cốt lõi đằng sau các quyết định thiết kế hệ thống, thay vì chỉ tập trung vào việc hoàn thành task.
- **Integrity (Sự liêm chính):** Chủ động xử lý các edge cases và duy trì chất lượng kỹ thuật cao nhất, ngay cả khi không bị giám sát trực tiếp.
- **Tầm nhìn dài hạn:** Ưu tiên việc tích lũy Experience, mở rộng Network và thu nạp Knowledge thay vì chỉ chú trọng vào mức đãi ngộ tài chính trong giai đoạn đầu của sự nghiệp.

#### 4. Phương pháp BMAD ứng dụng trong SDLC
- **Hạn chế của Context Window:** Việc prompt liên tục thiếu cấu trúc sẽ làm quá tải Context Window, dẫn đến hiện tượng Hallucination và sinh ra các đoạn code không thể deploy.
- **Role-based AI Agents:** Phương pháp BMAD khắc phục điều này bằng cách chia nhỏ quy trình SDLC và gán cho các AI Agent chuyên biệt:
  - **PM Agent:** Khởi tạo tài liệu PRD (Product Requirements Document).
  - **Architect Agent:** Thiết kế System Architecture.
  - **BA Agent:** Phân rã requirement thành các Epics và Stories chi tiết.
  - **Developer & QA Agents:** Xử lý code và testing độc lập cho từng story.
- **Lợi ích hệ thống:** Việc cô lập các task giúp kiểm soát chặt chẽ output, giảm thiểu sự chồng chéo logic và đảm bảo mã nguồn đạt chuẩn production.

### Ứng Dụng Vào Công Việc
- **Tối ưu LLM Prompting:** Áp dụng chặt chẽ Chain of Thought và cấu trúc prompt tiêu chuẩn vào quá trình phát triển ứng dụng AI.
- **Triển khai Serverless:** Pilot các dự án sử dụng AWS Lambda, Amazon API Gateway và Amazon Bedrock để xây dựng backend tối ưu chi phí.
- **Củng cố Foundation:** Dành thời gian review lý thuyết cốt lõi về hạ tầng phần mềm, hạn chế phụ thuộc AI khi giải quyết các bài toán logic nền tảng.
- **Ứng dụng BMAD:** Thiết lập cấu trúc phân vai rõ ràng cho AI Agent trước khi tiến hành code generation nhằm đảm bảo tính toàn vẹn của dự án.

![Ảnh sự kiện](/images/4-EventParticipated/4.1-event1/evt1.jpg)