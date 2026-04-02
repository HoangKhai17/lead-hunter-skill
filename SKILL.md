---
name: lead-hunter
description: |
  Tìm kiếm và tổng hợp nhu cầu khách hàng tiềm năng về các dịch vụ digital & AI: Agentic AI, AI Automation, thiết kế website, chatbot, email marketing, quản lý fanpage/mạng xã hội, quản lý website, thuê đội IT online, SEO, landing page,... trên các nền tảng mạng xã hội, diễn đàn và cộng đồng online.

  **Khi nào dùng skill này**: Dùng ngay khi người dùng muốn:
  - Tìm khách hàng có nhu cầu thuê dịch vụ Agentic AI, AI automation, website, chatbot, email marketing, social media, IT
  - Tìm kiếm leads, cơ hội bán hàng dịch vụ digital marketing / AI / công nghệ
  - Săn lead, tìm prospect, tìm khách hàng tiềm năng trên mạng
  - "Tìm người cần làm web", "tìm lead chatbot", "ai đang cần AI agent", "tìm người cần thuê đội IT"
  - Nghiên cứu nhu cầu thị trường cho dịch vụ AI / công nghệ / digital

  Skill này tự động đa nền tảng: Facebook Groups, LinkedIn, Reddit, Twitter/X, Diễn đàn Việt Nam (Vbiz, 5giay, Muaban...), Google Search operators.
---

# Lead Hunter — Tìm Khách Hàng Dịch Vụ Digital, IT & Agentic AI

## Tổng quan

Skill này tìm kiếm **tín hiệu nhu cầu** (demand signals) — các bài đăng, bình luận, câu hỏi trên internet của người đang tìm kiếm hoặc thể hiện nhu cầu thuê dịch vụ digital/IT/AI. Khi tìm được lead tiềm năng, **bắt buộc trích xuất và hiển thị SĐT, email nếu có** trong bài đăng hoặc profile.

---

## Bước 0 — Xác định thời điểm hiện tại (BẮT BUỘC)

**Trước khi tìm kiếm, PHẢI thực hiện ngay bước này:**

1. Lấy ngày/tháng/năm hiện tại từ context hoặc công cụ thời gian
2. Tính **ngưỡng loại bỏ** = ngày hiện tại trừ 90 ngày (3 tháng)
3. Xây dựng **bộ lọc thời gian động** cho từng nền tảng:
   - Google: dùng `after:YYYY-MM-DD` với ngày = 3 tháng trước hôm nay
   - Hoặc dùng năm/tháng hiện tại làm từ khóa bổ sung trong query
4. **TUYỆT ĐỐI KHÔNG** hardcode năm cụ thể trong skill — mọi bộ lọc thời gian phải tự động tính từ ngày thực thi

> Ví dụ logic: nếu hôm nay là 15/07/2025 → filter là `after:2025-04-15`, bổ sung từ khóa `"2025"` hoặc `"tháng 7 2025"`. Nếu hôm nay là 02/04/2026 → filter là `after:2026-01-02`, từ khóa `"2026"`.

---

## Bước 1 — Xác định yêu cầu

| Thông tin | Câu hỏi |
|-----------|---------|
| **Dịch vụ** | Agentic AI? Website? Chatbot? Email marketing? Social media? Thuê đội IT? Tất cả? |
| **Thị trường** | Việt Nam hay quốc tế? Ngành hàng cụ thể? |
| **Nền tảng ưu tiên** | Facebook, LinkedIn, Reddit, forum, hay tất cả? |
| **Mục đích** | Tìm lead bán hàng hay nghiên cứu thị trường? |

Nếu người dùng chưa rõ, mặc định tìm kiếm rộng trên nhiều nền tảng, tất cả dịch vụ, **ưu tiên Agentic AI vì đây là xu hướng tăng trưởng nhanh nhất hiện tại**.

---

## Bước 2 — Bộ từ khóa tìm kiếm

### 2.1 Từ khóa theo dịch vụ (Tiếng Việt)

**🤖 Agentic AI / AI Automation / AI Agent (ưu tiên hàng đầu):**
```
"cần làm AI agent" OR "tìm người làm AI agent"
"cần AI automation" OR "tự động hóa bằng AI" OR "cần workflow AI"
"cần tích hợp AI" OR "cần AI cho doanh nghiệp" OR "ứng dụng AI vào công việc"
"cần AI xử lý đơn hàng" OR "cần AI CSKH" OR "cần AI sales"
"cần làm AI bot" OR "tìm công ty làm AI" OR "cần AI assistant"
"cần AI phân tích dữ liệu" OR "cần AI report tự động"
"triển khai AI" OR "cần đội AI" OR "thuê AI developer"
"cần n8n" OR "cần make.com" OR "cần zapier" OR "cần automation workflow"
"cần RPA" OR "cần robot process automation" OR "tự động hóa quy trình"
```

