---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---



### Mục tiêu tuần 3:

* Nắm vững dịch vụ lưu trữ đối tượng (Object Storage) lớn nhất của AWS - Amazon S3.
* Hiểu về vòng đời dữ liệu và cách phân phối nội dung tĩnh (Static Website).
* Ứng dụng CloudFront để tối ưu hóa tốc độ tải trang Web.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Xem video và tài liệu lý thuyết Module 4 về các loại Storage trên AWS (Block, File, Object). <br> - Phân biệt sự khác nhau giữa EBS, EFS và S3. <br> - Tạo S3 Bucket, tải dữ liệu tĩnh (HTML, CSS, JS) và cấu hình bật tính năng Static Website Hosting. <br> - Cấu hình Block Public Access an toàn. | 04/05/2026 | 04/05/2026 | https://000057.awsstudygroup.com/vi/ |
| 3 | - Quản lý Bucket Policy, cấp quyền Public Read để Internet có thể truy cập Web. <br> - Kiểm tra Website trên trình duyệt, verify cấu hình MIME type. <br> - Thiết lập Amazon CloudFront (CDN) phân phối nội dung S3 để giảm độ trễ (latency) cho người dùng toàn cầu. | 05/05/2026 | 05/05/2026 | https://000057.awsstudygroup.com/vi/ |
| 4 | - Tìm hiểu tính năng S3 Versioning (Quản lý phiên bản file) để chống xóa nhầm hoặc ghi đè file. <br> - Cấu hình Lifecycle rules để chuyển đổi hạng lưu trữ (Storage Classes) nhằm tiết kiệm chi phí. <br> - Thực hành Cross-Region Replication (CRR) sao chép S3 Object sang Region khác để dự phòng. | 06/05/2026 | 06/05/2026 | https://000057.awsstudygroup.com/vi/ |
| 5 | - Rà soát hệ thống kiến thức AWS S3: Security, Performance, Cost Management. <br> - Đọc thêm tài liệu về S3 Presigned URLs và S3 Select. <br> - Clean up toàn bộ S3 Buckets, CloudFront Distributions. | 07/05/2026 | 07/05/2026 | https://000057.awsstudygroup.com/vi/ |
| 6 | - Review lại lý thuyết và hoàn thành các bài lab và dọn dẹp tài nguyên. | 08/05/2026 | 08/05/2026 |  |
