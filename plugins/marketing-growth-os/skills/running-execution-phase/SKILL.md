---
name: running-execution-phase
description: chạy liền mạch giai đoạn triển khai của Marketing Growth OS theo thứ tự 13 Roadmap/Campaign/Budget/RACI → 14 Content Calendar & Production, biến chiến lược thành lịch có tên người và deadline. dùng khi người dùng muốn chuyển chiến lược thành kế hoạch triển khai, "biến plan thành lịch chạy", làm roadmap kèm lịch nội dung trong một phiên. không dùng khi chỉ cần roadmap hoặc chỉ cần content calendar đơn lẻ, hay chưa có chiến lược 09–12.
---

# Execution Runner (A4)
Điều phối chạy liền mạch giai đoạn triển khai: 13 → 14. Kết thúc: chiến lược thành lịch có tên người và deadline. Đối tượng dùng: thương hiệu đã có chiến lược 09–12.

## Nguyên tắc cốt lõi
13 chốt công suất và chiến dịch trước; 14 lên lịch **không vượt công suất 13**. Không lên lịch sản xuất khi roadmap chưa xác định người và ngân sách.

## Kế thừa & điều kiện vào
Bắt buộc 09, 11, 12. Thiếu → dừng, đề nghị chạy A3 trước.

## Quy trình
### Giai đoạn 1 — 13 Roadmap/Campaign/Budget/RACI
Nạp 09, 11, 12, 01. Chạy planning-roadmap-campaign-budget-raci. **Gate: BOD duyệt ngân sách + RACI.**
### Giai đoạn 2 — 14 Content Calendar & Production
Nạp 02, 10, 12, 13. Chạy producing-content-calendar. Không vượt công suất 13.
### Giai đoạn 3 — Bàn giao
Xuất 13, 14. Ghi: số thực tế sau khi đăng phản hồi về 15.

## Cấu trúc kết quả
1. 13-roadmap-campaign-budget-raci.md. 2. 14-content-calendar-production.md. 3. Xác nhận lịch nằm trong công suất.

## Checklist chất lượng
- [ ] Có 09, 11, 12 trước khi bắt đầu.
- [ ] Gate duyệt ngân sách + RACI sau 13.
- [ ] Lịch 14 không vượt công suất 13.
- [ ] Mỗi việc có người và deadline.

## Tình huống đặc biệt
### Trường hợp — Khối lượng vượt công suất
**Cách xử lý:** ở 13 cắt hạng mục; ở 14 dùng repurpose thay vì quay thêm.
### Trường hợp — Ngân sách chưa được BOD duyệt
**Cách xử lý:** giữ Gate, chưa lên lịch sản xuất tốn chi phí.

## Anti-Patterns
- Không lên lịch 14 vượt công suất 13.
- Không bỏ Gate ngân sách.

## Recovery
### Khi thiếu chiến lược
Dừng, đề nghị chạy A3 (strategy) trước.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Biến chiến lược thành roadmap và lịch nội dung."
**Có kích hoạt:** Có.
### Test 2 — Không nên kích hoạt
**Prompt:** "Chỉ cần lịch đăng tháng sau."
**Có kích hoạt:** Không (gọi thẳng 14).
### Test 3 — Điều kiện vào thiếu
**Prompt:** "Chạy execution" (chưa có 12).
**Hành vi:** dừng, yêu cầu A3 trước.
