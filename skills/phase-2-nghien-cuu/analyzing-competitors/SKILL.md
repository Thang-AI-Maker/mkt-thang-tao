---
name: analyzing-competitors
description: tìm khoảng trống đối thủ chưa chiếm bằng cách chỉ ghi nhận điều quan sát được, dựng bản đồ định vị, và với mỗi khoảng trống trả lời "vì sao họ chưa chiếm". dùng khi người dùng muốn phân tích đối thủ, competitor analysis, so sánh giá và nội dung đối thủ, tìm khoảng trống thị trường, bản đồ định vị, kể cả khi chỉ yêu cầu một phần như "đối thủ đang mạnh chỗ nào". không dùng cho nghiên cứu quy mô thị trường, persona, hay chiến lược.
---

# Competitor Analysis
Thực hiện tài liệu số 06 của Marketing Growth OS: tìm chỗ trống đối thủ chưa chiếm để giành, không phải để bắt chước. Đối tượng đọc: trưởng marketing, BOD.

## Nguyên tắc cốt lõi
Chỉ ghi nhận điều **QUAN SÁT ĐƯỢC** (giá công khai, nội dung công khai, phản hồi khách công khai). Cấm suy diễn nội bộ đối thủ. Với mỗi khoảng trống phải trả lời: **vì sao họ chưa chiếm?** — nếu vì nó không có tiền thì đó không phải khoảng trống, đó là cái bẫy.

## Đặc tả kết quả
- Định dạng: Markdown, bảng so sánh + bản đồ định vị (mô tả trục).
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: BOD, trưởng marketing.
- Phạm vi: 5–10 đối thủ, khoảng 1.200–2.000 từ.
- Giọng điệu: khách quan, chỉ dựa quan sát.
- Quy tắc nguồn: mỗi nhận định gắn `(quan sát: link/ngày)`; suy đoán gắn `[GIẢ ĐỊNH]`.
- File đầu ra: `06-competitor-analysis.md`.
- Tuyệt đối không được tự bịa: doanh thu đối thủ, ngân sách ads, chiến lược nội bộ, số nhân sự — trừ khi công khai và có nguồn.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[QUAN SÁT]` (có link) · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần 01 (định vị mình) và 05 (phân khúc, quy mô). Chưa có 05 → vẫn phân tích được nhưng không đánh giá được khoảng trống có tiền hay không.

## Quy trình

### Giai đoạn 1 — Thu thập dữ liệu quan sát
**Đầu vào bắt buộc:** 5–10 đối thủ + link; giá công khai; 3–5 nội dung mạnh nhất của mỗi đối thủ; phản hồi xấu khách nói về họ.
**Đầu vào tùy chọn:** đối thủ gián tiếp/giải pháp thay thế, kênh chính của họ.
**Mặc định:** không đủ 5 đối thủ → phân tích số có, ghi thiếu.
**Thực hiện:** đọc dữ liệu; hỏi một lần tối đa 5 câu (ai là đối thủ trực tiếp thật sự, khách hay so mình với ai, giá họ công khai không, họ mạnh nội dung gì, khách chê họ điều gì).
**Điều kiện hoàn thành:** ≥ 3 đối thủ có giá + nội dung quan sát được.

### Giai đoạn 2 — Bảng so sánh & bản đồ định vị
1. Lập bảng: mỗi đối thủ × (định vị, giá, nội dung mạnh, điểm khách khen, điểm khách chê).
2. Chọn 2 trục có ý nghĩa mua hàng (không phải trục vô thưởng vô phạt) → đặt các đối thủ lên bản đồ, xem ai chiếm ô nào.

### Giai đoạn 3 — Đọc khoảng trống
1. Xác định các ô còn trống trên bản đồ.
2. Với mỗi ô trống hỏi: **vì sao chưa ai chiếm?** (không có nhu cầu / không có tiền / khó làm / họ bỏ sót).
3. Loại các ô trống "không có tiền". Giữ ô trống có nhu cầu chưa được phục vụ.
4. Cảnh báo đối thủ KHÔNG nên đối đầu trực diện (họ quá mạnh ở ô đó).

### Giai đoạn 4 — Kiểm tra và sửa
1. Mọi nhận định có `[QUAN SÁT]` hay đang là suy diễn nội bộ? Mỗi khoảng trống đã trả lời "vì sao trống"?
2. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `06-competitor-analysis.md` + bản đồ khoảng trống. Nạp vào 07 (insight) và 09 (chiến lược).

## Cấu trúc kết quả
1. Danh sách đối thủ + phân loại (trực tiếp/gián tiếp). 2. Bảng so sánh. 3. Bản đồ định vị (2 trục). 4. Khoảng trống + lý do chưa ai chiếm. 5. Đối thủ không nên đối đầu. 6. Kết luận: ô nào nên chiếm.

## Checklist chất lượng
- [ ] Mọi nhận định dựa quan sát công khai, có link/ngày.
- [ ] Không có số nội bộ đối thủ bịa ra.
- [ ] Bản đồ dùng 2 trục có ý nghĩa mua hàng.
- [ ] Mỗi khoảng trống trả lời được "vì sao chưa ai chiếm".
- [ ] Đã loại các khoảng trống "không có tiền".
- [ ] Có cảnh báo đối thủ không nên đối đầu.

## Tình huống đặc biệt
### Trường hợp — Đối thủ giấu giá
**Cách xử lý:** ghi `[CẦN BỔ SUNG: hỏi báo giá ẩn danh]`, không đoán giá.
**Không được:** bịa khoảng giá.
### Trường hợp — "Khoảng trống" thực ra là vùng không có nhu cầu
**Cách phát hiện:** không ai chiếm và cũng không có tín hiệu cầu.
**Cách xử lý:** đánh dấu là bẫy, không đề xuất chiếm.
**Không được:** coi mọi ô trống là cơ hội.

## Anti-Patterns
- Không suy diễn chiến lược nội bộ đối thủ.
- Không bịa doanh thu/ngân sách đối thủ.
- Không chọn trục bản đồ vô nghĩa để tạo cảm giác khác biệt.
- Không coi ô trống không có tiền là cơ hội.

## Recovery
### Khi thiếu đối thủ/dữ liệu
Phân tích số có, ghi rõ mẫu nhỏ, đề xuất bổ sung quan sát.
### Khi validation thất bại
Có nhận định không nguồn → hạ xuống `[GIẢ ĐỊNH]` hoặc bỏ.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Phân tích đối thủ, đây là 6 brand và link của họ."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Đối thủ đang mạnh nội dung chỗ nào?"
**Có kích hoạt:** Có.
### Test 3 — Không nên kích hoạt
**Prompt:** "Thị trường ngành này to cỡ nào?"
**Có kích hoạt:** Không (Market Research — 05).
### Test 4 — Đầu vào thiếu
**Prompt:** "Đối thủ của tôi thế nào?" (chưa nêu ai).
**Hành vi:** hỏi ai là đối thủ trực tiếp trước.
### Test 5 — Ngoại lệ
**Prompt:** chỉ ra một "khoảng trống" mà không ai làm vì không có cầu.
**Hành vi:** đánh dấu bẫy, không đề xuất.
