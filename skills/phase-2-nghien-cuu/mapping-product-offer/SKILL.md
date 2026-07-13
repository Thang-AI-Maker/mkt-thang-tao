---
name: mapping-product-offer
description: phân vai từng sản phẩm (tạo lead/tạo doanh thu/tạo lợi nhuận/đại diện năng lực), xử lý rào cản mua bằng cấu trúc offer thay vì giảm giá, và tính trần CAC từ biên lợi nhuận. marketing không cứu được offer dở nên phải chốt offer trước khi chốt content. dùng khi người dùng muốn map sản phẩm, thiết kế offer, phân vai sản phẩm, tính CAC trần, xử lý lý do khách từ chối mua, kể cả khi chỉ yêu cầu một phần như "offer này ổn chưa". không dùng cho persona, pricing chi tiết tài chính, hay content.
---

# Product & Offer Map
Thực hiện tài liệu số 08 của Marketing Growth OS: marketing không cứu được offer dở — chốt offer trước khi chốt content. Phân vai sản phẩm, cấu trúc offer, tính trần CAC. Đối tượng đọc: BOD, trưởng marketing, sale.

## Nguyên tắc cốt lõi
Mỗi sản phẩm phải có một vai trò trong hệ; **sản phẩm không có vai trò thì đề xuất dừng**. Rào cản mua xử lý bằng cấu trúc offer, **không phải bằng giảm giá**. Trần CAC tính từ biên lợi nhuận — vượt trần là lỗ.

## Đặc tả kết quả
- Định dạng: Markdown, bảng sản phẩm–vai trò + bảng offer.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: BOD, trưởng marketing, sale.
- Phạm vi: toàn bộ sản phẩm + offer + trần CAC, 1.000–1.800 từ.
- Giọng điệu: kinh doanh, ra quyết định.
- Quy tắc nguồn: giá vốn/biên lợi nhuận lấy từ người dùng; thiếu → `[CẦN BỔ SUNG]`, không suy CAC trần từ số bịa.
- File đầu ra: `08-product-offer-map.md`.
- Tuyệt đối không được tự bịa: giá vốn, biên lợi nhuận, tỷ lệ chốt, case study kết quả.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần 01 (danh sách sản phẩm, giá, ngân sách) và 07 (nỗi đau, lý do từ chối mua). Chưa có 07 → không xử lý được rào cản mua đúng insight.

## Quy trình

### Giai đoạn 1 — Thu thập dữ liệu sản phẩm
**Đầu vào bắt buộc:** toàn bộ sản phẩm với giá bán; giá vốn từng cái; phạm vi/nội dung; case study; lý do khách từ chối mua.
**Đầu vào tùy chọn:** tỷ lệ chốt theo sản phẩm, sản phẩm bán kèm, chi phí phục vụ.
**Mặc định:** thiếu giá vốn → không tính trần CAC, ghi `[CẦN BỔ SUNG]`, không suy đoán biên.
**Thực hiện:** đọc 01, 07; hỏi một lần tối đa 5 câu (giá vốn từng sản phẩm, sản phẩm nào biên tốt nhất, lý do từ chối phổ biến, có sản phẩm phễu chưa, sản phẩm nào BOD muốn đẩy).
**Điều kiện hoàn thành:** có giá bán + biên (hoặc `[CẦN BỔ SUNG]`) + lý do từ chối cho sản phẩm chính.

### Giai đoạn 2 — Phân vai sản phẩm
1. Gán mỗi sản phẩm một vai: **tạo lead / tạo doanh thu / tạo lợi nhuận / đại diện năng lực**.
2. Sản phẩm không rơi vào vai nào → đề xuất dừng hoặc tái cấu trúc.
3. Kiểm tra hệ có đủ sản phẩm phễu (tạo lead) không.

### Giai đoạn 3 — Cấu trúc offer & trần CAC
1. Với mỗi rào cản mua (từ 07): thiết kế yếu tố offer xử lý nó (bảo hành, dùng thử, chia nhỏ, bundle, bằng chứng) — không mặc định giảm giá.
2. Tính **trần CAC** = biên lợi nhuận đơn hàng × tỷ lệ chấp nhận chi cho acquisition (nêu công thức + giả định). Thiếu biên → ghi `[CẦN BỔ SUNG]`.
3. Kiến nghị chốt với BOD: giữ / sửa / dừng từng sản phẩm + offer đề xuất.

### Giai đoạn 4 — Kiểm tra và sửa
1. Mọi sản phẩm có vai? Rào cản xử lý bằng offer không phải giảm giá? Trần CAC có công thức?
2. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `08-product-offer-map.md` + kiến nghị chốt BOD. Nạp vào 09, 10, 11.

## Cấu trúc kết quả
1. Bảng sản phẩm × vai trò. 2. Sản phẩm đề xuất dừng/tái cấu trúc. 3. Bảng rào cản mua → yếu tố offer xử lý. 4. Trần CAC (công thức + giả định). 5. Kiến nghị chốt với BOD.

## Checklist chất lượng
- [ ] Mỗi sản phẩm có đúng một vai trò chính.
- [ ] Sản phẩm không có vai được đề xuất dừng.
- [ ] Mỗi rào cản mua có yếu tố offer xử lý, không mặc định giảm giá.
- [ ] Trần CAC có công thức và giả định rõ (hoặc `[CẦN BỔ SUNG]`).
- [ ] Hệ có ít nhất một sản phẩm tạo lead.
- [ ] BOD đọc xong ra được quyết định giữ/sửa/dừng.

## Tình huống đặc biệt
### Trường hợp — Thiếu giá vốn
**Cách xử lý:** không tính trần CAC, ghi `[CẦN BỔ SUNG]`, nêu rủi ro chạy ads mù trần.
**Không được:** đoán biên lợi nhuận.
### Trường hợp — Chỉ có một sản phẩm giá cao, không có phễu
**Cách xử lý:** đề xuất tạo sản phẩm/lead magnet tạo lead trước khi chạy ads.
**Không được:** đẩy thẳng ads vào sản phẩm giá cao mà không có bước làm ấm.

## Anti-Patterns
- Không mặc định giảm giá để xử lý rào cản.
- Không giữ sản phẩm không có vai chỉ vì "đang bán".
- Không tính trần CAC từ biên bịa.
- Không bỏ qua nhu cầu sản phẩm phễu.

## Recovery
### Khi thiếu dữ liệu tài chính
Phân vai định tính được nhưng hoãn trần CAC, ghi rõ cần số gì.
### Khi validation thất bại
Có sản phẩm không vai chưa xử lý → quay lại Giai đoạn 2.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Map sản phẩm và thiết kế offer, đây là danh mục và giá vốn."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Offer combo này ổn chưa, khách hay chê đắt."
**Có kích hoạt:** Có (cấu trúc offer xử lý rào cản).
### Test 3 — Không nên kích hoạt
**Prompt:** "Viết insight cho khách hàng."
**Có kích hoạt:** Không (Persona — 07).
### Test 4 — Đầu vào thiếu
**Prompt:** "Trần CAC của tôi nên là bao nhiêu?" (không có giá vốn).
**Hành vi:** ghi `[CẦN BỔ SUNG]`, không đoán biên.
### Test 5 — Ngoại lệ
**Prompt:** chỉ có 1 sản phẩm giá cao.
**Hành vi:** đề xuất tạo lead magnet/sản phẩm phễu trước.
