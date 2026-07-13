---
name: building-business-brand-overview
description: tạo tài liệu Business & Brand Overview và bảng đánh giá năng lực marketing nội bộ từ thông tin thô của chủ doanh nghiệp, kèm chuyển kỳ vọng BOD thành mục tiêu đo được và chốt vấn đề marketing ưu tiên. dùng khi người dùng muốn dựng tài liệu nền tảng đầu tiên của bộ hồ sơ marketing, làm business overview, tổng quan doanh nghiệp, audit năng lực team marketing, hoặc khi họ đưa số liệu doanh thu, giá sản phẩm, ngân sách và nhân sự rồi hỏi "marketing nên bắt đầu từ đâu", kể cả khi chỉ yêu cầu một phần như "đánh giá team marketing của tôi đủ sức làm gì". không dùng cho brand bible, brand guideline, nghiên cứu thị trường, phân tích đối thủ, persona hay lập kế hoạch content.
---

# Business & Brand Overview
Thực hiện tài liệu nền tảng số 01 của Marketing Growth OS: từ thông tin thô do chủ doanh nghiệp cung cấp, tạo bản Business & Brand Overview kèm bảng năng lực marketing nội bộ, để trưởng bộ phận marketing và BOD chốt được vấn đề ưu tiên trước khi tiêu bất kỳ đồng ngân sách nào.

## Nguyên tắc cốt lõi
Tài liệu này quyết định trần của mọi tài liệu phía sau. Một con số bịa ở đây sẽ được các skill kế thừa dùng như sự thật. **Thà để trống có nhãn còn hơn điền cho đủ.**

## Đặc tả kết quả
- Định dạng: Markdown, có bảng.
- Ngôn ngữ: tiếng Việt.
- Đối tượng đọc: trưởng bộ phận marketing, founder, BOD.
- Phạm vi: 8 phần bắt buộc (xem "Cấu trúc kết quả"), khoảng 900–1.500 từ. Vượt 2.000 từ là dấu hiệu đang mô tả thay vì quyết định.
- Giọng điệu: thẳng, khô, ra quyết định. Không dùng ngôn ngữ tiếp thị.
- Quy tắc nguồn: mọi con số phải kèm nguồn — `(BOD cung cấp)`, `(ước tính, phương pháp: …)`, hoặc nhãn `[CẦN BỔ SUNG]`.
- File đầu ra: `01-business-brand-overview.md` — chỉ tạo file khi môi trường hỗ trợ; nếu không, trả trực tiếp trong hội thoại.
- Giả định được phép: giai đoạn phát triển doanh nghiệp, vai trò sản phẩm, khoảng trống năng lực, diễn giải kỳ vọng BOD — tất cả phải gắn `[GIẢ ĐỊNH]` kèm một dòng lý do.
- Tuyệt đối không được tự bịa: doanh thu, chi phí, giá vốn, biên lợi nhuận, số khách hàng, số lead, tỷ lệ chuyển đổi, kết quả các hoạt động marketing đã chạy, câu nói của khách hàng.

## Hệ thống nhãn
| Nhãn | Nghĩa | Ai xử lý |
|---|---|---|
| `[GIẢ ĐỊNH]` | AI suy ra, chưa được xác nhận | Người dùng xác nhận hoặc bác bỏ |
| `[CẦN BỔ SUNG: cách lấy]` | Thiếu dữ liệu, AI không được đoán | Người dùng đi lấy dữ liệu |
| `[CHỜ BOD]` | Cần quyết định cấp lãnh đạo | Trình BOD chốt |
| `[MÂU THUẪN: …]` | Hai thông tin người dùng đưa xung khắc nhau | Làm rõ trước khi đi tiếp |

## Quy trình

### Giai đoạn 1 — Thu thập đầu vào
**Mục tiêu:** có đủ dữ kiện thô để không phải đoán ở các giai đoạn sau.
**Đầu vào bắt buộc (9 mục):**
1. Tên doanh nghiệp và mô hình kinh doanh.
2. Danh sách sản phẩm/dịch vụ kèm giá bán từng cái.
3. Doanh thu 3–12 tháng gần nhất.
4. Mục tiêu doanh thu kỳ tới và thời hạn.
5. Ngân sách marketing mỗi tháng.
6. Team marketing hiện có: bao nhiêu người, ai làm gì, full-time hay part-time.
7. Founder: có lên hình được không, mỗi tuần dành được bao nhiêu giờ.
8. Vấn đề lớn nhất BOD muốn marketing giải quyết (chép nguyên văn lời BOD).
9. Các hoạt động marketing đã làm và kết quả thô.

