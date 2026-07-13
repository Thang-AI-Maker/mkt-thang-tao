---
name: researching-market
description: xác định quy mô và sức hấp dẫn thị trường bằng ước tính top-down/bottom-up có phương pháp, tách phân khúc, chấm điểm hấp dẫn và chốt danh sách giả định cần kiểm chứng kèm cách kiểm rẻ nhất. dùng khi người dùng muốn nghiên cứu thị trường, ước tính quy mô ngành, TAM SAM SOM, phân khúc, đánh giá thị trường đang lên hay xuống, mùa vụ, ràng buộc pháp lý, kể cả khi chỉ yêu cầu một phần như "thị trường này to cỡ nào". không dùng cho phân tích đối thủ, persona khách hàng, hay chiến lược marketing.
---

# Market Research
Thực hiện tài liệu số 05 của Marketing Growth OS: xác định sân chơi to hay nhỏ, đang lên hay xuống, để tài liệu chiến lược đặt mục tiêu thực tế. Đối tượng đọc: founder, trưởng marketing, BOD.

## Nguyên tắc cốt lõi
Mọi con số quy mô phải có **nguồn và năm** cùng phương pháp ước tính rõ ràng. Một con số thị trường không nêu được lấy từ đâu là con số vô dụng. **Nghiên cứu kết thúc không phải bằng "thị trường lớn" mà bằng danh sách giả định cần kiểm chứng.**

## Đặc tả kết quả
- Định dạng: Markdown, có bảng.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: BOD, trưởng marketing.
- Phạm vi: quy mô + phân khúc + xu hướng + giả định, khoảng 1.000–1.800 từ.
- Giọng điệu: khách quan, dựa nguồn.
- Quy tắc nguồn: mỗi số ghi `(nguồn, năm, phương pháp: top-down/bottom-up)`. Không có nguồn → `[CẦN BỔ SUNG]` hoặc `[GIẢ ĐỊNH]` + cách kiểm.
- File đầu ra: `05-market-research.md`.
- Tuyệt đối không được tự bịa: số quy mô thị trường, tốc độ tăng trưởng, thị phần — nếu không tra được thì nói rõ chưa có nguồn.

## Hệ thống nhãn
`[GIẢ ĐỊNH]` · `[CẦN BỔ SUNG: cách lấy]` · `[CHỜ BOD]` · `[MÂU THUẪN: …]`.

## Kế thừa từ tài liệu trước
Cần tài liệu 01 (ngành, sản phẩm, giá, địa lý). Chưa có → hỏi ngành và phạm vi trước khi ước tính.

## Quy trình

### Giai đoạn 1 — Thu thập bối cảnh
**Đầu vào bắt buộc:** ngành/danh mục; phạm vi địa lý; mức giá phổ biến; mùa vụ; ràng buộc pháp lý.
**Đầu vào tùy chọn:** báo cáo ngành sẵn có, số khách hiện tại, dữ liệu bán hàng.
**Mặc định:** không có báo cáo ngành → ưu tiên bottom-up từ dữ liệu doanh nghiệp và nêu rõ giới hạn.
**Thực hiện:** đọc tài liệu 01; hỏi một lần tối đa 5 câu nếu thiếu (ngành cụ thể, vùng bán, giá phổ biến, có ràng buộc pháp lý không, đã có báo cáo ngành nào chưa).
**Điều kiện hoàn thành:** rõ ngành + phạm vi địa lý + mức giá. Thiếu → không ước tính quy mô.

### Giai đoạn 2 — Ước tính quy mô có phương pháp
1. Chọn **top-down** (từ số ngành công bố xuống) hoặc **bottom-up** (số khách tiềm năng × tần suất × giá) — nêu rõ đang dùng cái nào và vì sao.
2. Trình bày TAM / SAM / SOM, mỗi tầng ghi giả định và nguồn.
3. Kiểm tra chéo: hai phương pháp lệch nhau quá xa → gắn `[MÂU THUẪN]` và giải thích.

