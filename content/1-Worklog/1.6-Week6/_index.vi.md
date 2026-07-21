---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Xây dựng nền tảng giám sát (Monitoring) hệ thống vững chắc với CloudWatch.
* Quản lý DNS và định tuyến lưu lượng truy cập với Amazon Route53.
* Ứng dụng các công cụ này vào giải quyết bài toán vận hành hệ thống thực tế.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Giới thiệu Amazon CloudWatch: Metrics, Logs, và Events/EventBridge. <br> - Tầm quan trọng của việc thu thập log hệ thống và đặt cảnh báo (Alarms) trong quá trình vận hành. | 25/05/2026 | 25/05/2026 | https://000008.awsstudygroup.com/vi/ |
| 3 | - Thực hành cài đặt CloudWatch Agent lên EC2 để đẩy Memory/Disk metrics lên AWS. <br> - Xây dựng CloudWatch Dashboards giám sát tập trung các chỉ số. <br> - Tạo Billing Alarm gửi email khi chi phí vượt quá giới hạn $5. | 26/05/2026 | 26/05/2026 | https://000008.awsstudygroup.com/vi/ |
| 4 | - Giới thiệu dịch vụ Amazon Route53: Quản lý Domain, DNS Routing, Health Checks. <br> - Tìm hiểu các cơ chế Routing Policy (Simple, Weighted, Latency, Failover, Geolocation). | 27/05/2026 | 27/05/2026 | https://000010.awsstudygroup.com/vi/ |
| 5 | - Khởi tạo Route53 Hosted Zone. <br> - Cấu hình thiết lập hệ thống DNS Hybrid (lai) tích hợp giải quyết tên miền nội bộ giữa mạng Local (On-premise giả lập) và Amazon VPC. | 28/05/2026 | 28/05/2026 | https://000010.awsstudygroup.com/vi/ |
| 6 | - Cấu hình các bản ghi (A, CNAME, ALIAS) trên Route53 trỏ về máy chủ EC2 hoặc S3 Static Website. <br> - Cấu hình Health Check để route traffic sang hệ thống backup nếu máy chủ chính bị lỗi. | 29/05/2026 | 29/05/2026 | https://000010.awsstudygroup.com/vi/ |
