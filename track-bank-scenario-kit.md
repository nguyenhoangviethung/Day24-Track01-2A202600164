# Bộ track scenario kit Day 24

File này cung cấp bối cảnh sản phẩm đủ rõ để bạn chọn track và tự suy ra scenario, failure mode, test set, eval plan.

---

## Danh sách track

1. Chatbot tư vấn tuyển sinh đại học
2. Trợ lý đặt vé và chăm sóc khách hàng hàng không
3. Trợ lý sàng lọc triệu chứng cho phòng khám
4. Trợ lý ghi chú và tổng hợp chi tiêu
5. Pipeline viết nội dung marketing
6. Trình tạo báo cáo kinh doanh
7. Trợ lý sàng lọc CV và tuyển dụng
8. Pipeline xử lý ticket chăm sóc khách hàng
9. AI copilot hỗ trợ sales/CSKH trả lời khách hàng
10. AI chấm điểm cuộc gọi chăm sóc khách hàng

---

## Track 01 — Chatbot tư vấn tuyển sinh đại học

### Bối cảnh sản phẩm

Một trường đại học đặt chatbot AI trên website tuyển sinh để hỗ trợ học sinh và phụ huynh trong quá trình tìm hiểu ngành học, học phí, học bổng, deadline, hồ sơ xét tuyển và đăng ký tư vấn.

Chatbot không phải counselor chính thức. Nó là điểm hỗ trợ đầu tiên trước khi user đọc thêm thông tin hoặc liên hệ tư vấn viên.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Website tuyển sinh
Trang chương trình học
Trang học phí / học bổng
Form đăng ký tư vấn
Nút chat ở góc phải màn hình
```

### Flow người dùng mẫu

```text
Flow A:
User vào website tuyển sinh
→ Chọn một ngành quan tâm
→ Đọc thông tin ngành
→ Không chắc về học phí/học bổng/deadline
→ Mở chatbot để hỏi thêm
→ Dùng câu trả lời để quyết định có nộp hồ sơ hoặc đăng ký tư vấn không

Flow B:
Phụ huynh vào trang học phí
→ Chưa hiểu tổng chi phí cần chuẩn bị
→ Mở chatbot để hỏi về học phí, học bổng, thời hạn đóng phí
→ Lưu lại câu trả lời để trao đổi với gia đình

Flow C:
Học sinh bấm "Đăng ký tư vấn"
→ Form yêu cầu chọn ngành quan tâm
→ Chatbot xuất hiện để hỏi thêm nhu cầu
→ User quyết định có để lại số điện thoại/email cho counselor không
```

---

## Track 02 — Trợ lý đặt vé và chăm sóc khách hàng hàng không

### Bối cảnh sản phẩm

Một hãng hàng không dùng AI assistant để hỗ trợ khách trong quá trình đặt vé, quản lý chuyến bay, đổi vé, hỏi về hành lý, hoàn tiền, delay, và các yêu cầu hỗ trợ đặc biệt.

AI xuất hiện trong sản phẩm chính thức của hãng, nên user có thể xem câu trả lời như thông tin đáng tin cậy từ hãng.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Trang đặt vé
Trang thanh toán
Trang quản lý chuyến bay
Trang đổi vé / hoàn tiền
Trang hành lý
Help center của hãng
```

### Flow người dùng mẫu

```text
Flow A:
User chọn chuyến bay
→ Đến bước nhập thông tin hành khách
→ Không chắc hạng vé có bao gồm hành lý hay không
→ Mở trợ lý AI để hỏi
→ Dựa vào câu trả lời để quyết định mua thêm hành lý hoặc đổi hạng vé

Flow B:
User vào "Quản lý chuyến bay"
→ Muốn đổi ngày bay hoặc hoàn vé
→ Mở trợ lý AI trong trang đổi vé/hoàn tiền
→ Dựa vào câu trả lời để quyết định tiếp tục yêu cầu hoàn/đổi vé

Flow C:
Chuyến bay bị delay hoặc thay đổi lịch
→ User mở app hãng để xem quyền lợi
→ Trợ lý AI xuất hiện để hướng dẫn bước tiếp theo
→ User quyết định chờ, đổi chuyến, hoặc liên hệ nhân viên
```

---

## Track 03 — Trợ lý sàng lọc triệu chứng cho phòng khám

### Bối cảnh sản phẩm

