# Marketing Growth OS — Plugin

Marketplace + plugin đóng gói **21 skill** (15 chi tiết + 6 skill gom) để dựng trọn bộ hồ sơ marketing cho doanh nghiệp, cài **một lần** vào Claude/Cowork.

## Cấu trúc
```
marketing-growth-os-plugin/
├── .claude-plugin/
│   └── marketplace.json          # định nghĩa marketplace
└── plugins/
    └── marketing-growth-os/
        ├── .claude-plugin/plugin.json
        ├── skills/               # 21 skill (mỗi skill 1 SKILL.md)
        ├── README.md
        └── VALIDATION_KIT.md
```

## Cách cài (3 cách)

### Cách A — Qua GitHub marketplace (khuyến nghị, cài 1 lần)
1. Đẩy nguyên thư mục này lên một repo GitHub (ví dụ `thang-marketing-os`).
2. Trong Claude/Cowork: **Settings → Capabilities → Plugins/Marketplaces → Add marketplace**, dán URL repo GitHub.
3. Tìm plugin **marketing-growth-os** trong marketplace vừa thêm → **Install**.
4. Xong: 21 skill sẽ gọi được bằng lệnh (ví dụ gõ `/` sẽ thấy chúng), hoặc Claude tự kích hoạt theo ngữ cảnh.

Nếu dùng Claude Code CLI:
```
/plugin marketplace add <đường-dẫn-hoặc-URL-repo>
/plugin install marketing-growth-os@thang-marketing-os
```

### Cách B — Thêm từng skill qua Settings
Nếu chưa muốn dùng plugin: **Settings → Capabilities → Skills → Add**, thêm từng thư mục skill trong `plugins/marketing-growth-os/skills/`.

### Cách C — Thư mục skill cục bộ
Trỏ Claude Code tới thư mục `plugins/marketing-growth-os/` (chứa `skills/`) như một skills-directory plugin.

## Sau khi cài — cách gọi từng skill (test 15 bước)
Gọi theo thứ tự phụ thuộc. Tên lệnh = tên skill:

| Bước | Gọi skill | Việc |
|---|---|---|
| 01 | building-business-brand-overview | Tổng quan doanh nghiệp + năng lực team |
| 02 | building-brand-bible | Brand Bible 14 mục |
| 03 | building-brand-guideline | Nhận diện 11 mục |
| 04 | auditing-social-media-channels | Baseline kênh |
| 05 | researching-market | Quy mô thị trường |
| 06 | analyzing-competitors | Khoảng trống đối thủ |
| 07 | building-customer-persona-insight | Persona + insight |
| 08 | mapping-product-offer | Vai sản phẩm + offer |
| 09 | building-marketing-strategy | Chiến lược (cần 01,07,08) |
| 10 | mapping-customer-journey-funnel | Phễu |
| 11 | planning-channel-paid-media | Kênh + ads |
| 12 | building-content-strategy | Pillar nội dung |
| 13 | planning-roadmap-campaign-budget-raci | Roadmap + RACI |
| 14 | producing-content-calendar | Lịch + kịch bản |
| 15 | building-kpi-dashboard-reporting | KPI + báo cáo |

Không rõ bắt đầu từ đâu → gọi **orchestrating-marketing-growth-os**. Chạy trọn 1 giai đoạn → gọi **running-foundation-phase / running-research-audit-phase / running-strategy-phase / running-execution-phase / running-operation-phase**.

## Lưu ý
- Kiểm chứng skill trước khi dùng thật: xem `plugins/marketing-growth-os/VALIDATION_KIT.md`.
- Nếu UI Claude/Cowork của bạn khác, đường vào chung là **Settings → Capabilities**.