**Website / Landing Page / Thiết kế web:**
```
"cần làm website" OR "tìm người thiết kế web" OR "cần thuê làm web"
"ai làm website không" OR "làm landing page" OR "cần web bán hàng"
"tìm dev làm web" OR "cần website công ty" OR "làm web wordpress"
"cần thiết kế website" OR "tìm công ty làm web" OR "nhận báo giá làm web"
"cần làm web gấp" OR "tìm freelancer làm web" OR "cần agency web"
```

**Quản lý website / Bảo trì website:**
```
"cần người quản lý website" OR "tìm người bảo trì web"
"thuê người quản lý web" OR "cần người cập nhật web"
"cần bảo trì website" OR "tìm người fix lỗi web"
"cần support website" OR "thuê admin website" OR "quản trị website"
```

**Thuê đội IT / Outsource IT:**
```
"cần thuê đội IT" OR "tìm công ty IT outsource"
"cần outsource IT" OR "thuê lập trình viên" OR "cần developer"
"tìm công ty phần mềm" OR "cần thuê lập trình" OR "tìm team IT"
"cần thuê backend" OR "cần thuê frontend" OR "cần fullstack developer"
```

**Chatbot / AI Bot:**
```
"cần làm chatbot" OR "tìm người làm chatbot" OR "chatbot zalo"
"chatbot facebook" OR "bot tư vấn" OR "cần bot tự động trả lời"
"cần chatbot cho shop" OR "cần AI chatbot" OR "chatbot chăm sóc khách hàng"
"cần bot Zalo OA" OR "làm chatbot AI" OR "cần tích hợp chatbot"
```

**Email Marketing / Automation:**
```
"cần email marketing" OR "tìm người làm email marketing"
"gửi email hàng loạt" OR "email automation" OR "cần campaign email"
"cần setup mailchimp" OR "email drip campaign" OR "cần email sequence"
```

**Quản lý Fanpage / Social Media:**
```
"cần quản lý fanpage" OR "tìm người quản lý facebook"
"cần content social" OR "quản lý social media" OR "tìm SMM"
"cần người đăng bài" OR "quản lý tiktok" OR "cần content creator"
"cần agency social" OR "thuê người làm content" OR "cần page manager"
```

**SEO / Ads / Digital Marketing:**
```
"cần làm SEO" OR "tìm người làm SEO" OR "cần lên top google"
"cần chạy ads" OR "facebook ads" OR "google ads freelance"
"cần digital marketing" OR "tìm agency marketing"
```

### 2.2 Từ khóa tiếng Anh (thị trường quốc tế / Reddit / LinkedIn)

```
# Agentic AI (ưu tiên)
"need AI agent" OR "looking for AI automation" OR "hire AI developer"
"AI workflow automation" OR "need n8n developer" OR "build AI agent"
"agentic AI" OR "AI automation help" OR "need RPA developer"
"AI integration" OR "automate with AI" OR "AI for business"

# Các dịch vụ khác
"looking for web developer" OR "need website built" OR "hire web designer"
"need chatbot" OR "looking for chatbot developer" OR "build chatbot for"
"email marketing help" OR "need email campaign" OR "hire email marketer"
"social media manager needed" OR "looking for SMM"
"need IT outsourcing" OR "hire IT team" OR "looking for developer"
```

---

## Bước 3 — Chiến lược tìm kiếm theo nền tảng

> **Nhắc lại:** Thay `[FILTER_DATE]` bằng ngày 3 tháng trước hôm nay (tính tự động ở Bước 0), thay `[CURRENT_YEAR]` bằng năm hiện tại.

### 3.1 Google Search (dùng `web_search`)

**Facebook Groups:**
```
site:facebook.com "cần AI agent" OR "cần AI automation" after:[FILTER_DATE]
site:facebook.com "cần làm website" "[CURRENT_YEAR]"
site:facebook.com "cần quản lý fanpage" after:[FILTER_DATE]
site:facebook.com "cần thuê đội IT" OR "cần outsource IT" "[CURRENT_YEAR]"
site:facebook.com "cần chatbot" after:[FILTER_DATE]
site:facebook.com "cần email marketing" "[CURRENT_YEAR]"
site:facebook.com "triển khai AI" OR "tích hợp AI" after:[FILTER_DATE]
```

**LinkedIn:**
```
site:linkedin.com "AI agent" OR "AI automation" Vietnam after:[FILTER_DATE]
site:linkedin.com "looking for web developer" Vietnam "[CURRENT_YEAR]"
site:linkedin.com "need chatbot developer" "[CURRENT_YEAR]"
site:linkedin.com/posts "social media manager" Vietnam hiring
```

