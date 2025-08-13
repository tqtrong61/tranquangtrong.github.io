---
title : "Backup và Archive Migration với Tiered Storage"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
---
# Backup và Archive Migration với Tiered Storage

### Tổng quan

Trong workshop này, bạn sẽ học cách triển khai hệ thống Backup & Archive trên AWS với tiered storage nhằm tối ưu chi phí, bật Intelligent-Tiering, tự động hóa retrieval, và bảo đảm compliance.

Quy trình thực hành bao gồm: khởi tạo hạ tầng & baseline bảo mật, cấu hình bucket/backup vault và lifecycle tiers, thiết lập automation (AWS Backup Plans, S3 Batch Operations/Lambda/Step Functions), xây dựng quy trình retrieval có SLA, kiểm thử & xác thực compliance (AWS Backup Audit Manager/KMS/Object Lock), giám sát & cảnh báo (CloudWatch/CloudTrail), và dọn dẹp tài nguyên.


### Nội dung

 1. [Giới thiệu](1-introduce/)
 2. [Các bước chuẩn bị](2-Prerequiste/)
 3. [Cấu hình tiered storage & intelligent tiering](3-Configure Tiered Storage & Intelligent Tiering/)
 4. [Tự động hóa migration](4-Automate Migration/)
 5. [Quy trình retrieval & kiểm thử](5-Retrieval Process & Testing/)
 6. [Xác thực compliance & giám sát](6-Compliance Validation & Monitoring/)
 7. [Dọn dẹp tài nguyên](7-cleanup/)
