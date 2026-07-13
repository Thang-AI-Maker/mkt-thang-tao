---
name: building-brand-guideline
description: tạo Brand Guideline 11 mục (logo system, color palette, typography, photography, video style, icon, layout, social template, document template, website, packaging) kèm danh sách template cần thiết kế, để 5 người làm ra 1 thương hiệu nhất quán. dùng khi người dùng muốn dựng brand guideline, cẩm nang nhận diện, quy chuẩn thị giác, hệ màu, typography, quy tắc "mẫu đúng mẫu sai", danh sách template social, kể cả khi chỉ yêu cầu một phần như "chuẩn hóa bộ màu" hoặc "quy tắc dùng logo". không dùng cho brand bible (chiến lược thương hiệu), business overview, hay content calendar.
---

# Brand Guideline
Thực hiện tài liệu nền tảng số 03 của Marketing Growth OS: dịch tính cách thương hiệu (từ Brand Bible) thành quy chuẩn thị giác truy ngược được, để nhiều người thiết kế vẫn ra một thương hiệu. Đối tượng đọc: designer, người duyệt nội dung, đối tác thiết kế ngoài.

## Nguyên tắc cốt lõi
Mỗi quy tắc thị giác phải truy ngược được về một tính từ trong Brand Personality. **Quy tắc không giải thích được "vì sao" là quy tắc sẽ bị phá vỡ ngay tuần sau.**

## Đặc tả kết quả
- Định dạng: Markdown, có bảng; mã màu ghi đủ HEX/RGB/CMYK khi có.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: designer nội bộ và đối tác ngoài, người duyệt.
- Phạm vi: 11 mục (mục 11 chỉ khi có sản phẩm vật lý) + danh sách template cần thiết kế.
- Giọng điệu: chỉ dẫn, cụ thể, có ví dụ đúng/sai.
- Quy tắc nguồn: logo/màu/font đang dùng lấy từ người dùng; quy tắc mới suy từ Brand Bible gắn `[GIẢ ĐỊNH]` + lý do.
- File đầu ra: `03-brand-guideline.md`.
- Tuyệt đối không được tự bịa: mã màu chính xác, tên font bản quyền, kích thước file gốc khi người dùng chưa cung cấp — ghi `[CẦN BỔ SUNG]`.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Bắt buộc đã có tài liệu 02 (Brand Bible), đặc biệt mục 11 Personality và 12 Tone of Voice. Chưa có → cảnh báo guideline sẽ đẹp nhưng vô hồn, đề nghị làm 02 trước.

## Quy trình

### Giai đoạn 1 — Thu thập tài sản hiện có
**Đầu vào bắt buộc:** logo (các biến thể), mã màu đang dùng, font đang dùng, 5–10 hình ĐÚNG chất và 3–5 hình SAI chất.
**Đầu vào tùy chọn:** guideline cũ, file gốc, quy chuẩn website, nhu cầu bao bì.
**Mặc định:** thiếu file gốc logo → vẫn viết quy tắc dùng nhưng gắn `[CẦN BỔ SUNG]` ở phần file.
**Thực hiện:** đọc Brand Bible + tài sản; liệt kê tài sản thiếu; hỏi một lần tối đa 5 câu (mã màu chính, font, có logo ngang/dọc/icon không, nền tối/sáng, kênh chính cần template).
**Điều kiện hoàn thành:** có tối thiểu logo + 3 hình đúng chất. Thiếu → không dựng photography/video style bằng suy đoán.

### Giai đoạn 2 — Dịch tính từ thành quy tắc thị giác
1. Với mỗi tính từ Personality → 1 hệ quả thị giác (ví dụ "gần gũi" → bo góc, ảnh người thật; "chuyên gia" → lưới chặt, khoảng trắng rộng).
2. Dựng hệ màu: màu chính/phụ/nhấn + tỷ lệ dùng + màu cấm.
3. Dựng typography: font tiêu đề/thân + cỡ + **quy tắc riêng cho dấu tiếng Việt** (chọn font đủ dấu, tránh vỡ dấu).
4. Chốt logo system: vùng an toàn, kích thước tối thiểu, cách dùng sai.

### Giai đoạn 3 — Sinh danh sách template & bộ quy tắc duyệt
1. Sinh danh sách template social kèm kích thước và nội dung bắt buộc (feed dọc, story, cover, thumbnail video, carousel…).
2. Với mỗi loại: 1 mẫu ĐÚNG + 1 mẫu SAI kèm lý do.
3. Lập bảng "mẫu đúng / mẫu sai" cho người duyệt dùng khi ký duyệt.