**Reddit:**
```
site:reddit.com/r/forhire "AI agent" OR "AI automation" after:[FILTER_DATE]
site:reddit.com/r/forhire "chatbot" after:[FILTER_DATE]
site:reddit.com/r/forhire "website developer" after:[FILTER_DATE]
site:reddit.com/r/hiring "email marketing" after:[FILTER_DATE]
```

**Diễn đàn Việt Nam:**
```
site:vbiz.vn "cần AI" OR "cần làm website" OR "cần chatbot" "[CURRENT_YEAR]"
site:5giay.vn "cần dev" OR "cần thiết kế" OR "cần IT" "[CURRENT_YEAR]"
site:muaban.net "thiết kế website" OR "quản lý fanpage" after:[FILTER_DATE]
site:enbac.com "cần làm web" OR "cần digital marketing" OR "cần AI"
```

**Query mẫu ưu tiên chạy trước (copy và thay [FILTER_DATE], [CURRENT_YEAR]):**
1. `site:facebook.com "cần AI" OR "cần AI agent" after:[FILTER_DATE]`
2. `site:facebook.com "cần làm website" "[CURRENT_YEAR]"`
3. `site:facebook.com "cần quản lý fanpage" "[CURRENT_YEAR]"`
4. `site:reddit.com/r/forhire "AI automation" OR "chatbot" after:[FILTER_DATE]`
5. `site:vbiz.vn "cần AI" OR "cần website" OR "cần IT" "[CURRENT_YEAR]"`

### 3.2 Facebook Groups

Xem danh sách nhóm đầy đủ tại `references/platforms.md`.

**Cách tìm trên Facebook:**
1. Tìm kiếm Facebook → gõ từ khóa → tab **"Bài viết"**
2. Lọc theo **Nhóm** → **Ngày đăng: Hôm nay / Tuần này**
3. Ưu tiên nhóm 50K+ thành viên

### 3.3 LinkedIn

```
site:linkedin.com/posts "AI agent" OR "agentic AI" Vietnam
site:linkedin.com/posts "looking for" "web developer" Vietnam
site:linkedin.com/posts "need chatbot" developer
site:linkedin.com/jobs "AI developer" Vietnam
site:linkedin.com/jobs "web developer" freelance Vietnam
```

### 3.4 Reddit

```
https://www.reddit.com/r/forhire/search/?q=AI+agent&restrict_sr=1&sort=new
https://www.reddit.com/r/forhire/search/?q=chatbot&restrict_sr=1&sort=new
https://www.reddit.com/r/forhire/search/?q=website+developer&restrict_sr=1&sort=new
https://www.reddit.com/r/hiring/search/?q=AI+automation&sort=new
```

### 3.5 Twitter / X

```
"cần AI agent" OR "cần AI automation" lang:vi
"cần làm website" OR "cần chatbot" lang:vi
"cần quản lý fanpage" lang:vi
"need AI agent" developer -sponsored
"AI automation" "looking for" -newsletter
```

---

## Bước 4 — Thực thi tìm kiếm

**LƯU Ý BẮT BUỘC:**

1. **Thời gian động**: Dùng ngày hiện tại (lấy từ Bước 0) để tạo filter. KHÔNG dùng năm cố định. Bài đăng quá 3 tháng → LOẠI BỎ ngay.

2. **Trích xuất thông tin liên hệ**: Khi dùng `web_fetch`, **BẮT BUỘC quét**:
   - Số điện thoại: `0[0-9]{9}`, `+84[0-9]{9}`, các dạng có dấu chấm/gạch ngang
   - Email: `[text]@[domain]`
   - Zalo: "zalo:", "liên hệ zalo", số Zalo
   - Link profile Facebook / Messenger của người đăng
   - Thông tin này **hiển thị nổi bật** trong output

3. **Quy trình**:
   1. Tính `[FILTER_DATE]` và `[CURRENT_YEAR]` từ ngày hôm nay
   2. Chạy 3–5 queries Google với `web_search` (dùng bộ lọc động)
   3. Kiểm tra ngày đăng — quá 3 tháng: LOẠI BỎ
   4. Với kết quả mới và hứa hẹn: dùng `web_fetch` lấy nội dung đầy đủ
   5. Quét contact info, tổng hợp theo template output

**Số lượng queries khuyến nghị:**
- Tìm nhanh: 3–5 queries, 1–2 nền tảng
- Tìm đầy đủ: 10–15 queries, 3–5 nền tảng
- Nghiên cứu thị trường: 20+ queries, tất cả nền tảng

---

## Bước 5 — Đánh giá và phân loại leads

