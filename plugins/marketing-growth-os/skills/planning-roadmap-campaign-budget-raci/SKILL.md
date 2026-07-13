---
name: planning-roadmap-campaign-budget-raci
description: gắn deadline và tên người vào chiến lược — rải mục tiêu ra từng tháng, gắn chiến dịch, mỗi đầu việc đúng một người chịu trách nhiệm chính, đối chiếu khối lượng với công suất và giữ ngân sách có dự phòng ≥10%. không có bước này thì chiến lược chỉ là file trôi nổi. dùng khi người dùng muốn làm roadmap marketing, timeline, campaign plan, phân bổ ngân sách, bảng RACI, phân vai trách nhiệm, kể cả khi chỉ yêu cầu một phần như "chia việc theo tháng" hoặc "lập ngân sách marketing". không dùng cho content calendar chi tiết, chiến lược, hay KPI.
---

# Roadmap · Campaign · Budget · RACI
Thực hiện tài liệu số 13 của Marketing Growth OS: gắn deadline và tên người vào chiến lược, nếu không nó chỉ là file trôi nổi. Đối tượng đọc: trưởng marketing, PM, BOD.

## Nguyên tắc cốt lõi
Mỗi đầu việc chỉ được có **ĐÚNG MỘT người chịu trách nhiệm chính** — không có "cả team làm". Tổng khối lượng phải đối chiếu công suất ở tài liệu 01; vượt thì **cắt và nói rõ cắt gì**. Ngân sách phải có **dự phòng ≥ 10%**.

## Đặc tả kết quả
- Định dạng: Markdown, bảng roadmap theo tháng + bảng RACI + bảng ngân sách.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: trưởng marketing, PM, BOD.
- Phạm vi: roadmap + campaign + ngân sách + RACI, 1.200–2.000 từ.
- Giọng điệu: điều hành, có deadline và tên người.
- Quy tắc nguồn: quỹ thời gian từng người, ngân sách lấy từ người dùng; thiếu → `[CẦN BỔ SUNG]`, không tự gán giờ công.
- File đầu ra: `13-roadmap-campaign-budget-raci.md`.
- Tuyệt đối không được tự bịa: quỹ thời gian nhân sự, đơn giá công việc, chi phí hạng mục.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần 09 (mục tiêu, Big Idea), 11 (kênh, ngân sách kênh), 12 (pillar). Và 01 (công suất team). Thiếu 01 → không đối chiếu được khối lượng.

## Quy trình

### Giai đoạn 1 — Thu thập ràng buộc vận hành
**Đầu vào bắt buộc:** mốc kinh doanh cố định (mùa vụ, sự kiện); danh sách team + quỹ thời gian từng người; ngân sách tổng; quy trình duyệt.
**Đầu vào tùy chọn:** đối tác ngoài, công cụ, chi phí cố định.
**Mặc định:** thiếu quỹ giờ → dùng công suất từ 01; thiếu cả 01 → dừng.
**Thực hiện:** đọc 09/11/12/01; hỏi tối đa 5 câu (mốc kinh doanh cố định, ai làm được gì và bao nhiêu giờ/tuần, ngân sách tổng, ai được ký duyệt, có thuê ngoài không).
**Điều kiện hoàn thành:** có mốc + team + quỹ giờ + ngân sách.

### Giai đoạn 2 — Rải mục tiêu & gắn chiến dịch
1. Rải mục tiêu (09) ra từng tháng của kỳ.
2. Gắn chiến dịch vào từng tháng quanh mốc kinh doanh; mỗi chiến dịch: mục tiêu, kênh (11), pillar (12).
3. Xếp thứ tự chiến dịch theo ưu tiên chiến lược.

### Giai đoạn 3 — RACI, ngân sách, kiểm tải
1. Bảng RACI: mỗi đầu việc **đúng một R (Responsible)**; A/C/I rõ ràng.
2. Bảng ngân sách theo hạng mục + kênh; **dự phòng ≥ 10%**.
3. **Kiểm tải:** tổng giờ việc vs quỹ giờ team. Vượt → cắt hạng mục cụ thể và ghi rõ cắt gì, hoãn gì.

### Giai đoạn 4 — Kiểm tra và sửa
1. Mỗi việc đúng một R? Ngân sách có dự phòng ≥ 10%? Khối lượng ≤ công suất? Mọi chiến dịch có deadline?
2. Sửa, kiểm lại.

### Giai đoạn 5 — Bàn giao
Xuất `13-roadmap-campaign-budget-raci.md`. Nạp vào 14 (lịch sản xuất theo chiến dịch), 15 (KPI theo mốc).

## Cấu trúc kết quả
1. Roadmap theo tháng. 2. Campaign plan (mục tiêu/kênh/pillar mỗi chiến dịch). 3. Bảng ngân sách (+ dự phòng ≥10%). 4. Bảng RACI (mỗi việc một R). 5. Kết quả kiểm tải + phần cắt/hoãn.

## Checklist chất lượng
- [ ] Mỗi đầu việc có đúng một người chịu trách nhiệm chính (R).
- [ ] Ngân sách có dự phòng ≥ 10%.
- [ ] Tổng khối lượng ≤ công suất team (01); vượt thì ghi rõ cắt gì.
- [ ] Mỗi chiến dịch có deadline và mốc kinh doanh.
- [ ] Không bịa quỹ giờ hay đơn giá.

## Tình huống đặc biệt
### Trường hợp — Khối lượng vượt xa năng lực
**Cách xử lý:** trình bảng kiểm tải, đề xuất cắt theo ưu tiên chiến lược, hoặc thuê ngoài có chi phí.
**Không được:** nhồi lịch rồi để team vỡ.
### Trường hợp — "Cả team cùng làm" một việc
**Cách xử lý:** ép chỉ định một R, người khác thành C/I.
**Không được:** để trách nhiệm chung chung.

## Anti-Patterns
- Không để một việc nhiều R.
- Không bỏ dự phòng ngân sách.
- Không lập lịch vượt công suất mà không cắt.
- Không bịa chi phí/giờ công.

## Recovery
### Khi thiếu quỹ giờ/ngân sách
Dùng công suất từ 01, gắn `[CẦN BỔ SUNG]` cho phần thiếu; không tự gán số.
### Khi validation thất bại
Vượt tải → cắt hạng mục, cập nhật roadmap, ghi phần hoãn.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Lập roadmap, ngân sách và RACI cho quý tới."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Chia việc marketing theo từng tháng giúp tôi."
**Có kích hoạt:** Có (roadmap + RACI).
### Test 3 — Không nên kích hoạt
**Prompt:** "Viết kịch bản 20 video tháng sau."
**Có kích hoạt:** Không (Content Calendar — 14).
### Test 4 — Đầu vào thiếu
**Prompt:** "Lập ngân sách marketing" (không có tổng ngân sách).
**Hành vi:** hỏi ngân sách tổng, không bịa hạng mục.
### Test 5 — Ngoại lệ
**Prompt:** kế hoạch cần 200 giờ, team có 80 giờ.
**Hành vi:** kiểm tải, cắt theo ưu tiên, ghi rõ cắt gì.
