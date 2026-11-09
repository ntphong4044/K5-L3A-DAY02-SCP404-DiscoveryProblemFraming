# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: SCP404
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Sinh viên IT năm cuối đang tìm thực tập mất 8–10 phút cho mỗi JD dài, viết không chuẩn (group Facebook, web công ty nhỏ) để tự đối chiếu yêu cầu với kỹ năng của mình rồi mới quyết định nộp hay bỏ.
- Quyết định cuối: **Not Yet**

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Đỗ Nhật Anh | Khi gặp JD thực tập dài, muốn biết ngay mình thiếu kỹ năng nào, để quyết định nộp hay bỏ | Sinh viên đang tìm thực tập | Đọc JD + tự đối chiếu từng yêu cầu: 7–8' trong ~10'/JD, ~20 JD/tuần | "Lần gần nhất đọc một JD là khi nào, mất bao lâu thật? 10 phút là bấm giờ hay ước lượng?" (Phong); "Nếu có sẵn checklist kỹ năng rồi Ctrl+F thì có đủ không, cần gì hơn?" (Bình) |
| 2 | Đỗ Nhật Anh | Khi đã nộp CV nhiều nơi, muốn biết chỗ nào đã gửi / chưa trả lời / có lịch PV, để không gửi trùng, không quên lịch | Sinh viên nộp nhiều hồ sơ thực tập | Tìm lại trạng thái và lịch PV ở nhiều kênh (Gmail, Zalo); đã sót 2 lịch PV | "Một Google Sheet + Calendar là giải được rồi, vấn đề thật là thiếu công cụ hay thiếu thói quen ghi lại?" (Thắng) |
| 3 | Đỗ Nhật Anh | Khi tối mở máy tìm thực tập, muốn xem tin mới ở một chỗ, để khỏi mở lần lượt 4 nguồn | Sinh viên đang tìm thực tập | Tìm trong group FB, web công ty, tự nhớ tin đã xem; ~45'/tối × 4–5 tối/tuần | "'Xem ở một chỗ' nghe giống giải pháp rồi. Với lại LinkedIn, group FB có cho lấy tin tự động không?" (Phong) |
| 4 | Kim Đức Thắng | Khi gặp lỗi trong lúc code, muốn tìm ra nguyên nhân nhanh hơn, để không mất quá nhiều thời gian sửa lỗi | Sinh viên làm đồ án / học lập trình | Bước tìm nguyên nhân lỗi: tra Google, Stack Overflow, hỏi bạn/AI rồi sửa thử, chạy lại; chưa đo số phút mỗi lỗi | "Trung bình một lỗi mất bao lâu? Lỗi mỗi lần một kiểu thì đo baseline kiểu gì?" (Nhật Anh) |
| 5 | Kim Đức Thắng | Khi tìm thực tập, muốn tổng hợp yêu cầu từ các tin tuyển dụng, để biết mình còn thiếu kiến thức gì | Sinh viên đang tìm thực tập | Đọc nhiều tin, so sánh yêu cầu giữa các công ty bằng tay; chưa đếm số tin/tuần | "Cái này khác gì card #1 của Anh?" (Nhật Anh); "Ngoài bạn còn ai gặp không? Một tuần bạn đọc khoảng bao nhiêu tin?" (Bình) |
| 6 | Kim Đức Thắng | Khi học một công nghệ mới, muốn tổng hợp kiến thức từ nhiều nguồn, để dễ hiểu và áp dụng | Sinh viên tự học công nghệ mới | Đọc bài viết, video, tài liệu chính thức rồi tự ghi chú lại; chưa đo thời gian | "Đo 'hiểu được' bằng gì? Tổng hợp nhanh hơn mà hiểu sai thì sao?" (Phong) |
| 7 | Nguyễn Tuấn Phong | Khi phải theo dõi lịch học, lịch thi, deadline từ nhiều nhóm chat và web trường, muốn biết hôm nay/tuần này có việc gì quan trọng, để không bỏ lỡ | Sinh viên học 3 môn, 5 nhóm Zalo/Discord | Lọc tin quan trọng giữa nhiều tin không liên quan: 10' trong 27'/ngày; đã lỡ 1 lần (học phí thi) | "Bottleneck thật là bước lọc tin, hay là bước trước nó (có quá nhiều nguồn)? Lỡ 1 lần/kỳ đã đủ gọi là pain chưa?" (Nhật Anh); "Lấy tin nhắn Zalo ra kiểu gì, có dính tin nhắn riêng của người khác không?" (Thắng) |
| 8 | Nguyễn Tuấn Phong | Khi làm FE cần BE thêm/sửa API, muốn biết API nào xong/đang làm, để không phải nhắn hỏi và chờ | Sinh viên làm FE trong nhóm 4 người (đồ án Java Card) | Chờ BE phản hồi: ~18'/lần, ~4 lần/tuần | "Đây là chuyện phối hợp trong nhóm, có bảng task + mock API là xong, có cần AI không?" (Bình) |
| 9 | Nguyễn Tuấn Phong | Khi ôn thi môn có 5–10 file tài liệu, muốn nắm nhanh nội dung chính và tìm lại đúng chỗ, để ôn kịp | Sinh viên ôn thi (môn CTDL&GT) | Đọc lướt tài liệu: 60' trong 150'/lần ôn | "Ôn nhanh hơn mà điểm thấp hơn thì sao? Metric mới đo thời gian, chưa đo hiểu bài." (Thắng) |
| 10 | Dương Thái Bình | Khi đến kỳ báo cáo, muốn có đủ số liệu tải, doanh thu, người chơi của từng game, để không bỏ sót | Junior Game Dev làm báo cáo cho CEO và Senior | Tổng hợp số liệu từ nhiều store: ~30' trong 90' | "Báo cáo hằng ngày hay hằng tuần? Bảng scan ghi 60'/ngày mà card ghi 90'." (Phong); "Store có cho export CSV không? Nếu có thì Google Sheets là đủ rồi?" (Thắng) |
| 11 | Dương Thái Bình | Khi CEO và Senior cần góc nhìn khác nhau, muốn hiểu rõ nhu cầu từng người, để không phải sửa báo cáo nhiều lần | Junior Game Dev; người nhận là CEO, Senior | Nhận phản hồi rồi phân tích lại + sửa: ~60' mỗi vòng | "Hỏi thẳng CEO với Senior một lần rồi làm template cố định có được không?" (Nhật Anh) |
| 12 | Dương Thái Bình | Khi nhận báo cáo nhiều số liệu, CEO muốn thấy ngay thay đổi quan trọng, để ra quyết định ưu tiên | CEO (người đọc); Junior Game Dev (người viết) | CEO hỏi lại / yêu cầu giải thích thêm sau khi đọc | "Actor là CEO, nhóm mình không phỏng vấn CEO được thì kiểm chứng kiểu gì?" (Thắng) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #1, #2, #3, #5 | Tìm và ứng tuyển thực tập: thông tin tuyển dụng dài, rải rác, khó theo dõi (2 người độc lập cùng gặp) |
| B | #7, #9, #6 | Thông tin học tập nằm rải rác nhiều nguồn, mất thời gian lọc và tổng hợp |
| C | #10, #11, #12 | Báo cáo số liệu game cho quản lý: thu thập, trình bày, sửa nhiều vòng |
| D | #4, #8 | Bị chặn việc khi làm đồ án lập trình (lỗi, phụ thuộc người khác) |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm số phút mỗi tuần phải tự đọc, lục lại và đối chiếu thông tin nằm rải rác
├── Opportunity A: Tìm thực tập — tin tuyển dụng dài, nằm nhiều nơi, khó biết mình có hợp không
│   ├── A1: Phải đọc hết JD rồi tự đối chiếu mới biết mình thiếu kỹ năng gì (~10'/JD, ~20 JD/tuần) (#1, #5)
│   ├── A2: Tin mới nằm ở ~4 nguồn, mất ~45'/tối và không nhớ tin nào đã xem (#3)
│   ├── A3: Không nhớ hồ sơ nào đã nộp, đang chờ hay có lịch phỏng vấn; đã sót 2 lịch (#2)
│   ✗ "Xem tin tuyển dụng mới ở một chỗ"            ← SOLUTION, gạch bỏ
│   ✗ "Tool tự trích kỹ năng trong JD rồi so với CV" ← SOLUTION, gạch bỏ
├── Opportunity B: Thông tin học tập lẫn trong nhiều nguồn, khó lọc ra cái quan trọng
│   ├── B1: Thông báo, deadline lẫn giữa nhiều tin không liên quan; mất 10' lọc/ngày, đã lỡ 1 lần (#7)
│   ├── B2: Tài liệu dài, nhiều nguồn, khó nắm ý chính khi ôn thi / học cái mới (#9, #6)
│   ✗ "AI tóm tắt tài liệu theo chương"                    ← SOLUTION, gạch bỏ
└── Opportunity C: Số liệu game nằm ở nhiều store, người đọc báo cáo khó thấy điểm quan trọng nên phải hỏi lại, sửa nhiều vòng (#10, #11, #12)
    ✗ "Dashboard số liệu game tự cập nhật"  ← SOLUTION, gạch bỏ
```

> Cluster D (#4 lỗi code, #8 chờ BE) không đưa vào cây vì pain của nó là bị chặn việc (do lỗi hoặc do chờ người khác), không phải do thông tin rải rác, nên không khớp với outcome chung.

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~"Xem tin tuyển dụng mới ở một chỗ"~~ (#3) — đây là cách giải (gom nguồn), pain thật là mất ~45'/tối và không nhớ tin nào đã xem → viết lại thành A2.
- ~~"Tool tự trích kỹ năng trong JD rồi so với CV"~~ (#1) — đã nói luôn cách làm, nhu cầu thật là biết nhanh mình thiếu gì để quyết định nộp hay bỏ → giữ lại dạng pain là A1.
- ~~"AI tóm tắt tài liệu theo chương"~~ (#9) — có chữ "AI" và là tính năng, pain thật là đọc lướt mất 60' mà vẫn khó xác định trọng tâm → B2.
- ~~"Dashboard số liệu game tự cập nhật"~~ (#10) — là công cụ, pain thật là mất ~30' tổng hợp số liệu bằng tay và dễ sót → C.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| A1 — Đọc JD và tự đối chiếu kỹ năng (#1 + #5) | 5 | 4 | 3 | 4 | 5 | 5 | 5 | **31** |
| B1 — Lọc thông báo/deadline từ nhiều nhóm chat (#7) | 5 | 5 | 4 | 4 | 3 | 4 | 5 | **30** |
| C — Tổng hợp số liệu game cho báo cáo (#10) | 4 | 4 | 3 | 4 | 2 | 3 | 2 | **22** |

**Candidate được chọn:** A1 — Sinh viên IT đang tìm thực tập phải đọc hết từng JD dài rồi tự đối chiếu với kỹ năng của mình (ước tính ~10 phút/JD, ~20 JD/tuần) mới quyết định được có nên nộp hay không. Gộp card #1 của Nhật Anh và card #5 của Thắng vì hai bạn tự gặp cùng một vấn đề.

**Vì sao chọn:**

- Điểm cao nhất (31/35). Hai người trong nhóm (Nhật Anh, Thắng) cùng gặp vấn đề này, các bạn khác cùng lớp cũng đang tìm việc thực tập nên dễ phỏng vấn thêm ở CP4.
- Quy trình khá rõ (mở JD → đọc → nhớ lại kỹ năng → đối chiếu → quyết định), bottleneck nằm ở bước đọc và đối chiếu.
- Vừa sức một buổi lab: đầu vào chỉ là đoạn text JD và danh sách kỹ năng của mình, không cần xin quyền truy cập hệ thống nào.
- So sánh được đủ 4 mức: No AI (checklist + Ctrl+F), Rule (lọc theo từ khóa), Workflow (trích yêu cầu rồi đối chiếu, người kiểm tra lại), Agent (tự tìm JD và tự đánh giá). Câu hỏi của Bình "Ctrl+F có đủ không" là chỗ nhóm cần trả lời ở CP6.
- Điểm yếu cần xử lý ngay ở CP4: số phút chưa đo thật → phải hỏi thêm người khác để có baseline.

**Vì sao loại các candidate còn lại:**

- **B1 (#7, thông báo/deadline):** sát điểm nhất (30), số liệu chi tiết nhất. Nhưng muốn làm phải lấy tin nhắn từ nhóm Zalo/Discord, vừa khó lấy vừa dính tin nhắn riêng của người khác. Ngoài ra phương án No AI (ẩn bớt nhóm, lớp trưởng tổng hợp tuần, ghi ngay vào Google Calendar) có vẻ đã giải được phần lớn. Nhóm để B1 làm **phương án dự phòng**.
- **C (#10, số liệu game):** chỉ Bình hiểu domain, dữ liệu là của công ty nên không đem ra lab được, số phút còn chưa thống nhất (60'/ngày hay 90'/tuần). Nếu store cho export CSV thì nhiều khả năng chỉ cần Google Sheets + công thức (Rule) là đủ.
- **#2 (theo dõi hồ sơ đã nộp):** chính Nhật Anh tự đánh giá là No AI, một Google Sheet + Calendar nhắc lịch là giải được.
- **#3 (tin mới ở nhiều nguồn):** LinkedIn và group Facebook hạn chế lấy tin tự động; bật thông báo theo từ khóa (Rule) là được phần lớn.
- **#4 (tìm lỗi code), #6 (học công nghệ mới), #9 (ôn thi):** chưa có số liệu đo được, hoặc metric mới đo thời gian chứ chưa đo được "hiểu bài", khó chứng minh cải thiện trong một buổi.
- **#8 (chờ BE):** là vấn đề phối hợp trong nhóm, bảng task + API contract + mock API là giải được, không cần AI.
- **#11, #12 (báo cáo cho CEO):** actor chính là CEO và Senior, nhóm không phỏng vấn được trong buổi lab nên không kiểm chứng được.

**Xử lý bất đồng (nếu có):** Không có

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
