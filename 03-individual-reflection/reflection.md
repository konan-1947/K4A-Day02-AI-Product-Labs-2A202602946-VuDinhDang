# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Vũ Đình Đăng
- Mã học viên: 2A202602946
- Nhóm: 1 — Research
- Candidate problem nhóm chọn: Học viên toàn thời gian mỗi tối chỉ có khoảng 2 tiếng nhưng phải đọc trước 50–100 trang slide của lab và lecture ngày hôm sau, nên thường không kịp và vào buổi học bị động.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 8 problem trong workflow dùng AI CLI, tập trung vào việc developer khó nhìn thấy, review và kiểm soát thay đổi do AI tạo ra. | Tôi có đủ danh sách để pitch; Card #1 về thiếu kiểm soát với thay đổi AI được chọn là card muốn pitch nhất. |
| Pitch Problem Card | Tôi trình bày Card #1: developer phải tự tìm file, xem diff và quyết định giữ/bỏ sau mỗi phiên AI. | Nhóm thấy đây là pain có actor, workflow và bottleneck rõ, đồng thời có thể đo thời gian review. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về actor, baseline thời gian, bước nghẽn và cách đo “nắm được ý chính” của candidate đọc slide. | Nhóm thu hẹp bài toán từ “hỗ trợ học tập” thành việc chuẩn bị slide trước lớp trong quỹ thời gian khoảng 2 tiếng. |
| Gom trùng / cluster | Tôi góp ý gom các ý về đọc slide quá tải và tổng hợp kiến thức vào cụm “quá tải tiếp nhận kiến thức”. | Nhóm phân biệt được bài đọc slide với các bài rộng hơn như tìm thông tin rải rác hoặc quản lý deadline. |
| Chọn candidate problem | Tôi so sánh candidate theo actor, workflow, evidence, impact, khả năng làm trong lab và độ phù hợp với Rule/Workflow/Agent. | Nhóm chọn A1 — đọc trước slide quá tải vì pain lặp lại, dễ đo và ít phụ thuộc BTC. |
| Validation / research | Với vai trò Research, tôi rà soát các hướng đã có như NotebookLM, ChatPDF/AskYourPDF và Mapify/Gamma; đồng thời ghi rõ cần bổ sung survey/interview và kiểm link trước khi nộp. | Nhóm nhận ra không cần build tool mới; trọng tâm là thiết kế workflow tóm tắt, tạo mục lục/mindmap và để người học tự kiểm. |
| Workflow nhóm | Tôi góp ý xác định điểm AI can thiệp sau khi tải slide và trước khi người học đọc–kiểm; luôn cần fallback về slide gốc. | Workflow sau có ranh giới người/AI rõ, cùng baseline hơn 120 phút và mục tiêu khoảng 45 phút. |
| Problem Statement | Tôi góp ý làm rõ rằng pain nằm ở khối lượng đọc vượt quỹ thời gian, không phải chỉ ở việc slide tải chậm; metric phải có cách đo. | PS v1 có actor, bottleneck, impact, metric trước/sau, boundary và số lỗi tóm tắt cần theo dõi. |
| Rule / Workflow / Agent | Tôi tham gia so sánh: Rule chỉ hỗ trợ tải/đọc theo mục lục, Workflow xử lý tóm tắt theo chuỗi cố định, Agent là quá mức cần thiết. | Nhóm chọn Workflow có AI hỗ trợ, kèm Rule phụ và human-in-the-loop. |
| Decision | Tôi ủng hộ Go pilot nhỏ trên slide của một ngày, nhưng nhấn mạnh phải đo thời gian, độ bao phủ ý chính và lỗi tóm tắt. | Quyết định Go có điều kiện; nếu AI sai thường xuyên hoặc thời gian kiểm lại lâu hơn tự đọc thì rollback về cách cũ. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi đóng góp rõ nhất ở phần research và boundary của workflow: công cụ có sẵn chỉ hỗ trợ cô đọng nội dung, còn học viên vẫn phải kiểm tra slide gốc và tự chịu trách nhiệm với phần hiểu bài.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi tự scan trước; sau đó dùng AI như một người phản biện để gợi ý thêm góc nhìn về việc lặp lại, tốn thời gian và thiếu kiểm soát. | AI giúp mở rộng danh sách problem và nhắc tôi ghi actor, workflow, dấu hiệu thật. | AI dễ đưa ra ý tưởng sản phẩm quá rộng hoặc mặc định rằng cứ có pain là nên làm Agent. | Tôi giữ lại các pain gắn với workflow dùng AI CLI và ghi số liệu chưa có là giả thuyết cần kiểm chứng. |
| Problem Card | Dùng AI để kiểm tra Card #1 có đủ actor, bottleneck, impact, metric và non-AI alternative chưa. | AI chỉ ra các chỗ còn mơ hồ như “kiểm soát tốt hơn” và “nhanh hơn”. | AI không thể tự biết tần suất developer bỏ sót thay đổi hay thời gian review thực tế. | Tôi đổi thành các metric cần phỏng vấn/đo pilot, không trình bày giả thuyết như kết quả đã có. |
| Workflow | Dùng AI để gợi ý cách diễn đạt flow trước/sau bằng Mermaid và kiểm tra điểm fallback. | AI giúp nhìn rõ các bước tìm file, chuyển context, review và accept/reject. | Flow do AI gợi ý có thể làm như thể người dùng luôn chấp nhận output hoặc AI hiểu đúng mọi thay đổi. | Tôi giữ human review, lựa chọn partial accept/reject và fallback về Git diff trong workflow của mình. |
| Research | Dùng AI để gợi ý các nhóm công cụ tóm tắt tài liệu và mindmap cho bài nhóm, sau đó tự kiểm tra tên công cụ và phạm vi sử dụng. | AI giúp lập bảng so sánh nhanh NotebookLM, ChatPDF/AskYourPDF và Mapify/Gamma. | Mô tả tính năng và giới hạn có thể lỗi thời hoặc chung chung nếu không mở nguồn chính thức. | Tôi ghi rõ link cần kiểm lại, không dùng số liệu chưa xác minh và bổ sung cột rủi ro/khoảng trống. |
| Problem Statement | Dùng AI để phản biện PS v0 và hỏi field nào còn mơ hồ. | AI giúp phát hiện “nắm ý chính” chưa phải metric đủ đo được. | AI thường viết PS trơn tru nhưng không tự phân biệt baseline thật với target giả định. | Tôi bổ sung cách đo bằng bấm giờ, đối chiếu slide gốc và đếm lỗi/ý bị thiếu. |
| Rule / Workflow / Agent | Dùng AI để so sánh ba mức độ tự động hóa trên cùng một workflow. | AI giúp nêu nhanh ưu/nhược điểm và rủi ro của Agent. | AI có xu hướng đề xuất Agent vì nghe đầy đủ hơn, dù bài toán chỉ đi theo chuỗi cố định. | Tôi ủng hộ Workflow + Rule phụ vì dễ kiểm soát, có human boundary và không cần AI tự lập kế hoạch. |
| Decision | Dùng AI để challenge điều kiện Go và các trường hợp rollback. | AI giúp đặt câu hỏi về dữ liệu đầu vào, lỗi tóm tắt và owner kiểm tra. | AI không thể thay nhóm quyết định mức lỗi nào chấp nhận được trong bối cảnh học tập. | Tôi đề xuất pilot nhỏ trên một ngày học, đo ba số và dừng nếu kiểm lại lâu hơn tự đọc hoặc lỗi quan trọng lặp lại. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn, tôi nhận ra một problem tốt không nhất thiết phải bắt đầu từ ý tưởng sản phẩm; nó phải chỉ ra được actor, workflow và bước nghẽn cụ thể. Problem của tôi về việc developer thiếu kiểm soát thay đổi do AI khá rõ, nhưng nhóm chọn bài đọc slide quá tải vì pain này lặp lại hằng ngày và dễ đo hơn trong phạm vi lab. Tôi đã thay đổi cách nhìn về “AI phù hợp” sau khi so sánh ba phương án: Agent nghe mạnh hơn nhưng không cần thiết nếu các bước chỉ đi theo một chuỗi cố định. Đóng góp rõ nhất của tôi là phần research và việc nhấn mạnh boundary: AI chỉ tóm tắt, tạo mục lục hoặc mindmap; học viên vẫn phải kiểm tra phần quan trọng bằng slide gốc. Tôi cũng nhận ra “nắm được ý chính” là một mục tiêu còn mơ hồ nếu không có cách đối chiếu và đếm lỗi cụ thể. AI hữu ích khi giúp phản biện cấu trúc và chỉ ra chỗ thiếu metric, nhưng thường viết rất trơn tru dù bằng chứng chưa đủ. Vì vậy tôi giữ các con số trong bài ở dạng baseline/target hoặc giả thuyết cần kiểm chứng, không coi chúng là kết quả thực tế. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về quote phỏng vấn, số người trong survey và link research trước khi chốt quyết định Go. Tôi cũng sẽ hỏi rõ hơn tiêu chí thế nào là một “lỗi quan trọng” của bản tóm tắt để pilot có thể quyết định dừng hay tiếp tục. Bài học lớn nhất của tôi là workflow tốt phải cho thấy cả chỗ AI làm việc, chỗ con người kiểm tra và cách quay về phương án cũ khi AI sai.
```

---

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
