# VALIDATION KIT — Cổng kiểm chứng bộ Marketing Growth OS

Mục đích: kiểm chứng một skill **trước khi tin nó vào việc thật**. Một skill chưa qua Lớp 1 thì chưa được coi là dùng được. Bộ kiểm này dùng chung một case giả lập ("Măng Non") và 6 bẫy mà mọi skill phải chống được, cộng với rubric riêng theo từng skill.

## Cách chạy
1. Mở phiên Claude mới (sạch context).
2. Nạp `SKILL.md` của skill cần kiểm.
3. Dán prompt của case Măng Non tương ứng skill đó.
4. Chấm theo rubric: mỗi tiêu chí Đạt/Không. **Không đạt bất kỳ tiêu chí "cơ chế lõi" nào = trượt, phải sửa skill.**

---

## Case giả lập — "Măng Non"
Dùng làm dữ liệu đầu vào chung để test mọi skill.

> **Măng Non** — thương hiệu bán bột rau củ cho trẻ ăn dặm, thành lập 2023, founder là một bà mẹ bỉm.
> - Sản phẩm: Bột rau củ hộp 200g giá 180k (giá vốn: *không nhớ*); Combo 3 hộp 480k; Khoá học ăn dặm online 990k.
> - Doanh thu ~120 triệu/tháng, chủ yếu từ TikTok Shop. Ngân sách marketing 15 triệu/tháng.
> - Team: founder (lên hình được, ~5h/tuần) + 1 bạn part-time dựng video.
> - BOD (chính là founder) nói: *"Tôi muốn bán chạy hơn và ai cũng biết đến Măng Non."*
> - Đã chạy: đăng TikTok đều, "có bài mấy chục nghìn view mà không ra đơn".
> - Không có: số liệu export, giá vốn, tỷ lệ chốt, câu nói khách thật.

---

## 6 BẪY mọi skill phải chống được

### Bẫy 1 — Bịa số
**Kích:** hỏi skill một con số case không cung cấp (giá vốn, tỷ lệ chốt, quy mô thị trường).
**Đạt:** gắn `[CẦN BỔ SUNG: cách lấy]`, không đưa con số cụ thể.
**Trượt:** tự điền một con số nghe hợp lý.

### Bẫy 2 — Suy luận không nhãn
**Kích:** để skill diễn giải kỳ vọng mơ hồ của BOD ("bán chạy hơn").
**Đạt:** gắn `[GIẢ ĐỊNH]` + lý do, hoặc dịch thành mục tiêu có số kèm `[CHỜ BOD]`.
**Trượt:** khẳng định mục tiêu như thể BOD đã chốt.

### Bẫy 3 — Kế thừa sai / lặp lại
**Kích:** cung cấp một dữ kiện đã có ở tài liệu trước, hơi khác đi.
**Đạt:** phát hiện, gắn `[MÂU THUẪN]`, dừng hỏi.
**Trượt:** âm thầm chọn một bản hoặc hỏi lại từ đầu thứ đã có.

### Bẫy 4 — Mô tả suông, không quyết định
**Kích:** yêu cầu output.
**Đạt:** kết bằng quyết định (làm gì / KHÔNG làm gì / ai / đo bằng gì).
**Trượt:** dừng ở mô tả, không có quyết định hay đề xuất dừng.

### Bẫy 5 — Vượt năng lực / nguồn lực
**Kích:** yêu cầu quy mô vượt team 5h/tuần + 15 triệu (vd 5 kênh, 60 video/tháng).
**Đạt:** đối chiếu công suất, ép về khả thi, ghi rõ cắt gì.
**Trượt:** đồng ý kế hoạch team không kham nổi.

### Bẫy 6 — Chạy sai thứ tự phụ thuộc
**Kích:** yêu cầu skill 09 (hoặc bất kỳ skill nào) khi tài liệu phụ thuộc chưa có.
**Đạt:** chặn, nêu thiếu gì, đề xuất chạy phụ thuộc trước.
**Trượt:** vẫn tạo output đầy đủ như thể đủ dữ liệu.

---

## Rubric Lớp 1 theo từng skill
Với mỗi skill, ngoài 6 bẫy chung, kiểm thêm 2–3 tiêu chí đặc thù (lấy từ checklist chất lượng trong SKILL.md). Ví dụ trọng yếu:

| Skill | Tiêu chí đặc thù bắt buộc Đạt |
|---|---|
| 01 Overview | Quy nhân sự ra công suất thật/tuần; chốt đúng MỘT vấn đề ưu tiên |
| 02 Brand Bible | Định vị loại trừ được ≥1 nhóm khách; mỗi Core Value có hành vi đi ngược |
| 03 Guideline | Mỗi quy tắc truy ngược về một tính từ Personality; font đủ dấu tiếng Việt |
| 04 Social Analysis | Dữ liệu <8 tuần gắn `[CHƯA ĐỦ MẪU]`; có ≥1 đề xuất DỪNG |
| 05 Market Research | Mỗi số có nguồn+năm+phương pháp; kết bằng giả định cần kiểm |
| 06 Competitor | Chỉ dùng dữ liệu quan sát được; mỗi khoảng trống trả lời "vì sao chưa ai chiếm" |
| 07 Persona | Không có câu khách thật → gắn `[CẦN PHỎNG VẤN]`; có nhóm KHÔNG phục vụ |
| 08 Offer Map | Sản phẩm không vai → đề xuất dừng; không giảm giá để xử lý rào cản |
| 09 Strategy | Mục tiêu tính ngược ra lead/traffic; có mục "KHÔNG làm gì" |
| 10 Funnel | Mỗi giai đoạn đúng 1 chỉ số; vá theo ROI |
| 11 Channel | ≤2 kênh chính; mỗi kênh có điều kiện dừng bằng số |
| 12 Content Strategy | Pillar không map insight+phễu → loại; bán ≤30% |
| 13 Roadmap/RACI | Mỗi việc đúng 1 người R; ngân sách dự phòng ≥10% |
| 14 Calendar | Mỗi nội dung có pillar+phễu; hook 3 giây viết thành lời |
| 15 KPI | Mỗi KPI đủ 6 thành phần; báo cáo kết bằng hành động+người+deadline |
| A0 Orchestrator | Chặn 09 khi thiếu 01/07/08; không bắt làm lại thứ đã có |
| A1–A5 Runners | Dừng Gate đúng chỗ; kế thừa bản đã duyệt; đủ file đầu ra |

## Kết luận kiểm
- **Qua Lớp 1:** đạt cả 6 bẫy + tiêu chí đặc thù → skill được phép dùng vào việc thật.
- **Trượt:** ghi lỗi cụ thể, sửa nguyên nhân gốc trong SKILL.md, chạy lại từ phiên sạch.
- **Lớp 2 (khuyến nghị):** chạy skill trên dữ liệu thật của một thương hiệu và để người trong nghề review output trước khi tiêu ngân sách.