Một phòng khám hoặc ứng dụng chăm sóc sức khỏe dùng AI assistant để giúp người dùng mô tả triệu chứng trước khi đặt lịch khám.

AI không thay thế bác sĩ. Nó chỉ hỗ trợ người dùng mô tả tình trạng, chọn loại lịch hẹn phù hợp, hoặc tìm hướng dẫn tiếp theo.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Website phòng khám
App đặt lịch khám
Trang "Mô tả triệu chứng"
Trang "Tôi nên đặt lịch khám chuyên khoa nào?"
Chat trước khi gặp điều phối viên
```

### Flow người dùng mẫu

```text
Flow A:
User vào website phòng khám
→ Bấm "Đặt lịch khám"
→ Hệ thống hỏi lý do khám
→ AI assistant giúp user mô tả triệu chứng rõ hơn
→ User chọn đặt lịch hoặc nhận hướng dẫn liên hệ phòng khám

Flow B:
User mở app buổi tối
→ Không chắc triệu chứng có cần đi khám ngay không
→ Chat với AI để mô tả triệu chứng
→ Dựa vào câu trả lời để quyết định chờ, đặt lịch, hoặc tìm hỗ trợ khẩn cấp

Flow C:
Người nhà nhập thông tin thay cho bệnh nhân
→ Thông tin ban đầu còn thiếu
→ AI hỏi thêm để làm rõ bối cảnh
→ User được hướng dẫn sang kênh phù hợp
```

---

## Track 04 — Trợ lý ghi chú và tổng hợp chi tiêu

### Bối cảnh sản phẩm

Một ứng dụng quản lý chi tiêu cá nhân dùng AI để giúp user ghi chú khoản chi, phân loại giao dịch, tổng hợp thói quen chi tiêu, và tạo báo cáo ngắn cuối tuần/tháng.

Track này không tập trung vào tư vấn đầu tư, vay nợ, hoặc lời khuyên tài chính chuyên sâu. Mục tiêu là một workflow nhẹ hơn: ghi nhận, phân loại, tóm tắt, và giúp user nhìn lại chi tiêu.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
App ghi chú chi tiêu
Màn hình thêm khoản chi
Màn hình import giao dịch
Trang tổng hợp chi tiêu tuần/tháng
Chat hỏi "tháng này tiền của tôi đi đâu?"
```

### Flow người dùng mẫu

```text
Flow A:
User đi ăn, mua đồ, trả tiền dịch vụ
→ Mở app ghi nhanh khoản chi bằng text hoặc voice
→ AI phân loại khoản chi và hỏi lại nếu thông tin thiếu
→ User xác nhận để lưu vào sổ chi tiêu

Flow B:
User import danh sách giao dịch từ file hoặc ảnh chụp
→ AI đọc và gợi ý phân loại
→ User xem lại các khoản chưa rõ
→ App tạo bảng tổng hợp chi tiêu

Flow C:
Cuối tháng user mở báo cáo
→ AI tóm tắt nhóm chi tiêu lớn, khoản bất thường, xu hướng tăng/giảm
→ User dùng phần tóm tắt để tự điều chỉnh thói quen
```

---

## Track 05 — Pipeline viết nội dung marketing

### Bối cảnh sản phẩm

Một team marketing dùng AI để tạo bản nháp social post, email, landing page, ad copy, hoặc nội dung campaign từ brief nội bộ.

AI nằm trong workflow làm việc của marketer. Nó giúp tạo draft nhanh hơn, nhưng nội dung cuối cùng vẫn cần người thật kiểm tra trước khi xuất bản.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Campaign workspace
Brief-to-copy generator
Content calendar
Landing page editor
Email campaign editor
Ad copy variant generator
```

### Flow người dùng mẫu

```text
Flow A:
Marketer tạo campaign mới
→ Nhập campaign brief ngắn
→ AI sinh 3 phiên bản headline và body copy
→ Marketer chọn bản tốt nhất để chỉnh sửa

Flow B:
Marketer có landing page draft
→ Nhờ AI viết lại cho thuyết phục hơn
→ AI đề xuất claim, CTA, testimonial-style copy
→ Marketer chuẩn bị gửi cho brand/legal review

