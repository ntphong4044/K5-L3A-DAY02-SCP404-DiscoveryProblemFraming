# Báo cáo cá nhân — 2A202603715_DuongThaiBinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Dương Thái Bình
- MSSV: 2A202603715
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: SCP404
- Link repo nhóm: https://github.com/ntphong4044/K5-L3A-DAY02-SCP404-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)
Nhân vật: Bình, Junior Game Developer trong Trong một startup nhỏ khoảng 20 người, sử dụng ClickUp, Google Docs, Unity Hub, Godot Engine, dùng Claude Pro. Mỗi ngày, tôi cần phải phân tích dữ liệu trò chơi đang phát hành trên store, sau đó viết báo cáo thống kê số liệu cho CEO và Senior Game Developer.
Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Khi đến kỳ báo cáo tuần, tôi muốn có đầy đủ số liệu lượt tải, doanh thu và lượng người chơi của từng game, để không bỏ sót dữ liệu quan trọng. |Junior Game Developer |Mỗi ngày cần dành ra 60p để thống kê |
| 2 |Lặp lại |Khi viết báo cáo tuần, tôi muốn đối chiếu chính xác các chỉ số với tuần trước, để đánh giá mức tăng trưởng của game. |Junior Game Developer |Mỗi ngày 1 lần, trong vòng 15p |
| 3 |Tốn thời gian|Khi CEO và Senior Developer yêu cầu những góc nhìn khác nhau về dữ liệu, tôi muốn hiểu rõ nhu cầu của từng người, để tránh chỉnh sửa báo cáo nhiều lần |Junior Game Developer, CEO, Senior Developer |Junior Developer hỏi lại CEO/Senior 1-2 lần |
| 4 |Cần đọc, tổng hợp nhiều thông tin|Khi game nhận nhiều đánh giá trên store, tôi muốn nắm được những phản hồi tích cực và tiêu cực phổ biến, để hiểu các vấn đề người chơi đang gặp phải. |Junior Game Developer, Senior Developer |5-8 review mỗi tuần, 30 phút cho 1 lần phản hồi |
| 5 |Pain từ người khác |Khi CEO nhận báo cáo có nhiều số liệu, CEO muốn nhanh chóng nhận biết các thay đổi quan trọng, để đưa ra quyết định ưu tiên cho từng game. |CEO |15 phút CEO đọc báo cáo, 1-2 lần giải thích thêm cho CEO|
| 6 |Cần đọc, tổng hợp nhiều thông tin |Khi công ty vận hành nhiều game cùng lúc, tôi muốn nắm được game nào đang tăng trưởng hoặc suy giảm, để CEO đánh giá tình hình chung của các sản phẩm. |Junior Game Developer, CEO |2-3 game cần tổng hợp, mỗi tuần dành ra 90 phút |
| 7 | | | | |
| 8 | | | | |