### Tiêu chí chấm điểm

| Tiêu chí | Điểm |
|---------|------|
| Nêu rõ dịch vụ cần (AI/web/chatbot/...) | +2 |
| Có ngân sách / budget cụ thể | +2 |
| Bài đăng mới (< 7 ngày) | +3 |
| Bài đăng mới (7–30 ngày) | +1 |
| **Có SĐT / email / Zalo liên hệ** | **+3** |
| Tương tác cao (nhiều comment hỏi giá) | +1 |
| Nêu deadline / thời gian cần gấp | +1 |
| Là doanh nghiệp / có tên công ty | +1 |
| Nhu cầu Agentic AI / AI Automation | +1 (bonus xu hướng) |

**Phân loại:**
- 🔥 **Hot lead** (9–14 điểm): Tiếp cận ngay trong 24h
- ⚡ **Warm lead** (5–8 điểm): Tiếp cận trong 48–72h
- ❄️ **Cold lead** (< 5 điểm): Lưu vào pipeline

---

## Bước 6 — Format output

```
## 📊 Tổng quan kết quả
- Ngày tìm kiếm: [ngày hôm nay - tự động lấy]
- Khoảng thời gian lọc: [ngày hiện tại - 90 ngày] đến nay
- Tổng leads tìm được: X
- Hot leads 🔥: X | Warm leads ⚡: X | Cold leads ❄️: X
- Nền tảng: [danh sách]
- Dịch vụ: [danh sách]
- Từ khóa đã dùng: [danh sách]

---

## 🔥 Hot Leads

### Lead #1 — [Tên/Username] | [Nền tảng] | [Dịch vụ]
- **Nhu cầu**: [mô tả ngắn gọn, rõ ràng]
- **Dịch vụ**: Agentic AI / AI Automation / Website / Chatbot / Email marketing / Quản lý fanpage / Thuê đội IT / ...
- **Ngân sách**: [nếu có] / Chưa rõ
- **Ngày đăng**: [ngày cụ thể]
- **Link bài đăng**: [URL]
- 📞 **SĐT**: [số điện thoại — bỏ trống nếu không có]
- 📧 **Email**: [email — bỏ trống nếu không có]
- 💬 **Zalo/Liên hệ khác**: [nếu có]
- **Điểm**: X/14
- **Ghi chú**: [thông tin thêm hữu ích]

---

## ⚡ Warm Leads
[tương tự cấu trúc trên]

---

## ❄️ Cold Leads
[tương tự cấu trúc trên]

---

## 💡 Đề xuất tiếp cận
[Script liên hệ cho từng hot lead, cá nhân hóa theo nhu cầu cụ thể]
```

---

## Bước 7 — Script tiếp cận (tùy chọn)

Nếu user muốn, tạo **outreach message** cho từng hot lead:

**Template cho Agentic AI:**
```
Chào [Tên],

Mình thấy bạn đang cần [AI agent / AI automation / tự động hóa quy trình]. 
Bên mình chuyên triển khai giải pháp AI cho [ngành của họ] — từ AI agent xử lý 
đơn hàng, CSKH tự động, đến workflow automation toàn diện.

Bạn muốn mình demo thử giải pháp AI phù hợp với nghiệp vụ của bạn không?

Liên hệ: [thông tin công ty]
```

**Template cho dịch vụ digital khác:**
```
Chào [Tên],

Mình thấy bạn đang cần [dịch vụ cụ thể]. Bên mình chuyên [dịch vụ] 
cho [ngành/loại doanh nghiệp tương tự].

[1 câu proof]

Bạn có muốn mình tư vấn miễn phí và gửi báo giá không?
```

**Lưu ý:**
- Không spam, cá nhân hóa theo từng lead
- Dưới 100 từ mỗi message
- Ưu tiên Zalo với lead có SĐT (phản hồi cao hơn gọi điện lạnh)

---

## Lưu ý quan trọng

- **Thời gian là động** — skill tự tính ngày filter từ thời điểm thực thi, không bao giờ hardcode năm
- **Ưu tiên leads mới < 7 ngày** — nhu cầu cũ hơn có thể đã được đáp ứng
- **SĐT/email = +3 điểm** — lead có contact info phải được ưu tiên tiếp cận trước
- **Agentic AI là xu hướng nóng** — leads nhu cầu AI automation thường có budget cao hơn
- Không scrape dữ liệu cá nhân — chỉ tổng hợp thông tin được đăng công khai
- Google cache có thể chậm 1–3 ngày → ghi rõ ngày tìm kiếm trong output

---

## Tham khảo thêm

Xem file `references/platforms.md` để biết danh sách đầy đủ nhóm Facebook, subreddit, và forum Việt Nam theo từng ngành hàng.