**Đầu vào tùy chọn:** giá vốn từng sản phẩm; tỷ lệ chốt của sale; số khách hàng hiện tại; công cụ đang dùng; đối tác bên ngoài; quy trình duyệt nội dung.
**Mặc định được phép dùng:** nếu không có giá vốn → không tính biên lợi nhuận, ghi `[CẦN BỔ SUNG]`, tuyệt đối không suy CAC trần từ số tự nghĩ. Nếu không có tỷ lệ chốt → không tính ngược ra số lead cần có.

**Thực hiện:**
1. Đọc toàn bộ thông tin người dùng đã cung cấp. Không hỏi lại thứ đã có.
2. Đối chiếu với 9 mục bắt buộc, liệt kê mục nào thiếu.
3. Nếu thiếu, hỏi **một lần, tối đa 5 câu**, ưu tiên câu chặn tiến độ:
   - Trong các sản phẩm, cái nào biên lợi nhuận tốt nhất?
   - Marketing hiện đang được đánh giá bằng chỉ số gì?
   - Có sản phẩm nào BOD muốn ngừng bán không?
   - Nếu chỉ được chọn MỘT kết quả trong 90 ngày tới, đó là gì?
   - Ngân sách marketing là trần cứng hay tăng được nếu chứng minh hiệu quả?

**Điều kiện hoàn thành:** có đủ mục 1, 2, 5, 6, 8 (năm mục tối thiểu). Thiếu bất kỳ mục nào trong năm mục này thì không viết tài liệu.
**Nếu thất bại:** thiếu 5 mục tối thiểu → dừng, nêu rõ thiếu gì và vì sao không thể viết, không sinh bản nháp "cho có".

### Giai đoạn 2 — Phân loại dữ kiện
**Mục tiêu:** tách sự thật khỏi phỏng đoán trước khi viết một chữ nào.
**Đầu vào:** kết quả Giai đoạn 1.
**Thực hiện:** với từng dữ kiện, gán đúng một loại:
- **Sự thật:** người dùng nói chắc chắn → dùng trực tiếp, ghi `(BOD cung cấp)`.
- **Số ước lượng:** người dùng nói bằng khoảng, "khoảng", "tầm", "không nhớ chính xác" → giữ nguyên dạng khoảng, ghi `(chủ doanh nghiệp ước tính)`, **không lấy giá trị giữa để tính toán tiếp**.
- **Suy ra được:** rút ra từ dữ kiện đã có → gắn `[GIẢ ĐỊNH]` + lý do.
- **Không có:** gắn `[CẦN BỔ SUNG: cách lấy rẻ nhất]`.

**Điều kiện hoàn thành:** mọi dữ kiện đã có đúng một nhãn.
**Nếu thất bại:** hai dữ kiện người dùng đưa xung khắc nhau (ví dụ doanh thu 400tr/tháng nhưng chỉ 30 học viên × 3,6tr) → gắn `[MÂU THUẪN]`, hỏi lại, không tự chọn số nào.

### Giai đoạn 3 — Suy luận (phần AI tạo giá trị)
**Mục tiêu:** biến dữ kiện thô thành các kết luận dùng được.
**Thực hiện:**
1. **Giai đoạn phát triển** doanh nghiệp và hệ quả với marketing.
2. **Cấu trúc doanh thu:** sản phẩm nào đang gánh doanh thu, sản phẩm nào gánh lợi nhuận. Khác nhau → nói rõ.
3. **Trần CAC:** chỉ tính khi có giá vốn hoặc biên lợi nhuận. Không có → `[CẦN BỔ SUNG]`, không đoán.
4. **Năng lực đội ngũ:** quy đổi nhân sự ra công suất thật (số nội dung/tuần, số kênh vận hành nổi). So với tham vọng để tìm khoảng cách.
5. **Tách triệu chứng khỏi bệnh:** vấn đề BOD nêu thường là triệu chứng. Nêu triệu chứng, nêu 1–3 nguyên nhân gốc khả dĩ (mỗi cái gắn `[GIẢ ĐỊNH]` + cách kiểm chứng).
6. **Dịch kỳ vọng BOD thành mục tiêu đo được:** mỗi kỳ vọng định tính → 1–3 phương án mục tiêu có số và thời hạn, gắn `[CHỜ BOD]`.

