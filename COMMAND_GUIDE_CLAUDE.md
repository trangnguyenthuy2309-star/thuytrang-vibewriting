# COMMAND GUIDE - CÁC LỆNH GỌI CLAUDE

**Hướng dẫn câu lệnh để bắt đầu hoặc nhảy vào bất kỳ bước nào trong hệ thống sản xuất nội dung.**

---

## 🚀 **LỆNH KHỞI ĐỘNG WORKFLOW**

### **Bắt đầu từ đầu (lần đầu tiên)**

```
"Bắt đầu Step 1 - Xây dựng hệ thống"
```
Claude sẽ:
- Hướng dẫn đọc Strategy Overview
- Kiểm tra hiểu rõ về dự án
- Chuẩn bị cho brainstorm tuần 1

---

### **Bắt đầu Step 2 - Đọc & Hiểu (Review)**

```
"Bắt đầu Step 2 - Tôi muốn hiểu hệ thống"
```
Claude sẽ:
- Dẫn dắt đọc 3 files cơ bản (Strategy, Audience, Ideation System)
- Kiểm tra hiểu rõ trước brainstorm

---

### **Bắt đầu Step 3 - Brainstorm tuần (THƯỜNG XUY DÙNG)**

```
"Bắt đầu Step 3 - Brainstorm tuần này"
```
Claude sẽ:
- Dẫn dắt 5 methods ideation
- Giúp ghi ideas vào 3.2_CONTENT_IDEAS_BANK.csv
- Chọn 7 ideas tốt nhất
- Setup 7 sub-folders trong 4.5_WEEKLY_DRAFTS
- Update status ideas

**Kết quả:** Ready to write!

---

## 📝 **LỆNH NHẢY VÀO CÁC BƯỚC**

Dùng khi muốn skip các bước trước & đi thẳng vào:

### **Muốn viết draft (Step 5)**

```
"Tôi muốn viết draft hôm nay - dẫn dắt tôi"
```
Claude sẽ:
- Confirm: Bạn có 7 ideas ready & folders setup chưa?
- Nếu chưa → Hướng dẫn setup nhanh
- Nếu có → Dẫn dắt viết draft bài đầu tiên
- Nhắc: Đọc framework, dùng template

---

### **Muốn edit draft (Step 6)**

```
"Tôi muốn edit drafts tuần này - check hộ tôi"
```
Claude sẽ:
- Yêu cầu: Paste 1 draft hoặc nói nó ở đâu
- Self-edit checklist
- Brand voice check (dùng 4.3 checklist)
- Feedback: Hook? Structure? Evidence? CTA? Voice?
- Output: Suggestions để improve

---

### **Muốn publish (Step 7)**

```
"Tôi muốn publish hôm nay - check trước publish hộ"
```
Claude sẽ:
- Yêu cầu: Paste FINAL content
- Run 5 Quality Gates check:
  1. Hook check
  2. Structure check
  3. Evidence check
  4. CTA check
  5. Brand voice check
- Pass? → "Ready to publish!" + Update tracking guide
- Fail? → Show which gate failed + how to fix

---

## 🎯 **LỆNH CHO CÁC BƯỚC SPECIFIC**

### **Brainstorm ideas (5 methods)**

```
"Giúp tôi brainstorm ideas ngày hôm nay"
```
Claude sẽ:
- Dẫn dắt 5 ideation methods
- Gợi ý ideas dựa trên 2.1_AUDIENCE_PERSONA
- Giúp phân loại tuyến & cột trụ

---

### **Lựa chọn ideas tốt nhất**

```
"Tôi có 15 ideas - giúp tôi chọn 7 tốt nhất"
```
Claude sẽ:
- Yêu cầu: Paste 15 ideas
- Analyze: Tuyến mix, cột trụ, audience resonance
- Recommend: 7 ideas & lý do tại sao

---

### **Setup content calendar**

```
"Giúp tôi setup calendar tuần này"
```
Claude sẽ:
- Yêu cầu: 7 ideas đã chọn
- Layout: FB + TikTok schedule
- Verify: Content mix % đúng không?
- Output: Calendar sẵn để dùng

---

### **Setup weekly folders**

```
"Giúp tôi tạo 7 sub-folders cho tuần này"
```
Claude sẽ:
- Yêu cầu: 7 ideas + hook chính mỗi cái
- Guide: Cách đặt tên folder [NGAY]_[HOOK]
- Verify: Folder structure đúng không?

---

### **Check brand voice**

```
"Check tone bài này có đúng brand voice không"
```
Claude sẽ:
- Yêu cầu: Paste content
- Check 5 attributes:
  - Conversational?
  - Specific?
  - Vulnerable?
  - Evidence?
  - Me-to-you?
