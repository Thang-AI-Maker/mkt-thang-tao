---
name: orchestrating-marketing-growth-os
description: điều phối toàn bộ hệ thống Marketing Growth OS — hỏi đã có tài liệu nào, xác định điểm vào, chặn chạy sai thứ tự và đề xuất lộ trình 15 bước. dùng khi người dùng muốn bắt đầu bộ hồ sơ marketing, "marketing nên bắt đầu từ đâu", không biết chạy skill nào trước, muốn lộ trình tổng, hoặc có sẵn vài tài liệu và hỏi bước tiếp theo. quy tắc cứng: không cho chạy tài liệu 09 khi chưa có 01, 07, 08. không dùng khi người dùng đã biết rõ cần chạy một skill cụ thể (khi đó gọi thẳng skill đó).
---

# Orchestrator — Marketing Growth OS
Điều phối 15 skill chi tiết + 5 skill gom giai đoạn: xác định điểm vào đúng, chặn chạy sai thứ tự, đề xuất lộ trình phù hợp nguồn lực. Đối tượng dùng: người mới bắt đầu bộ hồ sơ hoặc đang có sẵn một phần.

## Nguyên tắc cốt lõi
Chạy một skill khi tài liệu phụ thuộc của nó chưa có → output là suy diễn, không phải chiến lược. **Quy tắc cứng: không cho chạy 09 (Marketing Strategy) khi chưa có 01, 07, 08.** Không bắt người đã có Brand Bible làm lại.

## Bản đồ phụ thuộc (dùng để chặn)
| Skill | Phụ thuộc bắt buộc |
|---|---|
| 01 Business & Brand Overview | — |
| 02 Brand Bible | 01 |
| 03 Brand Guideline | 02 |
| 04 Social Media Analysis | 01, 02 |
| 05 Market Research | 01 |
| 06 Competitor Analysis | 01, 05 |
| 07 Persona & Insight | 02, 04, 06 |
| 08 Product & Offer Map | 01, 07 |
| 09 Marketing Strategy | 01, 02, 04–08 (cứng: 01, 07, 08) |
| 10 Journey & Funnel | 07, 08, 09 |
| 11 Channel & Paid Media | 04, 07, 09, 10 |
| 12 Content Strategy | 02, 07, 09, 11 |
| 13 Roadmap/Campaign/Budget/RACI | 09, 11, 12 |
| 14 Content Calendar & Production | 12, 13 |
| 15 KPI Dashboard & Reporting | 09, 10, 11, 13 |

## Quy trình

### Giai đoạn 1 — Kiểm kê tài liệu đã có
**Thực hiện:**
1. Hỏi một lần: người dùng đã có tài liệu nào trong 15 (đặc biệt 01, 02, 07, 08)?
2. Với tài liệu đã có: hỏi nhanh nó có bị lỗi thời hoặc mâu thuẫn không.
**Điều kiện hoàn thành:** biết rõ điểm xuất phát.

### Giai đoạn 2 — Xác định điểm vào & lộ trình
1. Xác định skill kế tiếp hợp lệ theo bản đồ phụ thuộc.
2. Đề xuất lộ trình: chạy tuần tự 15 bước, hoặc dùng skill gom A1–A5 cho từng giai đoạn.
3. Nếu người dùng thiếu thời gian, đề xuất **một trong ba lối tắt hợp lệ** (xem dưới) và ghi rõ nợ kỹ thuật.

### Giai đoạn 3 — Chặn & bàn giao lộ trình
1. Nếu người dùng đòi chạy skill mà phụ thuộc chưa đủ → **chặn**, giải thích thiếu gì, đề xuất chạy tài liệu phụ thuộc trước.
2. Bàn giao lộ trình có thứ tự + ước lượng skill nào chạy trước.

## Ba lối tắt hợp lệ
- **Cần lead gấp:** 01 → 07 → 08 → 10 → 11 → 14. Bỏ brand, quay lại sau — ghi rõ nợ kỹ thuật.
- **Đã có brand rõ:** bắt đầu từ 04, nạp tài liệu brand cũ vào Project.
- **Chỉ cần content:** 07 → 12 → 14. Cảnh báo: content không chiến lược thì không đo được.

## Cấu trúc kết quả
1. Bảng kiểm kê tài liệu đã có / còn thiếu. 2. Điểm vào được xác định. 3. Lộ trình đề xuất (đủ hoặc lối tắt). 4. Cảnh báo chặn nếu có.

## Checklist chất lượng
- [ ] Đã hỏi tài liệu đã có trước khi đề xuất.
- [ ] Không bắt làm lại tài liệu đã có và còn đúng.
- [ ] Chặn đúng khi phụ thuộc chưa đủ (đặc biệt 09).
- [ ] Lộ trình rõ thứ tự và có phương án theo nguồn lực.

## Tình huống đặc biệt
### Trường hợp — Người dùng muốn nhảy thẳng vào content/ads
**Cách xử lý:** cho phép nhưng chỉ rõ tài liệu thiếu và rủi ro; đề xuất lối tắt phù hợp + ghi nợ kỹ thuật.
**Không được:** để chạy 09 thiếu 01/07/08.
### Trường hợp — Đã có bộ tài liệu cũ, chỉ cần cập nhật
**Cách xử lý:** xác định tài liệu lỗi thời, chỉ chạy phần cần; kiểm mâu thuẫn giữa tài liệu cũ.

## Anti-Patterns
- Không đề xuất lộ trình mà chưa kiểm kê.
- Không bỏ qua quy tắc chặn 09.
- Không bắt làm lại thứ đã có.

## Recovery
### Khi người dùng không rõ đã có gì
Hỏi theo checklist 15 tài liệu; mặc định bắt đầu từ 01.

## Bộ test
### Test 1 — Trigger trực tiếp
**Prompt:** "Marketing nên bắt đầu từ đâu, tôi chưa có gì cả."
**Có kích hoạt:** Có → đề xuất bắt đầu 01.
### Test 2 — Trigger một phần
**Prompt:** "Tôi có Brand Bible rồi, giờ làm gì tiếp?"
**Có kích hoạt:** Có → điểm vào 03/04.
### Test 3 — Không nên kích hoạt
**Prompt:** "Viết cho tôi Brand Bible."
**Có kích hoạt:** Không (gọi thẳng skill 02).
### Test 4 — Chặn phụ thuộc
**Prompt:** "Làm luôn chiến lược marketing đi" (chưa có 07/08).
**Hành vi:** chặn, yêu cầu 01/07/08 trước.
### Test 5 — Lối tắt
**Prompt:** "Tôi cần ra lead trong 2 tuần."
**Hành vi:** đề xuất lối tắt 01→07→08→10→11→14 + ghi nợ kỹ thuật.