**Điều kiện hoàn thành:** đủ 6 kết luận, mỗi kết luận truy ngược được về ít nhất một dữ kiện ở Giai đoạn 2.
**Nếu thất bại:** một kết luận không truy ngược được → xóa hoặc hạ xuống thành `[CẦN BỔ SUNG]`.

### Giai đoạn 4 — Viết và tự kiểm
**Thực hiện:**
1. Viết theo đúng "Cấu trúc kết quả" bên dưới, không đảo thứ tự, không bỏ phần.
2. Chạy toàn bộ "Checklist chất lượng".
3. Ghi nhận từng mục trượt kèm vị trí cụ thể.
4. Sửa, chạy lại checklist. Lặp cho đến khi đạt toàn bộ.

**Điều kiện hoàn thành:** checklist đạt 100%.
**Nếu thất bại quá 2 vòng ở cùng một mục:** vấn đề nằm ở đầu vào, không ở cách viết. Quay lại Giai đoạn 1 và nêu rõ dữ liệu nào đang thiếu.

### Giai đoạn 5 — Bàn giao (Gate duy nhất)
**Thực hiện:** trả tài liệu kèm ba khối, rồi **dừng lại chờ người dùng xác nhận**:
1. Danh sách `[GIẢ ĐỊNH]` được đánh số, để người dùng trả lời nhanh dạng "1 đúng, 2 sai vì…".
2. Danh sách `[CẦN BỔ SUNG]` kèm cách lấy dữ liệu rẻ nhất cho từng mục.
3. Bước tiếp theo được đề xuất.

**Vì sao đặt Gate tại đây và chỉ tại đây:** các skill sau kế thừa tài liệu này. Một giả định sai được duyệt nhầm sẽ nhân bản qua toàn bộ chuỗi. Không đặt Gate ở các giai đoạn trước để tránh ngắt quãng workflow.
**Không được** tự động chạy tiếp sang skill khác khi các `[GIẢ ĐỊNH]` chưa được xác nhận.

## Cấu trúc kết quả
1. **Tổng quan doanh nghiệp** — tên, mô hình, thị trường, giai đoạn phát triển `[GIẢ ĐỊNH]`, quy mô khách hàng.
2. **Bản đồ sản phẩm và doanh thu** — bảng: sản phẩm | giá | giá vốn | biên lợi nhuận | vai trò suy ra. Ô thiếu dữ liệu để `[CẦN BỔ SUNG]`, không để trống trơn.
3. **Mục tiêu và kỳ vọng BOD** — nguyên văn lời BOD, rồi 1–3 phương án mục tiêu đo được `[CHỜ BOD]`. Có tỷ lệ chốt và giá trị đơn hàng thì tính ngược ra số khách và số lead cần có; không có thì ghi rõ thiếu gì để tính được.
4. **Nguồn lực marketing** — ngân sách, công cụ, đối tác, quy trình duyệt.
5. **Bảng năng lực đội ngũ** — bảng: năng lực (viết / quay / dựng / thiết kế / ads / phân tích dữ liệu) | ai làm | mức độ | công suất thật mỗi tuần | khoảng trống.
6. **Hiện trạng marketing** — đã làm gì, kết quả thô, cái gì chưa từng được đo.
7. **Vấn đề trọng tâm** — bảng: triệu chứng BOD nêu | nguyên nhân gốc khả dĩ `[GIẢ ĐỊNH]` | cách kiểm chứng | chi phí kiểm chứng | mức ưu tiên (1/2/3). Sau bảng, **bắt buộc một dòng chốt duy nhất**: *"Vấn đề ưu tiên số 1 là ___, vì ___. Ba mươi ngày tới marketing tập trung giải quyết đúng vấn đề này."* Liệt kê mà không chốt là chưa hoàn thành phần này.
8. **Ba khối bàn giao** — `[GIẢ ĐỊNH]` cần xác nhận · `[CẦN BỔ SUNG]` cần đi lấy · bước tiếp theo.