Flow C:
Team cần nhiều phiên bản quảng cáo
→ AI tạo các biến thể cho nhiều tệp người dùng
→ Marketer so sánh tone, claim, và rủi ro trước khi publish
```

---

## Track 06 — Trình tạo báo cáo kinh doanh

### Bối cảnh sản phẩm

Một team vận hành, marketing, sales, hoặc product dùng AI để tạo báo cáo tuần/tháng từ spreadsheet, dashboard screenshot, và ghi chú ngắn.

AI hỗ trợ tóm tắt dữ liệu và viết narrative. Báo cáo có thể được gửi cho quản lý, nên phần số liệu và kết luận cần đáng tin.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Analytics workspace
Weekly report generator
Dashboard summary tool
Spreadsheet add-on
Internal reporting template
```

### Flow người dùng mẫu

```text
Flow A:
Analyst upload spreadsheet tuần này
→ AI tạo executive summary
→ Analyst xem lại số liệu và insight
→ Báo cáo được gửi cho manager

Flow B:
Manager mở dashboard
→ Bấm "Generate weekly insight"
→ AI tóm tắt biến động chính
→ Manager dùng bản nháp để chuẩn bị họp

Flow C:
Team có dashboard screenshot và vài dòng note
→ AI viết báo cáo ngắn
→ Analyst kiểm tra caveat, anomaly, và nguyên nhân được nêu trong báo cáo
```

---

## Track 07 — Trợ lý sàng lọc CV và tuyển dụng

### Bối cảnh sản phẩm

Một công ty dùng AI assistant trong hệ thống tuyển dụng để tóm tắt CV, so sánh ứng viên với tiêu chí công việc, và hỗ trợ recruiter chuẩn bị shortlist hoặc câu hỏi phỏng vấn.

AI hỗ trợ recruiter, nhưng quyết định tuyển dụng vẫn thuộc về con người.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Applicant tracking system
Trang danh sách ứng viên
Trang chi tiết CV
Màn hình shortlist
Màn hình chuẩn bị câu hỏi phỏng vấn
```

### Flow người dùng mẫu

```text
Flow A:
Recruiter mở danh sách 200 CV
→ Bấm "AI summarize candidates"
→ AI tạo tóm tắt từng ứng viên
→ Recruiter lọc danh sách để review sâu hơn

Flow B:
Hiring manager mở hồ sơ một ứng viên
→ AI so sánh CV với job description
→ AI gợi ý điểm cần hỏi thêm trong phỏng vấn
→ Người thật quyết định bước tiếp theo

Flow C:
Recruiter cần chuẩn bị shortlist
→ AI hiển thị ghi chú về kinh nghiệm, kỹ năng, project
→ Recruiter kiểm tra lại CV gốc trước khi đưa vào danh sách
```

---

## Track 08 — Pipeline xử lý ticket chăm sóc khách hàng

### Bối cảnh sản phẩm

Một team support dùng AI để đọc ticket/email khách hàng, phân loại vấn đề, tóm tắt nội dung, gợi ý routing, và tạo bản nháp phản hồi cho support agent.

AI chủ yếu phục vụ nhân viên hỗ trợ, không nhất thiết chat trực tiếp với khách hàng.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Ticket inbox
Helpdesk dashboard
Email support queue
Màn hình chi tiết ticket
Routing / escalation panel
Suggested reply panel
```

### Flow người dùng mẫu

```text
Flow A:
Khách hàng gửi ticket qua form hỗ trợ
→ Ticket vào inbox
→ AI tự phân loại intent và độ ưu tiên
→ Support agent kiểm tra và xử lý

Flow B:
Agent mở ticket dài
→ AI tóm tắt vấn đề, lịch sử trao đổi, và yêu cầu chính
→ Agent dùng bản tóm tắt để quyết định hướng xử lý

Flow C:
AI gợi ý câu trả lời dựa trên policy
→ Agent chỉnh sửa trước khi gửi
→ Hệ thống lưu lại feedback của agent cho lần sau
```

---

## Track 09 — AI copilot hỗ trợ sales/CSKH trả lời khách hàng

### Bối cảnh sản phẩm

Một đội sales hoặc chăm sóc khách hàng dùng AI copilot trong lúc trao đổi với khách qua chat/email. AI không tự gửi tin nhắn, mà tóm tắt bối cảnh và gợi ý câu trả lời để nhân viên chọn, sửa, rồi gửi.

