
## 1. Danh sách Vai trò / Nhân sự

| Vai trò                  | Mô tả nhiệm vụ chính                                         |
| ------------------------ | ------------------------------------------------------------ |
| **PM** (Project Manager) | Lập kế hoạch, điều phối, giám sát tiến độ và nhân sự         |
| **PO** (Product Owner)   | Thu thập yêu cầu, làm việc với khách hàng và người dùng cuối |
| **Tech Lead**            | Thiết kế kiến trúc, hỗ trợ kỹ thuật cho nhóm dev             |
| **Developer**            | Phát triển frontend và backend ứng dụng                      |
| **UI/UX Designer**       | Thiết kế giao diện người dùng                                |
| **Tester**               | Viết test case, kiểm thử hệ thống                            |

---

## 2. Bảng Ma trận RACI

| **Gói công việc**                         | **PM** | **Tech Lead** | **Developer** | **UI/UX Designer** | **Tester** | **Product Owner** |
| ----------------------------------------- | ------ | ------------- | ------------- | ------------------ | ---------- | ----------------- |
| Phân tích yêu cầu người dùng              | A      | C             |               |                    |            | R                 |
| Thiết kế giao diện người dùng             | C      |               |               | R/A                |            | C                 |
| Phát triển API đặt lịch                   | C      | A             | R             |                    |            | C                 |
| Phát triển frontend                       | C      | C             | R             |                    |            | A                 |
| Tích hợp với hệ thống bệnh viện           | A      | R             | R             |                    |            | C                 |
| Kiểm thử tính năng                        | C      | C             | C             |                    | R/A        |                   |
| Hướng dẫn sử dụng cho nhân viên bệnh viện | A      |               |               |                    |            | C                 |
| Thu thập phản hồi & cải tiến              | R      | C             |               |                    | C          | A                 |

---

## 3. Bảng Ma trận RAM (Responsibility Assignment Matrix)

| **WBS ID** | **Gói công việc**                        | **PM** | **Tech Lead** | **Developer** | **UI/UX Designer** | **Tester** | **PO** |
| ---------- | ---------------------------------------- | ------ | ------------- | ------------- | ------------------ | ---------- | ------ |
| 1.1        | Phân tích yêu cầu                        | R/A    | C             |               |                    |            | R      |
| 1.2        | Lập kế hoạch dự án                       | A      | C             |               |                    |            | C      |
| 1.3        | Thiết kế giao diện                       | C      |               |               | R/A                |            | C      |
| 1.4        | Thiết kế kiến trúc hệ thống              | C      | R/A           | C             |                    |            |        |
| 2.1        | Phát triển frontend                      | C      | C             | R             |                    |            | A      |
| 2.2        | Phát triển backend                       | C      | A             | R             |                    |            |        |
| 2.3        | Tích hợp hệ thống quản lý lịch bệnh viện | A      | R             | R             |                    |            | C      |
| 3.1        | Kiểm thử chức năng                       | C      | C             | C             |                    | R/A        |        |
| 3.2        | Kiểm thử giao diện                       | C      |               |               |                    | R/A        | C      |
| 4.1        | Triển khai hệ thống                      | A      | R             | R             |                    | C          | C      |
| 4.2        | Hướng dẫn sử dụng cho nhân viên          | R/A    |               |               |                    |            | C      |
| 5.1        | Thu thập phản hồi người dùng & cải tiến  | R      | C             |               |                    | C          | A      |

---

## 4. Ghi chú

* **PM (Project Manager)**: người điều phối tổng thể, có trách nhiệm chính trong việc lập kế hoạch, triển khai và báo cáo tiến độ.
* **PO (Product Owner)**: đại diện cho khách hàng/bệnh viện, chịu trách nhiệm chính với phần yêu cầu và phản hồi.
* **RACI vs RAM**:

  * **RACI** tập trung vào mối quan hệ trách nhiệm giữa các cá nhân và công việc.
  * **RAM** gắn trực tiếp với **WBS** – dùng để phân công nguồn lực cụ thể cho từng gói công việc.