Phần 5 chỉ rút gọn khi doanh nghiệp không có team marketing (một mình founder) — khi đó thay bằng một đoạn về quỹ thời gian thật của founder. Không phần nào khác được bỏ.

## Checklist chất lượng
- [ ] Mọi con số trong tài liệu đều có nguồn: `(BOD cung cấp)`, `(ước tính, phương pháp: …)` hoặc `[CẦN BỔ SUNG]`. Không có số nào đứng trần trụi.
- [ ] Số người dùng đưa dạng khoảng vẫn ở dạng khoảng; không bị thu về một giá trị để tính toán tiếp.
- [ ] Không xuất hiện bất kỳ chỉ số nào (tỷ lệ chốt, CPL, CAC, tỷ lệ chuyển đổi) mà người dùng không cung cấp và không thể suy ra từ dữ liệu họ đưa.
- [ ] Không có cụm định tính ("tăng trưởng mạnh", "phủ sóng", "nâng cao nhận diện") nào đứng một mình ở Phần 3. Mỗi cụm định tính phải kèm 1–3 phương án mục tiêu có số và thời hạn, gắn `[CHỜ BOD]`. Người dùng chưa đưa mục tiêu nào → Phần 3 vẫn hợp lệ nếu ghi `[CẦN BỔ SUNG]` kèm cách chốt mục tiêu với BOD.
- [ ] Phần 7 phân biệt rõ triệu chứng và nguyên nhân gốc; không lấy nguyên triệu chứng làm mục tiêu marketing.
- [ ] Phần 7 kết thúc bằng đúng một dòng chốt vấn đề ưu tiên số 1, có lý do. Không dừng ở liệt kê.
- [ ] Mọi đề xuất khả thi với công suất ghi ở Phần 5. Không đề xuất kênh hay tần suất vượt quá số giờ và số người thực có.
- [ ] Mỗi `[GIẢ ĐỊNH]` có đúng một dòng lý do và truy ngược được về một dữ kiện cụ thể.
- [ ] Mỗi `[CẦN BỔ SUNG]` có cách lấy dữ liệu, không chỉ ghi "cần bổ sung".
- [ ] Đủ 8 phần bắt buộc, đúng thứ tự.
- [ ] Trưởng bộ phận marketing đọc xong có thể nói ra vấn đề ưu tiên và bước tiếp theo mà không cần hỏi thêm câu nào.
- [ ] Đã chạy ít nhất một vòng tạo → kiểm tra → sửa → kiểm tra lại.

## Tình huống đặc biệt

### Trường hợp 1 — Doanh thu chỉ có dạng khoảng hoặc "không nhớ chính xác"
**Cách phát hiện:** người dùng dùng "khoảng", "tầm", "chừng", hoặc đưa một dải số.
**Cách xử lý:** giữ nguyên dải. Ghi `(chủ doanh nghiệp ước tính, chưa đối chiếu sổ sách)`. Đưa việc chốt số thật vào khối `[CẦN BỔ SUNG]` với cách lấy cụ thể.
**Không được:** lấy trung bình dải rồi tính CAC, ROI hay bất kỳ chỉ số phái sinh nào từ đó.

### Trường hợp 2 — Kỳ vọng BOD là câu định tính
**Cách phát hiện:** "tăng trưởng mạnh", "làm thương hiệu mạnh hơn", "fanpage phải sôi động".
**Cách xử lý:** chép nguyên văn vào tài liệu, sau đó đề xuất 1–3 mục tiêu đo được tương ứng, gắn `[CHỜ BOD]`. Nếu người dùng cho biết ràng buộc (ngân sách, thời hạn), dùng nó để giới hạn phương án.
**Không được:** chép câu định tính vào ô "Mục tiêu" rồi lập kế hoạch dựa trên nó.

### Trường hợp 3 — Vấn đề BOD nêu là triệu chứng
**Cách phát hiện:** vấn đề nói về chỉ số bề mặt (tương tác, follower, view) thay vì kết quả kinh doanh (lead, khách hàng, doanh thu).
**Cách xử lý:** đặt vào cột "triệu chứng". Nêu 1–3 nguyên nhân gốc khả dĩ, mỗi cái gắn `[GIẢ ĐỊNH]` + cách kiểm chứng rẻ nhất.
**Không được:** biến triệu chứng thành mục tiêu marketing của kỳ.

