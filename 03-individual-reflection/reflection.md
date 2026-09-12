# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Minh Kiệt
- Mã học viên:2A202602373
- Nhóm: Berserkers - Zone C
- Vai trò: Lead / Facilitator
- Candidate problem nhóm chọn: Thẩm định và tóm tắt review thật/ảo trên Shopee

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 pain point từ công việc Project Coordinator và Phó phòng KD, tập trung vào tracking nhiều workstream, documentation, licensing và reporting. | Đưa thêm góc nhìn doanh nghiệp thực tế vào danh sách candidate. |
| Pitch Problem Card | Tôi pitch các problem từ công việc thực tế của mình, gồm theo dõi tiến độ đa nguồn, documentation/knowledge transfer và thay đổi thủ tục pháp lý. | Nhóm hiểu thêm các pain trong môi trường doanh nghiệp, đồng thời nhận ra một số bài cần thêm evidence mới đo được. |
| Challenge bài của bạn khác | Tôi lắng nghe và challenge các problem của thành viên theo actor, bottleneck, evidence, metric và human boundary. | Việc challenge giúp nhóm phân biệt pain thật với ý tưởng solution-first, đặc biệt khi cân nhắc review Shopee và các bài tự động hóa. |
| Gom trùng / cluster | Tôi tham gia gom các problem có pattern giống nhau, như dữ liệu phân tán, tìm kiếm thông tin cũ và việc phải đối chiếu nhiều nguồn. | Nhóm nhìn ra các cluster rõ hơn thay vì xem từng candidate là một bài hoàn toàn riêng. |
| Chọn candidate problem | Với vai trò Lead/Facilitator, tôi điều phối phần lắng nghe, challenge và so sánh candidate theo pain, evidence và khả năng làm trong lab. | Nhóm hội tụ về bài review Shopee vì validation và metric rõ hơn, dù bài licensing gần với công việc của tôi hơn. |
| Validation / research | Tôi đóng góp ý kiến về cách validation, source link và cách kiểm tra kết quả với dữ liệu gốc. | Nhóm bổ sung interview, survey, research tool và ưu tiên bóc tách lỗi thực tế hơn so sánh voucher. |
| Workflow nhóm | Tôi góp ý workflow phải tách Rule lọc rác, LLM gom cụm lỗi và bước người mua kiểm tra review gốc. | Workflow có bottleneck, human boundary và fallback khi DOM hoặc LLM lỗi. |
| Problem Statement | Tôi góp ý viết pain theo hướng quá tải thông tin và thiếu niềm tin, không chỉ là nhu cầu có extension. | Problem Statement có actor, workflow, impact, metric và boundary rõ hơn. |
| Rule / Workflow / Agent | Tôi challenge việc làm Agent và ủng hộ Workflow pipeline có Rule tiền xử lý, LLM phân tích và human review. | Nhóm chọn Workflow vì các bước cố định và dễ kiểm soát hơn Agent. |
| Decision | Với vai trò Lead/Facilitator, tôi giúp giữ hướng thảo luận, tổng hợp ý kiến theo evidence, khả năng làm trong lab và rủi ro triển khai. | Nhóm chốt Go cho Browser Extension, có fallback review thô và rollback khi AI không đáng tin. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đóng góp rõ nhất của tôi là làm Lead/Facilitator: điều phối phần pitch, lắng nghe và challenge các problem, sau đó giúp nhóm gom trùng và hội tụ về một bài phù hợp nhất. Trong artifact cuối, tôi đóng góp nhiều nhất ở phần workflow và validation, đặc biệt là yêu cầu phải có nguồn gốc để kiểm tra và có fallback khi AI sai.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Phản biện các pain point cá nhân và phân biệt real pain với process gap. | Gợi ý actor, bottleneck và cách đo cụ thể hơn. | Dễ gọi một việc thủ công là “AI problem”, trong khi có thể chỉ cần tracker hoặc template. | Tôi giữ các pain có impact, hạ các ý thiếu evidence và bổ sung cách xác minh bằng thời gian, số nguồn và số lần rework. |
| Problem Card | Gợi ý cấu trúc workflow, metric, non-AI alternative và AI hypothesis. | Giúp tôi thấy card cần có human boundary và fallback. | Một số metric ban đầu chưa có baseline thật. | Tôi ghi các số chưa chắc là ước tính và giữ người dùng/reviewer ở bước quyết định. |
| Workflow | So sánh current state và future state cho các candidate. | Giúp chỉ ra bước nào dùng Rule, bước nào cần AI và bước nào người kiểm tra. | AI có xu hướng nhảy nhanh sang Agent và tự động hóa toàn bộ luồng. | Tôi ủng hộ Workflow cố định cho bài nhóm và chỉ chấp nhận Agent trong vai trò giới hạn khi có nguồn whitelist. |
| Research | Gợi ý tool/pattern tham khảo cho review analysis và browser extension. | Gợi ý hướng review reliability, aspect extraction và product summary. | Link hoặc claim do AI đưa ra không thể dùng ngay nếu chưa kiểm tra. | Nhóm giữ nguồn kiểm được và không dùng số liệu AI tự tạo. |
| Problem Statement | Phản biện actor, bottleneck, impact, metric và boundary của bài Shopee. | Giúp nhận ra bài cần thu hẹp vào sản phẩm giá trị cao, review 1–3 sao và lỗi thực tế. | AI không tự biết hành vi người dùng nếu thiếu interview/survey. | Tôi dựa vào validation của nhóm và nhấn mạnh phải đối chiếu summary với review gốc. |
| Rule / Workflow / Agent | So sánh ba mức giải pháp trên cùng một pipeline. | Làm rõ Rule lọc rác thô, LLM xử lý ngữ nghĩa và Agent là quá mức cần thiết. | AI dễ bỏ qua latency, anti-bot, DOM change và hallucination khi mô tả Agent. | Tôi ủng hộ Workflow, thêm fallback raw review và human boundary trước quyết định mua. |
| Decision | Dùng AI như người phản biện trước khi nhóm chốt. | Giúp đặt câu hỏi về rủi ro và điều kiện rollback. | AI không thể quyết định thay nhóm vì còn phụ thuộc evidence và khả năng làm trong lab. | Nhóm tự chấm score, thảo luận candidate và chọn bài có pain, evidence và metric rõ hơn. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

