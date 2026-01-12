# PROPOSAL WORKSHOP

**Building an AI-Powered Security & Observability Platform**

---

## 1. Thông tin chung

**Tên workshop:**
**Building an AI-Powered Security & Observability Platform**

**Chủ đề:**
Ứng dụng AI + Cloud + Cyber Security để giám sát hệ thống, phát hiện sự cố và tạo báo cáo tự động.

**Đối tượng tham gia:**

* Sinh viên CNTT / ATTT / Khoa học dữ liệu
* DevOps / Cloud / Cyber Security
* Người mới tìm hiểu AI trong hệ thống thực tế

**Thời lượng trình bày:**
2 tiếng

**Hình thức:**
Hybrid (Online / Offline)

---

## 2. Mục tiêu workshop

Sau workshop, người tham gia có thể:

1. Hiểu cách thu thập log hệ thống
2. Áp dụng AI để phát hiện bất thường
3. Hiểu quy trình xử lý sự cố (Incident Response)
4. Dùng GenAI để viết báo cáo tự động
5. Triển khai hệ thống trên AWS hoặc môi trường khác

---

## 3. Nội dung chính

### Module 1 – Tổng quan hệ thống

* Kiến trúc AI + Cloud + Security
* Luồng dữ liệu: Log → AI → Alert → Report

### Module 2 – Thu thập dữ liệu

* Log hệ thống
* Log mạng
* Log ứng dụng

### Module 3 – AI phân tích

* Phát hiện bất thường
* Phân loại sự cố
* Đánh giá rủi ro

### Module 4 – Incident Response

* Quy trình xử lý sự cố
* Playbook phản ứng
* Tự động cảnh báo

### Module 5 – GenAI viết báo cáo

* Incident Report
* Security Summary
* Weekly Report

### Module 6 – Demo & Q&A

* Trình diễn hệ thống
* Thảo luận ứng dụng thực tế

---

## 4. Kiến trúc hệ thống demo

```
Data Source → Collector → AI Engine → Decision Engine → GenAI → Dashboard / Report
```
Triển khai được trên:

* AWS
* Local (On-prem)
* Cloud khác

---

## 5. Ứng dụng cho các ngành

| Ngành          | Lợi ích            |
| -------------- | ------------------ |
| IT / DevOps    | Giám sát hệ thống  |
| Cyber Security | Phát hiện tấn công |
| Cloud Engineer | Quản lý hạ tầng    |
| Data / AI      | Phân tích log      |
| Doanh nghiệp   | Quản trị rủi ro    |
| Giáo dục       | Đào tạo thực hành  |

---
## 6. Đội ngũ thực hiện (Chi tiết theo vai trò)

**Cơ cấu team (6 người):**

## 🔹 AI Team (2 người)

### AI Engineer 1 – Log Analysis & Anomaly Detection

**Nhiệm vụ chính:**

* Thiết kế pipeline xử lý log (parse, clean, normalize)
* Xây dựng mô hình phát hiện bất thường (Anomaly Detection)
* Phân loại sự cố (Classification)
* Đánh giá mức độ rủi ro (Risk Scoring)

**Công việc cụ thể:**

* Thu thập dataset log
* Train model (Isolation Forest / LSTM / Autoencoder)
* Test độ chính xác
* Xuất kết quả cho Decision Engine

---

### AI Engineer 2 – GenAI & Automated Reporting

**Nhiệm vụ chính:**

* Tích hợp GenAI để tạo báo cáo
* Thiết kế prompt cho Incident Report
* Tạo Weekly / Monthly Security Report

**Công việc cụ thể:**

* Viết prompt cho GenAI
* Kết nối AI Engine → GenAI
* Xuất báo cáo PDF / Markdown
* Tối ưu nội dung báo cáo cho doanh nghiệp

---

## 🔹 IA / Cyber Team (4 người)

### IA/Cyber 1 – Log Collection & Monitoring

**Nhiệm vụ chính:**

* Thu thập log hệ thống, mạng, ứng dụng
* Thiết lập log pipeline

**Công việc cụ thể:**

* Setup log agent (Filebeat / Fluentd)
* Thu thập:

  * System logs
  * Network logs
  * Application logs
* Đẩy log về AI Engine

---

### IA/Cyber 2 – Incident Response & Playbook

**Nhiệm vụ chính:**

* Thiết kế quy trình xử lý sự cố
* Xây dựng playbook phản ứng

**Công việc cụ thể:**

* Viết Incident Response Flow
* Định nghĩa:

  * Alert level
  * Response action
* Mapping AI output → Response action

---

### IA/Cyber 3 – Cloud Security & Deployment

**Nhiệm vụ chính:**

* Triển khai hệ thống trên AWS / Local
* Đảm bảo bảo mật hạ tầng

**Công việc cụ thể:**

* Setup EC2 / S3 / IAM
* Docker hóa hệ thống
* Thiết lập firewall, access control
* Đảm bảo data protection

---

### IA/Cyber 4 – System Architecture & API

**Nhiệm vụ chính:**

* Thiết kế kiến trúc tổng thể
* Phát triển API kết nối các thành phần

**Công việc cụ thể:**

* Vẽ sơ đồ hệ thống
* Xây API:

  * Log Ingestion
  * AI Result
  * Report Output
* Kết nối Dashboard

---

## 🔹 Phân công theo module workshop

| Module             | Người phụ trách |
| ------------------ | --------------- |
| Tổng quan hệ thống | IA/Cyber 4      |
| Thu thập log       | IA/Cyber 1      |
| AI phân tích       | AI Engineer 1   |
| Incident Response  | IA/Cyber 2      |
| GenAI báo cáo      | AI Engineer 2   |
| Demo hệ thống      | IA/Cyber 3      |
| Slide & tài liệu   | Cả team         |

---

## 🔹 Phân công cho đồ án / startup / workshop

| Hạng mục      | Phụ trách  |
| ------------- | ---------- |
| AI Engine     | AI Team    |
| GenAI Report  | AI Team    |
| Security Flow | IA Team    |
| Cloud Setup   | IA Team    |
| Demo          | IA Team    |
| Proposal      | Cả team    |
| GitHub        | IA/Cyber 4 |
| Slide         | AI + IA    |
---

## 7. Kế hoạch triển khai

### Giai đoạn 1 – Chuẩn bị

* Thiết kế kiến trúc
* Setup môi trường
* Chuẩn bị tài liệu

### Giai đoạn 2 – Xây dựng hệ thống

* AI Engine
* Log Pipeline
* API

### Giai đoạn 3 – Hoàn thiện workshop

* Dashboard
* Slide
* Video demo

---

## 8. Kết quả mong đợi

* 1 hệ thống demo hoàn chỉnh
* Slide workshop
* Tài liệu hướng dẫn
* Video trình diễn
* Report mẫu

---

## 9. Giá trị mang lại

### Với người học

* Kỹ năng thực tế
* Hiểu AI + Cloud + Security
* Có sản phẩm demo

### Với nhà trường / doanh nghiệp

* Nội dung đào tạo hiện đại
* Ứng dụng thực tế
* Giảm rủi ro hệ thống

---

## 10. Kết luận

Workshop này giúp kết nối:

> **AI – Cloud – Security – Thực tế doanh nghiệp**

Phù hợp cho:

* Đào tạo
* Đồ án
* Startup
* Nghiên cứu ứng dụng
