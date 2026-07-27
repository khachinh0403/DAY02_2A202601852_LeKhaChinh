# Individual Problem Scan

## 1. Scan vấn đề

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Review lại slide bài giảng sau lớp để chép lại ghi chú | Bản thân | Mất 20-30 phút buổi tối khi nội dung chưa rõ |
| 2 | Tốn thời gian | Liên lạc với đồng đội trong nhóm đôi khi kéo dài mới có phản hồi | Cả team | Đã có lần chờ 1 ngày mới nhận được trả lời, delay tiến độ |
| 3 | Lặp lại | Viết báo cáo tiến độ nhóm mỗi tuần | Nhóm | Tốn 30-40 phút mỗi lần tổng hợp và thường cần họp bổ sung |
| 4 | AI có thể hỗ trợ tốt hơn | Tổng hợp thông tin từ Discord/Google Docs/Email thành bản tóm tắt chung | Người tổng hợp | Mất 20-25 phút, vẫn thiếu rõ ràng và lặp lại thông tin |
| 5 | Khó khăn đến từ người khác | Thành viên nhóm không đồng bộ deadline và task, phải nhắc lại nhiều lần | Cả nhóm | Ít nhất 2-3 lần/tuần phải nhắc nhở, gây xáo trộn |
| 6 | Lặp lại | Đọc email hoặc tin nhắn dài để biết trạng thái công việc | Nhóm | Mất 10-15 phút mỗi lần kiểm tra status |
| 7 | Tốn thời gian | Ôn tập tài liệu bài giảng bằng cách đọc hết rồi ghi chép tay | Bản thân | Mất 30 phút, dễ bỏ sót ý chính |
| 8 | AI có thể hỗ trợ tốt hơn | Tìm ví dụ code và cách giải trong Python khi tự học | Bản thân | Dành nhiều thời gian tìm tài liệu và thử code |

## 2. Top 3 Problem Cards

### Problem Card #1

**Problem 1 câu:**
Nhóm dự án tốn quá nhiều thời gian để tổng hợp tiến độ vì thông tin rời rạc trên Discord, Google Docs và Email, dẫn đến họp bổ sung và thiếu bức tranh chung.

**Actor:**
Người tổng hợp tiến độ trong nhóm dự án học tập.

**Thời điểm / bối cảnh:**
Trước mỗi buổi cập nhật tiến độ hoặc khi giảng viên yêu cầu báo cáo nhóm.

**Current workflow:**
1.Thu thập cập nhật từ Discord/Google Docs/Email.
2.Đọc lại từng thông tin và tìm dữ liệu cần thiết.
3.Nhắc lại nếu thông tin thiếu hoặc không rõ.
4.Viết báo cáo chung.
5.Gửi cho nhóm/giảng viên.

**Bottleneck:**
Bước 2-3 — đọc nhiều nguồn và chờ phản hồi mất 20-25 phút.

**Impact:**
Mất 30-40 phút mỗi lần, gây delay, họp bổ sung và dễ quên task quan trọng.

**Success metric:**
Giảm thời gian chuẩn bị báo cáo từ 30-40 phút xuống dưới 15 phút và giảm số lần họp bổ sung ít nhất 50%.

**Non-AI alternative:**
Dùng form cập nhật định kỳ hoặc template thống nhất để giảm lượng thông tin cần đọc.

**AI hypothesis:**
AI có thể gộp các update rời rạc thành bản tóm tắt tiến độ, giúp người tổng hợp chỉ cần review và hoàn thiện.

**Quick gut:**
[ ] No AI / process fix   [ ] Rule   [x] Workflow   [ ] Agent   [ ] Chưa biết

### Draft workflow cho Problem #1

#### Current workflow

```text
CURRENT STATE — 35-40 phút
[1] Thu thập update từ Discord/Docs/Email: 10-15'
→ [2] Đọc và lọc thông tin: 15-20'  <-- bottleneck
→ [3] Nhắc hoặc hỏi bổ sung: 5-10'
→ [4] Viết báo cáo chung: 5-10'
→ [5] Gửi cho nhóm/giảng viên: 1'
```

