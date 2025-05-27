# Kế hoạch quản lý dự án: Ứng dụng đặt lịch khám bệnh

## 1. Tổng quan dự án
- **Tên dự án**: Ứng dụng đặt lịch khám bệnh (HealthCare Booking App).
- **Mục tiêu**: Phát triển ứng dụng di động và web cho phép bệnh nhân đặt lịch khám tại bệnh viện, bác sĩ quản lý lịch hẹn, và bệnh viện theo dõi thông tin bệnh nhân.
- **Thời gian dự kiến**: 6 tháng (từ 01/06/2025 đến 30/11/2025).
- **Ngân sách ước tính**: 500 triệu VND (bao gồm nhân sự, phần cứng, phần mềm).
- **Các bên liên quan**:
  - Khách hàng: Bệnh viện XYZ.
  - Đội dự án: Quản lý dự án (PM), lập trình viên, thiết kế UI/UX, chuyên gia bảo mật, kiểm thử (QA).
  - Nhà cung cấp: Dịch vụ gửi SMS/Email, cổng xác thực OTP.

## 2. Phạm vi dự án
Dựa trên yêu cầu đã cung cấp, phạm vi bao gồm:
- **Yêu cầu chức năng**:
  - Đăng ký/đăng nhập bệnh nhân (xác thực OTP qua số điện thoại).
  - Tìm kiếm bác sĩ theo chuyên khoa, bệnh viện, hoặc lịch trống.
  - Đặt lịch khám: Chọn khung giờ, nhận xác nhận qua email/SMS.
  - Nhắc nhở: Gửi thông báo trước 24 giờ về lịch hẹn.
  - Hồ sơ y tế: Lưu trữ lịch sử khám bệnh.
  - Bảng quản trị cho bệnh viện: Quản lý lịch bác sĩ, thông tin bệnh nhân.
- **Yêu cầu phi chức năng**:
  - Giao diện thân thiện, dễ sử dụng cho người lớn tuổi.
  - Bảo mật thông tin y tế theo chuẩn HIPAA.
  - Hỗ trợ ngôn ngữ: Tiếng Việt và tiếng Anh.
  - Ứng dụng chạy trên iOS, Android, và web.
- **Loại trừ**: Không bao gồm tích hợp với thiết bị y tế hoặc thanh toán trực tuyến.

## 3. Các giai đoạn quản lý dự án

### 3.1. Khởi đầu (01/06/2025 - 07/06/2025)
- **Mục tiêu**: Xác định mục tiêu, phạm vi, và thành lập đội dự án.
- **Hoạt động**:
  - Họp khởi động với bệnh viện XYZ để xác nhận yêu cầu.
  - Lập điều lệ dự án (Project Charter).
  - Tuyển chọn đội dự án: 1 PM, 2 lập trình viên mobile, 1 lập trình viên web, 1 thiết kế UI/UX, 1 chuyên gia bảo mật, 1 QA.
- **Sản phẩm**:
  - Điều lệ dự án (Project Charter).
  - Danh sách các bên liên quan (Stakeholder Register).

### 3.2. Lập kế hoạch (08/06/2025 - 21/06/2025)
- **Mục tiêu**: Lập kế hoạch chi tiết, phân bổ nguồn lực, và xác định rủi ro.
- **Hoạt động**:
  - Phân tích yêu cầu chi tiết với bệnh viện XYZ.
  - Xây dựng **Cấu trúc phân rã công việc (WBS)**:
    - Giai đoạn 1: Phân tích yêu cầu.
    - Giai đoạn 2: Thiết kế UI/UX và database.
    - Giai đoạn 3: Phát triển backend (API, xác thực OTP, quản lý lịch).
    - Giai đoạn 4: Phát triển frontend (mobile, web).
    - Giai đoạn 5: Kiểm thử và triển khai.
  - Lập lịch trình bằng **biểu đồ Gantt** (sử dụng MS Project hoặc Trello).
  - Phân bổ nguồn lực: Gán nhiệm vụ cho từng thành viên.
  - Xây dựng **ma trận rủi ro**:
    - Rủi ro 1: Lỗi bảo mật dữ liệu (Xác suất: Trung bình, Tác động: Cao, Giải pháp: Áp dụng mã hóa AES-256, kiểm tra bảo mật định kỳ).
    - Rủi ro 2: Chậm tiến độ do thay đổi yêu cầu (Xác suất: Cao, Tác động: Trung bình, Giải pháp: Sử dụng Agile, họp định kỳ với khách hàng).
    - Rủi ro 3: Lỗi tích hợp SMS/Email (Xác suất: Thấp, Tác động: Trung bình, Giải pháp: Kiểm thử tích hợp sớm).
- **Sản phẩm**:
  - Tài liệu yêu cầu phần mềm (SRS).
  - Biểu đồ Gantt.
  - Ma trận quản lý rủi ro.
  - Kế hoạch nguồn lực.

