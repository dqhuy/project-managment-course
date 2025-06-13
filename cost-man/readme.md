---

## Slide 1: TIÊU ĐỀ: QUẢN LÝ CHI PHÍ DỰ ÁN CNTT

---

## Slide 2: Mục tiêu chương

Sau khi hoàn thành chương, sinh viên có thể:

- Hiểu rõ vai trò, bản chất và đối tượng chi phí trong dự án CNTT
- Nhận diện được các loại chi phí và mối liên hệ với phạm vi và tiến độ
- Áp dụng quy trình và công cụ để ước lượng, lập ngân sách, kiểm soát chi phí
- Tính toán và diễn giải các chỉ số EVM (Earned Value Management)
- Đề xuất biện pháp điều chỉnh khi có rủi ro vượt chi phí

---

## Slide 3: 1. Giới thiệu Quản lý chi phí

- **Chi phí**: nguồn lực tài chính cần thiết cho các hoạt động, tài nguyên và nhân lực trong dự án
- **Tầm quan trọng**:
  - Dự án CNTT thường bị đánh giá thấp chi phí ban đầu
  - Việc không kiểm soát chi phí dẫn đến phá sản dự án
  - Các bên liên quan luôn quan tâm đến ngân sách và hiệu quả sử dụng
- Gắn kết với các lĩnh vực quản lý khác như phạm vi, tiến độ, nhân lực và chất lượng

---

## Slide 4: 2. Quy trình Quản lý chi phí (PMBOK)

1. **Plan Cost Management**: Lập kế hoạch quản lý chi phí
2. **Estimate Costs**: Ước lượng chi phí chi tiết
3. **Determine Budget**: Tổng hợp ngân sách dự án
4. **Control Costs**: Kiểm soát chi phí thực tế trong quá trình thực hiện

---

## Slide 5: 2.1 Plan Cost Management

- Mục tiêu: Thiết lập các chính sách, quy trình và tài liệu cần thiết để quản lý chi phí
- Đầu ra: **Cost Management Plan** – hướng dẫn chi tiết cách quản lý chi phí trong toàn bộ vòng đời dự án
- Nội dung chính: cách ước lượng, ngân sách, báo cáo, kiểm soát, và cách xử lý dự phòng
- Công cụ: Expert judgment (chuyên gia), Analytical techniques (phân tích), Meetings (họp nhóm)

---

## Slide 6: 2.2 Estimate Costs

- Phân loại chi phí:
  - Trực tiếp: nhân lực, thiết bị
  - Gián tiếp: điện nước, quản lý chung
  - Cố định: phần mềm bản quyền, thuê hạ tầng
  - Biến đổi: theo khối lượng công việc, nhân công
- Phương pháp ước lượng:
  - **Analogous**: Dựa theo dự án tương tự trước đây
  - **Parametric**: Dựa theo đơn giá và thông số kỹ thuật
  - **Bottom-up**: Ước tính từ từng tác vụ nhỏ trong WBS
  - **Three-point estimate**: Ước lượng lạc quan, bi quan, và trung bình (PERT)
- Đầu ra: Bảng ước tính chi phí từng hạng mục

---

## Slide 7: 2.3 Determine Budget

- Tổng hợp ước tính chi phí thành **cost baseline** (đường cơ sở ngân sách)
- Bao gồm các khoản dự phòng:
  - **Contingency reserves**: cho rủi ro đã lường trước (ví dụ: trễ tiến độ, lỗi QA)
  - **Management reserves**: cho các yếu tố bất ngờ, chưa biết
- Ngân sách được phân bổ theo thời gian và mốc tiến độ (time-phased)
- Đầu ra: Tổng ngân sách dự án, kế hoạch dòng tiền

---

## Slide 8: 2.4 Control Costs

- Theo dõi và đối chiếu chi phí thực tế với ngân sách
- Phân tích nguyên nhân chênh lệch và đề xuất xử lý
- Áp dụng **Earned Value Management (EVM)** để kiểm soát hiệu suất chi phí và tiến độ
- Các công việc:
  - Đo lường chi phí định kỳ
  - Cập nhật chỉ số EV, AC, PV
  - Đề xuất điều chỉnh kế hoạch, báo cáo các bên liên quan

---

## Slide 9: 3. Earned Value Management (EVM)

- Ba chỉ số cơ bản:
  - **Planned Value (PV)**: giá trị theo kế hoạch tại thời điểm hiện tại
  - **Earned Value (EV)**: giá trị công việc đã hoàn thành thực tế
  - **Actual Cost (AC)**: chi phí đã chi trả thực tế

**Cách tính toán minh họa:**

Giả sử bảng ước lượng chi phí theo WBS như sau:

| Hạng mục           | Tổng chi phí (triệu VND) | % Hoàn thành | Thời gian dự kiến | Ghi chú |
|--------------------|--------------------------|---------------|-------------------|---------|
| Phân tích yêu cầu  | 100                      | 100%          | Tháng 1           | Done    |
| Thiết kế UI/UX     | 150                      | 100%          | Tháng 1-2         | Done    |
| Phát triển Backend | 300                      | 80%           | Tháng 2-4         | Đang làm|
| API Gateway        | 100                      | 50%           | Tháng 3           | Đang làm|
| Kiểm thử           | 150                      | 0%            | Tháng 4           | Chưa bắt đầu |
| Triển khai         | 100                      | 0%            | Tháng 5           | Chưa bắt đầu |

**Tính tại thời điểm cuối tháng 3:**

- **PV (Planned Value)**: Tổng giá trị công việc lẽ ra hoàn thành đến cuối tháng 3 = 100 (Yêu cầu) + 150 (UI/UX) + 200 (2/3 Backend) + 100 (API) = **550 triệu VND**
- **EV (Earned Value)**: Tổng giá trị phần trăm hoàn thành thực tế = 100 + 150 + 240 (80% của 300) + 50 (50% của 100) = **540 triệu VND**
- **AC (Actual Cost)**: Tổng chi phí đã chi đến nay (ví dụ theo báo cáo kế toán) = **600 triệu VND**

⇒ **CPI = EV / AC = 540 / 600 = 0.90** (hiệu suất chi phí kém)
⇒ **CV = EV – AC = -60 triệu** (vượt ngân sách)
⇒ **SV = EV – PV = -10 triệu** (chậm tiến độ nhẹ)

- Các chỉ số hiệu suất:
  - **Cost Performance Index (CPI)** = EV / AC → nếu <1: hiệu suất kém
  - **Schedule Performance Index (SPI)** = EV / PV

---

## Slide 10: Dự báo chi phí và hiệu suất

- **EAC (Estimate at Completion)**:
  - EAC = BAC / CPI → nếu hiệu suất chi phí không đổi
  - EAC = AC + ETC → tính khi biết phần còn lại cụ thể
- **ETC (Estimate to Complete)** = EAC - AC
- **VAC (Variance at Completion)** = BAC - EAC
- Biểu đồ: EVM timeline (trục thời gian, chi phí kế hoạch, chi phí thực tế, giá trị đạt được)

---

## Slide 11: 4. Công cụ và phần mềm

- **Excel template**: tạo bảng chi phí, tính EVM, biểu đồ động
- **Microsoft Project**: tích hợp chi phí vào WBS, biểu đồ Gantt
- **ERP / Primavera**: hệ thống chuyên nghiệp cho dự án lớn, nhiều phòng ban
- **Phần mềm kế toán tích hợp**: kiểm soát dòng tiền, báo cáo tài chính song song

---

## Slide 12: 5. Case study: Healthcare Booking App

- Dựa vào WBS đã có: chia chi phí cho các hạng mục như UI/UX, Backend, API, Testing, Deployment
- Budget: 900M VND, bao gồm contingency (10%) và reserve (5%)
- Sau 3 tháng triển khai:
  - **PV = 550M** (kế hoạch đến tháng 3)
  - **EV = 540M** (công việc hoàn thành thực tế)
  - **AC = 600M** (đã chi vượt)
  - CV = -60M → vượt chi phí, CPI = 0.90 → hiệu suất thấp
  - EAC ≈ 1,000M → vượt ngân sách dự kiến ~100M
- Cần phân tích nguyên nhân và đề xuất hành động sớm

---

## Slide 13: 6. Điều chỉnh & đề xuất

- Xem xét cắt giảm các hạng mục không thiết yếu: ví dụ bỏ chức năng chat nội bộ
- Tối ưu hóa nhân sự, outsource phần không cốt lõi
- Tự động hóa kiểm thử (QA automation)
- Xây dựng quy trình kiểm soát sử dụng reserve chặt chẽ
- Đánh giá lại giả định ban đầu về đơn giá nhân công và rủi ro kỹ thuật

---

## Slide 14: 7. Tổng kết

- Quản lý chi phí là yếu tố then chốt quyết định sự thành công hoặc thất bại của dự án
- Kỹ năng ước lượng, lập ngân sách và theo dõi hiệu suất chi phí cần thiết cho PM
- Áp dụng EVM giúp đánh giá dự án một cách định lượng, phát hiện sớm vấn đề vượt chi phí
- Cần sự phối hợp liên tục giữa các bộ phận để đảm bảo kiểm soát chi phí hiệu quả

---

## Slide 15: Thảo luận & Bài tập

- Tính toán EVM với bộ dữ liệu PV/EV/AC khác nhau, trình bày kết quả
- Lập cost baseline từ WBS cụ thể, xây dựng bảng ngân sách theo tháng
- Mô phỏng cuộc họp dự án: sinh viên đóng vai Project Manager, QA, CFO để giải quyết vấn đề vượt chi phí
- Thảo luận: Vì sao các dự án CNTT thường bị vượt ngân sách? Vai trò của communication?