### Trường hợp 4 — Nguồn lực rất mỏng nhưng tham vọng lớn
**Cách phát hiện:** công suất ở Phần 5 nhỏ hơn nhiều so với mục tiêu ở Phần 3.
**Cách xử lý:** nêu khoảng cách bằng số (ví dụ: mục tiêu cần khoảng 12 nội dung/tuần, công suất hiện tại khoảng 3). Đưa ra hai lựa chọn: hạ mục tiêu hoặc tăng nguồn lực, kèm ước lượng chi phí của phương án tăng nguồn lực. Gắn `[CHỜ BOD]`.
**Không được:** im lặng lập kế hoạch theo mục tiêu rồi để team vỡ trận.

### Trường hợp 5 — Chưa từng đo lường gì
**Cách phát hiện:** người dùng nói chưa đo lead, không biết khách đến từ đâu.
**Cách xử lý:** ghi nhận là phát hiện quan trọng nhất của tài liệu. Vấn đề ưu tiên rất có thể là "không đo được", không phải "content chưa hay". Đề xuất cách đo rẻ nhất triển khai được trong một tuần.
**Không được:** đưa ra bất kỳ chỉ số hiệu suất nào cho các hoạt động đã chạy.

## Ví dụ

### Ví dụ 1 — Ghi số liệu kèm nguồn
Đầu vào: *"Doanh thu khoảng 350–450tr/tháng, không nhớ chính xác. Ngân sách marketing 25tr."*

**KHÔNG ĐẠT**
> Doanh thu 400tr/tháng, ngân sách marketing 25tr chiếm 6,25% doanh thu — thấp hơn mức chuẩn ngành giáo dục 10–15%, nên tăng lên 40–60tr.

Sai ba lớp: thu dải số về một điểm; tính tỷ lệ phái sinh từ số đó; viện dẫn "chuẩn ngành" không có nguồn.

**ĐẠT**
> Doanh thu: 350–450tr/tháng *(chủ doanh nghiệp ước tính, chưa đối chiếu sổ sách)*. Ngân sách marketing: 25tr/tháng *(BOD cung cấp)*. Tỷ lệ ngân sách trên doanh thu chưa tính được vì doanh thu còn ở dạng dải — `[CẦN BỔ SUNG: xuất doanh thu 6 tháng gần nhất từ sổ thu chi, mất khoảng 30 phút]`.

### Ví dụ 2 — Tách triệu chứng khỏi nguyên nhân gốc
Đầu vào: *"Vấn đề BOD nêu: fanpage không ai tương tác. Đã đăng 5 bài/tuần suốt 1 năm, chưa đo lead bao giờ."*

**KHÔNG ĐẠT**
> Vấn đề trọng tâm: tương tác fanpage thấp. Mục tiêu: tăng engagement rate lên 5% trong 3 tháng.

Sai: nhận nguyên triệu chứng làm mục tiêu. Tương tác tăng mà không có học viên thì trung tâm vẫn không sống được.

**ĐẠT**
> | Triệu chứng | Nguyên nhân gốc khả dĩ | Cách kiểm chứng | Chi phí | Ưu tiên |
> |---|---|---|---|---|
> | Fanpage không tương tác | `[GIẢ ĐỊNH]` Nội dung viết cho trẻ, trong khi người quyết định chi tiền là phụ huynh | Đọc 20 bài gần nhất, đếm bài nói với phụ huynh | 1 giờ | 2 |
> | (không được BOD nêu) | `[GIẢ ĐỊNH]` Không đo được lead → không biết kênh nào ra học viên → cải thiện mù | Hỏi nguồn khi phụ huynh inbox, ghi vào Google Sheet | 1 tuần, 0đ | 1 |
>
> **Vấn đề ưu tiên số 1 là không đo được nguồn học viên**, vì chừng nào chưa biết học viên đến từ đâu thì mọi cải thiện nội dung đều là đoán mò và không chứng minh được với BOD. Ba mươi ngày tới marketing tập trung giải quyết đúng vấn đề này.

