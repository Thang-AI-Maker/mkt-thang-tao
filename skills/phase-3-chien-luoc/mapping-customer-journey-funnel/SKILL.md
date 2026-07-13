---
name: mapping-customer-journey-funnel
description: dựng hành trình khách 6 giai đoạn, mỗi giai đoạn đúng một chỉ số chính, liệt kê tài sản còn thiếu, tìm điểm rơi lớn nhất và xếp thứ tự vá phễu theo ROI. content không chuyển đổi thường vì phễu thủng chứ không vì content dở. dùng khi người dùng muốn map customer journey, thiết kế phễu marketing, funnel, tìm điểm rơi chuyển đổi, thứ tự vá phễu, kể cả khi chỉ yêu cầu một phần như "vì sao có traffic mà không ra đơn". không dùng cho channel strategy, content, hay KPI dashboard.
---

# Customer Journey & Funnel
Thực hiện tài liệu số 10 của Marketing Growth OS: content không chuyển đổi thường vì phễu thủng, không vì content dở. Dựng hành trình + phễu có chỉ số + thứ tự vá. Đối tượng đọc: trưởng marketing, sale, vận hành.

## Nguyên tắc cốt lõi
Mỗi giai đoạn phễu chỉ được có **ĐÚNG MỘT chỉ số chính**. Không thiết kế phễu cần nhiều tài sản hơn năng lực team (tài liệu 01). Vá phễu theo thứ tự ROI, không vá chỗ dễ trước.

## Đặc tả kết quả
- Định dạng: Markdown, bảng 6 giai đoạn + bảng tài sản thiếu.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: trưởng marketing, sale.
- Phạm vi: hành trình + phễu + thứ tự vá, 1.000–1.800 từ.
- Giọng điệu: chẩn đoán, ra thứ tự ưu tiên.
- Quy tắc nguồn: tỷ lệ giữa các bước lấy từ dữ liệu thật (04/CRM); thiếu → `[CẦN BỔ SUNG]`.
- File đầu ra: `10-customer-journey-funnel.md`.
- Tuyệt đối không được tự bịa: tỷ lệ chốt, tỷ lệ rơi, số liệu từng bước.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần 07 (hành trình cảm xúc, khoảnh khắc mua), 08 (offer, vai sản phẩm), 09 (mục tiêu, tính ngược). Chưa có 09 → không biết phễu phải tải bao nhiêu.

## Quy trình

### Giai đoạn 1 — Thu thập hành trình thật
**Đầu vào bắt buộc:** hành trình thật của khách hiện nay; CTA đang dùng; có CRM/form không; tỷ lệ chốt.
**Đầu vào tùy chọn:** số liệu từng bước, thời gian ra quyết định, kênh chạm.
**Mặc định:** không có số từng bước → dựng phễu định tính, gắn `[CẦN BỔ SUNG]` ở tỷ lệ, không đoán %.
**Thực hiện:** đọc 07/08/09; hỏi tối đa 5 câu (khách đi qua những bước nào, chốt ở đâu, có form/CRM không, tỷ lệ chốt hiện tại, bước nào hay mất khách).
**Điều kiện hoàn thành:** dựng được chuỗi bước thật của khách.

### Giai đoạn 2 — Dựng phễu 6 giai đoạn
1. Sáu giai đoạn: Nhận biết → Quan tâm → Cân nhắc → Hành động → Mua → Trung thành/Giới thiệu.
2. Mỗi giai đoạn: gán **đúng một chỉ số chính** + tài sản đang có.
3. Liệt kê **tài sản còn thiếu** để giai đoạn chạy được.

### Giai đoạn 3 — Tìm điểm rơi & xếp thứ tự vá
1. So tỷ lệ giữa các bước → tìm điểm rơi lớn nhất (số hoặc `[CẦN BỔ SUNG]`).
2. Xếp thứ tự vá theo ROI: chỗ rơi to + sửa rẻ làm trước.
3. Đối chiếu tài sản cần vá với năng lực team (01) — vượt thì cắt bớt phễu.

### Giai đoạn 4 — Kiểm tra và sửa
1. Mỗi giai đoạn đúng một chỉ số? Có điểm rơi chính? Thứ tự vá theo ROI? Không vượt năng lực?
2. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `10-customer-journey-funnel.md`. Nạp vào 11 (kênh theo giai đoạn), 12 (tỷ trọng content), 15 (KPI theo bước).

## Cấu trúc kết quả
1. Hành trình thật hiện tại. 2. Phễu 6 giai đoạn (mỗi giai đoạn 1 chỉ số + tài sản). 3. Tài sản còn thiếu. 4. Điểm rơi lớn nhất. 5. Thứ tự vá phễu theo ROI.

## Checklist chất lượng
- [ ] Mỗi giai đoạn có đúng một chỉ số chính.
- [ ] Có danh sách tài sản còn thiếu cụ thể.
- [ ] Chỉ ra điểm rơi lớn nhất (số hoặc `[CẦN BỔ SUNG]`).
- [ ] Thứ tự vá xếp theo ROI, không theo độ dễ.
- [ ] Không thiết kế phễu vượt năng lực team (01).

## Tình huống đặc biệt
### Trường hợp — Không có số từng bước
**Cách xử lý:** phễu định tính, đánh dấu chỗ nghi rơi, đề xuất gắn tracking (link tài liệu 15) trước khi kết luận.
**Không được:** bịa tỷ lệ rơi.
### Trường hợp — Phễu đòi quá nhiều tài sản
**Cách xử lý:** cắt còn phễu tối thiểu chạy được với team hiện tại; ghi phần hoãn.
**Không được:** vẽ phễu lý tưởng team không kham nổi.

## Anti-Patterns
- Không gán nhiều chỉ số cho một giai đoạn.
- Không bịa tỷ lệ chuyển đổi.
- Không vá chỗ dễ trước chỗ rơi to.
- Không thiết kế vượt năng lực.

## Recovery
### Khi thiếu số
Dựng phễu định tính + kế hoạch gắn tracking; hẹn tính lại.
### Khi validation thất bại
Giai đoạn có >1 chỉ số → ép chọn một chỉ số quyết định.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Dựng phễu marketing và tìm chỗ rơi cho tôi."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Có traffic mà không ra đơn, lỗi ở đâu?"
**Có kích hoạt:** Có (điểm rơi).
### Test 3 — Không nên kích hoạt
**Prompt:** "Chọn kênh nào để chạy ads."
**Có kích hoạt:** Không (Channel — 11).
### Test 4 — Đầu vào thiếu
**Prompt:** "Phễu của tôi thủng chỗ nào?" (không có số).
**Hành vi:** phễu định tính + đề xuất gắn tracking, không bịa %.
### Test 5 — Ngoại lệ
**Prompt:** phễu cần 12 tài sản, team 2 người.
**Hành vi:** cắt còn phễu tối thiểu, ghi phần hoãn.
