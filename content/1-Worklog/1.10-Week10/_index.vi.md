---
title: "Tuần 10"
date: 2026-04-17
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Chủ đề tuần

Lập kế hoạch deploy production và chuẩn bị báo cáo cho hệ thống game backend API trên AWS.

### Mục tiêu tuần

* Thống nhất phương án và lên kế hoạch đưa backend API lên môi trường production.
* Deploy thực tế hệ thống hạ tầng và ứng dụng lên AWS thông qua DNS và ALB.
* Bắt đầu soạn thảo các chương cốt lõi trong báo cáo thực tập tốt nghiệp.

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 22/06/2026 | Thứ 2 | Họp nhóm rà soát cấu hình production: biến môi trường bảo mật, credentials, IP whitelist và các thiết lập API. | Kế hoạch Deploy |
| 23/06/2026 | Thứ 3 | Cấu hình Route 53 DNS và tích hợp dịch vụ Cloudflare WAF bảo vệ cổng ALB, trỏ tên miền chính về AWS. | Domain & DNS |
| 24/06/2026 | Thứ 4 | Deploy các container API và Worker lên các máy chủ EC2 trong Private Subnet, kết nối RDS MySQL và ElastiCache. | Deployment |
| 25/06/2026 | Thứ 5 | Bắt đầu viết nội dung báo cáo thực tập: chương Giới thiệu tổng quan về đơn vị thực tập, phân tích yêu cầu phần mềm. | Viết Báo cáo |
| 26/06/2026 | Thứ 6 | Soạn thảo chương mô tả Kiến trúc hạ tầng AWS, mô tả chi tiết cách thiết lập bảo mật và tối ưu chi phí trong báo cáo. | Viết Báo cáo |

### Kết quả kỳ vọng

* Chốt bảng kiểm tra (checklist) triển khai sản phẩm thực tế.
* Hạ tầng production chạy ổn định trên AWS, API phản hồi tốt.
* Hệ thống được bảo vệ qua DNS và proxy layer phù hợp với yêu cầu workshop.
* Hoàn thành bản thảo 2 chương đầu tiên của Báo cáo thực tập tốt nghiệp.

### Tham chiếu tuần 10

* [Repo dự án](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* Domain management và bảo vệ ingress qua Route 53 + Cloudflare WAF
* Tài liệu báo cáo thực tập tốt nghiệp
