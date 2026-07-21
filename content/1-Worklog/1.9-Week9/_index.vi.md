---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Tập trung phát triển các tính năng cốt lõi của Money Manager (Frontend & Backend).
* Triển khai ứng dụng lên AWS theo đúng kiến trúc đã thiết kế ở tuần 8.
* Cấu hình kết nối an toàn giữa các dịch vụ AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Lập trình các API nghiệp vụ chính (quản lý thu chi, ngân sách). <br> - Xây dựng module xác thực người dùng và phân quyền cơ bản. | 15/06/2026 | 15/06/2026 | https://github.com/vinhpham2808/J2EE |
| 3 | - Khởi tạo RDS MySQL và cấu hình schema cơ sở dữ liệu. <br> - Kết nối backend Spring Boot với RDS và kiểm tra các giao dịch (transactions). | 16/06/2026 | 16/06/2026 | https://github.com/vinhpham2808/J2EE |
| 4 | - Cấu hình ElastiCache Redis để lưu trữ session và làm bộ đệm (cache). <br> - Tích hợp cache vào backend để tối ưu thời gian phản hồi. | 17/06/2026 | 17/06/2026 | https://github.com/vinhpham2808/J2EE |
| 5 | - Triển khai backend lên cụm EC2 nằm trong Auto Scaling Group. <br> - Cấu hình Application Load Balancer (ALB) để điều hướng traffic. | 18/06/2026 | 18/06/2026 | https://github.com/vinhpham2808/J2EE |
| 6 | - Kiểm thử end-to-end các luồng chính trực tiếp trên môi trường AWS. <br> - Viết tài liệu hướng dẫn deploy và tổng kết báo cáo tuần 9. | 19/06/2026 | 19/06/2026 | https://github.com/vinhpham2808/J2EE |

### Kết quả mong đợi
- Các API cốt lõi hoạt động trơn tru với xác thực an toàn.
- Backend được deploy thành công trên hạ tầng EC2 có ALB và Auto Scaling.
- RDS MySQL và ElastiCache Redis được cấu hình và kết nối ổn định.
