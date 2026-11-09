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
| 1 | Sinh viên IT khác (ngoài nhóm) đang tìm thực tập cũng đọc nhiều JD mỗi tuần (≥10 JD) và mất trên 5 phút/JD mới quyết định được | Value | 5 | 2 | ✅ |
| 2 | Bước mất thời gian nhất là **tự đối chiếu** yêu cầu với kỹ năng của mình, chứ không phải bước đọc để tìm phần yêu cầu | Value | 5 | 1 | ✅ |
| 3 | Có khá nhiều JD (khoảng 1/3 trở lên) đọc hết rồi mới thấy không hợp, tức là thời gian đó bị phí | Value | 4 | 2 | ✅ |
| 4 | Checklist kỹ năng + Ctrl+F **chưa đủ**, vì JD hay viết cùng một kỹ năng bằng nhiều cách (vd "RESTful API" / "làm việc với API", "ReactJS" / "React") | Feasibility | 4 | 1 | ✅ |
| 5 | Sinh viên chịu dán JD + danh sách kỹ năng vào một công cụ và tự kiểm tra lại kết quả, không tin mù | Usability | 3 | 2 | — (để sau) |
| 6 | Đưa danh sách kỹ năng / CV cá nhân vào công cụ bên ngoài không làm sinh viên ngại về thông tin cá nhân | Viability | 3 | 3 | — (để sau) |

Giả định nhóm kiểm chứng trong buổi này:#1, #2 và #4 (quan trọng cao nhưng gần như chưa có bằng chứng, vì 10 phút/JD hiện mới là ước lượng). #3 hỏi luôn trong lúc phỏng vấn. #5, #6 ít quan trọng hơn ở giai đoạn này nên để sau.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn trực tiếp 2 bạn học nhóm khác ngồi cạnh, trong buổi sáng lab Day 02, theo 3 luật The Mom Test (hỏi về lần gần nhất đã xảy ra, không hỏi "bạn có muốn…").

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

*Snapshot #1*

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | SV năm cuối CNTT, đang tìm thực tập Backend Java ở Hà Nội (bạn học lớp L3A, nhóm khác) |
| Khi nào, hỏi bằng cách nào | Buổi sáng trong buổi lab Day 02; phỏng vấn trực tiếp bạn ngồi bên cạnh, khoảng 5–10 phút |
| Câu nói đáng nhớ nhất (nguyên văn) | "Mình nhìn tiêu đề với số năm kinh nghiệm trước, ghi Intern mà đòi 1 năm là tắt luôn." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối qua tìm "Backend Intern Hà Nội" trên TopCV, mở khoảng 8 tin thì 5 tin là vị trí Middle/Senior lẫn vào kết quả, phải mở ra mới biết |
| Hiện đang xử lý bằng cách nào (workaround)? | Ctrl+F chữ "kinh nghiệm", "năm"; có một file note ghi sẵn kỹ năng của mình để so |
| Mất bao lâu, bao lần? | Khoảng 3–5 phút/tin, khoảng 15 tin/tuần; tin nào hợp thì mới đọc kỹ phần kỹ năng |
| Insight / opportunity rút ra | Phần lớn tin bị bỏ vì **số năm kinh nghiệm**, loại này Ctrl+F/lọc là đủ (Rule). Thời gian đối chiếu kỹ năng chỉ thật sự tốn với những tin đã qua vòng lọc đầu |

