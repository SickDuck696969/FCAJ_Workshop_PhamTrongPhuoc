---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tăng cường bảo mật toàn diện bằng IAM, WAF và các giao thức xác thực chuẩn.
* Tích hợp các dịch vụ AWS bất đồng bộ để xử lý tác vụ ngầm.
* Thực hiện kiểm thử toàn diện để đảm bảo tính ổn định của hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Rà soát và cấu hình các quyền IAM tuân theo nguyên tắc "đặc quyền tối thiểu". <br> - Hoàn thiện JWT/OAuth2 cho việc xác thực API. | 22/06/2026 | 22/06/2026 | https://github.com/vinhpham2808/J2EE |
| 3 | - Thiết lập Cloudflare WAF để bảo vệ hệ thống khỏi các lỗ hổng web phổ biến. <br> - Cấu hình chứng chỉ SSL/TLS mã hóa dữ liệu truyền tải. | 23/06/2026 | 23/06/2026 | https://github.com/vinhpham2808/J2EE |
| 4 | - Tích hợp SQS queue để xử lý tin nhắn bất đồng bộ. <br> - Cấu hình EC2 worker đọc tin nhắn từ SQS. | 24/06/2026 | 24/06/2026 | https://github.com/vinhpham2808/J2EE |
| 5 | - Lập trình AWS Lambda để thực thi các tác vụ ngầm (như xử lý file lưu lên S3). <br> - Chạy thử luồng xử lý: SQS -> Worker -> Lambda -> S3. | 25/06/2026 | 25/06/2026 | https://github.com/vinhpham2808/J2EE |
| 6 | - Viết và chạy các bài kiểm thử tích hợp (integration tests) cho luồng nghiệp vụ quan trọng. <br> - Đánh giá lại hệ thống bảo mật và hoàn thiện báo cáo tuần. | 26/06/2026 | 26/06/2026 | https://github.com/vinhpham2808/J2EE |

### Kết quả mong đợi
- Hệ thống được bảo mật tối đa với IAM, WAF và JWT/OAuth2.
- Luồng xử lý bất đồng bộ (SQS -> Worker -> Lambda -> S3) hoạt động trơn tru.
- Đạt độ bao phủ kiểm thử tốt cho các API cốt lõi và tiến trình chạy ngầm.
