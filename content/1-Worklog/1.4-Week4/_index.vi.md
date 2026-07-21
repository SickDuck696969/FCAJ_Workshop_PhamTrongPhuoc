---
title: "Tuần 4 - Auto Scaling, Route 53, DynamoDB & CloudFront"
date: 2026-04-17
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Chủ đề tuần

Nghiên cứu Auto Scaling, Route 53, CloudWatch và thiết kế kiến trúc HA cho hệ thống game backend API trên AWS.

### Mục tiêu tuần

* Hoàn thiện sơ đồ luồng traffic và cấu trúc hạ tầng cho backend game API.
* Tìm hiểu cơ chế Amazon EC2 Auto Scaling, Route 53 DNS và thiết kế hệ thống có tính sẵn sàng cao (High Availability).
* Rà soát giám sát hạ tầng bằng CloudWatch và chuẩn bị cho các bài thực hành tiếp theo.

### Lịch công việc

| Ngày | Thứ | Nội dung công việc | Lab / Dự án |
|---|---|---|---|
| 11/05/2026 | Thứ 2 | Phân tích luồng truy cập API chính của hệ thống game backend, xác định thành phần chịu tải và vùng triển khai. | Kiến trúc API |
| 12/05/2026 | Thứ 3 | Nghiên cứu cơ chế mở rộng tự động EC2 Auto Scaling để tự động tăng giảm số lượng instance theo lưu lượng tải. Thực hành Lab 000006. | [Lab 000006 - Tự động co giãn ứng dụng với EC2 Auto Scaling](https://000006.awsstudygroup.com)|
| 13/05/2026 | Thứ 4 | Nghiên cứu giám sát hạ tầng đám mây bằng CloudWatch và quản lý DNS nội bộ bằng Route 53. Thực hành Lab 000008 và Lab 000010. | [Lab 000008 - Tạo giám sát hệ thống với Amazon CloudWatch](https://000008.awsstudygroup.com)|
| 14/05/2026 | Thứ 5 | Cài đặt và sử dụng AWS CLI trên máy chủ EC2 để tự động hóa quản trị đám mây cho backend API. Thực hành Lab 000011. | [Lab 000011 - Sử dụng AWS CLI trên Amazon EC2](https://000011.awsstudygroup.com)|
| 15/05/2026 | Thứ 6 | Tìm hiểu và triển khai kiến trúc Web đa tầng High Availability (HA) sử dụng ALB và RDS Multi-AZ hỗ trợ backend game. Thực hành Lab 000021. | [Lab 000021 - Bài thực hành ứng dụng Web độ sẵn sàng cao](https://000021.awsstudygroup.com)|

### Kết quả kỳ vọng

* Xác định được luồng traffic và thành phần triển khai chính của hệ thống game backend API.
* Cấu hình thành công Auto Scaling Group kết hợp Application Load Balancer (ALB).
* Tạo CloudWatch Alarms và thiết lập các bản ghi DNS với Route 53.
* Viết script AWS CLI tương tác với tài nguyên AWS để hỗ trợ vận hành.
* Hiểu rõ cách thiết kế hệ thống HA chịu lỗi tốt bằng RDS Multi-AZ và ALB.

### Tham chiếu tuần 4

* [Repo dự án](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* [Lab 000006 - Tự động co giãn ứng dụng với EC2 Auto Scaling](https://000006.awsstudygroup.com)
* [Lab 000008 - Tạo giám sát hệ thống với Amazon CloudWatch](https://000008.awsstudygroup.com)
* [Lab 000010 - Quản lý DNS với Amazon Route 53](https://000010.awsstudygroup.com)
* [Lab 000011 - Sử dụng AWS CLI trên Amazon EC2](https://000011.awsstudygroup.com)
* [Lab 000021 - Bài thực hành ứng dụng Web độ sẵn sàng cao](https://000021.awsstudygroup.com)
