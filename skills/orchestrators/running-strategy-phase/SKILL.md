---
name: running-strategy-phase
description: chạy liền mạch giai đoạn chiến lược của Marketing Growth OS theo thứ tự 09 Marketing Strategy → 10 Journey & Funnel → 11 Channel & Paid → 12 Content Strategy, kết thúc bằng bản trình BOD 10 phần. dùng khi người dùng muốn làm trọn phần chiến lược trong một phiên, "lên chiến lược marketing đầy đủ", hoặc chuyển dữ liệu nghiên cứu thành kế hoạch trình BOD. quy tắc cứng: chặn nếu chưa có 01, 07, 08. không dùng khi chỉ cần một tài liệu đơn lẻ.
---

# Strategy Runner (A3)
Điều phối chạy liền mạch giai đoạn chiến lược: 09 → 10 → 11 → 12. Kết thúc: bản trình BOD 10 phần. Đối tượng dùng: thương hiệu đã đủ dữ liệu nghiên cứu.

## Nguyên tắc cốt lõi
**Chặn cứng: không bắt đầu nếu chưa có 01, 07, 08.** Chiến lược (09) là trục; 10–12 kế thừa nó. Dừng Gate sau 09 để BOD chốt hướng trước khi triển khai chi tiết.

## Kế thừa & điều kiện vào
Bắt buộc 01, 02, 04–08. Thiếu 01/07/08 → dừng, chỉ ra tài liệu cần chạy (gợi ý dùng A2).

## Quy trình
### Giai đoạn 1 — 09 Marketing Strategy
Kiểm 01/07/08. Chạy building-marketing-strategy. **Gate: BOD chốt mục tiêu, Big Idea, mục KHÔNG làm gì.**
### Giai đoạn 2 — 10 Journey & Funnel
Nạp 07, 08, 09. Chạy mapping-customer-journey-funnel.
### Giai đoạn 3 — 11 Channel & Paid Media
Nạp 04, 07, 09, 10. Chạy planning-channel-paid-media.
### Giai đoạn 4 — 12 Content Strategy
Nạp 02, 07, 09, 11. Chạy building-content-strategy.
### Giai đoạn 5 — Bàn giao trình BOD
Gộp 09–12 thành bản trình BOD 10 phần (bối cảnh, vấn đề, mục tiêu, STP, Big Idea, phễu, kênh, content, ngân sách sơ bộ, KHÔNG làm gì).

## Cấu trúc kết quả
1. 09, 10, 11, 12 (4 file). 2. Bản trình BOD 10 phần. 3. Danh sách `[CHỜ BOD]`.

## Checklist chất lượng
- [ ] Chặn đúng khi thiếu 01/07/08.
- [ ] Gate sau 09 để BOD chốt hướng.
- [ ] 10–12 kế thừa 09 nhất quán.
- [ ] Kết bằng bản trình BOD 10 phần.

## Tình huống đặc biệt
### Trường hợp — Mục tiêu 09 không khả thi
**Cách xử lý:** dừng ở 09, trình bảng tính ngược + 2 lựa chọn cho BOD, chưa chạy 10–12.
### Trường hợp — BOD chưa chốt Big Idea
**Cách xử lý:** giữ Gate, không lên content strategy trên Big Idea chưa duyệt.

## Anti-Patterns
- Không chạy 09 khi thiếu 01/07/08.
- Không lên 10–12 khi 09 chưa được BOD chốt.

## Recovery
### Khi thiếu tài liệu nền
Dừng, đề nghị chạy A2 (research & audit) trước.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Lên chiến lược marketing đầy đủ để trình sếp."
**Có kích hoạt:** Có.
### Test 2 — Chặn
**Prompt:** "Chạy strategy" (chưa có 07/08).
**Hành vi:** dừng, yêu cầu A2 trước.
### Test 3 — Không nên kích hoạt
**Prompt:** "Chỉ cần chọn kênh chạy ads."
**Có kích hoạt:** Không (gọi thẳng 11).
