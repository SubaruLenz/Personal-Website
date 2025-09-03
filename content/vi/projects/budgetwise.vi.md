---
title: "BudgetWise - Trình Quản Lý Ngân Sách AI"
description: "Nền tảng quản lý ngân sách cloud-native với thông tin chi tiết từ AI"
date: "2025-08-01"
showHero: false
tags: ["AWS", "FastAPI", "React", "AI", "Docker"]
---

## Liên Kết

**Vai trò:** Thực tập sinh Cloud Engineer  
**Công ty:** [Amazon Web Service Vietnam](https://masothue.com/0314175120-cong-ty-tnhh-amazon-web-services-viet-nam)  
**Link dự án:** [BudgetWise](https://workshop.suba-server.org)  

## Tổng Quan Dự Án

**Thời gian:** 3 tháng (Thực tập AWS Vietnam)  
**Nhóm:** Dự án cá nhân  
**Chi phí vận hành:** $30/tháng

## Công Nghệ Sử Dụng

**Backend:** FastAPI (Python), PostgreSQL, Docker  
**Frontend:** React (Vite)
**Hạ tầng (AWS):** Fargate, Aurora, Amplify, Bedrock, CloudWatch

## Tính Năng Chính

- **Theo Dõi Chi Tiêu & Thu Nhập** - Giám sát tài chính toàn diện
- **Thông Tin Chi Tiết AI** - Phân tích tài chính cá nhân hóa qua AWS Bedrock
- **Quản Lý Ngân Sách** - Lập ngân sách thông minh với khuyến nghị tự động
- **Phân Tích Thời Gian Thực** - Dashboard tương tác và báo cáo

## Kiến Trúc & Triển Khai

- **Backend Container hóa** - AWS Fargate cho auto-scaling và độ tin cậy
- **Cơ sở dữ liệu** - Aurora PostgreSQL với khả năng auto-scaling
- **Hosting Frontend** - AWS Amplify cho triển khai liền mạch
- **Tích Hợp AI** - AWS Bedrock cho tư vấn tài chính thông minh
- **Giám Sát** - CloudWatch cho logging và cảnh báo tập trung

## Thành Tựu

- Thiết kế và triển khai kiến trúc cloud-native hoàn chỉnh
- Tích hợp AI advisor cung cấp khuyến nghị tài chính cá nhân hóa
- Đạt được khả năng mở rộng cao thông qua container hóa và auto-scaling
- Triển khai giám sát toàn diện cho sự ổn định hệ thống

## Sơ Đồ

![Sơ Đồ Kiến Trúc](projects/BudgetWise_diagram.png)

## Tài Nguyên Bên Ngoài

### Frontend
{{< github repo="SubaruLenz/Budget-Tracker-Frontend" showThumbnail=false >}}

### Backend

{{< github repo="SubaruLenz/Budget-Tracker-Backend" showThumbnail=false >}}

### Tài Liệu
[Docs](https://workshop.suba-server.org)