### Giai đoạn 4 — Kiểm tra và sửa
1. Mỗi quy tắc truy ngược được về một tính từ? Nếu không → bỏ hoặc gắn `[GIẢ ĐỊNH]`.
2. Font có đủ dấu tiếng Việt? Màu có mã cụ thể hay còn `[CẦN BỔ SUNG]`?
3. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `03-brand-guideline.md` + **danh sách template cần thiết kế** (đầu ra hành động cho designer). Nạp cùng Brand Bible vào Claude Project.

## Cấu trúc kết quả
1. Logo System. 2. Color Palette. 3. Typography (kèm quy tắc dấu tiếng Việt). 4. Photography Style. 5. Video Style. 6. Visual Elements & Icon. 7. Layout & Composition. 8. Social Media Templates (+ kích thước). 9. Presentation & Document Templates. 10. Website & Landing Page Guideline. 11. Packaging Guideline *(chỉ khi có sản phẩm vật lý)*. + Danh sách template cần thiết kế. + Bảng mẫu đúng/mẫu sai.

## Checklist chất lượng
- [ ] Mỗi quy tắc thị giác truy ngược được về một tính từ Personality.
- [ ] Hệ màu có mã cụ thể (hoặc `[CẦN BỔ SUNG]`), không chỉ tên màu.
- [ ] Typography xử lý rõ dấu tiếng Việt.
- [ ] Có ít nhất một cặp mẫu đúng / mẫu sai cho mỗi loại template chính.
- [ ] Danh sách template ghi kích thước và nội dung bắt buộc.
- [ ] Một designer chưa từng biết thương hiệu có thể làm đúng 1 post chỉ bằng tài liệu này.

## Tình huống đặc biệt
### Trường hợp — Chưa có logo/nhận diện chuyên nghiệp
**Cách phát hiện:** logo tự làm, màu không nhất quán giữa các bài.
**Cách xử lý:** viết guideline "tối thiểu khả dụng" (1 màu chính, 1 font đủ dấu, 1 layout) và ghi rõ đây là bản tạm, kèm `[CẦN BỔ SUNG]` việc thuê thiết kế nhận diện.
**Không được:** bịa mã màu/chuẩn nhận diện như thể đã có.
### Trường hợp — Có sản phẩm vật lý
**Cách phát hiện:** người dùng nhắc bao bì, nhãn.
**Cách xử lý:** thêm mục 11 với quy chuẩn in ấn, vùng an toàn, chất liệu.
**Không được:** áp quy tắc màn hình (RGB) cho in ấn mà bỏ CMYK.

## Anti-Patterns
- Không liệt kê quy tắc mà không giải thích vì sao.
- Không chọn font thiếu dấu tiếng Việt.
- Không ghi "màu xanh thương hiệu" mà không có mã.
- Không quên kích thước khi liệt kê template.

## Recovery
### Khi thiếu tài sản gốc
Xuất khung guideline + danh sách file cần thu thập; không dựng photography/video style bằng tưởng tượng.
### Khi validation thất bại
Có quy tắc không truy ngược được về Personality → gắn `[GIẢ ĐỊNH]` hoặc loại.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Làm brand guideline, đây là logo và màu đang dùng."
**Có kích hoạt:** Có. **Hành vi:** kế thừa Brand Bible, dựng 11 mục + danh sách template.
### Test 2 — Trigger một phần
**Prompt:** "Chuẩn hóa bộ màu và font cho tôi."
**Có kích hoạt:** Có (mục 2, 3) nhưng gợi ý hoàn thiện cả bộ.
### Test 3 — Không nên kích hoạt
**Prompt:** "Viết vision mission và định vị thương hiệu."
**Có kích hoạt:** Không (đó là Brand Bible — 02).
### Test 4 — Đầu vào thiếu
**Prompt:** "Làm brand guideline" (không đưa logo/màu).
**Hành vi:** hỏi tối đa 5 câu, không bịa mã màu.
### Test 5 — Ngoại lệ
**Prompt:** Personality "tối giản, cao cấp" nhưng hình đưa vào rực rỡ, nhiều chi tiết.
**Hành vi:** gắn `[MÂU THUẪN]`, hỏi hình nào đúng chất trước khi viết quy tắc.
