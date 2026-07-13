---
name: building-brand-bible
description: tạo Brand Bible 14 mục (Vision, Mission, Purpose, Core Values, Positioning, Value Proposition, Personality, Tone of Voice, Message Architecture, Founder Brand) từ chất liệu thô của founder, làm chuẩn gốc cho mọi nội dung sau này. dùng khi người dùng muốn dựng brand bible, cẩm nang thương hiệu, định nghĩa "thương hiệu là ai", chốt vision mission giá trị cốt lõi, định vị, tone of voice, kiến trúc thông điệp, kể cả khi chỉ yêu cầu một phần như "viết định vị thương hiệu" hoặc "làm tone of voice". không dùng cho brand guideline (nhận diện thị giác), business overview, phân tích đối thủ, persona hay content calendar.
---

# Brand Bible
Thực hiện tài liệu nền tảng số 02 của Marketing Growth OS: từ câu chuyện founder và chất liệu thô, tạo Brand Bible 14 mục làm chuẩn gốc để mọi người viết nội dung ra cùng một thương hiệu. Đối tượng đọc: founder, trưởng marketing, người sáng tạo nội dung, và Claude Project được nạp tài liệu này.

## Nguyên tắc cốt lõi
Brand Bible là "hiến pháp" của thương hiệu. Nếu định vị không loại trừ được ít nhất một nhóm khách, đó chưa phải định vị — chỉ là mô tả. **Một thương hiệu cố gắng phục vụ tất cả mọi người là thương hiệu không có ai nhớ.**