Trước buổi làm nhóm, tôi nghĩ các bài toán theo dõi tiến độ và thay đổi pháp lý trong doanh nghiệp sẽ phù hợp nhất vì đó là việc tôi đang gặp thật. Khi nghe các bạn trình bày, tôi nhận ra nhiều problem khác cũng có cùng pattern: dữ liệu nằm rải rác, người dùng phải tự lọc và không chắc thông tin nào đáng tin. Tôi đã pitch problem của mình, lắng nghe và challenge các bài của các bạn theo actor, bottleneck, evidence và metric. Sau đó tôi tham gia gom những bài có pattern giống nhau và cùng nhóm quyết định bài nào có pain rõ, có thể validation và làm được trong lab. Bài review Shopee ban đầu không gần công việc của tôi bằng bài licensing, nhưng nhóm có evidence cụ thể hơn từ interview, survey và thời gian người mua phải đọc review. Tôi đổi ý vì bài này có workflow rõ và có thể đo trước/sau. Tôi cũng đồng ý challenge việc làm Agent, vì browser extension thực tế chỉ cần chạy một pipeline cố định rồi để người mua kiểm tra kết quả. Trong phần workflow và validation, tôi góp ý phải tách Rule lọc rác, AI gom cụm lỗi, link về review gốc và fallback khi DOM hoặc LLM lỗi. Điều khó nhất là viết metric đủ cụ thể nhưng không nói quá khả năng của AI, nhất là khi chưa có ground truth hoàn chỉnh. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về cách định nghĩa “review giả” và trường hợp AI bỏ sót một lỗi nghiêm trọng. Tôi học được rằng đóng góp của mình không nhất thiết phải là candidate được chọn; quan trọng hơn là giúp nhóm đặt câu hỏi đúng trước khi chốt solution.

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

