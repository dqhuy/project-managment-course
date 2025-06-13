# Ước lượng chi phí - Estimate Costs

| WBS Code | Task                      | Loại chi phí        | Ước lượng (₫) | Phương pháp           |
| -------- | ------------------------- | ------------------- | ------------- | --------------------- |
| 1.1      | Project Management        | Nhân công           | 80.000.000    | Bottom‑up             |
| 2.1      | UI/UX Design              | Nhân công + Công cụ | 50.000.000    | Bottom‑up + Analogous |
| 3.1      | Front‑end Development     | Nhân công           | 200.000.000   | Bottom‑up             |
| 3.2      | Back‑end Development      | Nhân công           | 250.000.000   | Bottom‑up             |
| 3.3      | Testing & QA              | Nhân công + License | 100.000.000   | Bottom‑up + Analogous |
| 4.1      | Deployment & Infra (AWS)  | Hạ tầng / Công cụ   | 70.000.000    | Analogous             |
| 5.1      | Contingency Reserve (10%) | Dự phòng            | 75.000.000    | % của tổng chi phí    |
|          | Tổng cộng                 |                     | 900.000.000   |                        |

---

**Tổng ước tính**: 825.000.000 ₫ + Dự phòng 75.000.000 ₫ = 900.000.000 ₫

# Phân bổ chi phí - Determine Budget
- Cost Baseline: 825.000.000 ₫
- Total Budget (with reserve): 900.000.000 ₫
- Phân bổ theo thời gian (giả sử dự án 6 tháng):
    Tháng 1: 150M
    Tháng 2: 200M
    Tháng 3: 200M
    Tháng 4: 150M
    Tháng 5: 150M
    Tháng 6: 50M

# Giám sát chi phí - Cost Control – Earned Value Management (EVM)
**Giả sử sau 3 tháng:**
- PV (planned value): 550M ₫
- AC (actual cost): 600M ₫
- EV (earned value): công việc hoàn thành đáng ra chi 500M ₫

**Tính toán:**

- CV = EV − AC = 500 − 600 = –100M ₫ → Over budget

- SV = EV − PV = 500 − 550 = –50M ₫ → Lỡ tiến độ

- CPI = EV / AC = 0.83

- SPI = EV / PV = 0.91

**Dự báo tại thời điểm hoàn tất:**

- EAC ≈ BAC / CPI = 825 / 0.83 ≈ 994M ₫

- ETC = EAC – AC = 994 – 600 = 394M ₫

**Phân tích:**

- Project đang vượt chi phí và chậm tiến độ.
