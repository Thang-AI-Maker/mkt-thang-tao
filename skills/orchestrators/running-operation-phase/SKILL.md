---
name: running-operation-phase
description: vận hành và tối ưu Marketing Growth OS qua tài liệu 15 KPI Dashboard & Reporting, lặp theo tuần/tháng/quý và phản hồi ngược về 04 (baseline) và 09 (chiến lược). dùng khi người dùng muốn thiết lập vòng vận hành đo lường - báo cáo - tối ưu, chạy review định kỳ, cập nhật baseline, hoặc "làm phần đo lường và tối ưu liên tục". không dùng khi chỉ cần một mẫu báo cáo đơn lẻ (gọi thẳng skill 15) hay chưa có chiến lược và baseline.
---

# Operation Runner (A5)
Điều phối giai đoạn vận hành: chạy 15 theo vòng tuần/tháng/quý, phản hồi ngược về 04 và 09. Đối tượng dùng: thương hiệu đã triển khai, cần vận hành liên tục.

## Nguyên tắc cốt lõi
Vận hành là **vòng lặp**, không phải tài liệu một lần: đo → báo cáo → tối ưu → cập nhật baseline (04) và chiến lược (09). Mỗi báo cáo kết bằng hành động + người + deadline.

## Kế thừa & điều kiện vào
Bắt buộc 04 (baseline), 09 (mục tiêu), 13 (người phụ trách). Thiếu 04 → KPI vô nghĩa; dừng, yêu cầu 04.

## Quy trình
### Giai đoạn 1 — Thiết lập khung KPI
Nạp 04, 09, 10, 11, 13. Chạy building-kpi-dashboard-reporting → khung KPI 6 thành phần.
### Giai đoạn 2 — Vòng tuần/tháng
Chạy mẫu báo cáo; phân loại nội dung Scale/Repurpose/Improve/Retest/Stop; giao hành động có người + deadline.
### Giai đoạn 3 — Review quý & phản hồi
Tổng hợp quý; cập nhật **baseline mới về 04**; đề xuất **điều chỉnh chiến lược về 09**.
### Giai đoạn 4 — Bàn giao vòng lặp
Xuất khung KPI + lịch báo cáo định kỳ (gợi ý đặt lịch tự động tuần/tháng).

## Cấu trúc kết quả
1. Khung KPI (6 thành phần). 2. Mẫu báo cáo tuần/tháng đã điền quy trình. 3. Kế hoạch review quý + điểm phản hồi về 04, 09.

## Checklist chất lượng
- [ ] Có baseline (04) và mục tiêu (09) trước khi bắt đầu.
- [ ] KPI đủ 6 thành phần.
- [ ] Báo cáo kết bằng hành động + người + deadline.
- [ ] Có vòng phản hồi cập nhật 04 và 09.

## Tình huống đặc biệt
### Trường hợp — Chưa gắn tracking
**Cách xử lý:** ưu tiên kế hoạch gắn GA4/Pixel/CRM; khung KPI để `[CẦN BỔ SUNG]` baseline.
### Trường hợp — Muốn tự động hóa báo cáo định kỳ
**Cách xử lý:** đề xuất đặt lịch chạy báo cáo tuần/tháng.

## Anti-Patterns
- Không chạy KPI khi thiếu baseline.
- Không để báo cáo chỉ liệt kê số.
- Không quên phản hồi về 04/09.

## Recovery
### Khi thiếu baseline/công cụ
Xuất kế hoạch gắn tracking; hoãn báo cáo tới khi có số.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Thiết lập đo lường và tối ưu marketing liên tục."
**Có kích hoạt:** Có.
### Test 2 — Không nên kích hoạt
**Prompt:** "Cho tôi một mẫu báo cáo tuần."
**Có kích hoạt:** Không (gọi thẳng 15).
### Test 3 — Điều kiện vào thiếu
**Prompt:** "Chạy operation" (chưa có baseline 04).
**Hành vi:** dừng, yêu cầu 04.
