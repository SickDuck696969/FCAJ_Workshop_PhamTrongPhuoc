---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Hoàn tất khâu kiểm tra cuối cùng: rà soát bảo mật và tối ưu chi phí AWS.
* Thực hiện thử nghiệm chịu lỗi (failover testing) để chứng minh tính HA.
* Nộp báo cáo chính thức và thuyết trình bảo vệ dự án Money Manager.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Rà soát bảo mật toàn diện cho tất cả các tài nguyên trên AWS. <br> - Phân tích AWS Billing dashboard và đề xuất phương án tối ưu chi phí. | 06/07/2026 | 06/07/2026 | https://github.com/vinhpham2808/J2EE |
| 3 | - Chạy thử nghiệm giả lập sự cố (failover) cho RDS Multi-AZ để đảm bảo an toàn dữ liệu. <br> - Giả lập sập ElastiCache và kiểm tra khả năng phục hồi của ứng dụng. | 07/07/2026 | 07/07/2026 | https://github.com/vinhpham2808/J2EE |
| 4 | - Xử lý các vấn đề phát sinh sau khi deploy và trong quá trình vận hành. <br> - Kiểm tra lại các dịch vụ bên thứ ba qua NAT Gateway: PayOS, Brevo SMTP, Google Gemini API. | 08/07/2026 | 08/07/2026 | https://github.com/vinhpham2808/J2EE |
| 5 | - Kiểm tra lại toàn bộ flow khi run script deploy, đảm bảo mọi thứ hoạt động trơn tru và đúng với hướng dẫn. <br> - Kiểm tra lại các tài liệu: README, tài liệu hướng dẫn tích hợp PayOS, hướng dẫn deploy. | 09/07/2026 | 09/07/2026 | https://github.com/vinhpham2808/J2EE |
| 6 | - Chính thức nộp báo cáo thực tập, mã nguồn và tài liệu liên quan. | 10/07/2026 | 10/07/2026 | https://github.com/vinhpham2808/J2EE |

### Kết quả mong đợi
- Hệ thống AWS đạt chuẩn bảo mật và có chiến lược tối ưu chi phí rõ ràng.
- Chứng minh được tính High Availability thông qua các bài test failover thành công.
- Buổi thuyết trình và nộp báo cáo dự án Money Manager diễn ra tốt đẹp.
