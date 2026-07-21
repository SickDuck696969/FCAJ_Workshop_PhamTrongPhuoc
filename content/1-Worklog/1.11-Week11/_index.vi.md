---
title: "Tuần 11 - Tích hợp backend & kiểm thử tải"
date: 2026-04-17
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Chủ đề tuần

Tích hợp các module backend, chuẩn bị luồng deploy và thực hiện kiểm thử chịu tải trên hạ tầng đám mây cho workshop game API.

### Mục tiêu tuần

* Tích hợp thành công các module backend và cơ sở dữ liệu phục vụ workshop.
* Hoàn thiện quy trình deploy và xác minh API hoạt động ổn định trên môi trường AWS.
* Thực hiện kiểm thử chịu tải để đánh giá khả năng co giãn và giới hạn chịu tải của hạ tầng AWS.

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 29/06/2026 | Thứ 2 | Tích hợp module backend: ghép nối các service API, cấu hình database và rà soát dependencies để chuẩn bị quy trình deploy. | Project cuối kỳ |
| 30/06/2026 | Thứ 3 | Kiểm thử triển khai và debug: xác minh endpoint API, kiểm tra kết nối service và chuẩn bị pipeline release cho game API. | Project cuối kỳ |
| 01/07/2026 | Thứ 4 | Tiếp tục kiểm thử tích hợp và sửa lỗi runtime khi deploy backend lên AWS. | Project cuối kỳ |
| 02/07/2026 | Thứ 5 | Kiểm thử chịu tải: Thiết lập kịch bản và chạy kiểm thử chịu tải (Load testing) lên hệ thống chạy trên AWS. Đánh giá tốc độ phản hồi của ALB và khả năng co giãn của Auto Scaling. | Project cuối kỳ |
| 03/07/2026 | Thứ 6 | Kiểm thử chịu tải (tiếp tục): Phân tích kết quả test tải, tối ưu hóa kích thước connection pool của database, tinh chỉnh cấu hình phần cứng EC2 và tối ưu tài nguyên AWS. | Project cuối kỳ |

### Kết quả kỳ vọng

* Các module backend được tích hợp hoàn chỉnh và hoạt động trơn tru.
* Quy trình deploy và kiểm thử hệ thống game API được hoàn thiện.
* Hoàn thành kiểm thử chịu tải hệ thống và tối ưu hóa các quy tắc tự động co giãn.

### Tham chiếu tuần 11

* [Repo dự án](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* Kịch bản kiểm thử tải hệ thống trên AWS, tối ưu hóa hiệu năng EC2 Auto Scaling và cơ sở dữ liệu
