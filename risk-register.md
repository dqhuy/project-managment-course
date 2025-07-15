# Mục đích của Risk Register:
- Ghi nhận mọi rủi ro đã được nhận diện.
- Ghi rõ mức độ nghiêm trọng (xác suất, tác động).
- Ghi lại kế hoạch ứng phó rủi ro.
-Theo dõi trạng thái xử lý rủi ro trong suốt vòng đời dự án.

# Cấu trúc của Risk Register (Có thể thay đổi tùy thuộc doanh nghiệp)

| Cột                       | Ý nghĩa                                              |
| ------------------------- | ---------------------------------------------------- |
| Mã rủi ro (Risk ID)       | Mã định danh duy nhất cho từng rủi ro                |
| Mô tả rủi ro              | Nội dung ngắn gọn mô tả rủi ro                       |
| Nguyên nhân (Cause)       | Tại sao rủi ro này có thể xảy ra                     |
| Hậu quả (Impact)          | Nếu xảy ra thì điều gì sẽ ảnh hưởng tới dự án        |
| Xác suất (Probability)    | Đánh giá khả năng xảy ra (1–5 hoặc %)                |
| Tác động (Impact Level)   | Mức độ ảnh hưởng nếu xảy ra (1–5)                    |
| Mức ưu tiên (Risk Score)  | Tính theo công thức: `P x I`                         |
| Chiến lược ứng phó        | Avoid, Mitigate, Transfer, Accept,...                |
| Kế hoạch hành động cụ thể | Biện pháp xử lý được đề xuất                         |
| Người phụ trách (Owner)   | Ai chịu trách nhiệm theo dõi và phản ứng             |
| Trạng thái (Status)       | Open / Monitoring / Mitigated / Occurred / Closed... |

# Ví dụ
| ID  | Rủi ro                                                   | Nguyên nhân                                      | Hậu quả                                              | Xác suất (P) | Tác động (I) | Risk Score | Mức ưu tiên | Chiến lược | Biện pháp cụ thể                                                           | Người phụ trách | Trạng thái |
| --- | -------------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------- | ------------ | ------------ | ---------- | ----------- | ---------- | -------------------------------------------------------------------------- | --------------- | ---------- |
| R01 | Yêu cầu thay đổi liên tục từ phía bệnh viện              | Phạm vi ban đầu không rõ ràng                    | Phát sinh chi phí, trễ tiến độ                       | 5            | 4            | 20         | Cao         | Mitigate   | Tổ chức workshop xác định yêu cầu rõ ràng; quản lý thay đổi theo quy trình | BA (Phương)     | Open       |
| R02 | Nhân sự dev backend thiếu kinh nghiệm với chuẩn HL7/FHIR | Công nghệ mới với team                           | Chậm tiến độ, chất lượng thấp                        | 4            | 4            | 16         | Cao         | Mitigate   | Đào tạo nội bộ và mời chuyên gia tư vấn chuẩn dữ liệu y tế                 | Dev lead (Tuấn) | Open       |
| R03 | Chất lượng video call không ổn định                      | Phụ thuộc WebRTC và kết nối Internet             | Trải nghiệm người dùng kém                           | 3            | 4            | 12         | Trung bình  | Mitigate   | Dùng server media relay, kiểm thử kỹ thuật mạng ở nhiều vùng               | DevOps (Hải)    | Open       |
| R04 | Bác sĩ không quen dùng giao diện quản trị                | Đối tượng người dùng lớn tuổi, ít dùng công nghệ | Không dùng hệ thống, thất bại triển khai             | 3            | 5            | 15         | Cao         | Mitigate   | Tổ chức đào tạo trực tiếp + làm video hướng dẫn ngắn                       | PM (Dũng)       | Open       |
| R05 | Tích hợp cổng thanh toán gặp lỗi                         | API nhà cung cấp thanh toán thay đổi             | Không thể thanh toán → gián đoạn quy trình khám bệnh | 2            | 5            | 10         | Trung bình  | Transfer   | Ký hợp đồng SLA với nhà cung cấp; test kỹ ở môi trường staging             | Dev (Trung)     | Open       |
| R06 | Trễ deadline do Tết Nguyên đán                           | Đội dev nghỉ dài, giảm năng suất làm việc        | Trễ milestone tháng 2                                | 3            | 3            | 9          | Trung bình  | Accept     | Lập kế hoạch buffer thời gian trước và sau Tết                             | PM (Dũng)       | Monitoring |
| R07 | Rò rỉ thông tin bệnh nhân                                | Lỗ hổng bảo mật hoặc cấu hình phân quyền sai     | Vi phạm luật dữ liệu y tế, ảnh hưởng nghiêm trọng    | 2            | 5            | 10         | Trung bình  | Transfer   | Kiểm thử bảo mật + thuê pen-test; mã hóa dữ liệu nhạy cảm                  | QA Lead (Hương) | Open       |
| R08 | Thiếu phản hồi nhanh từ phía bệnh viện                   | Bệnh viện không có người theo sát dự án          | Delay test UAT, trễ triển khai                       | 3            | 3            | 9          | Trung bình  | Mitigate   | Chỉ định đầu mối liên lạc chuyên trách từ phía bệnh viện                   | PM (Dũng)       | Open       |
