# Scope Management Plan

**Dự án:** Ứng dụng Đặt lịch Khám bệnh Trực tuyến (Healthcare Booking App)

**Ngày tạo:** 03/06/2025

**Người soạn:** Đinh Quang Huy

---

## 1. Mục đích (Purpose)

Tài liệu này mô tả cách xác định, quản lý, xác minh và kiểm soát phạm vi của dự án Healthcare Booking App. Mục tiêu là đảm bảo rằng dự án hoàn thành đúng chức năng đã cam kết, tránh phát sinh ngoài phạm vi kiểm soát.

---

## 2. Phạm vi công việc dự án (Project Scope Description)

Dự án nhằm xây dựng một ứng dụng đặt lịch khám bệnh trực tuyến, giúp kết nối bệnh nhân với bác sĩ/phòng khám, cho phép người dùng:

* Đăng ký và đăng nhập tài khoản.
* Tìm kiếm phòng khám/bác sĩ.
* Đặt lịch khám và nhận thông báo.
* Quản lý hồ sơ khám bệnh và đơn thuốc.
* Quản lý thông tin cá nhân.

Ứng dụng bao gồm Web App (cho bệnh nhân, bác sĩ) và Backend API phục vụ toàn bộ chức năng.
  
---

## 3. Quy trình quản lý phạm vi (Scope Management Process)

| Giai đoạn                  | Hoạt động chính                              | Đầu ra                                        |
| -------------------------- | -------------------------------------------- | --------------------------------------------- |
| **3.1. Thu thập yêu cầu**  | Phỏng vấn, khảo sát người dùng & stakeholder | Danh sách yêu cầu nghiệp vụ                   |
| **3.2. Xác định phạm vi**  | Tổng hợp yêu cầu thành chức năng hệ thống    | Tài liệu định nghĩa phạm vi (Scope Statement) |
| **3.3. Tạo WBS**           | Phân rã phạm vi thành các gói công việc      | WBS, từ cấp 1 → cấp 3                         |
| **3.4. Xác minh phạm vi**  | Khách hàng/stakeholder duyệt phạm vi         | Biên bản xác nhận phạm vi                     |
| **3.5. Kiểm soát phạm vi** | Theo dõi thay đổi, so sánh với baseline      | Biểu mẫu đề xuất thay đổi phạm vi (CR Form)   |

---

## 4. WBS Cơ bản (Work Breakdown Structure - Summary)

1. Khởi động dự án
2. Phân tích & thiết kế hệ thống
3. Phát triển frontend/backend
4. Tích hợp hệ thống ngoài: (gửi SMS/email)
5. Kiểm thử và triển khai
6. Đào tạo và hỗ trợ
7. Quản lý dự án

---

## 5. Vai trò và trách nhiệm (Roles and Responsibilities)

| Vai trò                         | Trách nhiệm                                   |
| ------------------------------- | --------------------------------------------- |
| Quản lý dự án                   | Xây dựng, theo dõi và cập nhật phạm vi        |
| Chuyên viên phân tích nghiệp vụ | Thu thập và phân tích yêu cầu                 |
| Nhóm phát triển                 | Thực hiện công việc theo đúng phạm vi đã định |
| Khách hàng/stakeholders         | Duyệt phạm vi và xác nhận kết quả nghiệm thu  |

---

## 6. Quản lý yêu cầu thay đổi phạm vi (Scope Change Control)

* Mọi thay đổi phải được ghi nhận bằng **Change Request Form**.
* Đội dự án sẽ đánh giá ảnh hưởng đến tiến độ, chi phí, chất lượng.
* Các thay đổi chỉ được thực hiện khi có phê duyệt của **Project Sponsor**.

---

## 7. Kết quả bàn giao trong phạm vi (In-Scope Deliverables)

- Web App cho bệnh nhân và bác sĩ
- Hệ thống API quản lý đặt lịch, thông tin người dùng, hồ sơ khám bệnh
- Giao diện quản lý lịch khám
- Tính năng gửi thông báo
- Hệ thống quản trị cơ bản (admin)
- Tài liệu hướng dẫn sử dụng
- Kịch bản kiểm thử và báo cáo kiểm thử

---

## 8. Hạng mục ngoài phạm vi (Out of Scope)

- Thanh toán online
- Tích hợp toàn diện với hệ thống quản lý bệnh viện (HIS)
- Phân tích dữ liệu nâng cao (BI, AI)
- Ứng dụng native mobile (chỉ triển khai responsive web)
- Hỗ trợ đa ngôn ngữ
- Quản lý vật tư, kho dược, thanh toán bảo hiểm y tế

---

## 9. Kiểm soát chất lượng liên quan đến phạm vi

* Tất cả chức năng trong phạm vi sẽ được kiểm thử theo test case đã duyệt.
* Tài liệu nghiệm thu sẽ được đối chiếu với danh sách tính năng đã xác nhận trong phạm vi.

---

## 10. Tài liệu tham chiếu

* Project Charter
* Business Requirement Document (BRD) [Nếu có]
* Functional Specification Document (FSD) [Nếu có]
* WBS chi tiết [Nếu có]
* Biểu mẫu đề xuất thay đổi phạm vi [Nếu có]

