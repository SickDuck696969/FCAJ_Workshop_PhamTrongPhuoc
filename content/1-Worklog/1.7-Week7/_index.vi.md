---
title: "Tuần 7 - Khởi động dự án cuối kỳ & phân tích"
date: 2026-04-17
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Chủ đề tuần

Tối ưu hóa API backend game, kiểm tra hiệu năng truy vấn dữ liệu và nghiên cứu cache cho hệ thống workshop.

### Mục tiêu tuần

* Làm việc trực tiếp tại văn phòng AWS ngày 1/6.
* Tối ưu hóa hiệu năng backend API và cấu trúc truy vấn dữ liệu game.
* Nâng cao tốc độ phản hồi API bằng cách tối ưu hóa cơ sở dữ liệu và tầng cache.

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 01/06/2026 | Thứ 2 | Lên văn phòng AWS thực tế làm việc, báo cáo kế hoạch tối ưu hóa các module backend và hạ tầng workshop với cán bộ hướng dẫn. | On-site AWS |
| 02/06/2026 | Thứ 3 | Tối ưu hóa các truy vấn database JPA/Hibernate ở backend Spring Boot, tránh lỗi N+1 và giảm thiểu thời gian truy xuất MySQL. | Backend Code |
| 03/06/2026 | Thứ 4 | Phân tích cơ chế caching dữ liệu tĩnh bằng Redis ElastiCache để lưu các cấu hình hệ thống ít thay đổi. | Tối ưu Caching |
| 04/06/2026 | Thứ 5 | Tinh chỉnh mô hình dữ liệu API và xây dựng flow xử lý sự kiện cho backend game. | API Optimization |
| 05/06/2026 | Thứ 6 | Khắc phục các lỗi liên quan đến đồng bộ dữ liệu và kiểm thử kết nối API ổn định khi có mạng. | Kiểm thử Tích hợp |

### Kết quả kỳ vọng

* Hoàn thành kế hoạch on-site tuần 7, thống nhất cấu trúc tối ưu với mentor.
* Tốc độ phản hồi các API chính tăng lên, thời gian query MySQL giảm đi rõ rệt.
* Thiết lập thành công cơ chế cache bằng Redis cho cấu hình hệ thống.
* Backend game API hoạt động ổn định hơn trong các luồng request thực tế.

### Tham chiếu tuần 7

* [Repo dự án](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* Dịch vụ AWS: EC2, RDS MySQL, ElastiCache Redis, API Gateway
