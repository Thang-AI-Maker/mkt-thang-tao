---
name: auditing-social-media-channels
description: đo hiện trạng kênh social bằng số liệu thật để tạo baseline, giải mã vì sao bài top thắng thành công thức tái dùng, audit đường chuyển đổi và ra quyết định giữ/sửa/dừng từng kênh. dùng khi người dùng muốn phân tích social media, audit kênh, đọc số liệu fanpage/tiktok/instagram, tìm baseline, review top content, tìm điểm rơi phễu, kể cả khi chỉ yêu cầu một phần như "vì sao bài này viral" hoặc "kênh nào nên bỏ". không dùng cho content strategy (lập pillar tương lai), channel strategy (chọn kênh mới), hay lập lịch đăng.
---

# Social Media Analysis
Thực hiện tài liệu nền tảng số 04 của Marketing Growth OS: từ số liệu 3–6 tháng, dựng baseline theo kênh, giải mã công thức bài thắng và ra quyết định giữ/sửa/dừng. Đây là mốc 0 để sau này đo tiến bộ. Đối tượng đọc: trưởng marketing, người vận hành kênh, BOD.

## Nguyên tắc cốt lõi
Baseline là sự thật, không phải cảm giác. Dữ liệu dưới 8 tuần thì **gắn nhãn "chưa đủ mẫu" thay vì phán**. Mọi phân tích phải kết bằng một quyết định giữ / sửa / dừng — mô tả suông là output hỏng.

