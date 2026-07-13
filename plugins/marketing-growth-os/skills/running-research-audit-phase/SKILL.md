---
name: running-research-audit-phase
description: chạy liền mạch giai đoạn nghiên cứu của Marketing Growth OS theo thứ tự 01 Business Overview → 05 Market Research → 06 Competitor Analysis → 07 Persona & Insight → 08 Product & Offer Map, kết thúc bằng đủ dữ liệu để làm chiến lược. dùng khi người dùng muốn làm trọn phần nghiên cứu và audit trong một phiên, "nghiên cứu thị trường khách hàng đối thủ cho tôi", hoặc chuẩn bị đủ đầu vào cho chiến lược. không dùng khi chỉ cần một tài liệu đơn lẻ (gọi thẳng skill đó).
---

# Research & Audit Runner (A2)
Điều phối chạy liền mạch giai đoạn nghiên cứu: 01 → 05 → 06 → 07 → 08. Kết thúc: đủ dữ liệu để chạy chiến lược (09). Đối tượng dùng: thương hiệu chuẩn bị nền dữ liệu trước khi ra quyết định.

## Nguyên tắc cốt lõi
Kết thúc giai đoạn phải đủ đầu vào cho 09 (đặc biệt 01, 07, 08). **Dừng Gate sau 07** vì persona quyết định ROI — sai ở đây lệch toàn bộ ngân sách.

## Kế thừa & điều kiện vào
Nên có tài liệu nền móng 02, 04 (cho 07). Thiếu → 07 sẽ độ tin cậy thấp; cảnh báo.

## Quy trình
### Giai đoạn 1 — 01 Business & Brand Overview
Nếu chưa có, chạy building-business-brand-overview. **Gate.**
### Giai đoạn 2 — 05 Market Research
Nạp 01. Chạy researching-market. Ghi giả định cần kiểm.
### Giai đoạn 3 — 06 Competitor Analysis
Nạp 01, 05. Chạy analyzing-competitors.
### Giai đoạn 4 — 07 Persona & Insight
Nạp 02, 04, 06. Chạy building-customer-persona-insight. **Gate: chờ duyệt** (bước quyết định ROI).
### Giai đoạn 5 — 08 Product & Offer Map
Nạp 01, 07. Chạy mapping-product-offer.
### Giai đoạn 6 — Bàn giao
Kiểm đủ 01, 07, 08 (điều kiện cứng cho 09). Xuất 5 file + kết luận sẵn sàng làm chiến lược.

## Cấu trúc kết quả
1. 01, 05, 06, 07, 08 (5 file). 2. Danh sách giả định cần kiểm chứng. 3. Xác nhận đủ điều kiện chạy 09.

## Checklist chất lượng
- [ ] Đủ 01, 07, 08 khi kết thúc.
- [ ] Gate sau 07 để duyệt persona.
- [ ] Mỗi tài liệu kế thừa bản đã duyệt của tài liệu trước.
- [ ] Kết bằng xác nhận sẵn sàng cho chiến lược.

## Tình huống đặc biệt
### Trường hợp — Không có dữ liệu khách thật cho 07
**Cách xử lý:** gắn `[CẦN PHỎNG VẤN]`, hoàn thành phần khác, cảnh báo chưa nên tiêu tiền.
### Trường hợp — Thiếu giá vốn cho 08
**Cách xử lý:** phân vai định tính, hoãn trần CAC với `[CẦN BỔ SUNG]`.

## Anti-Patterns
- Không kết thúc thiếu 07/08 rồi vẫn báo "sẵn sàng chiến lược".
- Không bỏ Gate persona.

## Recovery
### Khi một bước thiếu input
Dừng bước đó, hỏi input chặn; các bước độc lập vẫn tiếp tục.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Nghiên cứu thị trường, đối thủ và khách hàng cho tôi."
**Có kích hoạt:** Có.
### Test 2 — Không nên kích hoạt
**Prompt:** "Chỉ phân tích 5 đối thủ."
**Có kích hoạt:** Không (gọi thẳng 06).
### Test 3 — Ngoại lệ
**Prompt:** không có dữ liệu khách thật.
**Hành vi:** `[CẦN PHỎNG VẤN]` ở 07, cảnh báo.