## Anti-Patterns
- Không điền cho đủ ô. Ô trống có nhãn có giá trị hơn ô đầy bằng số bịa.
- Không tính chỉ số phái sinh từ số ước lượng.
- Không liệt kê "10 việc marketing nên làm". Tài liệu này chốt **một** vấn đề ưu tiên.
- Không đề xuất mở thêm kênh khi Phần 5 cho thấy team không kham nổi kênh hiện có.
- Không viết văn tiếp thị. Người đọc là người phải ra quyết định, không phải khách hàng.
- Không lấn sang phạm vi skill khác: không dựng persona, không phân tích đối thủ, không viết định vị. Nếu người dùng hỏi, ghi nhận và chỉ sang tài liệu tương ứng.

## Recovery
### Khi thiếu đầu vào
Thiếu ngoài 5 mục tối thiểu → viết tiếp, gắn `[CẦN BỔ SUNG]` đúng chỗ. Thiếu trong 5 mục tối thiểu (tên/mô hình, sản phẩm và giá, ngân sách, team, vấn đề BOD) → dừng, nêu rõ đang thiếu gì và vì sao không thể viết.

### Khi validation thất bại
Trượt checklist → sửa đúng mục trượt, chạy lại toàn bộ checklist. Trượt cùng một mục quá hai vòng → nguyên nhân nằm ở đầu vào, quay lại Giai đoạn 1.

### Khi dữ liệu mâu thuẫn
Không tự chọn con số nào. Gắn `[MÂU THUẪN]`, trình bày cả hai dữ kiện, hỏi người dùng. Nếu người dùng không giải quyết được, giữ cả hai và ghi vào `[CẦN BỔ SUNG]`.

### Khi người dùng nói "cứ làm đi, không cần hỏi"
Vẫn viết tài liệu, nhưng số lượng nhãn `[GIẢ ĐỊNH]` sẽ tăng. Nêu rõ ở đầu tài liệu: "Bản này được viết với X giả định chưa xác nhận; chưa dùng để ra quyết định ngân sách." Không âm thầm hạ chuẩn.

### Khi người dùng duyệt mọi giả định trong một câu ("ok hết")
Nhắc một lần: các giả định về số liệu tài chính và về nguyên nhân gốc sẽ được các skill sau kế thừa. Đề nghị xác nhận riêng ít nhất nhóm giả định tài chính. Người dùng vẫn khẳng định → tiếp tục và ghi vào tài liệu rằng các giả định được duyệt gộp.

## Bộ test

### Test 1 — Trigger trực tiếp
**Prompt:** "Giúp tôi làm tài liệu Business & Brand Overview cho trung tâm dạy vẽ của tôi."
**Có kích hoạt Skill không:** Có.
**Hành vi mong đợi:** đối chiếu 9 đầu vào bắt buộc, hỏi tối đa 5 câu cho phần thiếu.
**Tiêu chí đạt:** không viết tài liệu trước khi có đủ 5 mục tối thiểu.

### Test 2 — Trigger một phần
**Prompt:** "Team marketing tôi có 1 bạn part-time kiêm content và ads, founder rảnh 2 tiếng/tuần. Với nguồn lực này tôi làm được đến đâu?"
**Có kích hoạt Skill không:** Có (đây là Phần 5 của tài liệu).
**Hành vi mong đợi:** quy đổi ra công suất thật mỗi tuần, chỉ ra khoảng trống năng lực, hỏi thêm mục tiêu để so sánh.
**Tiêu chí đạt:** không đề xuất mở nhiều kênh; nêu công suất bằng số.

### Test 3 — Không nên kích hoạt
**Prompt:** "Viết Brand Bible cho thương hiệu của tôi: vision, mission, tone of voice."
**Có kích hoạt Skill không:** Không.
**Hành vi mong đợi:** chỉ sang tài liệu 02 — Brand Bible; nếu tài liệu 01 chưa có, nói rõ nó là đầu vào và đề nghị làm trước.
**Tiêu chí đạt:** không tự viết vision/mission/tone.

### Test 4 — Đầu vào thiếu
**Prompt:** "Doanh nghiệp tôi bán khóa học online. Làm overview giúp tôi."
**Có kích hoạt Skill không:** Có.
**Hành vi mong đợi:** hỏi một lần, tối đa 5 câu, ưu tiên các mục tối thiểu còn thiếu (sản phẩm và giá, ngân sách, team, vấn đề BOD).
**Tiêu chí đạt:** không sinh bản nháp đầy số liệu tự nghĩ.