- Output: Score + suggestions

---

### **Analyze content performance**

```
"Phân tích performance bài này - vì sao nó viral/flop?"
```
Claude sẽ:
- Yêu cầu: Paste content + metrics (reach, engagement)
- Analyze: Hook? Structure? Audience resonance?
- Output: Insights + "Làm nhiều thế nào tuần sau?"

---

## 🔄 **LỆNH QUẢN LÝ**

### **Tracking hàng tuần**

```
"Update KPI tracking tuần này"
```
Claude sẽ:
- Yêu cầu: 7 links + metrics
- Fill vào 5.1_KPI_TRACKING_SHEET.md
- Output: Tracking file ready

---

### **Review tháng & optimize**

```
"Review tháng này - insights & optimization"
```
Claude sẽ:
- Yêu cầu: Performance data từ tháng
- Analyze: Tuyến nào perform best? Hook type? Audience resonance?
- Output: 
  - What worked?
  - What didn't?
  - Adjustments for next month

---

### **Tìm ideas từ swipe file**

```
"Tôi có swipe file mới - integrate vào ideas không?"
```
Claude sẽ:
- Yêu cầu: New swipes từ 2.3_CONTENT_SWIPE_FILE.csv
- Analyze: Hooks? Structures? Angles?
- Output: "My Ideas" suggestions để add vào Ideas Bank

---

## 💬 **LỆNH HỎI & TÌNH HUỐNG**

### **Khi bị stuck**

```
"Tôi bị stuck - không biết viết cái gì. Giúp tôi tìm idea"
```
Claude sẽ:
- Yêu cầu: Context (đã có bao nhiêu ideas? Điểm yếu tuyến nào?)
- Use 5 ideation methods để brainstorm
- Output: 5-10 fresh ideas

---

### **Khi không chắc cách làm**

```
"Tôi không chắc bước [X] làm sao. Giải thích hộ tôi"
```
Claude sẽ:
- Explain step X chi tiết
- Reference file guide
- Ví dụ cụ thể

---

### **Khi muốn second opinion**

```
"Bài này tôi viết xong - cho tôi feedback trước publish"
```
Claude sẽ:
- Yêu cầu: Paste content
- Run QC checklist
- Output: Feedback chi tiết

---

## ⚡ **QUICK COMMANDS (SKIMMED VERSION)**

| Muốn làm gì | Lệnh |
|------|------|
| Bắt đầu từ đầu | "Bắt đầu Step 1" |
| Brainstorm tuần này | "Bắt đầu Step 3 - Brainstorm" |
| Viết draft | "Tôi muốn viết draft - dẫn dắt tôi" |
| Edit draft | "Check tone/structure bài này" |
| Publish | "Check trước publish - 5 gates?" |
| Tìm ideas | "Brainstorm ideas hôm nay" |
| Review performance | "Phân tích performance bài này" |
| Update tracking | "Update KPI tracking" |
| Stuck | "Tôi stuck - giúp tôi tìm idea" |

---

## 📌 **BEST PRACTICES**

### **1. Luôn provide context**

❌ Sai: "Brainstorm ideas"
✅ Đúng: "Giúp tôi brainstorm 7 ideas tuần này - tôi muốn focus tuyến 1 & 3"

### **2. Paste relevant files khi cần**

❌ Sai: "Check bài này"
✅ Đúng: "Check tone bài này - paste content + run brand voice check"

### **3. Nói rõ output bạn muốn**

❌ Sai: "Giúp tôi edit"
✅ Đúng: "Edit bài này + feedback chi tiết + suggestions cải thiện"

### **4. Refer tới files trong CLAUDE.md**

❌ Sai: "Làm sao để viết tốt?"
✅ Đúng: "Dẫn dắt viết draft - reference 4.1_FRAMEWORK_VIET_BAI_5_TUYEN.md"

---

## 🎯 **TYPICAL WEEKLY FLOW (Lệnh sequence)**

```
THỨ 2:
1. "Bắt đầu Step 3 - Brainstorm tuần này"
   → Brainstorm ideas, chọn 7, setup folders

THỨ 3-6:
2. "Tôi muốn viết draft - dẫn dắt tôi"
   → Viết 7 drafts (1-2 bài/ngày)
   → Update status ideas

THỨ 5-6:
3. "Check tone/structure bài này"
   → Edit mỗi bài

THỨ 7:
4. "Check trước publish - 5 gates?" 
   → Final QC
5. "Update KPI tracking"
   → Update metrics
```

---

**Ghi nhớ: Claude sẽ guide bạn từng bước. Chỉ cần nói rõ bạn muốn làm gì!** 🚀

---

**Last updated: 2026-06-07**
