

# 📄 **Requirements Management Plan – Healthcare Booking App**

---

## **1. Mục đích của tài liệu**

Tài liệu này mô tả cách các yêu cầu của dự án sẽ được thu thập, phân tích, theo dõi, quản lý và cập nhật trong suốt vòng đời dự án nhằm đảm bảo tất cả yêu cầu đều được đáp ứng đúng cách, đúng thời điểm và không bị bỏ sót.

---

## **2. Lập kế hoạch, theo dõi và báo cáo hoạt động yêu cầu**

### ● Lập kế hoạch:

* Yêu cầu sẽ được thu thập thông qua: phỏng vấn, khảo sát, workshop với bệnh viện XYZ.
* Mỗi yêu cầu được ghi lại trong **tài liệu đặc tả yêu cầu phần mềm (SRS)**.

### ● Theo dõi:

* Yêu cầu được mã hóa (ví dụ: REQ-001) để dễ truy vết.
* Trạng thái của từng yêu cầu (Đang phân tích, Đang phát triển, Hoàn thành, Từ chối) được cập nhật định kỳ trên Jira.

### ● Báo cáo:

* Báo cáo hàng tuần trình bày số lượng yêu cầu đang xử lý, hoàn thành, bị trì hoãn.
* Yêu cầu thay đổi sẽ được thống kê riêng và trình ban quản lý phê duyệt.

---

## **3. Quản lý cấu hình (Configuration Management)**

* Mỗi phiên bản của tài liệu yêu cầu (SRS) sẽ được đánh số phiên bản (v1.0, v1.1…).
* Thay đổi phải được ghi nhận trong **Change Log** với thông tin: mã yêu cầu, mô tả thay đổi, người yêu cầu, ảnh hưởng đến thời gian/chi phí.
* Tất cả tài liệu liên quan được lưu trữ có kiểm soát trên GitHub hoặc Google Drive (phân quyền truy cập rõ ràng).

---

## **4. Ưu tiên hóa yêu cầu**

Yêu cầu sẽ được ưu tiên bằng **phương pháp MoSCoW**:

* **Must-have:** Yêu cầu cốt lõi để ứng dụng hoạt động (ví dụ: xác thực OTP, đặt lịch).
* **Should-have:** Yêu cầu nên có nhưng có thể trì hoãn (ví dụ: thông báo qua email).
* **Could-have:** Tiện ích bổ sung (hỗ trợ đa ngôn ngữ).
* **Won’t-have:** Chưa thực hiện trong giai đoạn này (thanh toán online).

Ưu tiên được xác định dựa trên: mức độ quan trọng với người dùng, rủi ro kỹ thuật, và tác động đến phạm vi dự án.

---

## **5. Sử dụng các chỉ số sản phẩm (Product Metrics)**

Một số chỉ số sẽ được sử dụng để đo lường chất lượng yêu cầu và hiệu quả triển khai:

* **Tỷ lệ hoàn thành yêu cầu:** (Số yêu cầu đã hoàn thành / Tổng số yêu cầu) × 100%
* **Số lần thay đổi yêu cầu (scope change):** phản ánh mức ổn định của yêu cầu ban đầu.
* **Tỷ lệ lỗi do hiểu sai yêu cầu:** (Số lỗi liên quan đến yêu cầu / Tổng số lỗi)
* **Độ trễ yêu cầu:** Thời gian trung bình từ lúc thu thập đến lúc hoàn thành triển khai.

---

## **6. Truy vết và thuộc tính yêu cầu (Requirement Traceability & Attributes)**

### ● Thuộc tính yêu cầu:

* Mã định danh: REQ-001, REQ-002…
* Mô tả ngắn gọn
* Ưu tiên (Must, Should…)
* Trạng thái (Đang phân tích, Đã triển khai…)
* Nguồn yêu cầu (ai đề xuất)
* Liên kết kiểm thử tương ứng

### ● Truy vết (Traceability Matrix):

| Mã yêu cầu | Use Case   | Thiết kế UI | Mã nguồn      | Test Case |
| ---------- | ---------- | ----------- | ------------- | --------- |
| REQ-001    | UC-Login   | Figma-Login | login.js      | TC-001    |
| REQ-002    | UC-Booking | UI-Booking  | bookingAPI.js | TC-003    |

Việc truy vết giúp đảm bảo rằng mọi yêu cầu đều được thiết kế, mã hóa và kiểm thử.

