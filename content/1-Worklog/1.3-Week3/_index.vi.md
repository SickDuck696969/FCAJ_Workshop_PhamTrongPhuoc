---
title: "Tuần 3 - Workshop: kiến trúc, hạ tầng & API"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Chủ đề tuần

Nghiên cứu và triển khai kiến trúc hệ thống máy chủ trên AWS theo workshop: từ tổng quan kiến trúc, quản lý hạ tầng, database, API Gateway, SQS FIFO, DLQ, EventBridge, Backup cho đến kiểm thử và dọn dẹp tài nguyên.

### Mục tiêu tuần

* Hiểu tổng quan kiến trúc hệ thống máy chủ trò chơi trực tuyến trong workshop và xác định các tầng xử lý dữ liệu, lưu trữ và truyền tin.
* Khởi tạo và cấu hình hạ tầng cơ sở trên AWS, bao gồm quản lý tài nguyên, IAM, region và stack deployment.
* Thiết lập Aurora PostgreSQL, RDS Proxy và AWS Backup/S3 để xây dựng lớp dữ liệu và sao lưu tự động.
* Triển khai API Gateway, Lambda backend, SQS FIFO, DLQ, CloudWatch và EventBridge để hoàn thiện luồng xử lý nghiệp vụ.
* Thực hiện kiểm tra hiệu năng, xác nhận kết quả và dọn dẹp tài nguyên sau khi hoàn thành workshop.

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 04/05/2026 | Thứ 2 | Nghiên cứu tổng quan kiến trúc hệ thống và phân tích luồng dữ liệu của workshop: Compute Layer, Database Layer, API Gateway và hệ thống đồng bộ thời gian thực. | Workshop 5.1 - 5.2 |
| 05/05/2026 | Thứ 3 | Thiết lập hạ tầng cơ sở và quản lý tài nguyên AWS, kiểm tra cấu hình region, credentials, IAM và quy trình deploy stack. | Workshop 5.2 |
| 06/05/2026 | Thứ 4 | Xây dựng lớp cơ sở dữ liệu Aurora PostgreSQL, cấu hình RDS Proxy và thiết lập AWS Backup để tự động sao lưu dữ liệu lên S3 Storage. | Workshop 5.3 |
| 07/05/2026 | Thứ 5 | Khởi tạo API Gateway, cấu hình Lambda backend, triển khai SQS FIFO, DLQ và CloudWatch monitor để đảm bảo xử lý event an toàn. | Workshop 5.5 - 5.7 |
| 08/05/2026 | Thứ 6 | Cấu hình EventBridge, kiểm tra kết quả thực nghiệm, thực hiện dọn dẹp tài nguyên và tổng kết kiến thức từ workshop. | Workshop 5.8 - 5.11 |

### Kết quả kỳ vọng

* Nắm rõ kiến trúc tổng quan của hệ thống máy chủ trò chơi trực tuyến và vai trò của từng tầng trong workshop.
* Khởi tạo được hạ tầng AWS cơ bản và triển khai stack theo quy trình đã học.
* Thiết lập được database Aurora PostgreSQL và chính sách sao lưu dữ liệu bằng AWS Backup + S3.
* Hoàn thiện được luồng truy cập API thông qua API Gateway cùng Lambda, SQS FIFO và DLQ.
* Theo dõi và kiểm tra hệ thống bằng CloudWatch, EventBridge và các bước verification/testing trong workshop.

### Tham chiếu tuần 3

* [Workshop 5.1 - Tổng quan về kiến trúc hệ thống](../../5-Workshop/5.1-architecture-overview/)
* [Workshop 5.2 - Khởi tạo hạ tầng cơ sở và quản lý](../../5-Workshop/5.2-management/)
* [Workshop 5.3 - Xây dựng cơ sở dữ liệu và sao lưu](../../5-Workshop/5.3-database/)
* [Workshop 5.5 - Khởi tạo Amazon API Gateway](../../5-Workshop/5.5-API-Gateway/)
* [Workshop 5.6 - Amazon SQS FIFO](../../5-Workshop/5.6-sqs-fifo/)
* [Workshop 5.7 - AWS DLQ & AWS CloudWatch](../../5-Workshop/5.7-sqs-dlq-and-cloudwatch/)
* [Workshop 5.8 - AWS EventBridge](../../5-Workshop/5.8-eventbridge/)
* [Workshop 5.9 - AWS Backup](../../5-Workshop/5.9-aws-backup/)
* [Workshop 5.10 - Kiểm tra kết quả và thực nghiệm](../../5-Workshop/5.10-verification-and-testing/)
* [Workshop 5.11 - Dọn dẹp tài nguyên](../../5-Workshop/5.11-clean-up/)
