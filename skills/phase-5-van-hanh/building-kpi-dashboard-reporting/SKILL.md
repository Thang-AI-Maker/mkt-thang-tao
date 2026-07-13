---
name: building-kpi-dashboard-reporting
description: dựng khung KPI mà mỗi chỉ số đủ 6 thành phần (baseline, target, nguồn, người chịu trách nhiệm, ngưỡng cảnh báo, hành động), báo cáo tuần/tháng kết bằng nhận định→giả thuyết→hành động→người→deadline, và phân loại nội dung Scale/Repurpose/Improve/Retest/Stop. không đo thì không tối ưu. dùng khi người dùng muốn làm KPI dashboard, khung đo lường, báo cáo marketing tuần/tháng, quy trình tối ưu, review quý, phân loại nội dung nên scale hay dừng, kể cả khi chỉ yêu cầu một phần như "mẫu báo cáo marketing tuần". không dùng cho chiến lược, funnel design, hay lập lịch content.
---

# KPI Dashboard & Reporting
Thực hiện tài liệu số 15 của Marketing Growth OS: không đo thì không tối ưu, và mọi tranh luận sẽ dựa trên cảm giác. Đối tượng đọc: trưởng marketing, BOD, người vận hành số.

## Nguyên tắc cốt lõi
Mỗi KPI phải đủ **6 thành phần** (baseline, target, nguồn, người chịu trách nhiệm, ngưỡng cảnh báo, hành động) — **thiếu 1 là KPI không hợp lệ**. Báo cáo **cấm chỉ liệt kê số**, phải kết bằng: nhận định → giả thuyết → hành động → người làm → deadline.

## Đặc tả kết quả
- Định dạng: Markdown, bảng KPI + mẫu báo cáo.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: trưởng marketing, BOD.
- Phạm vi: khung KPI + báo cáo tuần/tháng + quy trình tối ưu + review quý.
- Giọng điệu: dựa số, kết bằng hành động.
- Quy tắc nguồn: baseline lấy từ 04; target từ 09; số vận hành từ công cụ thật (GA4/Pixel/CRM/Sheet). Thiếu công cụ → `[CẦN BỔ SUNG]`.
- File đầu ra: `15-kpi-dashboard-reporting.md`.
- Tuyệt đối không được tự bịa: số thực tế, baseline, kết quả chiến dịch.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần 04 (baseline), 09 (mục tiêu SMART), 10 (chỉ số từng giai đoạn phễu), 11 (KPI kênh), 13 (mốc, người phụ trách). Thiếu 04 → không có baseline, KPI vô nghĩa.

## Quy trình

### Giai đoạn 1 — Thu thập công cụ & baseline
**Đầu vào bắt buộc:** công cụ đang có (GA4, Pixel, CRM, Sheet); ai cập nhật số; baseline từ 04; BOD muốn xem gì.
**Đầu vào tùy chọn:** tần suất báo cáo, định dạng BOD thích, ngưỡng chấp nhận.
**Mặc định:** thiếu công cụ đo → ghi `[CẦN BỔ SUNG]` và đề xuất cách gắn tracking tối thiểu; không bịa số.
**Thực hiện:** đọc 04/09/10/11/13; hỏi tối đa 5 câu (công cụ đo nào đang có, ai nhập số, BOD quan tâm chỉ số gì, tần suất báo cáo, baseline đã chốt chưa).
**Điều kiện hoàn thành:** có baseline (04) + mục tiêu (09) + ít nhất một nguồn số thật.

### Giai đoạn 2 — Dựng khung KPI 6 thành phần
1. Mỗi KPI ghi đủ: baseline / target / nguồn / người chịu trách nhiệm / ngưỡng cảnh báo / hành động khi vượt ngưỡng.
2. KPI thiếu bất kỳ thành phần nào → đánh dấu **không hợp lệ**, bổ sung hoặc loại.
3. Gắn KPI vào từng giai đoạn phễu (10) và kênh (11).

### Giai đoạn 3 — Mẫu báo cáo & quy trình tối ưu
1. Mẫu báo cáo tuần/tháng: mỗi mục kết bằng **nhận định → giả thuyết → hành động → người → deadline**.
2. **Phân loại nội dung:** Scale / Repurpose / Improve / Retest / Stop — mỗi loại có tiêu chí số.
3. Quy trình review quý: phản hồi ngược về 04 (baseline mới) và 09 (điều chỉnh chiến lược).

### Giai đoạn 4 — Kiểm tra và sửa
1. Mọi KPI đủ 6 thành phần? Báo cáo có kết bằng hành động + người + deadline? Có phân loại Scale/Stop?
2. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `15-kpi-dashboard-reporting.md`. Đây là vòng lặp: chạy tuần/tháng/quý, phản hồi về 04 và 09.

## Cấu trúc kết quả
1. Khung KPI (mỗi KPI 6 thành phần). 2. Mẫu báo cáo tuần. 3. Mẫu báo cáo tháng. 4. Bảng phân loại nội dung Scale/Repurpose/Improve/Retest/Stop. 5. Quy trình review quý (phản hồi về 04, 09).

## Checklist chất lượng
- [ ] Mỗi KPI đủ 6 thành phần; KPI thiếu bị đánh dấu không hợp lệ.
- [ ] Baseline lấy từ 04, target từ 09.
- [ ] Mẫu báo cáo kết bằng nhận định → giả thuyết → hành động → người → deadline.
- [ ] Có phân loại nội dung với tiêu chí số.
- [ ] Không có số thực tế bịa ra.
- [ ] Có vòng phản hồi về 04 và 09.

## Tình huống đặc biệt
### Trường hợp — Chưa gắn tracking, không có số
**Cách xử lý:** ưu tiên kế hoạch gắn GA4/Pixel/CRM tối thiểu; khung KPI để trống baseline với `[CẦN BỔ SUNG]`.
**Không được:** bịa baseline để lấp bảng.
### Trường hợp — Báo cáo chỉ toàn số, không hành động
**Cách phát hiện:** người dùng đưa mẫu liệt kê số.
**Cách xử lý:** viết lại theo cấu trúc kết-bằng-hành-động.
**Không được:** giữ báo cáo mô tả suông.

## Anti-Patterns
- Không tạo KPI thiếu 6 thành phần.
- Không viết báo cáo chỉ liệt kê số.
- Không bịa baseline/kết quả.
- Không bỏ vòng phản hồi về 04/09.

## Recovery
### Khi thiếu công cụ đo
Xuất kế hoạch gắn tracking + khung KPI rỗng; hẹn chạy báo cáo khi có số.
### Khi validation thất bại
KPI không hợp lệ → bổ sung thành phần thiếu hoặc loại.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Dựng khung KPI và mẫu báo cáo marketing tháng."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Cho tôi mẫu báo cáo marketing tuần."
**Có kích hoạt:** Có (kết bằng hành động).
### Test 3 — Không nên kích hoạt
**Prompt:** "Đặt mục tiêu SMART cho quý."
**Có kích hoạt:** Không (Marketing Strategy — 09).
### Test 4 — Đầu vào thiếu
**Prompt:** "Làm dashboard KPI" (chưa có baseline 04).
**Hành vi:** yêu cầu baseline hoặc kế hoạch gắn tracking, không bịa số.
### Test 5 — Ngoại lệ
**Prompt:** đưa báo cáo cũ toàn số liệt kê.
**Hành vi:** viết lại theo nhận định → hành động → người → deadline.