Track này tập trung vào AI làm "copilot cho nhân viên", không phải chatbot tự động cho khách cuối.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
CRM
Live chat console
Sales inbox
Customer profile panel
Suggested reply panel
Conversation summary panel
```

### Flow người dùng mẫu

```text
Flow A:
Nhân viên sales mở cuộc chat với khách tiềm năng
→ AI tóm tắt nhu cầu khách từ lịch sử trao đổi
→ AI gợi ý 2-3 câu trả lời tiếp theo
→ Nhân viên chọn và chỉnh sửa trước khi gửi

Flow B:
Khách hỏi về giá, ưu đãi, hoặc điều kiện sử dụng
→ AI tìm thông tin liên quan trong CRM/FAQ
→ AI gợi ý câu trả lời cho nhân viên
→ Nhân viên kiểm tra trước khi gửi khách

Flow C:
Khách hàng đang bực vì vấn đề chưa được xử lý
→ AI tóm tắt lịch sử case và đề xuất tone phản hồi
→ Nhân viên quyết định có escalate hoặc đưa ra phương án xử lý không
```

---

## Track 10 — AI chấm điểm cuộc gọi chăm sóc khách hàng

### Bối cảnh sản phẩm

Một team QA/CSKH dùng AI để đọc transcript hoặc nghe lại cuộc gọi chăm sóc khách hàng, sau đó chấm điểm theo rubric nội bộ như chào hỏi, xác minh thông tin, hiểu vấn đề, tuân thủ script, thái độ, và bước xử lý tiếp theo.

AI hỗ trợ QA reviewer, team lead, hoặc trainer. Nó không nên là cơ sở duy nhất để kỷ luật hoặc đánh giá nhân sự.

### Điểm chạm với AI

User gặp AI trong các khu vực:

```text
Call center QA dashboard
Trang chi tiết cuộc gọi
Transcript viewer
Rubric scoring panel
Agent coaching notes
Team performance report
```

### Flow người dùng mẫu

```text
Flow A:
QA reviewer mở một cuộc gọi đã ghi âm
→ AI tạo transcript và tóm tắt nội dung
→ AI chấm theo rubric từng tiêu chí
→ Reviewer kiểm tra lại bằng chứng trước khi xác nhận điểm

Flow B:
Team lead xem báo cáo tuần
→ AI tổng hợp pattern từ nhiều cuộc gọi
→ Team lead chọn một số case để nghe lại
→ Kết quả được dùng cho coaching hoặc training

Flow C:
Agent nhận feedback sau cuộc gọi
→ AI highlight đoạn hội thoại liên quan đến từng tiêu chí
→ Agent đọc feedback và xem phần cần cải thiện
→ Trainer quyết định nội dung coaching tiếp theo
```

---

## Menu lớp giải pháp cho Day 25

Sau khi học viên tự xác định failure case, nhóm có thể chọn 1-2 layer để thiết kế solution ở Day 25. Phần này chỉ là gợi ý, không phải bài nộp Day 24.

| Layer | Gợi ý artifact Day 25 | Phù hợp khi |
|---|---|---|
| UX/UI response | Screen sketch, warning, source badge, escalation button | User cần thấy giới hạn hoặc bước tiếp theo |
| System prompt | Prompt rules + examples | Cần siết hành vi AI trong phạm vi rõ |
| Workflow process | Flowchart, handoff, approval path | Cần người thật hoặc bước kiểm tra |
| Data/RAG architecture | Source list, retrieval rule, fallback behavior | Câu trả lời phải dựa trên nguồn |
| Detection/monitoring | Log, alert, dashboard, audit review | Cần phát hiện lỗi lặp lại |
| Policy/disclosure | One-page rule, user-facing disclosure | Cần làm rõ boundary và trách nhiệm |
| Approval flow | Human review queue, signoff gate | Có quyết định hoặc hành động nhạy cảm |
| Feedback loop | Report wrong answer, weekly fix cycle | Cần cải thiện sau khi dùng |
| Hybrid architecture | Rule-based first, AI second | Có điều kiện nghiệp vụ rõ hơn AI nên tự đoán |

---

## Gợi ý vận hành peer review

Pairing tốt nhất:

```text
Cùng failure mode + khác domain
```

Ví dụ:

```text
Hallucination: tuyển sinh ↔ hàng không
Escalation failure: phòng khám ↔ ticket CSKH
Unsupported claim: marketing ↔ sales/CSKH copilot
Bias/fairness: tuyển dụng ↔ chấm điểm cuộc gọi CSKH
Summary factuality: báo cáo kinh doanh ↔ ticket CSKH
```