*Snapshot #2*

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | SV năm cuối CNTT, đang tìm thực tập Mobile (Flutter) ở Hà Nội (bạn học lớp L3A, nhóm khác) |
| Khi nào, hỏi bằng cách nào | Buổi sáng trong buổi lab Day 02; phỏng vấn trực tiếp bạn ngồi bên cạnh, khoảng 5–10 phút |
| Câu nói đáng nhớ nhất (nguyên văn) | "Đọc thì nhanh, cái lâu là không biết họ ghi 'có kiến thức state management' thì mình mới dùng Provider có được tính không." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tuần trước thấy tin của một công ty nhỏ đăng trong group Facebook, JD dài, viết lẫn tiếng Anh. Đọc và tự so mất gần 10 phút, cuối cùng vẫn nộp vì không chắc mình đủ hay chưa |
| Hiện đang xử lý bằng cách nào (workaround)? | Hỏi bạn cùng lớp đang làm Mobile; thỉnh thoảng dán JD vào ChatGPT hỏi nhưng phải kiểm lại vì có lúc nó nói chung chung |
| Mất bao lâu, bao lần? | Tin dài, không chuẩn: khoảng 8–10 phút/tin; khoảng 10 tin/tuần, trong đó tầm một nửa là tin từ group/web công ty |
| Insight / opportunity rút ra | Bottleneck nằm ở bước **đối chiếu khi JD dùng từ khác với kỹ năng mình ghi** (khớp giả định #2, #4). Pain rõ nhất với tin từ group FB/web công ty, đúng phần mà công cụ có sẵn chưa phủ |


Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 2 | Cả 2 người đọc 10–15 tin/tuần; người #2 mất 8–10 phút/tin dài ở bước đối chiếu, đã từng nộp mà không chắc mình đủ điều kiện | Người #1 chỉ mất 3–5 phút/tin, chủ yếu bỏ vì số năm kinh nghiệm, Ctrl+F là đủ → không phải JD nào cũng là pain |
| Research (mục 3.3) | 3 công cụ | Đã có nhiều công cụ làm bước trích kỹ năng + so khớp → chứng tỏ đây là pain có thật, có người trả tiền | Vì đã có công cụ, pain có thể đã được giải một phần cho tin trên LinkedIn |


**Nhóm đã sửa problem thế nào sau kiểm chứng:** 
1. **Tách 2 loại JD:** loại bị loại vì điều kiện dễ thấy (số năm kinh nghiệm, ngoại ngữ) thì checklist + Ctrl+F/lọc là đủ → để mức **Rule/No AI**, không đưa vào problem chính.
2. **Thu hẹp bottleneck:** pain thật nằm ở bước **đối chiếu kỹ năng với những JD dài, viết không chuẩn** (tin từ group FB, web công ty nhỏ), khi JD gọi cùng một kỹ năng bằng từ khác.
3. **Sửa baseline:** từ "~10 phút/JD cho mọi JD" thành "3–5 phút với JD ngắn/chuẩn, 8–10 phút với JD dài/không chuẩn" (cần đo lại bằng phỏng vấn thật).
4. Vì mới hỏi 2 người và số phút do họ tự ước lượng (chưa bấm giờ), giả định #1 mới có **bằng chứng yếu** → CP6 nghiêng về **Not Yet** cho đến khi hỏi thêm người và đo thật.

Ngoài ra, phần research cũng làm nhóm sửa một điểm: các công cụ có sẵn chủ yếu giúp **chấm điểm CV để sửa CV cho qua lọc hồ sơ tự động (ATS)**, và chỉ chạy tốt với tin đăng ngay trên nền tảng của họ. Vì vậy nhóm thu hẹp problem thành: *"Với JD lấy từ **group Facebook, website công ty** (không có sẵn phần so khớp), sinh viên mất thời gian đọc và tự đối chiếu để quyết định **nộp hay bỏ**"*, chứ không phải "chấm điểm CV".


### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Jobscan (so CV với JD, ra Match Rate) | https://www.jobscan.co/jobscan-tutorial | B2 + B4 + B5: dán CV và JD vào, ra % khớp, liệt kê hard skill / soft skill còn thiếu | Làm đúng phần "trích kỹ năng + so khớp", không cần tự xây | Mục tiêu là **sửa CV cho qua ATS**, không nói nên nộp hay bỏ. Bản free chỉ được 5 lượt scan/tháng; bản trả phí $49,95/tháng, hoặc $29,98/tháng nếu trả theo quý (đắt với SV). Nhóm chưa thử với JD tiếng Việt | Phần so khớp đã có người làm, **không nên tự xây từ đầu**; điểm % chỉ là tham khảo |
| Teal — Resume Job Description Match | https://tealhq.com/tool/resume-job-description-match | B2 + B4 + B5: ra điểm 0–100%, chỉ ra từ khóa và kỹ năng còn thiếu. Có thêm job tracker (liên quan card #2 của Nhật Anh) | Bản free có job tracking không giới hạn và so khớp cơ bản | Bản free chỉ hiện top 5 keyword; muốn đủ phải lên Teal+ $29/tháng (rẻ nhất khoảng $15/tháng nếu trả cả năm). Phải nhập CV vào Teal và lưu JD vào tracker trước, thêm bước | Cũng chỉ dừng ở **gợi ý sửa CV**; bước quyết định (B6) vẫn là người dùng |
| LinkedIn — Job Match (ra mắt 01/2025) | https://www.engadget.com/social-media/linkedin-wants-you-to-apply-for-fewer-jobs-140049139.html | B2 + B4 + B6: hiện tóm tắt ngay cạnh tin, cho biết mình đáp ứng yêu cầu nào, thiếu yêu cầu nào, để quyết định có nên nộp | Miễn phí cho mọi người dùng, không phải dán gì. Không chỉ so từ khóa mà cố hiểu kinh nghiệm của mình. Mục tiêu giống nhóm: **bớt nộp vào chỗ không hợp** | **Chỉ có với tin đăng trên LinkedIn**, phụ thuộc profile có cập nhật hay không. Premium mới xem được mức độ khớp chi tiết hơn | Với tin trên LinkedIn thì pain gần như đã được giải → problem nên tập trung vào **tin ở nguồn khác** |

**Kết luận research:**

```text
Bước trích kỹ năng + so khớp (B2, B4, B5) đã có nhiều công cụ làm, nhưng:
- Chỉ chạy tốt với tin đăng trên chính nền tảng đó (vd LinkedIn) hoặc phải dán vào tool trả phí.
- Mục tiêu của họ là sửa CV cho qua ATS, không giúp quyết định "nộp hay bỏ".
=> Không tự xây công cụ so khớp. Phần còn trống: JD từ group Facebook / web công ty,
   và bước quyết định B6 vẫn phải do sinh viên tự làm.
=> Hướng nghĩ cho CP5–CP6: thử No AI trước (checklist kỹ năng có ghi cả từ đồng nghĩa + Ctrl+F),
   so với Workflow (dán JD → trích yêu cầu kèm câu gốc trong JD → SV tự kiểm và quyết định).
```

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — khoảng 4 phút (tin ngắn, chuẩn) đến 10 phút (tin dài, không chuẩn) / 1 JD

[1. Mở tin: TopCV / LinkedIn / group FB / web công ty: 0,5']
        ↓
[2. Đọc tìm phần yêu cầu + điều kiện cứng (số năm KN, ngoại ngữ): 1–2']
        ↓
[3. Mở file note kỹ năng / CV của mình: 0,5']
        ↓
[4. Đối chiếu từng yêu cầu kỹ năng, tự đoán từ đồng nghĩa: 1–6']  ← BOTTLENECK
        ↓
[5. Ghi lại kỹ năng còn thiếu: 0,5–1']
        ↓
[6. Quyết định nộp / bỏ: 0,5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | SV | Link tin tuyển dụng | Trang JD đang mở | 0,5' / tin; 10–20 tin/tuần | Khoảng một nửa là tin từ group FB, web công ty |
| 2 | SV | Text JD | Biết tin có điều kiện cứng không hợp không | 1–2' | Tin đòi 1+ năm KN thường bị bỏ ở đây |
| 3 | SV | File note kỹ năng / CV | Danh sách kỹ năng của mình | 0,5' | Mỗi lần lại mở lại |
| 4 | SV | Yêu cầu trong JD + danh sách kỹ năng | Biết yêu cầu nào có / thiếu | 1–2' (tin ngắn) đến 3–6' (tin dài) | **Bottleneck**: JD gọi cùng kỹ năng bằng từ khác ("state management" ↔ Provider, "làm việc với API" ↔ RESTful) |
| 5 | SV | Kết quả bước 4 | Ghi chú kỹ năng thiếu | 0,5–1' | Hay bị bỏ qua khi vội |
| 6 | SV | Ghi chú + cảm giác | Nộp / bỏ | 0,5' | Có lúc nộp mà không chắc mình đủ điều kiện |

**Bottleneck chính:** Bước 4, đối chiếu kỹ năng với JD dài, viết không chuẩn: 3–6 phút/tin, vì phải tự đoán từ đồng nghĩa và dễ đoán sai.


### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — kỳ vọng ≤ 3 phút / 1 JD dài

[1. SV mở tin, copy text JD]                                   — CON NGƯỜI
        ↓
[2. Lọc điều kiện cứng: số năm KN, ngoại ngữ, địa điểm]         — RULE (từ khóa)
        ├── Không đạt → hiện "Gợi ý bỏ" + câu trích từ JD → SV liếc 10 giây, đồng ý hay không
        ↓ Đạt
[3. Trích danh sách yêu cầu kỹ năng, mỗi yêu cầu kèm câu gốc]    — AI
        ↓
[4. Đối chiếu với file kỹ năng của SV → Có / Thiếu / Không chắc] — AI
        ↓
[5. SV kiểm tra bảng, xem kỹ mọi dòng "Không chắc" và "Thiếu"]  — CON NGƯỜI (HITL)
        ↓
[6. SV quyết định nộp / bỏ, tự nộp]                             — CON NGƯỜI

BOUNDARY:
- AI không quyết định nộp/bỏ, không tự nộp, không sửa CV.
- Mỗi yêu cầu phải có câu trích nguyên văn từ JD; không có câu trích = coi như AI bịa.
- Khi không chắc, AI phải ghi "Không chắc", không được ghi "Thiếu".
- SV chỉ dán danh sách kỹ năng, không dán CV có số điện thoại, địa chỉ.

PHƯƠNG ÁN QUAY VỀ:
- Câu trích không tìm thấy trong JD, hoặc SV phải sửa > 2 dòng
  → bỏ kết quả AI, quay về checklist kỹ năng + Ctrl+F (cách hiện tại).
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 6 | Số bước giữ nguyên nhưng 3 bước do máy làm |
| Tổng thời gian | 4–10' / tin | ≤ 3' / tin dài | Tin bị loại ở bước 2 chỉ mất khoảng 1' |
| Số bước thủ công | 6 | 3 | Còn bước 1, 5, 6 |
| Bottleneck chính | Bước 4: tự đối chiếu (3–6') | Bước 5: SV kiểm bảng (1–2') | Kiểm có câu trích nên nhanh hơn tự đọc lại |
| Rủi ro mới phát sinh | — | AI hiểu sai / bỏ sót yêu cầu; SV tin mù kết quả; lộ thông tin nếu dán cả CV | Xử lý bằng câu trích bắt buộc, nhãn "Không chắc", chỉ dán danh sách kỹ năng |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên IT năm cuối đang tìm thực tập (Backend, Mobile) ở Hà Nội, đọc khoảng 10–20 tin/tuần, trong đó khoảng một nửa là tin từ group Facebook, web công ty |
| **Quy trình** | Mở tin → đọc tìm phần yêu cầu → mở note kỹ năng → đối chiếu từng yêu cầu → ghi kỹ năng thiếu → quyết định nộp/bỏ |
| **Bottleneck** | Bước 4: đối chiếu kỹ năng với JD, mất 3–6 phút/tin với JD dài vì JD gọi kỹ năng bằng từ khác với cách SV ghi |
| **Impact** | Khoảng 10 tin dài/tuần × 8–10' ≈ 1,5 giờ/tuần; có lúc nộp mà không chắc mình đủ điều kiện, hoặc bỏ nhầm tin hợp |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian quyết định 1 tin dài: 8–10' → ≤ 3'. (2) Tỷ lệ dòng đối chiếu đúng ≥ 90%. Cách đo: SV bấm giờ 10 tin dài trước và sau khi dùng; ghi số dòng phải sửa |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không quyết định nộp/bỏ, không tự nộp, không sửa CV. Mỗi yêu cầu phải kèm câu trích từ JD. SV kiểm tra mọi dòng trước khi quyết định |

Phản biện nhận được từ AI (nhờ AI đóng vai PM hoài nghi, chỉ chỉ ra lỗ hổng, không viết lại) và nhóm có đồng ý không:

- *"Baseline 8–10' chỉ lấy từ 1 người tự ước lượng, chưa bấm giờ thật."* → **Đồng ý.** Giữ con số nhưng ghi rõ là ước tính; phải đo thật trước khi pilot (xem mục 8).
- *"Tỷ lệ đúng ≥ 90% do chính SV tự chấm thì dễ chủ quan."* → **Đồng ý.** v1 thêm cách chấm: một bạn khác trong nhóm làm bảng đối chiếu tay trên cùng 10 JD để so.
- *"Chỉ tốn khoảng 1,5 giờ/tuần, có đáng làm không?"* → **Đồng ý một phần.** Mùa tìm thực tập kéo dài 2–3 tháng, và rủi ro bỏ nhầm tin hợp còn đáng ngại hơn số phút. Nhưng nhóm ghi điểm này vào rủi ro Value (mục 8.1).
- *"Tin đòi 1+ năm KN thì đâu cần AI, sao lại cho hết vào?"* → **Đồng ý.** v1 tách bước lọc điều kiện cứng ra làm Rule, AI chỉ chạy với tin đã qua lọc.

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