### Giai đoạn 3 — Phân khúc & xu hướng
1. Tách 3–5 phân khúc; chấm sức hấp dẫn từng phân khúc (quy mô, tăng trưởng, khả năng tiếp cận, mức cạnh tranh, biên lợi nhuận).
2. Nêu xu hướng: đang lên / đi ngang / xuống + tín hiệu.
3. Ghi mùa vụ và ràng buộc pháp lý ảnh hưởng marketing.

### Giai đoạn 4 — Chốt giả định cần kiểm chứng
1. Liệt kê các `[GIẢ ĐỊNH]` đã dùng.
2. Với mỗi giả định: **cách kiểm rẻ nhất** (khảo sát nhỏ, chạy test ad, phỏng vấn 5 khách).
3. Kiểm lại: mọi số có nguồn/năm? Phương pháp rõ? Sửa nếu thiếu.

### Giai đoạn 5 — Bàn giao
Xuất `05-market-research.md` + danh sách giả định cần kiểm chứng. Nạp vào tài liệu 06 và 09.

## Cấu trúc kết quả
1. Định nghĩa thị trường & phạm vi. 2. Ước tính quy mô (TAM/SAM/SOM + phương pháp). 3. Phân khúc + bảng chấm hấp dẫn. 4. Xu hướng & mùa vụ. 5. Ràng buộc pháp lý. 6. Danh sách giả định cần kiểm chứng + cách kiểm rẻ nhất.

## Checklist chất lượng
- [ ] Mỗi con số có nguồn, năm và phương pháp.
- [ ] Nêu rõ dùng top-down hay bottom-up.
- [ ] Có bảng chấm sức hấp dẫn phân khúc.
- [ ] Kết bằng danh sách giả định + cách kiểm rẻ nhất, không kết bằng "thị trường lớn".
- [ ] Không có số quy mô nào không truy được nguồn.

## Tình huống đặc biệt
### Trường hợp — Không có báo cáo ngành đáng tin
**Cách xử lý:** dùng bottom-up từ dữ liệu doanh nghiệp, nêu rõ độ tin cậy thấp, đề xuất kiểm bằng test rẻ.
**Không được:** trích số từ nguồn không kiểm chứng như thể là sự thật.
### Trường hợp — Thị trường ngách rất nhỏ
**Cách xử lý:** cảnh báo trần doanh thu; gợi ý mở rộng phân khúc kề hoặc chấp nhận quy mô nhỏ có chủ đích.
**Không được:** thổi phồng quy mô để hợp lý hóa ngân sách.

## Anti-Patterns
- Không đưa số thị trường không nguồn.
- Không trộn top-down và bottom-up mà không ghi rõ.
- Không bỏ qua mùa vụ và pháp lý.
- Không kết thúc mà thiếu giả định cần kiểm.

## Recovery
### Khi thiếu dữ liệu ngành
Chuyển sang bottom-up, ghi rõ giới hạn, đề xuất khảo sát nhỏ.
### Khi validation thất bại
Hai phương pháp lệch xa → trình bày cả hai, gắn `[MÂU THUẪN]`, không chọn bừa.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Nghiên cứu quy mô thị trường ngành X ở Việt Nam."
**Có kích hoạt:** Có.
### Test 2 — Trigger một phần
**Prompt:** "Thị trường này to cỡ nào, đang lên hay xuống?"
**Có kích hoạt:** Có.
### Test 3 — Không nên kích hoạt
**Prompt:** "Phân tích 5 đối thủ của tôi."
**Có kích hoạt:** Không (Competitor Analysis — 06).
### Test 4 — Đầu vào thiếu
**Prompt:** "Thị trường của tôi thế nào?" (chưa rõ ngành/vùng).
**Hành vi:** hỏi ngành + phạm vi trước khi ước tính.
### Test 5 — Ngoại lệ
**Prompt:** ngành mới chưa có báo cáo.
**Hành vi:** bottom-up + ghi độ tin cậy thấp + cách kiểm rẻ.
