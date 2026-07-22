---
title: "Tuần 2"
date: 2026-05-11
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---


### Chủ đề tuần

Nghiên cứu tài liệu kỹ thuật AWS, làm chủ giao diện AWS Console và triển khai quản trị tài nguyên Amazon EC2.

### Mục tiêu tuần

* Đi sâu vào nguyên lý vận hành cùng các kịch bản ứng dụng thực tế của dịch vụ điện toán đám mây AWS.
* Thao tác thành thạo trên AWS Management Console và làm chủ công tác quản lý tài nguyên tính toán (EC2).
* Phân tích giải pháp kết nối an toàn từ EC2 tới các dịch vụ lưu trữ mà không cần lưu trữ khoá cứng (static key).

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 11/05/2026 | Thứ 2 | Củng cố lại mô hình VPC và các cấu hình IAM từ tuần 1. Thiết lập Billing Alarm mốc 5 USD để chủ động kiểm soát chi phí. | Hệ thống AWS |
| 12/05/2026 | Thứ 3 | Nghiên cứu cơ chế IAM Roles dành cho EC2 và mô hình Instance Profile nhằm đảm bảo truy cập an toàn, loại bỏ việc dùng static access key. Hoàn thành Lab 000048. | [Lab 000048 - IAM Roles cho EC2 (Instance Profile)](https://000048.awsstudygroup.com)|
| 13/05/2026 | Thứ 4 | Tìm hiểu dịch vụ điện toán ảo Amazon EC2. Triển khai khởi tạo máy chủ Amazon Linux & Windows, cấu hình key pairs, AMI cùng Security Group. Thực hành Lab 000004. | [Lab 000004 - Giới thiệu Amazon EC2](https://000004.awsstudygroup.com)|

### Kết quả kỳ vọng

* Nắm vững phương pháp gán Instance Profile giúp máy chủ EC2 giao tiếp an toàn với S3 hoặc DynamoDB.
* Làm chủ các tính năng quản lý, theo dõi tài nguyên trực tiếp trên giao diện AWS Console.
* Triển khai, thiết lập và kết nối thành công tới instance Linux (qua SSH/Session Manager) cũng như máy chủ Windows (qua RDP).
* Phân biệt rõ các thành phần cốt lõi: AMI, Instance Types, Security Groups và Key Pairs trong hệ sinh thái EC2.

### Tham chiếu tuần 2

* [Lab 000002 - Quản lý truy cập với AWS IAM](https://000002.awsstudygroup.com)
* [Lab 000003 - Kiến thức mạng cơ bản với Amazon VPC](https://000003.awsstudygroup.com)
* [Lab 000048 - IAM Roles cho EC2 (Instance Profile)](https://000048.awsstudygroup.com)
* [Lab 000004 - Giới thiệu Amazon EC2](https://000004.awsstudygroup.com)