### 3.3. Thực hiện (22/06/2025 - 15/10/2025)
- **Mục tiêu**: Phát triển ứng dụng theo yêu cầu, sử dụng mô hình Agile.
- **Hoạt động**:
  - **Sprint 1 (2 tuần)**: Thiết kế UI/UX (giao diện tìm kiếm bác sĩ, đặt lịch).
    - Sản phẩm: Mockup giao diện, được khách hàng phê duyệt.
  - **Sprint 2 (2 tuần)**: Phát triển backend (API đăng nhập, xác thực OTP).
    - Sản phẩm: API hoàn chỉnh, kiểm thử đơn vị.
  - **Sprint 3 (2 tuần)**: Phát triển module đặt lịch và gửi thông báo.
    - Sản phẩm: Chức năng đặt lịch, tích hợp SMS/Email.
  - **Sprint 4 (2 tuần)**: Phát triển frontend mobile (iOS, Android).
    - Sản phẩm: Ứng dụng mobile cơ bản.
  - **Sprint 5 (2 tuần)**: Phát triển frontend web và bảng quản trị.
    - Sản phẩm: Website và bảng quản trị.
  - Họp đánh giá sprint hàng tuần với khách hàng để lấy phản hồi.
  - Sử dụng Jira để quản lý công việc và theo dõi tiến độ.
- **Sản phẩm**:
  - Mã nguồn (lưu trên GitHub).
  - Báo cáo tiến độ hàng tuần.
  - Phản hồi khách hàng sau mỗi sprint.

### 3.4. Kiểm soát (16/10/2025 - 31/10/2025)
- **Mục tiêu**: Đảm bảo chất lượng và tiến độ dự án.
- **Hoạt động**:
  - Kiểm thử:
    - Kiểm thử chức năng: Đảm bảo tất cả chức năng (đặt lịch, thông báo, quản trị) hoạt động đúng.
    - Kiểm thử bảo mật: Kiểm tra lỗ hổng SQL Injection, XSS.
    - Kiểm thử hiệu năng: Đáp ứng 1.000 người dùng đồng thời.
    - Kiểm thử khả năng sử dụng: Đánh giá giao diện với nhóm người dùng lớn tuổi.
  - Sửa lỗi và tối ưu hóa dựa trên kết quả kiểm thử.
  - Theo dõi tiến độ: So sánh tiến độ thực tế với biểu đồ Gantt, điều chỉnh nếu cần.
  - Quản lý thay đổi: Nếu khách hàng yêu cầu thêm chức năng (ví dụ: hỗ trợ thêm ngôn ngữ), đánh giá tác động đến tiến độ và ngân sách.
- **Sản phẩm**:
  - Báo cáo kiểm thử.
  - Nhật ký thay đổi (Change Log).
  - Phiên bản ứng dụng beta.

### 3.5. Kết thúc (01/11/2025 - 30/11/2025)
- **Mục tiêu**: Triển khai ứng dụng và bàn giao cho khách hàng.
- **Hoạt động**:
  - Triển khai ứng dụng lên App Store, Google Play, và máy chủ web.
  - Đào tạo nhân viên bệnh viện sử dụng bảng quản trị.
  - Bàn giao tài liệu: Hướng dẫn sử dụng, tài liệu kỹ thuật, mã nguồn.
  - Họp đánh giá dự án với khách hàng và đội dự án.
  - Đóng dự án: Lưu trữ tài liệu, giải phóng nguồn lực.
- **Sản phẩm**:
  - Ứng dụng hoàn thiện.
  - Tài liệu bàn giao.
  - Báo cáo tổng kết dự án.

## 4. Ngân sách và nguồn lực
- **Nhân sự**:
  - Quản lý dự án: 1 người (20 triệu/tháng).
  - Lập trình viên: 3 người (15 triệu/tháng/người).
  - Thiết kế UI/UX: 1 người (15 triệu/tháng).
  - Chuyên gia bảo mật: 1 người (20 triệu/tháng).
  - Kiểm thử: 1 người (12 triệu/tháng).
- **Phần mềm**: Jira (quản lý công việc), Figma (thiết kế UI/UX), AWS (máy chủ).
- **Phần cứng**: Máy chủ thuê (10 triệu/tháng).
- **Tổng chi phí**: ~500 triệu VND.

## 5. Công cụ quản lý dự án
- **Quản lý công việc**: Jira, Trello.
- **Theo dõi tiến độ**: MS Project (biểu đồ Gantt).
- **Giao tiếp**: Slack, Google Meet.
- **Lưu trữ mã nguồn**: GitHub.
- **Kiểm thử**: Postman (API), Selenium (web).

## 6. Ma trận rủi ro
| **Rủi ro**                     | **Xác suất** | **Tác động** | **Giải pháp giảm thiểu**                          |
|--------------------------------|--------------|--------------|--------------------------------------------------|
| Lỗi bảo mật dữ liệu            | Trung bình   | Cao          | Mã hóa AES-256, kiểm tra bảo mật định kỳ         |
| Chậm tiến độ do thay đổi yêu cầu | Cao          | Trung bình   | Sử dụng Agile, họp định kỳ với khách hàng        |
| Lỗi tích hợp SMS/Email         | Thấp         | Trung bình   | Kiểm thử tích hợp sớm, dự phòng nhà cung cấp     |
| Giao diện không thân thiện     | Trung bình   | Trung bình   | Kiểm thử khả năng sử dụng với người lớn tuổi     |

## 7. Biểu đồ Gantt (Mô tả)
- **Tháng 1**: Khởi đầu, lập kế hoạch (2 tuần).
- **Tháng 2-4**: Phát triển (12 tuần, 5 sprint).
- **Tháng 5**: Kiểm thử, tối ưu hóa (2 tuần).
- **Tháng 6**: Triển khai, bàn giao (4 tuần).

## 8. Đánh giá thành công
- Ứng dụng triển khai đúng hạn (30/11/2025).
- Đáp ứng 100% yêu cầu chức năng và phi chức năng.
- Khách hàng hài lòng (đánh giá ≥ 8/10).
- Không vượt ngân sách.
