---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch "FCAJ Community Day 23/05/2026"

| Thông tin | Chi tiết |
|------|---------|
| Ngày | 23/05/2026 |
| Địa điểm | Tầng 26 Tòa nhà Bitexco, 02 Hải Triều, Phường Bến Nghé, Quận 1, TP Hồ Chí Minh |
| Vai trò | Người tham dự |

### Mục Đích Của Sự Kiện
- Chia sẻ kiến thức thực tiễn về GenAIOps và tầm quan trọng của ngữ cảnh (context) khi xây dựng các ứng dụng Generative AI.
- Giải thích cách thức hoạt động cốt lõi của LLM và tính không tất định (non-determinism) của các thiết lập cấu hình trên môi trường production.
- Giới thiệu Amazon Quick Suite nhằm tự động hóa quy trình kinh doanh với các trợ lý AI.
- Trình bày các case study thực tế về thiết kế hệ thống Multi-Agent chuẩn doanh nghiệp và hành trình phát triển sản phẩm tại hackathon.
- Tìm hiểu về Amazon CloudFront như một nền tảng bảo mật và tối ưu hóa ứng dụng với chính sách giá dễ dự đoán.

### Danh Sách Diễn Giả
- **Mr. Tịnh Trương** (Platform Engineer, GoTymeX) - Context is Everything.
- **Mr. Đào Đức** (Solution Architect, Cloud Kinetics) - Cách LLM thực sự hoạt động.
- **Mr. Hải Anh** (G-AsiaPacific Vietnam) - Trợ lý AI thân thiện với Amazon Quick.
- **Team VIB** - Xây dựng UTMorpho từ ý tưởng đến thực tế.
- **Ms. Vy Lâm** (Senior Business Systems Analyst, VPBank) - Hệ thống Multi-Agent chuẩn Enterprise.
- **Mr. Nguyễn Tuấn Thịnh** (DevOps Engineer, First Cloud AI Journey) - CloudFront - Nền tảng từ Edge đến Origin.

### Nội Dung Nổi Bật

#### Context Là Tất Cả Trong GenAIOps
- Các mô hình AI rất mạnh mẽ, nhưng việc cung cấp ngữ cảnh yếu kém sẽ dẫn đến các câu trả lời chung chung, sai hướng hoặc dài dòng.
- Một ngữ cảnh tốt sẽ biến một yêu cầu mơ hồ thành một tác vụ có thể giải quyết được thông qua việc cung cấp mục tiêu, tình huống, ràng buộc và dẫn chứng cụ thể.
- Sự phát triển của AI đang hướng tới khái niệm "Second AI Brain" (Bộ não AI thứ hai) với quy trình tự động: Lưu trữ → Truy xuất → Tạo nội dung → Học hỏi.

#### Tính Không Tất Định Của LLM
- Ngay cả khi cài đặt Temperature bằng 0, đầu ra của LLM vẫn có thể biến thiên do sai số trong phép toán dấu phẩy động trên GPU và quá trình gom cụm suy luận (inference batching).
- Sự thiếu nhất quán này tạo ra rủi ro lớn cho các ứng dụng yêu cầu độ chính xác tuyệt đối như y tế hay phân tích tài chính.
- Giải pháp khắc phục bao gồm việc chạy truy vấn nhiều lần và áp dụng phương pháp bầu chọn đa số (majority voting).

#### Tự Động Hóa Với Amazon Quick Suite
- Hỗ trợ người dùng doanh nghiệp tự động hóa các tác vụ lặp đi lặp lại và thu thập thông tin từ nhiều nguồn dữ liệu khác nhau.
- Ứng dụng như một trợ lý quản lý dự án (PM assistant) có khả năng tự động tạo biên bản cuộc họp (MoM), gửi email cho các bên liên quan và lên lịch họp tiếp theo.

