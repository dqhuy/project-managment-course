## 📄 **PROJECT CHARTER – ỨNG DỤNG ĐẶT LỊCH KHÁM BỆNH**

---

### **1. Thông tin chung**

* **Tên dự án:** Ứng dụng đặt lịch khám bệnh (Healthcare Booking App)
* **Ngày khởi tạo:** 01/06/2025
* **Người khởi xướng (Project Sponsor):** Bệnh viện XYZ – Ban Giám đốc
* **Người quản lý dự án (Project Manager):** \[Tên sẽ được cập nhật theo tổ chức triển khai – ví dụ: Nguyễn Văn A]

---

### **2. Mục tiêu dự án**

Phát triển ứng dụng di động và web cho phép:

* Bệnh nhân đặt lịch khám bệnh từ xa, nhận thông báo nhắc lịch qua SMS/email.
* Bác sĩ quản lý lịch làm việc.
* Bệnh viện theo dõi lịch khám và thông tin bệnh nhân.
  Dự án góp phần số hóa hoạt động y tế và nâng cao trải nghiệm bệnh nhân.

---

### **3. Sản phẩm bàn giao (Deliverables)**

* Ứng dụng di động chạy trên Android và iOS.
* Website đặt lịch và hệ thống bảng điều khiển quản trị.
* API backend (đăng nhập OTP, quản lý bác sĩ, lịch hẹn).
* Tài liệu hướng dẫn sử dụng (bệnh nhân, quản trị).
* Tài liệu kỹ thuật và mã nguồn (trên GitHub).
* Đào tạo người dùng và hỗ trợ sau triển khai.

---

### **4. Phạm vi sơ bộ (High-level Scope)**

**Bao gồm:**

* Đăng ký, đăng nhập (xác thực OTP).
* Tìm kiếm bác sĩ, chọn lịch trống.
* Đặt lịch khám và nhận thông báo.
* Xem hồ sơ khám bệnh cơ bản.
* Bảng quản trị: bác sĩ, lịch khám, hồ sơ bệnh nhân.
* Giao diện thân thiện cho người lớn tuổi, hỗ trợ tiếng Việt & tiếng Anh.

**Không bao gồm:**

* Tích hợp thiết bị y tế, thanh toán trực tuyến.
* Tư vấn video call hoặc tích hợp hệ thống HIS.

---

### **5. Lý do kinh doanh (Business Case)**

* Hạn chế tình trạng quá tải khi đăng ký khám trực tiếp.
* Nâng cao trải nghiệm bệnh nhân, tiết kiệm thời gian.
* Góp phần vào chiến lược chuyển đổi số của bệnh viện XYZ.
* Giảm chi phí vận hành và nâng cao hình ảnh bệnh viện.

---

### **6. Rủi ro sơ bộ**

| Rủi ro                           | Xác suất   | Tác động   | Giải pháp                                    |
| -------------------------------- | ---------- | ---------- | -------------------------------------------- |
| Lỗi bảo mật dữ liệu              | Trung bình | Cao        | Áp dụng AES-256, kiểm tra định kỳ            |
| Chậm tiến độ do thay đổi yêu cầu | Cao        | Trung bình | Agile, họp định kỳ với khách hàng            |
| Giao diện không thân thiện       | Trung bình | Trung bình | Kiểm thử khả năng sử dụng với người lớn tuổi |

---

### **7. Ngân sách và thời gian**

* **Ngân sách ước tính:** 500.000.000 VND
* **Thời gian thực hiện:** 6 tháng (01/06/2025 – 30/11/2025)

---

### **8. Các bên liên quan chính (Key Stakeholders)**

| Tên                    | Vai trò                      | Mối quan tâm                      |
| ---------------------- | ---------------------------- | --------------------------------- |
| Bệnh viện XYZ          | Khách hàng/Sponsor           | Tăng hiệu quả tiếp nhận bệnh nhân |
| PM                     | Quản lý dự án                | Đảm bảo tiến độ và chất lượng     |
| Đội phát triển         | Lập trình viên, thiết kế, QA | Yêu cầu rõ ràng, phản hồi nhanh   |
| Nhà cung cấp SMS/Email | Bên thứ ba                   | Dịch vụ ổn định, dễ tích hợp      |
| Người dùng cuối        | Bệnh nhân                    | Trải nghiệm đơn giản, bảo mật     |

---

### **9. Phê duyệt**

| Họ tên                        | Vai trò         | Chữ ký         | Ngày       |
| ----------------------------- | --------------- | -------------- | ---------- |
| \[Tên đại diện Bệnh viện XYZ] | Project Sponsor | \_\_\_\_\_\_\_ | 01/06/2025 |
| \[Tên PM]                     | Project Manager | \_\_\_\_\_\_\_ | 01/06/2025 |

