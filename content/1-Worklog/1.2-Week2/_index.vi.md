---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---



### Mục tiêu tuần 2:

* Hệ thống hóa và thực hành chuyên sâu quyền truy cập IAM, mạng VPC.
* Nắm vững các khái niệm và kỹ năng thao tác với máy chủ Amazon EC2 (Linux & Windows).
* Tích hợp cấp quyền linh hoạt cho ứng dụng trên EC2 thông qua IAM Roles.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Ôn tập toàn bộ lý thuyết và troubleshooting các vấn đề thường gặp với IAM và VPC. <br> - Vẽ sơ đồ mạng liên kết giữa: VPC, Subnets, Internet Gateway, NAT Gateway, NACLs, và Security Groups. <br> - Chuẩn bị môi trường để thực hành chuyên sâu EC2. | 27/04/2026 | 27/04/2026 |  |
| 3 | - Nghiên cứu lý thuyết Module 3 (Amazon EC2). <br> - Tìm hiểu về các loại Instance (T-family, M-family, C-family) và cách chọn loại Instance phù hợp cho ứng dụng. <br> - Chuẩn bị Key Pair (SSH) và Security Group cho EC2. | 28/04/2026 | 28/04/2026 | https://000004.awsstudygroup.com/vi/ |
| 4 | - Khởi tạo đồng thời Windows Server Instance và Amazon Linux Instance. <br> - Thực hành các thao tác quản trị: Đổi kích thước Instance (Instance Type), thay đổi dung lượng ổ cứng (EBS Volume). <br> - Backup dữ liệu bằng cách tạo EBS Snapshots và tạo Custom AMI. <br> - Thực hành kỹ thuật lấy lại quyền truy cập (Recovery) khi vô tình làm mất file KeyPair. | 29/04/2026 | 29/04/2026 | https://000004.awsstudygroup.com/vi/ |
| 5 | - Triển khai thành công ứng dụng Node.js cơ bản trên cả 2 môi trường Amazon Linux và Windows. <br> - Kết hợp dịch vụ IAM để giới hạn tài nguyên mà ứng dụng được phép sử dụng. <br> - Review và rà soát hệ thống Billing, dọn dẹp tài nguyên bài lab. | 30/04/2026 | 30/04/2026 | https://000004.awsstudygroup.com/vi/ |
| 6 | - Thực hành kỹ thuật ủy quyền (Delegation) thay vì hardcode Access Key vào code. <br> - Cấp quyền cho ứng dụng chạy trên EC2 truy cập vào S3 Bucket một cách an toàn qua IAM Role. <br> - Cấu hình EC2 Instance Profile. <br> - Clean up dọn dẹp các role và tài nguyên. | 01/05/2026 | 01/05/2026 | https://000048.awsstudygroup.com/vi/ |
