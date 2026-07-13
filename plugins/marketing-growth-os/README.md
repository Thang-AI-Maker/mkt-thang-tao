# Marketing Growth OS — Bộ 21 Agent Skill

Hệ thống 15 skill chi tiết + 6 skill gom điều phối, biến toàn bộ quy trình marketing của một thương hiệu thành các Agent Skill chạy được, tự kiểm tra và không bịa số. Mỗi skill = một tài liệu trong bộ hồ sơ marketing. Người dùng cung cấp phần "Bạn phải cung cấp", AI làm phần "Logic xử lý bên trong".

Bộ này ghép với ba tài liệu gốc:
- **Marketing_Growth_Plan_Template.docx** — đích đến, nơi output các skill đổ vào.
- **Marketing_Growth_Plan_Tracker.xlsx** — bảng điều khiển theo dõi tiến độ.
- **Marketing_Grow_Plan_Map.xlsx** (trong repo này) — bản đồ logic + link tới từng skill.

## Bốn cơ chế chạy trong MỌI skill
1. **Cấm bịa số** — không có dữ liệu thì gắn `[CẦN BỔ SUNG: cách lấy]`. Một con số bịa sẽ được các skill sau kế thừa như sự thật.
2. **Đánh dấu suy luận** — mọi thứ AI tự suy gắn `[GIẢ ĐỊNH]` + một dòng lý do; người dùng duyệt trước khi đi tiếp.
3. **Kế thừa, không lặp** — thông tin đã có ở tài liệu trước thì trích nguồn; phát hiện xung khắc thì gắn `[MÂU THUẪN]` và dừng hỏi.
4. **Kết bằng quyết định** — mỗi tài liệu nói rõ: làm gì, KHÔNG làm gì, ai làm, đo bằng gì.

## Cấu trúc thư mục
```
marketing-growth-os/
├── README.md
├── VALIDATION_KIT.md
├── Marketing_Grow_Plan_Map.xlsx
└── skills/
    ├── phase-1-nen-mong/
    │   ├── building-business-brand-overview/SKILL.md      (01)
    │   ├── building-brand-bible/SKILL.md                  (02)
    │   ├── building-brand-guideline/SKILL.md              (03)
    │   └── auditing-social-media-channels/SKILL.md        (04)
    ├── phase-2-nghien-cuu/
    │   ├── researching-market/SKILL.md                    (05)
    │   ├── analyzing-competitors/SKILL.md                 (06)
    │   ├── building-customer-persona-insight/SKILL.md     (07)
    │   └── mapping-product-offer/SKILL.md                 (08)
    ├── phase-3-chien-luoc/
    │   ├── building-marketing-strategy/SKILL.md           (09)
    │   ├── mapping-customer-journey-funnel/SKILL.md       (10)
    │   ├── planning-channel-paid-media/SKILL.md           (11)
    │   └── building-content-strategy/SKILL.md             (12)
    ├── phase-4-trien-khai/
    │   ├── planning-roadmap-campaign-budget-raci/SKILL.md (13)
    │   └── producing-content-calendar/SKILL.md            (14)
    ├── phase-5-van-hanh/
    │   └── building-kpi-dashboard-reporting/SKILL.md      (15)
    └── orchestrators/
        ├── orchestrating-marketing-growth-os/SKILL.md     (A0)
        ├── running-foundation-phase/SKILL.md              (A1)
        ├── running-research-audit-phase/SKILL.md          (A2)
        ├── running-strategy-phase/SKILL.md                (A3)
        ├── running-execution-phase/SKILL.md               (A4)
        └── running-operation-phase/SKILL.md               (A5)
```

## Thứ tự chạy & phụ thuộc (quy tắc bắt buộc)
Chạy skill mà tài liệu phụ thuộc chưa có thì output là suy diễn, không phải chiến lược.

| # | Skill | Tên thư mục | Phụ thuộc |
|---|---|---|---|
| 01 | Business & Brand Overview | building-business-brand-overview | — |
| 02 | Brand Bible | building-brand-bible | 01 |
| 03 | Brand Guideline | building-brand-guideline | 02 |
| 04 | Social Media Analysis | auditing-social-media-channels | 01, 02 |
| 05 | Market Research | researching-market | 01 |
| 06 | Competitor Analysis | analyzing-competitors | 01, 05 |
| 07 | Persona & Insight | building-customer-persona-insight | 02, 04, 06 |
| 08 | Product & Offer Map | mapping-product-offer | 01, 07 |
| 09 | Marketing Strategy | building-marketing-strategy | 01, 02, 04–08 (cứng: 01, 07, 08) |
| 10 | Journey & Funnel | mapping-customer-journey-funnel | 07, 08, 09 |
| 11 | Channel & Paid Media | planning-channel-paid-media | 04, 07, 09, 10 |
| 12 | Content Strategy | building-content-strategy | 02, 07, 09, 11 |
| 13 | Roadmap/Campaign/Budget/RACI | planning-roadmap-campaign-budget-raci | 09, 11, 12 |
| 14 | Content Calendar & Production | producing-content-calendar | 12, 13 |
| 15 | KPI Dashboard & Reporting | building-kpi-dashboard-reporting | 09, 10, 11, 13 |
| A0 | Orchestrator | orchestrating-marketing-growth-os | — (điều phối) |
| A1 | Foundation Runner | running-foundation-phase | 01 → 02,03,04 |
| A2 | Research & Audit Runner | running-research-audit-phase | 01,05,06,07,08 |
| A3 | Strategy Runner | running-strategy-phase | 09,10,11,12 |
| A4 | Execution Runner | running-execution-phase | 13,14 |
| A5 | Operation Runner | running-operation-phase | 15 |

## Ba lối tắt hợp lệ (khi không đủ thời gian chạy đủ 15 bước)
- **Cần lead gấp:** 01 → 07 → 08 → 10 → 11 → 14 (bỏ brand, quay lại sau — ghi rõ nợ kỹ thuật).
- **Đã có brand rõ:** bắt đầu từ 04, nạp tài liệu brand cũ vào Project.
- **Chỉ cần content:** 07 → 12 → 14 (cảnh báo: content không chiến lược thì không đo được).

## Cách dùng
1. Không rõ bắt đầu từ đâu → chạy **A0 Orchestrator**.
2. Muốn chạy trọn một giai đoạn trong một phiên → dùng skill gom A1–A5.
3. Chỉ cần một tài liệu → gọi thẳng skill tương ứng theo tên thư mục.
4. Trước khi tin một skill vào việc thật → chạy **VALIDATION_KIT.md** (Lớp 1: case Măng Non, 6 bẫy).

## Cài đặt (Claude / Cowork / Agent Skills)
Mỗi thư mục con chứa một `SKILL.md` tự chứa theo chuẩn Agent Skills (frontmatter `name` + `description`). Copy thư mục skill vào nơi lưu skill của môi trường đích, hoặc trỏ marketplace/plugin tới repo này.

## Trạng thái
21/21 skill đã viết đầy đủ theo framework `Build_Any_Skill` và tự audit. Skill 01 giữ nguyên bản v1.1. Chạy VALIDATION_KIT trước khi đưa vào việc thật.
