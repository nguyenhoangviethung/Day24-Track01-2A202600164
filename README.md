# Day 24 — Responsible AI: Map the Failure

Day 24 là bài tập cá nhân. Bạn chọn một AI workflow, dự đoán workflow đó có thể fail ở đâu, rồi viết test set và eval plan để kiểm tra trước khi dùng hoặc launch.

## Bạn cần nộp gì?

Chỉ nộp **2 file chính** trong folder `worksheet/`:

| File nộp | Nội dung |
|---|---|
| `worksheet/01-risk-map.md` | Track đã chọn, scenario, 3 failure candidates, layer chính/phụ, primary failure deep dive, harm map |
| `worksheet/02-test-eval-plan.md` | Safety question, test set v0, eval plan v0 |

Không nộp file System Map riêng, Harm Map riêng, Safety Question riêng, Test Set riêng hay Eval Plan riêng. Các phần đó đã được gom vào 2 file trên.

## Flow làm bài

```text
Đọc 8 failure modes
   -> chọn track
   -> viết scenario
   -> chọn 3 failure candidates
   -> gắn layer chính / layer phụ
   -> chọn primary failure
   -> viết Harm Map
   -> viết Safety Question
   -> viết Test Set v0
   -> viết Eval Plan v0
```

## Bài tập 1 — `01-risk-map.md`

File này trả lời câu hỏi: **AI có thể fail kiểu gì, fail từ layer nào, và ai bị hại?**

Bạn cần điền 5 phần:

1. Chọn track: track number, tên track, vì sao chọn.
2. Scenario: system/workflow, user, context, real-work consequence.
3. Failure candidates: 3 lỗi có thể xảy ra, mỗi lỗi có failure mode, trigger, bad behavior, severity, layer chính, layer phụ.
4. Primary failure deep dive: đào sâu 1 lỗi chính bằng prompt, bad response, expected safe behavior, harm, layer và failure pattern sentence.
5. Harm Map: direct user, affected person, hidden harm, case eval đơn giản sẽ bỏ sót.

## Bài tập 2 — `02-test-eval-plan.md`

File này trả lời câu hỏi: **Ta sẽ test failure đó như thế nào, và chấm Pass/Fail ra sao?**

Bạn cần điền 3 phần:

1. Safety Question: một câu hỏi hẹp, testable, bám primary failure trong file 1.
2. Test Set v0: ít nhất 5 test cases gồm normal, critical, edge, pressure trap, escalation/out-of-scope.
3. Eval Plan v0: Pass nếu, Fail nếu, Unclear nếu, severity rule, evidence cần collect, và phần “What this eval does NOT test”.

## Track bank

Chọn 1 track từ [`track-bank-scenario-kit.md`](track-bank-scenario-kit.md):

1. Chatbot tư vấn tuyển sinh đại học
2. Trợ lý đặt vé và CSKH hàng không
3. Trợ lý sàng lọc triệu chứng phòng khám
4. Trợ lý ghi chú và tổng hợp chi tiêu
5. Pipeline viết nội dung marketing
6. Trình tạo báo cáo kinh doanh
7. Trợ lý sàng lọc CV và tuyển dụng
8. Pipeline xử lý ticket CSKH
9. AI copilot hỗ trợ sales/CSKH
10. AI chấm điểm cuộc gọi CSKH

## Tài liệu tham khảo trong folder

| File | Dùng để làm gì? |
|---|---|
| `track-bank-scenario-kit.md` | Chọn track và đọc bối cảnh mẫu |
| `03-references/student-reference-document.md` | Đọc song song với lecture, có link nguồn chính |

## Checklist trước khi nộp

- [ ] `01-risk-map.md` đã điền đủ track, scenario, 3 candidates, primary failure, harm map.
- [ ] Mỗi failure candidate có layer chính và layer phụ.
- [ ] Primary failure có example prompt, bad AI response, expected safe behavior.
- [ ] `02-test-eval-plan.md` có safety question hẹp và testable.
- [ ] Test set có đủ 5 type case.
- [ ] Eval plan có Pass / Fail / Unclear, severity rule, evidence requirement, limitation.
- [ ] Nếu dùng AI để hỗ trợ, đã ghi note dùng AI ở cuối file liên quan.

## Nguồn tham khảo chính

| Chủ đề | Nguồn |
|---|---|
| AI Safety và Responsible AI | [Stanford CS120](https://web.stanford.edu/class/cs120/) · [Helen Toner, Georgetown CSET](https://cset.georgetown.edu/staff/helen-toner/) |
| Air Canada chatbot | [CanLII: Moffatt v. Air Canada, 2024 BCCRT 149](https://www.canlii.org/en/bc/bccrt/doc/2024/2024bccrt149/2024bccrt149.html) · [BBC Travel](https://www.bbc.com/travel/article/20240222-air-canada-chatbot-misinformation-what-travellers-should-know) |
| 3 lens Human-Centered AI | [James Landay, Stanford HAI](https://hai.stanford.edu/events/ai-good-isnt-good-enough-call-human-centered-ai) |
| Uber Tempe | [NTSB HAR-19/03](https://www.ntsb.gov/investigations/AccidentReports/Reports/HAR1903.pdf) |
| Responsible AI defense in depth | [Microsoft Responsible AI Transparency Report 2025](https://www.microsoft.com/en-us/corporate-responsibility/responsible-ai-transparency-report/) |
| Evaluation | [Chip Huyen, AI Engineering, Chapter 4](https://www.oreilly.com/library/view/ai-engineering/9781098166298/ch04.html) |
| RAGAS | [RAGAS evaluate() docs](https://docs.ragas.io/en/latest/references/evaluate/) |