#### Future workflow

```text
FUTURE STATE — 15 phút
[1] Thu thập update bằng form hoặc chat cấu trúc: 3'
→ [2] AI gộp và tạo bản summary tiến độ: 4'
→ [3] Người tổng hợp review và chỉnh sửa: 7'
→ [4] Gửi báo cáo: 1'
```

Fallback nếu AI tóm tắt sai: người tổng hợp sửa trực tiếp hoặc dùng dữ liệu input để viết thủ công.

### Problem Card #2

**Problem 1 câu:**
Liên lạc với đồng đội trong nhóm đôi khi mất quá nhiều thời gian vì phải chờ trả lời từng người và nhắc lại nhiều lần.

**Actor:**
Thành viên nhóm dự án.

**Thời điểm / bối cảnh:**
Khi cần xác nhận task, deadline, hoặc cập nhật trạng thái.

**Current workflow:**
1.Gửi tin nhắn/Discord hỏi mọi người.
2.Chờ trả lời từng người.
3.Nhắc thêm nếu chưa có phản hồi.
4.Tổng hợp câu trả lời.

**Bottleneck:**
Bước 2-3 — chờ và nhắc mất nhiều thời gian.

**Impact:**
Delay tới 1 ngày, gây nghẽn bước quyết định và chậm tiến độ.

**Success metric:**
Giảm số lần nhắc và thời gian chờ trả lời từ 24 giờ xuống dưới 6 giờ.

**Non-AI alternative:**
Quy định thời gian trả lời và form cập nhật nhanh.

**AI hypothesis:**
AI có thể nhắc timeline và gợi ý cách hỏi chuẩn, giúp thu thập thông tin nhanh hơn.

**Quick gut:**
[ ] No AI / process fix   [ ] Rule   [x] Workflow   [ ] Agent   [ ] Chưa biết

### Problem Card #3

**Problem 1 câu:**
Review slide và tài liệu bài giảng sau lớp tốn nhiều thời gian vì phải đọc toàn bộ nội dung và tự chép ghi chú.

**Actor:**
Sinh viên tự học và ôn tập.

**Thời điểm / bối cảnh:**
Buổi tối sau giờ học hoặc trước khi làm bài tập.

**Current workflow:**
1.Mở slide/tài liệu.
2.Đọc toàn bộ nội dung.
3.Ghi chép lại ý chính.
4.So sánh với ghi chú cũ.

**Bottleneck:**
Bước 2-3 — đọc và chép ghi chú mất 25-30 phút.

**Impact:**
Giảm thời gian ôn tập và dễ bỏ sót nội dung quan trọng.

**Success metric:**
Giảm thời gian từ 30 phút xuống dưới 15 phút, vẫn giữ được cấu trúc nội dung chính.

**Non-AI alternative:**
Dùng template ghi chú và đọc theo mục lục.

**AI hypothesis:**
AI có thể tóm tắt slide và tạo sườn ghi chú để người học review nhanh.

**Quick gut:**
[ ] No AI / process fix   [ ] Rule   [x] Workflow   [ ] Agent   [ ] Chưa biết

## 3. Summary top 3

| Rank | Problem | Vì sao chọn | Điều cần kiểm chứng |
|---|---|---|---|
| 1 | Đồng bộ tiến độ nhóm từ nhiều nguồn | Workflow rõ, có evidence thực tế, có metric thời gian | AI có thể tổng hợp đủ chính xác và rõ ràng |
| 2 | Liên lạc đồng đội chậm trả lời | Pain thật, ảnh hưởng tiến độ nhóm | Phù hợp scope lab không quá rộng |
| 3 | Review slide bài giảng | Tốn thời gian cá nhân, có thể dùng AI tóm tắt | Chất lượng tóm tắt có đủ dùng không |

---