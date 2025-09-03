---
title: "Ollama - Mô Hình Ngôn Ngữ Đa Dạng Tự Host"
description: "Hạ tầng máy chủ tự host với 2 PC cho triển khai LLM và nghiên cứu mạng"
showDate: true
date: "2024-12-01"
showAuthor: true
showReadingTime: true
tags: ["Ubuntu Server", "Cloudflare", "Docker", "Prometheus", "Grafana", "Ollama"]
---

## Tổng Quan Dự Án

**Thời gian:** 12 tháng  
**Nhóm:** Dự án cá nhân  
**Mục đích:** Nghiên cứu mạng và hạ tầng AI tự host

## Công Nghệ Sử Dụng

**Hệ điều hành:** Ubuntu Server  
**Container hóa:** Docker  
**Mạng:** Cloudflare Tunnel  
**Giám sát:** Prometheus, Grafana  
**Nền tảng AI:** Ollama

## Kiến Trúc

Xây dựng hạ tầng 2 PC tối ưu hóa cho cả hiệu quả năng lượng và sức mạnh tính toán:

- **PC Tiết Kiệm Năng Lượng** - Host website qua Cloudflare tunnel với domain cá nhân
- **Máy Chủ Hiệu Năng Cao** - Xử lý các tác vụ tính toán nặng bao gồm mô hình ngôn ngữ lớn

## Tính Năng Chính

- 🖥️ **Thiết Lập 2 PC** - Phân bổ tài nguyên tối ưu giữa mạng và tính toán
- 🐳 **Container Hóa Hoàn Toàn** - Tất cả dịch vụ được Docker hóa để quản lý hiệu quả
- 🔄 **Tự Động Khởi Động Lại** - Khôi phục và quản lý dịch vụ tự động
- 📊 **Giám Sát Hiệu Năng** - Metrics thời gian thực với Prometheus
- 📈 **Trực Quan Hóa Log** - Phân tích được tối ưu qua dashboard Grafana
- 🌐 **Truy Cập Bảo Mật** - Tích hợp Cloudflare tunnel với domain cá nhân

## Triển Khai Kỹ Thuật

- Container hóa website, Cloudflare tunnel và các dịch vụ LLM
- Triển khai stack giám sát toàn diện để theo dõi hiệu năng
- Cấu hình cơ chế khởi động lại tự động cho độ tin cậy dịch vụ
- Thiết lập truy cập từ xa bảo mật thông qua hạ tầng Cloudflare

## Kết Quả Học Tập

- Các khái niệm mạng nâng cao và cấu hình tunnel
- Điều phối container và quản lý dịch vụ
- Giám sát hạ tầng và khả năng quan sát
- Chiến lược triển khai AI tự host
- Thiết kế kiến trúc máy chủ tiết kiệm năng lượng