## Đặc tả kết quả
- Định dạng: Markdown, có bảng số.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: trưởng marketing, BOD.
- Phạm vi: 9 mục (xem cấu trúc), khoảng 1.200–2.000 từ.
- Giọng điệu: khô, dựa số, ra quyết định.
- Quy tắc nguồn: mọi số phải kèm nguồn và khoảng thời gian; số người dùng không cung cấp → `[CẦN BỔ SUNG: cách export]`, tuyệt đối không đoán.
- File đầu ra: `04-social-media-analysis.md`.
- Tuyệt đối không được tự bịa: lượt xem, tương tác, tỷ lệ chuyển đổi, chi phí, doanh thu từ kênh.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]` · `[CHƯA ĐỦ MẪU]` (dữ liệu < 8 tuần).

## Kế thừa từ tài liệu trước
Cần tài liệu 01 (bối cảnh kinh doanh, ngân sách) và 02 (Personality/Tone để đánh giá bài đúng chất). Chưa có 02 → vẫn đo được số nhưng không đánh giá được "đúng thương hiệu hay không".

## Quy trình

### Giai đoạn 1 — Thu thập số liệu
**Đầu vào bắt buộc:** link các kênh; export số liệu 3–6 tháng (reach, tương tác, follower, lưu, chia sẻ); chi phí vận hành kênh; 10–20 bài tốt nhất; 5–10 bài kém nhất.
**Đầu vào tùy chọn:** số liệu quảng cáo, dữ liệu website/GA4, form/CRM, tỷ lệ chốt.
**Mặc định:** dữ liệu < 8 tuần → gắn `[CHƯA ĐỦ MẪU]` cho kênh đó, chỉ mô tả không kết luận.
**Thực hiện:** đọc số đã đưa; liệt kê kênh thiếu số; hỏi một lần tối đa 5 câu (kênh nào là chính, chi phí thật/tháng, có theo dõi chuyển đổi không, KPI hiện tại là gì, mục tiêu kênh).
**Điều kiện hoàn thành:** có tối thiểu 1 kênh đủ số ≥ 8 tuần. Không có → chỉ dựng khung baseline, không phán.

### Giai đoạn 2 — Dựng baseline & giải mã bài thắng
1. Lập channel inventory: mỗi kênh 1 hàng — follower, reach TB, ER TB, tần suất, chi phí.
2. Với 10–20 bài top: phân tích hook / insight / format / thời điểm → rút **công thức tái dùng** (ít nhất 3 mẫu lặp lại).
3. Với bài kém: tìm điểm chung để tránh.

### Giai đoạn 3 — Audit chuyển đổi & ra quyết định
1. Audit đường chuyển đổi: kênh → hành động → điểm rơi lớn nhất.
2. Với mỗi kênh: quyết định **GIỮ / SỬA / DỪNG** kèm lý do bằng số.
3. Bắt buộc đề xuất DỪNG ít nhất một thứ (kênh, định dạng, hoặc thói quen tốn công vô ích).

### Giai đoạn 4 — Kiểm tra và sửa
1. Mọi con số có nguồn + mốc thời gian? Bài thắng có công thức tái dùng được không?
2. Có ít nhất một đề xuất dừng chưa? Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `04-social-media-analysis.md`. Đây là baseline nạp vào tài liệu 09 (mục tiêu) và 15 (KPI). Ghi rõ ngày chốt baseline.

## Cấu trúc kết quả
1. Channel Inventory. 2. Profile Audit. 3. Content Audit. 4. Performance Audit (baseline số). 5. Top Content Review (+ công thức tái dùng). 6. Low-performing Review. 7. Audience Analysis. 8. Conversion Path Audit (+ điểm rơi). 9. Key Findings + Quyết định giữ/sửa/dừng từng kênh.

## Checklist chất lượng
- [ ] Mỗi con số có nguồn và khoảng thời gian.
- [ ] Kênh dữ liệu < 8 tuần được gắn `[CHƯA ĐỦ MẪU]`, không bị phán.
- [ ] Bài top được giải mã thành công thức tái dùng (≥ 3 mẫu).
- [ ] Có audit đường chuyển đổi và chỉ ra điểm rơi lớn nhất.
- [ ] Có ít nhất một đề xuất DỪNG cụ thể.
- [ ] Mỗi kênh kết bằng quyết định giữ/sửa/dừng, không mô tả suông.

## Tình huống đặc biệt
### Trường hợp — Không export được số, chỉ có cảm giác
**Cách phát hiện:** người dùng nói "bài này hình như tốt".
**Cách xử lý:** liệt kê chính xác cần export gì và cách lấy; không dựng baseline bằng ước lượng.
**Không được:** ghi số phỏng đoán vào baseline.
### Trường hợp — Kênh mới chạy < 8 tuần
**Cách xử lý:** mô tả xu hướng, gắn `[CHƯA ĐỦ MẪU]`, hoãn quyết định dừng.
**Không được:** kết luận "kênh này không hiệu quả" khi chưa đủ mẫu.

## Anti-Patterns
- Không phán "viral/flop" mà không có số.
- Không kết luận trên dữ liệu < 8 tuần.
- Không phân tích mà không ra quyết định giữ/sửa/dừng.
- Không né việc đề xuất dừng vì sợ mất lòng.

## Recovery
### Khi thiếu số liệu
Xuất khung baseline rỗng + hướng dẫn export theo từng nền tảng; hẹn chạy lại khi có số.
### Khi validation thất bại
Chưa có đề xuất dừng → quay lại Giai đoạn 3, buộc chọn thứ kém nhất để dừng.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Audit giúp tôi các kênh social, đây là số liệu 6 tháng."
**Có kích hoạt:** Có. **Hành vi:** dựng baseline, giải mã top, ra quyết định.
### Test 2 — Trigger một phần
**Prompt:** "Vì sao mấy bài này nhiều view hơn hẳn?"
**Có kích hoạt:** Có (mục 5) — rút công thức tái dùng.
### Test 3 — Không nên kích hoạt
**Prompt:** "Lên pillar nội dung cho quý tới."
**Có kích hoạt:** Không (Content Strategy — 12).
### Test 4 — Đầu vào thiếu
**Prompt:** "Kênh của tôi ổn không?" (không có số).
**Hành vi:** hỏi export gì, không phán bằng cảm giác.
### Test 5 — Ngoại lệ
**Prompt:** kênh mới chạy 3 tuần, hỏi nên bỏ không.
**Hành vi:** gắn `[CHƯA ĐỦ MẪU]`, hoãn quyết định.