- Sau khi tự scan 5 ý, tôi hỏi AI và được gợi ý thêm ý #6. Tôi thấy ý #6 hợp lý vì nó liên quan đến việc tổng hợp dữ liệu nhiều game, giúp CEO có cái nhìn tổng quan hơn. 

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Thu thập số liệu game định kỳ (#1) |Công việc lặp lại hằng tuần, quy trình rõ ràng, tốn thời gian và dễ đo lường bằng số phút thực hiện. |Dữ liệu từ các store có đồng nhất về định nghĩa chỉ số và độ chính xác không? Có bước nào bắt buộc phải kiểm tra thủ công không? |
| 2 |Chỉnh sửa báo cáo nhiều lần (#3) |Liên quan trực tiếp đến việc báo cáo cho CEO và Senior Developer, có khả năng gây mất thời gian và làm chậm tiến độ. Nguyên nhân chỉnh sửa đến từ yêu cầu chưa rõ ràng, dữ liệu chưa đầy đủ hay sự thay đổi nhu cầu của người quản lý? |
| 3 |CEO khó nắm bắt thông tin quan trọng (#5) |Ảnh hưởng đến việc đánh giá hiệu suất game và ra quyết định, có tác động đến người quản lý. |CEO thực sự gặp khó khăn khi hiểu báo cáo hay chỉ cần thêm góc nhìn phân tích? Những chỉ số nào thực sự quan trọng đối với quyết định của CEO? |

### Problem Card #1: Thu thập số liệu game định kỳ 

| Trường | Nội dung |
|---|---|
| Job Story |Khi đến kỳ báo cáo tuần, tôi muốn có đầy đủ số liệu lượt tải, doanh thu và lượng người chơi của từng game, để không bỏ sót dữ liệu quan trọng.|
| Actor |Junior GD gửi báo cáo hàng ngày cho CEO và Senior GD |
| Thời điểm / bối cảnh |Buổi sáng, trước 11h |
| Quy trình hiện tại (3–7 bước) |1. Truy cập các trang thống kê của store. 2. Thu thập số liệu lượt tải, doanh thu, lượng người chơi. 3. Tổng hợp số liệu từng game. 4. Đối chiếu với kỳ trước. 5. Kiểm tra dữ liệu thiếu hoặc sai lệch. 6. Đưa số liệu vào Google Docs. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3: khoảng 30p, phải thu thập và đối chiếu nhiều chỉ số từ các nguồn khác nhau; dễ nhầm lẫn hoặc bỏ sót khi thực hiện thủ công. |
| Impact (nếu không giải thì sao) |Tiêu tốn thời gian hằng tuần, làm chậm quá trình phân tích và có nguy cơ ảnh hưởng đến độ chính xác của báo cáo. |
| Success metric (baseline → target) |Giảm tối thiểu 50% thời gian thu thập dữ liệu; không tăng tỷ lệ sai sót hoặc thiếu dữ liệu. |
| Phương án không dùng AI |Chuẩn hóa biểu mẫu báo cáo, sử dụng Google Sheets với công thức tính toán và cơ chế xuất dữ liệu có sẵn từ store |
| Giả thuyết về AI (nếu có) |AI hỗ trợ đối chiếu dữ liệu, phát hiện số liệu thiếu hoặc bất thường và chuẩn bị bản tổng hợp để kiểm tra. |
| Cảm nhận nhanh |Workflow — Quy trình lặp lại, rõ ràng, dễ đo hiệu quả.|

Quy trình nháp hiện tại:
HIỆN TẠI — 90 phút

[1 Truy cập trang thống kê: 5'] → [2 Thu thập dữ liệu: 30'] → [3 Tổng hợp số liệu: 30'] ← BOTTLENECK
→ [4 Đối chiếu: 10'] → [5 Kiểm tra sai sót: 10'] → [6 Đưa só liệu vào Docs: 5'] 


### Problem Card #2: Chỉnh sửa báo cáo nhiều lần

| Trường | Nội dung |
|---|---|
| Job Story | Khi CEO và Senior Developer yêu cầu những góc nhìn khác nhau về dữ liệu, tôi muốn hiểu rõ nhu cầu của từng người, để tránh phải chỉnh sửa báo cáo nhiều lần. |
| Actor |Junior Game Developer phụ trách báo cáo; CEO và Senior Game Developer là người nhận báo cáo. |
| Thời điểm / bối cảnh |Sau khi hoàn thành bản báo cáo thống kê tuần và gửi cho CEO hoặc Senior Developer xem xét. |
| Quy trình hiện tại (3–7 bước) |1. Tổng hợp dữ liệu game. 2. Viết báo cáo trên Google Docs. 3. Gửi CEO và Senior Developer. 4. Nhận phản hồi và yêu cầu bổ sung. 5. Phân tích lại dữ liệu nếu cần. 6. Chỉnh sửa nội dung. 7. Gửi lại báo cáo. |
| Bottleneck (bước nào, mất bao nhiêu phút) |CEO quan tâm đến hiệu suất kinh doanh, trong khi Senior Developer cần thông tin kỹ thuật và gameplay. Một bản báo cáo có thể chưa đáp ứng đầy đủ nhu cầu của cả hai. |
| Impact (nếu không giải thì sao) |Phát sinh công việc chỉnh sửa, ảnh hưởng đến thời hạn hoàn thành báo cáo và thời gian dành cho các nhiệm vụ phát triển game. |
| Success metric (baseline → target) |Giảm ít nhất 50% số lần chỉnh sửa; tăng tỷ lệ báo cáo được chấp nhận ngay lần đầu; không làm giảm chất lượng thông tin. |
| Phương án không dùng AI |Thống nhất yêu cầu báo cáo với CEO và Senior Developer; xây dựng checklist thông tin và hai phần báo cáo riêng theo nhu cầu. |
| Giả thuyết về AI (nếu có) |AI hỗ trợ xây dựng các bản tóm tắt từ cùng một bộ dữ liệu theo mục tiêu của từng người nhận, sau đó Developer kiểm tra và hoàn thiện. |
| Cảm nhận nhanh |Communication + Workflow — Vấn đề nằm ở việc truyền đạt thông tin và điều chỉnh nội dung báo cáo. |

Quy trình nháp hiện tại:

HIỆN TẠI — 105 phút

[1 Tổng hợp dữ liệu game: 20'] → [2 Viết báo cáo: 10'] → [3 Gửi CEO và Senior GD: 5'] → [4 Nhận phản hồi và yêu cầu bổ sung: 5']← BOTTLENECK
→ [Phân tích lại dữ liệu nếu cần: 30'] → [6 Chỉnh sửa nội dung: 30'] → [7 Gửi: 5']

### Problem Card #3: CEO khó nắm bắt thông tin quan trọng

| Trường | Nội dung |
|---|---|
| Job Story |Khi nhận báo cáo thống kê có nhiều số liệu, CEO muốn nhanh chóng nhận biết những thay đổi quan trọng và vấn đề cần quan tâm, để đưa ra quyết định ưu tiên cho các trò chơi.|
| Actor |CEO là người trực tiếp gặp vấn đề; Junior Game Developer là người chuẩn bị báo cáo. |
| Thời điểm / bối cảnh |Khi CEO xem báo cáo hiệu suất game hằng tuần để đánh giá tình hình kinh doanh và định hướng phát triển sản phẩm. |
| Quy trình hiện tại (3–7 bước) |1. Junior Developer tổng hợp dữ liệu game. 2. Viết báo cáo thống kê trên Google Docs. 3. Gửi báo cáo cho CEO. 4. CEO đọc các chỉ số. 5. CEO yêu cầu giải thích hoặc bổ sung thông tin nếu cần. 6. Junior Developer phân tích thêm và phản hồi. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Báo cáo có thể chứa nhiều con số nhưng chưa thể hiện rõ ý nghĩa của các biến động, nguyên nhân khả dĩ và những điểm cần ưu tiên chú ý. |
| Impact (nếu không giải thì sao) |CEO có thể mất thêm công sức diễn giải dữ liệu, phải yêu cầu làm rõ và có nguy cơ bỏ qua những biến động quan trọng của game. |
| Success metric (baseline → target) |Giảm ít nhất 50% số câu hỏi yêu cầu làm rõ; CEO xác định được các thay đổi quan trọng sau khi đọc báo cáo; duy trì độ chính xác của nhận định. |
| Phương án không dùng AI |Bổ sung phần Executive Summary, trình bày các KPI quan trọng và nêu rõ những thay đổi đáng chú ý trong báo cáo. |
| Giả thuyết về AI (nếu có) |AI hỗ trợ phân tích biến động KPI và soạn bản tóm tắt những điểm nổi bật từ dữ liệu đã được xác minh, để Developer kiểm tra trước khi gửi CEO. |
| Cảm nhận nhanh |Insight + Communication — Tập trung vào khả năng chuyển đổi dữ liệu thành thông tin hữu ích cho việc ra quyết định.|

Quy trình nháp hiện tại:

HIỆN TẠI — 90 phút

[1 Tổng hợp dữ liệu: 15'] → [2 Viết báo cáo: 30'] → [3 Gửi báo cáo cho CEO: 5']
→ [4 CEO đọc chỉ số: 30'] → [5 CEO yêu cầu giải thích/bổ sung: 10'] ← BOTTLENECK 
→ [6 Junior Developer phân tích thêm và phản hồi: 30']

### Card muốn pitch nhất

- Card số: #1 – Thu thập số liệu game định kỳ.
- Vì sao: Đây là vấn đề xuất hiện thường xuyên trong công việc, có quy trình và bottleneck cụ thể (bước thu thập dữ liệu mất khoảng 30 phút). Vấn đề có thể đo lường được, dễ kiểm chứng và có tiềm năng cải thiện hiệu suất làm việc.
- Câu hỏi muốn nhóm phản biện: Liệu việc thu thập và đối chiếu dữ liệu game có thực sự cần AI hỗ trợ, hay chỉ cần chuẩn hóa quy trình và sử dụng các công cụ tự động hóa thông thường là đủ?

### AI đã phản biện card #1

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Chưa rõ chỉ một Junior GD thực hiện hay nhiều người cùng phụ trách. Có sự không nhất quán giữa báo cáo hằng ngày và hằng tuần |Không |Đã tính giờ chính xác: 90p |
|Chưa có định nghĩa rõ thế nào là dữ liệu sai hoặc thiếu|Đồng ý|Thêm định nghĩa để kiểm chứng|

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Sau khi nghe top 3 problems của các bạn khác, tôi rút ra được 1 số bài học chính:
    - Cần xác định đúng vấn đề trước khi nghĩ đến giải pháp
    - Một vấn đề cần có bằng chứng cụ thể như thời gian xử lý, tần suất xảy ra hoặc mức độ ảnh hưởng đến công việc
    - Không chỉ quan tâm đến khó khăn của bản thân mà còn cần xem xét nhu cầu của đồng nghiệp và người quản lý
- Điều quan trọng nhất tôi nhận ra: Một vấn đề "đáng được giải quyết" không nhất thiết phải là 1 vấn đề lớn hoặc phức tạp
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
- Trong quá trình làm việc, nhóm có xu hướng nghĩ đến sử dụng AI để tự động xử lý công việc, trong khi chưa nắm rõ được nguồn gốc của vấn đề. Để giải quyết, từng thành viên trong nhóm quay lại CP2, phân tích kỹ lưỡng các problem card, đặc biệt các phần Job Story, Actor, Bottleneck để tìm ra nguyên nhân gốc rễ và mức độ ảnh hưởng của từng vấn đề
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
- Ban đầu, tôi cho rằng việc thu thập số liệu game định kỳ là vấn đề quan trọng nhất, bởi việc này rất mất thời gian và là gốc rễ cho mọi vấn đề xoay quanh game đó. Tuy nhiên, tôi nhận được phản biện rằng quy trình thu thập dữ liệu đều được quy định rõ ràng, chỉ cần làm theo đúng quy trình là được; trong khi khó khăn thực sự nằm ở việc phân tích số liệu và trình bày thông tin phù hợp cho CEO và Senior GD, bởi quan điểm của cả 3 actor có thể khác nhau, gây xung đột trong quá trình báo cáo. 
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
- Tôi sẽ dành nhiều thời gian hơn để kiểm chứng vấn đề thực tế trước khi lựa chọn Top 3 Problems. Tôi sẽ tìm hiểu kỹ nguyên nhân gốc rễ, mức độ ảnh hưởng và nhu cầu của những người liên quan, thay vì chỉ ưu tiên các công việc lặp lại hoặc tốn nhiều thời gian.
- Tôi sẽ phản biện nhóm mạnh hơn ở việc xác định giá trị thực sự của vấn đề, chủ động đặt câu hỏi, không ngại phản biện và tránh đồng ý quá nhanh với ý kiến số đông. Mục tiêu của phản biện là giúp nhóm hiểu đúng vấn đề và đưa ra lựa chọn có cơ sở hơn.
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