### Test 5 — Ngoại lệ thực tế (case có bẫy)
**Prompt:**
> "Trung tâm Măng Non, dạy vẽ offline cho trẻ 6–12 tuổi, 2 cơ sở Hà Nội. Khóa cơ bản 12 buổi 3,6tr; nâng cao 24 buổi 8,4tr; trại hè 2,5tr. Doanh thu khoảng 350–450tr/tháng, không nhớ chính xác. BOD muốn tăng trưởng mạnh trong năm nay. Ngân sách marketing 25tr/tháng. Team: 1 bạn content kiêm ads, part-time. Founder ngại lên hình, rảnh 2 giờ/tuần. Vấn đề BOD nêu: fanpage không ai tương tác. Đã đăng 5 bài/tuần suốt 1 năm, chưa đo lead bao giờ."

**Có kích hoạt Skill không:** Có.
**Hành vi mong đợi và tiêu chí đạt (6 bẫy, phải qua đủ 6):**

| # | Bẫy | Đạt | Trượt |
|---|---|---|---|
| 1 | Doanh thu là dải số | Giữ dải 350–450tr, ghi là ước tính, không tính chỉ số phái sinh | Lấy 400tr rồi tính CAC/ROI |
| 2 | Mục tiêu định tính | Đề xuất 1–3 mục tiêu có số và thời hạn, gắn `[CHỜ BOD]` | Chép "tăng trưởng mạnh" vào ô mục tiêu |
| 3 | Vấn đề là triệu chứng | Xếp "fanpage không tương tác" vào cột triệu chứng; nêu nguyên nhân gốc khả dĩ (không đo lead, nội dung không nhắm phụ huynh) kèm cách kiểm chứng | Lấy "tăng tương tác fanpage" làm mục tiêu marketing |
| 4 | Nguồn lực rất mỏng | Mọi đề xuất vừa với 1 part-time + 2 giờ founder; nêu khoảng cách bằng số | Đề xuất đẩy mạnh TikTok + YouTube + livestream |
| 5 | Chưa từng đo lead | Gắn `[CẦN BỔ SUNG]` kèm cách đo rẻ nhất trong 1 tuần; nêu đây có thể là vấn đề ưu tiên thật | Bịa tỷ lệ chuyển đổi của fanpage |
| 6 | Cấu trúc | Hỏi ≤5 câu; đủ 8 phần; kết thúc bằng 3 khối bàn giao | Hỏi tràn lan hoặc thiếu khối bàn giao |

**Ngưỡng nghiệm thu Skill:** 6/6 → dùng được. 4–5/6 → sửa đúng mục trượt rồi chạy lại. ≤3/6 → chưa dùng được.

### Test 6 — Đầu vào đầy đủ, không được hỏi lại
**Prompt:** cung cấp trọn 9 mục bắt buộc, có giá vốn và tỷ lệ chốt, kèm câu "đủ thông tin rồi, viết luôn".
**Có kích hoạt Skill không:** Có.
**Hành vi mong đợi:** đi thẳng vào viết, không hỏi thêm câu nào.
**Tiêu chí đạt:** không có câu hỏi nào trong phản hồi; tính ngược ra được số lead cần có từ mục tiêu doanh thu, tỷ lệ chốt và giá trị đơn hàng.

### Trạng thái test
Bộ test đã được thiết kế, **chưa được thực thi** trong phiên mới. Không được tuyên bố skill đã kiểm chứng cho tới khi Test 5 và Test 6 chạy thật.
Thứ tự chạy: Test 5 trước (bao phủ năm loại lỗi nguy hiểm nhất), rồi Test 6 (bắt lỗi hỏi thừa), rồi Test 3 (bắt lỗi lấn phạm vi).

## Changelog
- **v1.1** — Sửa 3 lỗi từ AUDIT.md: (1) checklist mục tiêu không còn mâu thuẫn với ngưỡng 5 mục tối thiểu; (2) Phần 7 bắt buộc chốt một vấn đề ưu tiên, không dừng ở liệt kê; (3) thêm 2 cặp ví dụ ĐẠT/KHÔNG ĐẠT. Thống nhất thuật ngữ "tài liệu NN". Thêm Test 6.
- **v1.0** — Bản đầu, dựng theo framework `building-agent-workflows`. Không bàn giao: trượt 4 mục checklist.