## Đặc tả kết quả
- Định dạng: Markdown, có bảng.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: founder, trưởng marketing, content creator, Claude Project.
- Phạm vi: 14 mục bắt buộc (xem "Cấu trúc kết quả"), khoảng 1.500–2.500 từ.
- Giọng điệu: dứt khoát, có quan điểm. Brand Bible mờ nhạt là Brand Bible hỏng.
- Quy tắc nguồn: câu chuyện, giá trị, tham vọng phải lấy từ lời founder — trích nguồn `(founder cung cấp)`; điều AI suy ra gắn `[GIẢ ĐỊNH]`.
- File đầu ra: `02-brand-bible.md`.
- Giả định được phép: diễn giải Vision/Mission thành câu dùng được, chọn 3–5 tính từ personality, gợi ý từ cấm trong tone — tất cả gắn `[GIẢ ĐỊNH]` + lý do.
- Tuyệt đối không được tự bịa: câu nói thật của khách hàng, cột mốc lịch sử, con số thành tựu, lời hứa sản phẩm chưa được founder xác nhận.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` = AI suy ra, chờ duyệt · `[CẦN BỔ SUNG: cách lấy]` = thiếu dữ liệu, không đoán · `[CHỜ BOD]` = cần quyết định lãnh đạo · `[MÂU THUẪN: …]` = hai thông tin xung khắc, dừng hỏi.

## Kế thừa từ tài liệu trước
Bắt buộc đã có tài liệu 01 (Business & Brand Overview). Lấy sẵn: mô hình kinh doanh, sản phẩm chính, vấn đề ưu tiên, giai đoạn phát triển. Không hỏi lại các mục này. Nếu chưa có tài liệu 01 → cảnh báo output sẽ là suy diễn và đề nghị chạy 01 trước.

## Quy trình

### Giai đoạn 1 — Thu thập chất liệu thô
**Mục tiêu:** có đủ nguyên liệu người thật để không phải bịa cảm xúc thương hiệu.
**Đầu vào bắt buộc:**
1. Câu chuyện founder: vì sao bắt đầu, trải nghiệm cá nhân ảnh hưởng lớn.
2. Giá trị sống thật của founder/đội ngũ (không phải khẩu hiệu đẹp).
3. Tham vọng 3–5 năm: muốn trở thành ai, chiếm vị trí nào.
4. 5–10 câu nói thật của khách về thương hiệu hoặc về vấn đề của họ.
5. Điều thương hiệu **không bao giờ** nói/làm (ranh giới).
**Đầu vào tùy chọn:** cột mốc phát triển, đối thủ/giải pháp thay thế, 3 từ muốn được nhớ, chi tiết không truyền thông ra ngoài.
**Mặc định được phép dùng:** thiếu câu nói khách thật → viết Message Architecture nhưng gắn `[CẦN BỔ SUNG]` ở proof point, không bịa lời chứng thực.
**Thực hiện:**
1. Đọc tài liệu 01 và mọi chất liệu người dùng đã đưa. Không hỏi lại.
2. Đối chiếu 5 đầu vào bắt buộc, liệt kê phần thiếu.
3. Nếu thiếu, hỏi một lần tối đa 5 câu, ưu tiên: câu chuyện gốc, giá trị thật, điều không bao giờ nói, nhóm khách muốn loại trừ, 3 từ muốn được nhớ.
**Điều kiện hoàn thành:** có tối thiểu đầu vào 1, 2, 3. Thiếu bất kỳ mục nào trong ba → không dựng Vision/Mission/Purpose, dừng lại hỏi.

### Giai đoạn 2 — Suy ra tầng chiến lược
**Thực hiện:**
1. Từ câu chuyện + tham vọng → viết Vision (nơi đến), Mission (lý do tồn tại hằng ngày), Purpose (thay đổi ngoài doanh thu) thành câu dùng được, mỗi câu ≤ 30 từ.
2. Từ giá trị thật → chốt 3–5 Core Values, mỗi giá trị kèm hành vi thể hiện + hành vi đi ngược (giá trị không có phản-hành-vi là giá trị vô nghĩa).
3. Dựng Positioning theo công thức bắt buộc, kiểm tra loại trừ được một nhóm khách.
4. Chốt Value Proposition: vấn đề → kết quả cụ thể → bằng chứng.
**Công thức định vị:** "Dành cho [khách mục tiêu], [thương hiệu] là [danh mục] giúp [kết quả chính] thông qua [phương pháp khác biệt], thay vì [giải pháp thông thường]."
**Điều kiện hoàn thành:** định vị nêu rõ nhóm KHÔNG phục vụ; nếu không → viết lại.

### Giai đoạn 3 — Suy ra tầng biểu đạt
**Thực hiện:**
1. Chốt Brand Personality: 3–5 tính từ + mô tả "nếu là một người thì là ai".
2. Dựng Tone of Voice cho 6 bối cảnh (bài bán hàng, bài giá trị, xử lý khủng hoảng, trả lời bình luận, email, kịch bản video) — mỗi bối cảnh 1 ví dụ câu đúng + 1 câu sai.
3. Lập **danh sách từ cấm** (từ thương hiệu không bao giờ dùng).
4. Dựng Message Architecture: 1 thông điệp lõi + 3–4 thông điệp trụ, mỗi cái gắn proof point (hoặc `[CẦN BỔ SUNG]`).
5. Chốt Founder Brand Alignment: founder xuất hiện thế nào, ranh giới cá nhân/thương hiệu.

### Giai đoạn 4 — Kiểm tra và sửa
1. Đối chiếu 14 mục với checklist chất lượng.
2. Kiểm định vị có loại trừ; tone có ví dụ đúng/sai; mỗi giá trị có phản-hành-vi.
3. Ghi từng lỗi, sửa, kiểm lại đến khi đạt.

### Giai đoạn 5 — Bàn giao
- Xuất `02-brand-bible.md`, đủ 14 mục, mọi `[GIẢ ĐỊNH]` được liệt kê ở cuối để founder duyệt.
- Ghi một dòng: "Nạp tài liệu này vào Claude Project trước khi làm tài liệu 03, 04 và mọi content."

## Cấu trúc kết quả
1. Brand Overview — tóm tắt kế thừa từ tài liệu 01.
2. Brand Origin Story — câu chuyện nên kể thường xuyên + chi tiết không truyền thông.
3. Vision — 1 câu.
4. Mission — 1 câu.
5. Core Values — 3–5, mỗi giá trị có hành vi thể hiện + đi ngược.
6. Brand Purpose.
7. Target Audience — tóm tắt (chi tiết để tài liệu 07).
8. Customer Insight — insight lõi (đầy đủ ở tài liệu 07).
9. Brand Positioning — theo công thức, có nhóm loại trừ.
10. Value Proposition — vấn đề → kết quả → bằng chứng.
11. Brand Personality — 3–5 tính từ.
12. Tone of Voice — 6 bối cảnh + danh sách từ cấm.
13. Brand Message Architecture — thông điệp lõi + trụ + proof point.
14. Founder Brand Alignment.

## Checklist chất lượng
- [ ] Vision/Mission/Purpose mỗi cái là một câu dùng được, không phải đoạn văn.
- [ ] Định vị loại trừ được ít nhất một nhóm khách cụ thể.
- [ ] Mỗi Core Value có hành vi đi ngược (chứng minh không rỗng).
- [ ] Tone of Voice có ví dụ câu đúng và câu sai cho từng bối cảnh.
- [ ] Có danh sách từ cấm cụ thể (không phải "tránh từ tiêu cực").
- [ ] Mỗi thông điệp trụ có proof point hoặc nhãn `[CẦN BỔ SUNG]`.
- [ ] Không có câu nói khách hàng bịa ra.
- [ ] Content creator có thể viết một bài đúng giọng chỉ bằng tài liệu này, không cần hỏi thêm.

## Tình huống đặc biệt
### Trường hợp — Founder chỉ đưa khẩu hiệu đẹp, không có chất liệu thật
**Cách phát hiện:** giá trị nghe như copy từ web ("tận tâm, uy tín, chất lượng"), không có câu chuyện đằng sau.
**Cách xử lý:** hỏi lại bằng câu chuyện cụ thể ("kể một lần thương hiệu từ chối tiền vì giá trị này"). Không có ví dụ thật → gắn `[GIẢ ĐỊNH]`, không đưa vào như sự thật.
**Không được:** biến khẩu hiệu sáo rỗng thành Core Value chính thức.

### Trường hợp — Thương hiệu đã có brand cũ, chỉ cần chuẩn hóa
**Cách phát hiện:** người dùng nạp tài liệu brand cũ.
**Cách xử lý:** kế thừa phần đã rõ, chỉ bổ sung mục thiếu; gắn `[MÂU THUẪN]` nếu brand cũ chọi tài liệu 01.
**Không được:** viết lại từ đầu thứ đã đúng.

## Anti-Patterns
- Không viết Vision dài như một đoạn văn quảng cáo.
- Không tạo Core Value không có hành vi đi ngược.
- Không viết định vị "phục vụ tất cả khách hàng muốn chất lượng".
- Không bịa lời chứng thực khách hàng để lấp proof point.

## Recovery
### Khi thiếu chất liệu thật của founder
Dừng ở Vision/Mission, xuất phần khung + danh sách câu hỏi phỏng vấn founder, không dựng tiếp tầng biểu đạt dựa trên suy diễn.
### Khi validation thất bại
Định vị không loại trừ được ai → quay lại Giai đoạn 2, buộc chọn nhóm khách sẵn sàng bỏ.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Giúp tôi làm Brand Bible cho thương hiệu, đây là câu chuyện founder…"
**Có kích hoạt:** Có. **Hành vi mong đợi:** kế thừa tài liệu 01, thu thập 5 chất liệu, dựng 14 mục.
### Test 2 — Trigger một phần
**Prompt:** "Viết giúp tôi phần định vị và tone of voice."
**Có kích hoạt:** Có. **Hành vi mong đợi:** làm mục 9 và 12 nhưng cảnh báo nên hoàn thiện cả 14 mục.
### Test 3 — Không nên kích hoạt
**Prompt:** "Làm giúp tôi bộ màu và font cho thương hiệu."
**Có kích hoạt:** Không (đó là Brand Guideline — tài liệu 03).
### Test 4 — Đầu vào thiếu
**Prompt:** "Làm Brand Bible" (không có câu chuyện founder).
**Hành vi mong đợi:** hỏi tối đa 5 câu chặn tiến độ, không tự bịa câu chuyện.
### Test 5 — Ngoại lệ
**Prompt:** cung cấp giá trị mâu thuẫn với vấn đề ưu tiên ở tài liệu 01.
**Hành vi mong đợi:** gắn `[MÂU THUẪN]`, dừng hỏi trước khi viết tiếp.
