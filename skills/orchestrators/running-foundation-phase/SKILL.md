---
name: running-foundation-phase
description: chạy liền mạch giai đoạn nền móng của Marketing Growth OS theo thứ tự 02 Brand Bible → 03 Brand Guideline → 04 Social Media Analysis, dừng chờ xác nhận [GIẢ ĐỊNH] sau mỗi tài liệu rồi nạp làm input bước sau. dùng khi người dùng muốn làm trọn bộ nền móng thương hiệu trong một phiên, dựng brand bible + guideline + audit kênh cùng lúc, hoặc "làm hết phần foundation cho tôi". không dùng khi chỉ cần một tài liệu đơn lẻ (gọi thẳng skill đó) hoặc chưa có tài liệu 01.
---

# Foundation Runner (A1)
Điều phối chạy liền mạch giai đoạn nền móng: 02 → 03 → 04. Kết thúc: bộ 3 tài liệu nạp vào Claude Project. Đối tượng dùng: thương hiệu đã có tài liệu 01, muốn dựng nền móng trong một phiên.

## Nguyên tắc cốt lõi
Sau mỗi tài liệu, **dừng chờ người dùng xác nhận/bác bỏ các `[GIẢ ĐỊNH]`** rồi mới nạp làm input cho bước sau. Không chạy tuột cả ba rồi kế thừa giả định chưa duyệt.

## Kế thừa & điều kiện vào
Bắt buộc đã có tài liệu 01 (Business & Brand Overview). Chưa có → dừng, đề nghị chạy 01 (skill building-business-brand-overview) trước.

## Quy trình
### Giai đoạn 1 — Chạy 02 Brand Bible
Gọi logic skill building-brand-bible. Kết thúc → liệt kê `[GIẢ ĐỊNH]`, **Gate: chờ duyệt**.
### Giai đoạn 2 — Chạy 03 Brand Guideline
Nạp Brand Bible đã duyệt làm input. Gọi logic building-brand-guideline. **Gate: chờ duyệt.**
### Giai đoạn 3 — Chạy 04 Social Media Analysis
Nạp 01 + 02 đã duyệt. Gọi logic auditing-social-media-channels. **Gate: chờ duyệt.**
### Giai đoạn 4 — Bàn giao
Xuất 3 file (02, 03, 04). Ghi: "Nạp cả ba vào Claude Project trước khi sang giai đoạn nghiên cứu."

## Cấu trúc kết quả
1. 02-brand-bible.md. 2. 03-brand-guideline.md. 3. 04-social-media-analysis.md. 4. Danh sách `[GIẢ ĐỊNH]` đã duyệt.

## Checklist chất lượng
- [ ] Có tài liệu 01 trước khi bắt đầu.
- [ ] Mỗi tài liệu dừng Gate chờ duyệt `[GIẢ ĐỊNH]`.
- [ ] Tài liệu sau kế thừa bản đã duyệt của tài liệu trước.
- [ ] Đủ ba file, không bỏ dở giữa chừng.

## Tình huống đặc biệt
### Trường hợp — Đã có Brand Bible cũ
**Cách xử lý:** bỏ qua 02, bắt đầu từ 03, nạp brand cũ; kiểm mâu thuẫn với 01.
### Trường hợp — Không export được số cho 04
**Cách xử lý:** hoàn thành 02, 03; để 04 ở khung baseline + `[CẦN BỔ SUNG]`.

## Anti-Patterns
- Không chạy tuột ba tài liệu bỏ qua Gate.
- Không bắt đầu khi thiếu 01.

## Recovery
### Khi một bước thiếu input
Dừng đúng bước đó, hỏi input chặn, không nhảy sang bước sau.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Làm trọn bộ nền móng thương hiệu cho tôi."
**Có kích hoạt:** Có.
### Test 2 — Không nên kích hoạt
**Prompt:** "Chỉ cần viết tone of voice."
**Có kích hoạt:** Không (gọi thẳng 02).
### Test 3 — Điều kiện vào thiếu
**Prompt:** "Chạy foundation" (chưa có 01).
**Hành vi:** dừng, yêu cầu 01 trước.