#### UTMorpho (LotusHacks 2026)
- Team VIB đã chia sẻ về 36 giờ tham gia LotusHacks để xây dựng UTMorpho — một trình tạo giao diện UI bằng AI cho phép người dùng chỉnh sửa trực tiếp trên canvas (chuẩn WYSIWYG).
- Hệ thống này giải quyết triệt để tình trạng AI tạo ra chi tiết dư thừa hoặc làm trôi ngữ cảnh bằng cách cho phép chỉnh sửa nhỏ, tiết kiệm token mà không cần phải viết lại toàn bộ prompt.

#### Hệ Thống Multi-Agent Chuẩn Doanh Nghiệp (Enterprise-Grade)
- Các mô hình chấm điểm tín dụng truyền thống thất bại khi áp dụng cho startup do đối tượng này thường thiếu dữ liệu lịch sử và tài sản thế chấp.
- Nếu chỉ sử dụng một AI Agent duy nhất để phân tích, hệ thống sẽ gặp phải giới hạn về ngưỡng ngữ cảnh, làm loãng chuyên môn và thiếu cơ chế kiểm tra chéo.
- Giải pháp là áp dụng kiến trúc Multi-Agent (Hội đồng tín dụng ảo) với các Agent chuyên biệt (Chuyên viên Tài chính, Phân tích Thị trường, Đánh giá Đội ngũ) để tối ưu hóa chuyên môn sâu, dễ dàng kiểm toán và tăng khả năng chịu lỗi.

#### CloudFront & Chính sách giá Flat-Rate
- Amazon CloudFront không chỉ đơn thuần là dịch vụ CDN, mà nó đóng vai trò là một nền tảng (Foundation) giúp bảo vệ và tối ưu hóa ứng dụng thông qua mạng lưới phân phối toàn cầu với hơn 700 điểm hiện diện (PoPs).
- Để giải quyết bài toán rủi ro tài chính khi khách hàng đối mặt với các hóa đơn tăng đột biến (bill spikes) do lượng truy cập bùng nổ hoặc bị tấn công DDoS, AWS đã cho ra mắt chính sách giá cố định (flat-rate pricing) vào tháng 11/2025.
- Gói cước flat-rate cung cấp chi phí dễ dự đoán hàng tháng bằng cách gộp chung CDN, WAF, chống DDoS, DNS (Route 53) và Storage credits (S3) vào một gói duy nhất, phù hợp với mọi quy mô từ website nhỏ đến doanh nghiệp lớn.
- Ngăn chặn các cuộc tấn công phân tán bằng cơ chế phòng thủ phân tán: CloudFront chặn lưu lượng độc hại ngay tại Edge (gần nguồn tấn công nhất) và dùng kỹ thuật gom request (request collapsing) để giảm tải và bảo vệ origin server an toàn.

### Ứng Dụng Vào Công Việc
- **Cải thiện Kỹ năng Prompting:** Chấm dứt thói quen đưa toàn bộ tài liệu không chọn lọc vào model; thay vào đó, cần xác định rõ các ràng buộc và định dạng đầu ra.
- **Quản lý giới hạn của LLM:** Hiểu và chấp nhận tính không tất định của LLM để từ đó thiết kế các phương án dự phòng an toàn (mitigation strategies) trên môi trường production.
- **Áp dụng Multi-Agent Architecture:** Dùng nhiều Agent có tính chuyên môn cao, kết hợp với các bộ quy tắc (guardrails) và quy chuẩn bảo mật chặt chẽ cho các luồng nghiệp vụ phức tạp.
- **Tối ưu Hóa Hạ Tầng Bằng Gói Cước Cố Định:** Đánh giá lại mức độ biến động lưu lượng ứng dụng hiện tại và xem xét chuyển sang sử dụng gói giá flat-rate của CloudFront để loại bỏ rủi ro tài chính và hợp nhất khả năng bảo mật.

![Ảnh sự kiện](/images/4-EventParticipated/4.2-event2/evt2.jpg)