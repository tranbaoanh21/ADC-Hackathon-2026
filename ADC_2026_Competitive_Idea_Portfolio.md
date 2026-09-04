# ADC Hackathon 2026 — Danh mục ý tưởng có khả năng cạnh tranh

> **Mục đích:** tạo một danh mục ý tưởng đủ sâu để cả nhóm dùng khi nhận brief chính thức, phỏng vấn end-user (người dùng trực tiếp) và quyết định sản phẩm sẽ làm tại ADC Hackathon 2026.
>
> Đây là **idea portfolio (danh mục giả thuyết ý tưởng)**, không phải danh sách sản phẩm phải code trước. Brief cụ thể chỉ được công bố ở Day 1. Bất kỳ ý tưởng nào dưới đây cũng phải được sửa, thu hẹp hoặc loại bỏ nếu end-user evidence (bằng chứng từ người dùng) không ủng hộ.
>
> **Cập nhật:** 03/09/2026.

---

## Mục lục

1. [Kết luận nhanh](#1-kết-luận-nhanh)
2. [Lợi thế thật của team](#2-lợi-thế-thật-của-team)
3. [Nguyên tắc tạo và loại ý tưởng](#3-nguyên-tắc-tạo-và-loại-ý-tưởng)
4. [Cách chấm điểm nội bộ](#4-cách-chấm-điểm-nội-bộ)
5. [Bảng xếp hạng 16 ý tưởng](#5-bảng-xếp-hạng-16-ý-tưởng)
6. [Nhóm A — Visual Impairment](#6-nhóm-a--visual-impairment)
7. [Nhóm B — Neurodivergence](#7-nhóm-b--neurodivergence)
8. [Nhóm C — Deaf or Hard of Hearing](#8-nhóm-c--deaf-or-hard-of-hearing)
9. [Nhóm D — Mobility Impairment](#9-nhóm-d--mobility-impairment)
10. [Hai ý tưởng cross-disability](#10-hai-ý-tưởng-cross-disability)
11. [Những hướng không nên chọn nếu chưa có insight rất mạnh](#11-những-hướng-không-nên-chọn-nếu-chưa-có-insight-rất-mạnh)
12. [Cách dùng Codex như một lợi thế khi build](#12-cách-dùng-codex-như-một-lợi-thế-khi-build)
13. [Kiến trúc nền nên chuẩn bị trước](#13-kiến-trúc-nền-nên-chuẩn-bị-trước)
14. [Quy trình chọn một ý tưởng sau khi nhận brief](#14-quy-trình-chọn-một-ý-tưởng-sau-khi-nhận-brief)
15. [Bộ câu hỏi phỏng vấn end-user](#15-bộ-câu-hỏi-phỏng-vấn-end-user)
16. [Cách chứng minh từng tiêu chí chấm](#16-cách-chứng-minh-từng-tiêu-chí-chấm)
17. [Nguồn và prior art cần đọc](#17-nguồn-và-prior-art-cần-đọc)

---

# 1. Kết luận nhanh

Nếu phải mang một shortlist (danh sách rút gọn) vào phòng thi ngay lúc này, tôi sẽ giữ năm hướng sau:

1. **ClarityLoop — Shared Work Agreement:** biến yêu cầu công việc mơ hồ thành một bản thống nhất có thể xác nhận giữa nhân viên và quản lý.
2. **EvidenceLens — Accessible Shared-Visual Workspace:** giúp nhân viên khiếm thị khám phá chart, dashboard, screenshot và sơ đồ bằng cấu trúc, số liệu và bằng chứng kiểm chứng được.
3. **ReturnPoint — Interruption Recovery Companion:** giúp người dùng quay lại đúng trạng thái công việc sau khi bị gián đoạn mà không theo dõi họ một cách xâm phạm.
4. **ScreenTrail — Accessible Visual Work Instruction:** chuyển hướng dẫn bằng screenshot thành các bước có cấu trúc, điều hướng được bằng bàn phím và screen reader.
5. **TurnBridge — Participation Layer for Hybrid Meetings:** không chỉ tạo caption mà giúp người Điếc/khiếm thính biết ai đang nói, lúc nào có chồng lời, câu hỏi nào đang chờ và cách yêu cầu sửa transcript.

Hai hướng phù hợp nhất với hai preference (lựa chọn ưu tiên) hiện tại của nhóm là:

- **Visual Impairment:** EvidenceLens hoặc ScreenTrail.
- **Neurodivergence:** ClarityLoop hoặc ReturnPoint.

Thứ hạng này chỉ phản ánh những gì chúng ta biết **trước khi có brief và phỏng vấn người dùng**. Một insight rất mạnh trong Day 1–2 có quyền đảo toàn bộ bảng xếp hạng.

Điểm chung của năm hướng trên:

- gắn với một tình huống công việc cụ thể;
- không cần train model mới trong ba ngày;
- tạo được vertical slice (luồng cốt lõi chạy xuyên suốt) hoàn chỉnh;
- có chỗ để Phúc thể hiện AI evaluation (đánh giá AI), không chỉ prompt engineering;
- có chỗ để Anh build một sản phẩm polished (chỉn chu), accessible và deploy được;
- cho Linh đủ chất liệu user research, feasibility, impact và pitch;
- có thể demo bằng một câu chuyện trước/sau rất rõ.

---

# 2. Lợi thế thật của team

## 2.1. Đội hình ba người bổ trợ nhau

### Bảo Anh — Product Engineering và AI Integration

Anh có thể sở hữu toàn bộ application layer (lớp ứng dụng):

- React/Next.js;
- backend API;
- database khi thật sự cần;
- tích hợp model/API;
- schema validation (kiểm tra đầu ra theo khuôn dữ liệu);
- error handling và fallback;
- accessibility implementation;
- testing, Docker và deployment.

Lợi thế không phải “biết nhiều công nghệ”, mà là có thể biến một model hoặc API thành **một sản phẩm end-to-end dùng được**.

### Phương Linh — Product, Business, Research và Pitch

Linh nên giữ quyền sở hữu problem, evidence và câu chuyện:

- chuẩn bị và thực hiện phỏng vấn;
- phân biệt observation (điều quan sát được) với assumption (giả định);
- competitor scan (khảo sát giải pháp hiện có);
- xác định actor, buyer, adopter và stakeholder;
- theo dõi thay đổi thiết kế sau feedback;
- xây impact, feasibility, roadmap;
- deck, video, pitch và Q&A.

Linh không chỉ “làm slide”. Nếu không có một người giữ problem chặt, hai thành viên kỹ thuật rất dễ mở rộng sản phẩm theo những gì code được thay vì những gì người dùng cần.

### Hồng Phúc — Applied AI, Multimodal và Evaluation

Phúc có lợi thế ở:

- image–text và multimodal AI;
- CNN/ResNet/Transformer/Swin Transformer;
- NLP, RAG, embeddings và vector search;
- thiết kế test set;
- metrics và failure analysis;
- security risk của RAG;
- đưa model ra khỏi notebook thành một component có contract rõ.

Trong hackathon, giá trị lớn nhất của Phúc không phải train một model mới. Phúc nên giúp đội trả lời: **AI nào vừa đủ, sai ở đâu, đo thế nào và ứng dụng phải phản ứng ra sao khi AI không chắc chắn?**

## 2.2. Lợi thế khi có Codex đồng hành

Codex có thể rút ngắn đáng kể thời gian từ quyết định sản phẩm tới prototype:

- dựng repository và kiến trúc;
- tạo accessible component;
- viết API, schema và adapter cho AI provider;
- xây test fixture và evaluation harness;
- đọc log, tìm lỗi và sửa integration;
- kiểm tra keyboard flow, semantic HTML và trạng thái loading/error;
- viết tài liệu kỹ thuật, demo script và Q&A bank;
- giúp Anh giữ tốc độ mà vẫn kiểm soát chất lượng.

Nhưng lợi thế này chỉ phát huy nếu team phân công đúng:

```text
Con người sở hữu:
problem, consent, user relationship, product decision, ethical judgment, pitch

Codex hỗ trợ:
implementation, iteration, testing, documentation, technical synthesis
```

Codex không thay thế việc nói chuyện với người dùng. Một prototype hoàn hảo của một giả định sai vẫn là bài yếu.

---

# 3. Nguyên tắc tạo và loại ý tưởng

## 3.1. Bám đúng rubric chính thức

ADC 2026 công bố năm tiêu chí:

1. **Innovation & Impact** — tính mới và tác động đối với rào cản accessibility/employability thật.
2. **User-Centred Design & Accessibility** — mức độ hiểu người dùng và áp dụng thiết kế hòa nhập.
3. **Feasibility & Practicality** — khả năng triển khai trong bối cảnh và nguồn lực thật.
4. **Use of AI** — AI được tích hợp hiệu quả, phù hợp và có trách nhiệm.
5. **Presentation & Communication** — chỉ áp dụng ở Finale.

BTC không công bố trọng số. Vì thế bảng điểm trong tài liệu này là công cụ ra quyết định nội bộ, không phải công thức chấm chính thức. Nguồn: [ADC Hackathon 2026 — Judging Criteria](https://industryhub.rmit.edu.vn/ADC/#judging).

## 3.2. Không làm lại bài thắng cũ dưới một tên khác

Danh sách tiền lệ cần tránh sao chép trực tiếp:

- nhận dạng/dịch ngôn ngữ ký hiệu tổng quát: HANDTALK, 7 Rings;
- nhạc Braille: dự án năm 2020, The Great Musica;
- interview coach: AI Speech Companion, NeuroAICC;
- nhận diện cảm xúc/tín hiệu xã hội cho người khiếm thị: SightSence, InSight;
- smart walker: AllStep;
- ghi chú và transcript đa năng: Accesstant;
- khớp/công cụ cơ khí cho chi trên: Versatile Mechanical Joint.

Một ý tưởng cùng lĩnh vực vẫn có thể hợp lệ nếu problem, người dùng, workflow và contribution (đóng góp mới) khác thật sự. “Thêm chatbot” hoặc “đổi model” không phải khác biệt đủ mạnh.

## 3.3. Không cạnh tranh với tính năng phổ thông bằng một bản clone nhỏ hơn

Các baseline (giải pháp nền) hiện đã khá mạnh:

- Microsoft Teams có transcript, speaker timeline và AI recap.
- Google Voice Access cho phép điều khiển thiết bị bằng giọng nói.
- Goblin Tools đã có chia nhỏ task, đổi giọng văn, ước lượng thời gian và chuyển brain dump thành action.
- Các hệ thống như Umwelt, SeeChart, Chart Reader và ParaCharts đã nghiên cứu hoặc triển khai chart accessibility.

Vì vậy:

- “AI tóm tắt cuộc họp” không đủ mới.
- “AI chia task thành các bước” không đủ mới.
- “điều khiển điện thoại bằng giọng nói” không đủ mới.
- “đọc biểu đồ thành một đoạn mô tả” không đủ mới.

Ý tưởng phải giải quyết phần **còn thiếu trong workflow**, đặc biệt là sự tham gia, xác nhận, truy vết nguồn, sửa lỗi, chuyển giao giữa employee và employer hoặc accessibility trong nội dung không có dữ liệu gốc.

## 3.4. Một ý tưởng đủ tốt phải trả lời bảy câu

1. Người dùng cụ thể là ai?
2. Khoảnh khắc công việc nào tạo ra rào cản?
3. Cách xử lý hiện tại là gì và phần nào chưa ổn?
4. AI làm đúng một nhiệm vụ nào mà quy tắc thông thường khó làm?
5. Nếu AI sai thì người dùng phát hiện, sửa hoặc bỏ qua thế nào?
6. Trong ba ngày, demo được điều gì từ đầu đến cuối?
7. Sau hackathon, ai có động lực triển khai hoặc trả chi phí?

---

# 4. Cách chấm điểm nội bộ

Mỗi ý tưởng được chấm trên thang 100. Đây là thang tự xây để tránh việc cả nhóm chọn theo cảm giác.

| Thành phần | Điểm tối đa | Câu hỏi dùng để chấm |
|---|---:|---|
| Workplace impact | 15 | Rào cản có ảnh hưởng rõ tới khả năng làm việc hoặc cơ hội việc làm không? |
| User-evidence potential | 15 | Có thể kiểm chứng với end-user và thay đổi thiết kế trong thời gian thi không? |
| Accessibility depth | 15 | Accessibility nằm trong kiến trúc hay chỉ là giao diện trang trí? |
| Novelty/white space | 15 | Có khoảng trống rõ so với bài cũ và sản phẩm phổ biến không? |
| 3-day feasibility | 15 | Team có thể hoàn thành vertical slice ổn định trong ba ngày không? |
| Meaningful AI | 15 | AI có cần thiết, đo được và dùng có trách nhiệm không? |
| Demo and pitch power | 10 | Có một khoảnh khắc trước/sau dễ hiểu và đáng nhớ không? |
| **Tổng** | **100** | |

Quy tắc loại sớm:

- Bất kỳ ý tưởng nào dưới **10/15 về user evidence** không được build trước khi có thêm bằng chứng.
- Bất kỳ ý tưởng nào dưới **10/15 về feasibility** phải thu hẹp scope.
- Nếu AI không đạt **9/15**, cân nhắc bỏ AI hoặc bỏ ý tưởng; không được thêm AI chỉ để lấy điểm.
- Ý tưởng có safety-critical decision (quyết định liên quan an toàn) phải có deterministic safeguard và manual override.

---

# 5. Bảng xếp hạng 16 ý tưởng

Điểm dưới đây là đánh giá trước brief và trước phỏng vấn người dùng.

| Hạng | Ý tưởng | Nhóm chính | Điểm /100 | Nhận định ngắn |
|---:|---|---|---:|---|
| 1 | ClarityLoop | Neurodivergence | 91 | Hai phía cùng xác nhận yêu cầu; khác rõ chatbot chia task |
| 2 | EvidenceLens | Visual Impairment | 90 | Demo mạnh, hợp full-stack + multimodal; phải vượt khỏi chart caption |
| 3 | ReturnPoint | Neurodivergence | 87 | Problem đời thực và khá mới; privacy phải được thiết kế từ đầu |
| 4 | ScreenTrail | Visual Impairment | 86 | Chuyển screenshot/manual thành luồng thao tác accessible, workplace fit rõ |
| 5 | TurnBridge | Deaf/Hard of Hearing | 84 | Tập trung participation và repair, không clone live caption |
| 6 | ActionRail | Mobility Impairment | 83 | Software-first, demo đẹp; cần giới hạn một workflow cụ thể |
| 7 | QuietDescribe | Visual Impairment | 82 | Audio description cho training video có timing và evidence |
| 8 | ChangeMap | Neurodivergence | 80 | Làm rõ thay đổi kế hoạch, tác động và phần chưa chắc chắn |
| 9 | CaptionProof | Deaf/Hard of Hearing | 78 | Sửa caption theo domain/glossary; dễ làm nhưng cần insight mạnh |
| 10 | FormPilot | Mobility Impairment | 77 | Giảm thao tác chính xác trong form; có thể bị xem là browser automation |
| 11 | ZoomAnchor | Visual Impairment | 76 | Hữu ích cho low vision; phải chứng minh AI cần thiết thay vì chỉ sửa UI |
| 12 | SensoryPlan | Neurodivergence | 75 | Privacy-friendly và có giá trị quy trình; AI role còn nhẹ |
| 13 | AccessRoute Desk | Mobility Impairment | 74 | Lập kế hoạch workstation/đường đi tốt nhưng dữ liệu địa điểm khó có |
| 14 | SoundScope | Deaf/Hard of Hearing | 72 | Demo trực quan; rủi ro safety và dataset âm thanh cao |
| 15 | AccessHandoff | Cross-disability | 71 | Feasible và có tác động quy trình; AI có thể chưa đủ trung tâm |
| 16 | JobPost Mirror | Cross-disability | 69 | Hữu ích cho employer nhưng dễ thành công cụ rewrite chung chung |

Không nên hiểu chênh lệch 1–3 điểm là có ý nghĩa thống kê. Các ý tưởng trong cùng một tier gần như ngang nhau cho tới khi có evidence.

### Chi tiết điểm của sáu hướng đầu

| Ý tưởng | Impact /15 | User evidence /15 | Accessibility /15 | Novelty /15 | Feasibility /15 | AI /15 | Demo /10 | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| ClarityLoop | 14 | 14 | 14 | 14 | 14 | 12 | 9 | 91 |
| EvidenceLens | 14 | 13 | 15 | 12 | 13 | 14 | 9 | 90 |
| ReturnPoint | 13 | 13 | 14 | 14 | 14 | 11 | 8 | 87 |
| ScreenTrail | 13 | 13 | 15 | 13 | 14 | 11 | 7 | 86 |
| TurnBridge | 14 | 14 | 14 | 11 | 11 | 12 | 8 | 84 |
| ActionRail | 14 | 12 | 14 | 13 | 11 | 11 | 8 | 83 |

Điểm AI thấp hơn không nhất thiết là nhược điểm. ClarityLoop được xếp đầu vì cân bằng tốt cả problem, hành vi hai phía và feasibility; EvidenceLens có AI sâu hơn nhưng rủi ro extraction cao hơn. Đây chính là loại trade-off team phải thảo luận thay vì mặc định chọn ý tưởng có model phức tạp nhất.

### Tier A — Có thể đi thẳng vào discovery

- ClarityLoop.
- EvidenceLens.
- ReturnPoint.
- ScreenTrail.

### Tier B — Mạnh nếu brief và end-user xác nhận đúng problem

- TurnBridge.
- ActionRail.
- QuietDescribe.
- ChangeMap.

### Tier C — Chỉ chọn khi có access hoặc insight đặc biệt

- CaptionProof.
- FormPilot.
- ZoomAnchor.
- SensoryPlan.
- AccessRoute Desk.
- SoundScope.
- AccessHandoff.
- JobPost Mirror.

---

# 6. Nhóm A — Visual Impairment

W3C ghi nhận người khiếm thị hoặc low vision có thể gặp rào cản khi hình ảnh không có text alternative, cấu trúc trang không được mã hóa đúng, layout không phóng to được, video thiếu audio description và ứng dụng không hỗ trợ đầy đủ bàn phím. Với complex image như chart hay sơ đồ, một câu alt text ngắn thường không đủ; long description cần chứa cấu trúc, giá trị và xu hướng. Nguồn: [W3C — Visual disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/visual/), [W3C — Complex Images](https://www.w3.org/WAI/tutorials/images/complex/).

## 6.1. EvidenceLens — Accessible Shared-Visual Workspace

### Một câu mô tả

EvidenceLens biến chart, dashboard, screenshot và sơ đồ đang được chia sẻ trong công việc thành một workspace có cấu trúc mà người khiếm thị có thể khám phá bằng bàn phím, hỏi theo mục tiêu và kiểm tra từng câu trả lời về đúng vùng nguồn.

### Khoảnh khắc người dùng

Trong weekly review, một đồng nghiệp share dashboard dưới dạng hình ảnh. Screen reader không truy cập được dữ liệu gốc. Việc nhờ người khác mô tả khiến nhân viên khiếm thị chậm một nhịp và khó tự đặt câu hỏi.

### Khoảng trống so với công cụ hiện có

Umwelt và các nghiên cứu chart accessibility rất mạnh khi có dataset hoặc chart được tạo trong hệ thống. EvidenceLens chỉ đáng làm nếu tập trung vào tình huống khó hơn:

- người dùng chỉ nhận screenshot hoặc nội dung shared screen;
- có nhiều loại visual trong cùng một cuộc họp;
- cần biết câu trả lời đến từ đâu;
- cần điều hướng theo cấu trúc thay vì nghe một đoạn caption dài.

Đây không phải “upload ảnh rồi AI mô tả”. Contribution phải là **evidence-grounded exploration (khám phá có bằng chứng gắn với nguồn)**.

### Luồng sản phẩm

```text
Screenshot / PDF page / chart / dashboard
                    ↓
Phân loại visual và phát hiện layout
                    ↓
OCR + chart/diagram extraction + VLM
                    ↓
Structured evidence graph:
regions, labels, values, relations, confidence
                    ↓
Accessible navigator:
overview → sections → data points → source evidence
                    ↓
Question answering bị giới hạn bởi evidence graph
```

### AI làm gì?

- phân loại loại visual;
- OCR và gắn text vào đúng vùng;
- đề xuất quan hệ giữa label, value và shape;
- tạo overview và trả lời câu hỏi;
- phát hiện khi bằng chứng không đủ.

### Phần không giao cho AI

- tính toán số liệu khi đã trích xuất được bảng: dùng code xác định;
- schema validation;
- đánh dấu câu trả lời không có source region;
- keyboard navigation và semantic HTML;
- rule không cho model khẳng định số liệu khi confidence thấp.

### MVP ba ngày

Chỉ hỗ trợ ba input mẫu:

1. bar chart;
2. line chart;
3. dashboard có KPI card và một chart.

MVP cần có:

- upload hoặc paste screenshot;
- overview ngắn;
- bảng dữ liệu accessible;
- danh sách trend/comparison;
- hỏi ba dạng câu: cao nhất/thấp nhất, thay đổi, so sánh;
- mỗi câu trả lời dẫn tới vùng nguồn hoặc cell đã trích xuất;
- trạng thái “không đủ chắc chắn”;
- dùng hoàn toàn bằng bàn phím và screen reader.

### Demo 90 giây

```text
Trước: nhân viên nhận một dashboard ảnh và chỉ nghe “sales dashboard”.

Sau:
1. Paste screenshot.
2. Screen reader thông báo loại chart và ba section.
3. Người dùng nhảy tới KPI, trend hoặc data table.
4. Hỏi “Miền nào giảm mạnh nhất?”.
5. Hệ thống trả lời, đọc con số và liên kết tới evidence.
6. Một số mờ được đánh dấu cần xác nhận thay vì bị AI bịa.
```

### Evaluation

- exact match của số liệu;
- accuracy của label–value association;
- tỉ lệ câu trả lời có evidence hợp lệ;
- unsupported-claim rate;
- task completion time với screen reader;
- số thao tác để tìm một data point;
- người dùng có nhận ra output không chắc chắn hay không.

### Rủi ro

- model bịa số liệu;
- OCR gắn nhầm trục;
- chart phức tạp vượt scope;
- tài liệu doanh nghiệp nhạy cảm;
- output quá dài cạnh tranh với giọng người đang thuyết trình.

### Cách giảm rủi ro

- xử lý stateless, mặc định không lưu file;
- structured extraction trước, generation sau;
- mọi con số phải có tọa độ vùng nguồn;
- cho phép mức verbosity ngắn/vừa/chi tiết;
- có demo prerecorded dự phòng nhưng prototype vẫn chạy live.

### Vì sao có thể đạt giải cao

- problem workplace rõ;
- có chiều sâu accessibility thực sự;
- AI là bắt buộc nhưng được kiểm soát;
- demo có khoảnh khắc “từ bị chặn sang tự khám phá”;
- tận dụng đúng giao điểm kỹ năng của Anh và Phúc.

## 6.2. ScreenTrail — Accessible Visual Work Instruction

### Một câu mô tả

ScreenTrail chuyển tài liệu hướng dẫn nội bộ phụ thuộc vào screenshot và mũi tên thành checklist thao tác có cấu trúc, có tên control, trạng thái dự kiến và cách phục hồi khi giao diện khác với hướng dẫn.

### Khoảnh khắc người dùng

Một nhân viên mới phải làm theo tài liệu: “bấm biểu tượng bánh răng ở góc phải như hình dưới”. Screen reader chỉ đọc “image” hoặc tên file. Người dùng phải nhờ đồng nghiệp chỉ từng bước.

### Điểm mới

Không chỉ tạo alt text cho từng screenshot. Sản phẩm biến cả chuỗi hình thành một **executable mental model (mô hình thao tác có thể lần theo)**:

```text
Mục tiêu → điều kiện ban đầu → control cần tìm → hành động
→ trạng thái mong đợi → cách kiểm tra → cách quay lại
```

### Pipeline kỹ thuật

```text
PDF/manual có text + screenshot
              ↓
Document layout extraction
              ↓
Ghép instruction với screenshot tương ứng
              ↓
OCR + UI element detection + VLM reasoning
              ↓
Step schema có source reference
              ↓
Accessible step player
```

Ví dụ schema:

```json
{
  "goal": "Export the monthly report",
  "steps": [
    {
      "instruction": "Open the Export menu",
      "controlName": "Export",
      "controlRole": "button",
      "expectedState": "A menu with PDF and CSV options appears",
      "sourcePage": 3,
      "confidence": 0.91
    }
  ]
}
```

### MVP ba ngày

- một manual 4–6 trang;
- 5–8 bước cho một phần mềm mẫu;
- chế độ overview và one-step-at-a-time;
- phím tắt bước trước/sau, lặp lại, mở nguồn;
- đánh dấu bước không chắc;
- cho phép employee hoặc trainer sửa label.

### Demo

Cho giám khảo xem tài liệu gốc gần như không dùng được bằng screen reader, sau đó hoàn thành cùng quy trình bằng step player mà không nhìn screenshot.

### Evaluation

- tỉ lệ step được ghép đúng screenshot;
- control name/role accuracy;
- task completion rate;
- số lần phải mở ảnh gốc hoặc nhờ người khác;
- thời gian hoàn thành;
- số lỗi phục hồi được.

### Rủi ro

- giao diện phần mềm thay đổi sau khi manual được tạo;
- AI đoán control không tồn tại;
- tài liệu chứa credential hoặc dữ liệu nội bộ;
- scope “mọi tài liệu, mọi phần mềm” quá rộng.

### Phạm vi cạnh tranh hợp lý

Nên chọn một workflow doanh nghiệp cụ thể: export report, submit leave request hoặc tạo expense claim. Không nên hứa tự động hiểu mọi enterprise software.

## 6.3. QuietDescribe — Audio Description cho video đào tạo

### Một câu mô tả

QuietDescribe tạo audio description có bằng chứng cho video training, ưu tiên chèn mô tả vào khoảng lặng và cho người dùng chọn pause-on-demand khi không đủ chỗ.

### Khoảnh khắc người dùng

Video onboarding nói “hãy làm như trên màn hình” trong khi con trỏ thực hiện một chuỗi thao tác. Transcript có đầy đủ lời nói nhưng thiếu toàn bộ hành động thị giác.

### Khoảng trống

Caption không giải quyết thông tin chỉ xuất hiện bằng hình ảnh. W3C cũng lưu ý audio description cần timing cẩn thận; nếu người nói liên tục, có thể không đủ khoảng trống và phải dùng extended description hoặc phương án khác. Nguồn: [W3C — Description of Visual Information](https://www.w3.org/WAI/media/av/description/).

### Pipeline

```text
Video
  ↓
ASR + shot/scene segmentation + silence detection
  ↓
VLM mô tả thay đổi thị giác quan trọng
  ↓
Description planner:
importance, timing, duration, source frame
  ↓
Human review
  ↓
Audio track + descriptive transcript
```

### MVP

- một video training 60–90 giây;
- transcript và scene timeline;
- 4–6 description segment;
- preview từng đoạn với source frame;
- TTS;
- hai chế độ: chèn khoảng lặng và tạm dừng video để mô tả.

### AI safeguard

- description phải liên kết frame nguồn;
- không mô tả ý định hay cảm xúc nếu chỉ thấy hành động;
- reviewer duyệt trước khi xuất bản;
- giới hạn độ dài theo khoảng trống audio.

### Vì sao chưa xếp cao hơn

Ý tưởng tốt và demo rõ, nhưng trong ba ngày phần xử lý video, đồng bộ timeline và tạo media output có thể tốn thời gian. Nên làm player trong web thay vì render lại một file video hoàn chỉnh.

## 6.4. ZoomAnchor — Workspace ổn định cho người low vision

### Một câu mô tả

ZoomAnchor giúp người low vision theo dõi vị trí, cấu trúc và thay đổi khi phải phóng to một dashboard hoặc ứng dụng nội bộ đến mức chỉ nhìn thấy một phần màn hình.

### Problem

Khi zoom cao, người dùng mất context: đang ở section nào, notification vừa xuất hiện ở đâu, bảng còn bao nhiêu cột và nội dung nào vừa thay đổi ngoài viewport.

### Điểm AI có thể dùng

- tóm tắt thay đổi ngoài vùng nhìn;
- ưu tiên notification theo task hiện tại;
- mô tả vị trí tương đối của section;
- dự đoán điểm quay lại sau khi pan/zoom.

### MVP

Một dashboard mock với 200–400% zoom, breadcrumb không gian, change summary và phím quay về anchor. Không cần can thiệp toàn hệ điều hành.

### Lý do chỉ là phương án dự phòng

AI không phải lúc nào cũng thật sự cần; nhiều phần có thể giải bằng layout và state management tốt. Ý tưởng chỉ nên chọn nếu end-user xác nhận mất orientation là rào cản chính và AI change summarization tạo khác biệt rõ.

---

# 7. Nhóm B — Neurodivergence

W3C nhấn mạnh cognitive and learning disabilities là một phổ rất rộng, không đồng nghĩa năng lực trí tuệ thấp và không phải ai cũng có chẩn đoán hoặc muốn disclose. Nội dung rõ, cấu trúc nhất quán, tương tác có thể dự đoán, khả năng tắt chuyển động và quyền cá nhân hóa là những hỗ trợ quan trọng. Nguồn: [W3C — Cognitive and learning barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/cognitive/), [W3C — Clear and Understandable Content](https://www.w3.org/WAI/WCAG2/supplemental/objectives/o3-clear-content/).

## 7.1. ClarityLoop — Shared Work Agreement

### Một câu mô tả

ClarityLoop biến một yêu cầu công việc mơ hồ thành bản nháp có cấu trúc, làm nổi bật điều còn thiếu, rồi cho employee và manager cùng xác nhận một “work agreement” trước khi công việc bắt đầu.

### Khoảnh khắc người dùng

Manager gửi: “Em tổng hợp nhanh số liệu và làm deck đẹp giúp anh, ưu tiên sớm nhé.” Người nhận không biết phạm vi, audience, deadline, nguồn số liệu hay tiêu chí hoàn thành. Việc phải hỏi nhiều lần có thể tạo lo lắng hoặc bị hiểu nhầm là thiếu năng lực.

### Tại sao đây không phải task-breakdown chatbot

Goblin Tools và nhiều ứng dụng đã chia task thành bước nhỏ. Điểm khác của ClarityLoop là **shared clarification loop (vòng làm rõ có hai phía)**:

1. AI chỉ ra điều đã được nói và điều chưa được nói.
2. Employee chọn câu hỏi họ muốn gửi.
3. Manager trả lời hoặc sửa.
4. Hai bên xác nhận cùng một definition of done.
5. Mọi suy luận chưa được xác nhận vẫn mang nhãn “assumption”.

Sản phẩm không giúp employee “chịu đựng yêu cầu mơ hồ” tốt hơn; nó cải thiện chính cách tổ chức giao việc.

### Luồng sản phẩm

```text
Email / chat / task description
              ↓
Structured extraction
              ↓
Facts | ambiguities | assumptions | conflicts
              ↓
Clarification question generator
              ↓
Employee review
              ↓
Manager response / confirmation
              ↓
Shared Work Agreement có version history
```

### Schema cốt lõi

```json
{
  "goal": "Create the monthly performance deck",
  "audience": null,
  "deadline": null,
  "deliverables": ["Presentation deck"],
  "definitionOfDone": [],
  "knownFacts": [
    {
      "value": "Use monthly performance data",
      "sourceSpan": "tổng hợp nhanh số liệu"
    }
  ],
  "ambiguities": [
    "Which month and data source should be used?",
    "What does 'sớm' mean as a deadline?"
  ],
  "assumptions": [],
  "status": "awaiting_confirmation"
}
```

### AI làm gì?

- trích xuất các thành phần của task;
- phát hiện trường bị thiếu hoặc mâu thuẫn;
- tạo câu hỏi làm rõ với tone lịch sự;
- so sánh hai phiên bản để giải thích điều gì đã thay đổi;
- tạo một bản plain-language view theo preference của người dùng.

### AI không được làm gì?

- tự gán deadline rồi coi đó là sự thật;
- suy đoán chẩn đoán của employee;
- đánh giá thái độ hoặc năng lực;
- gửi tin nhắn cho manager khi chưa được người dùng duyệt;
- tự thay đổi scope đã xác nhận.

### MVP ba ngày

- paste một message hoặc email;
- structured task card;
- highlight facts và gaps;
- chọn/gửi giả lập tối đa ba clarification question;
- manager confirmation view;
- final agreement và change log;
- hai mode trình bày: concise và step-by-step;
- không cần đăng nhập thật hoặc tích hợp Slack/Teams.

### Demo 90 giây

```text
1. Paste một yêu cầu mơ hồ.
2. AI tách facts khỏi assumptions.
3. Employee chọn hai câu cần hỏi, bỏ một câu không phù hợp.
4. Manager xác nhận deadline và audience.
5. Hệ thống tạo definition of done có dấu “confirmed”.
6. Khi manager đổi deadline, Change View cho biết phần nào bị ảnh hưởng.
```

### Evaluation

- field extraction precision/recall trên bộ 20 task mẫu;
- ambiguity detection precision;
- tỉ lệ AI biến assumption thành fact;
- task-understanding score trước/sau;
- số lượt nhắn cần thiết để hai bên thống nhất;
- confidence của người dùng về “tôi biết phải làm gì tiếp theo”.

### Rủi ro

- biến mọi giao tiếp thành quy trình cứng nhắc;
- manager dùng tool để giám sát employee;
- AI tạo quá nhiều câu hỏi;
- thông tin công việc nhạy cảm;
- sản phẩm bị nhìn như productivity tool chung chung.

### Cách giữ đúng accessibility

- thiết kế preference-based, không yêu cầu khai báo diagnosis;
- employee kiểm soát câu hỏi nào được gửi;
- manager cũng nhận hướng dẫn viết yêu cầu rõ hơn;
- UI ổn định, không gamification bắt buộc, không countdown;
- mỗi thay đổi có diff rõ và lý do;
- cho phép dùng sản phẩm mà không gắn nhãn người dùng.

### Vì sao có thể thắng

ClarityLoop chuyển trách nhiệm từ “sửa người neurodivergent” sang **thiết kế giao tiếp công việc rõ cho cả hai phía**. Đây là impact và attitudinal change, không chỉ là một AI utility.

## 7.2. ReturnPoint — Interruption Recovery Companion

### Một câu mô tả

ReturnPoint cho phép người dùng chủ động tạo một checkpoint nhẹ trước khi rời task, rồi AI khôi phục “tôi đang làm gì, vì sao, bước kế tiếp và thứ gì chưa chắc” khi họ quay lại.

### Khoảnh khắc người dùng

Một nhân viên đang làm báo cáo thì nhận cuộc gọi gấp. Sau khi quay lại, họ mở nhiều tab nhưng không nhớ đoạn suy luận, file nguồn hoặc quyết định dở dang. Việc tái tạo context tốn thời gian và năng lượng.

Nghiên cứu về interruption cho thấy việc quay lại task không đơn giản là mở lại cửa sổ; người dùng phải tái thu nhận trạng thái và mục tiêu. Nguồn tham khảo: [Microsoft Research — Conversations Amidst Computing](https://www.microsoft.com/en-us/research/publication/conversations-amidst-computing-study-interruptions-recovery-task-activity/), [Clipping Lists and Change Borders](https://www.microsoft.com/en-us/research/publication/clipping-lists-and-change-borders-improving-multitasking-efficiency-with-peripheral-information-design/).

### Điểm khác productivity tracker

- không đo mọi hoạt động;
- không chụp màn hình liên tục;
- không chấm điểm hiệu suất;
- checkpoint do người dùng chủ động tạo;
- output tập trung vào phục hồi context, không ép lịch làm việc.

### Luồng

```text
Người dùng bấm “Pause with checkpoint”
                ↓
Nhập nhanh: mục tiêu, đoạn đang làm, điều còn vướng
+ chọn tab/file được phép đưa vào context
                ↓
AI tạo checkpoint có cấu trúc
                ↓
Khi quay lại: 30-second re-entry view
                ↓
Why → current state → next action → unresolved question
```

### MVP

- workspace giả lập với note, link và checklist;
- nút Pause;
- checkpoint tự động gợi ý nhưng phải được duyệt;
- Resume view chỉ một màn hình;
- chọn mức chi tiết;
- xóa checkpoint và data control rõ.

### AI role

- tóm tắt trạng thái từ dữ liệu người dùng cho phép;
- phân biệt completed, in-progress, blocked;
- đề xuất một next action;
- phát hiện unresolved question.

### Evaluation

- thời gian trả lời ba câu sau khi quay lại: đang làm gì, đã tới đâu, tiếp theo là gì;
- resumption lag;
- số lần mở nhầm file/tab;
- mức chính xác của checkpoint;
- cảm nhận về control và privacy.

### Rủi ro

- surveillance (giám sát) trá hình;
- thu thập dữ liệu nhạy cảm;
- summary sai làm người dùng đi sai hướng;
- demo khó nếu không dàn dựng khoảnh khắc gián đoạn rõ.

### Safeguard

Chỉ dùng opt-in context, mặc định xử lý cục bộ với text được chọn, không ghi keystroke và không chụp màn hình nền.

## 7.3. ChangeMap — Giải thích thay đổi công việc

### Một câu mô tả

ChangeMap so sánh hai phiên bản của kế hoạch, lịch, brief hoặc task và tạo một bản “điều gì thay đổi — vì sao — tôi bị ảnh hưởng thế nào — cần xác nhận gì”.

### Khoảnh khắc người dùng

Một lịch sự kiện, quy trình hoặc project brief thay đổi nhiều lần qua email và chat. Người dùng phải tự ráp context, dễ bỏ sót một dependency hoặc thay đổi ngầm.

### Pipeline

```text
Old document/message + new document/message
                  ↓
Deterministic text diff
                  ↓
Semantic change classification bằng LLM
                  ↓
Changed facts | affected tasks | unknown reason | questions
                  ↓
Accessible timeline + acknowledgment
```

### Điểm kỹ thuật quan trọng

Diff nguyên văn phải do code xác định. LLM chỉ phân loại ý nghĩa và giải thích, không được sửa lịch sử. Mỗi nhận xét phải liên kết về đoạn before/after.

### MVP

- hai phiên bản project brief;
- timeline thay đổi;
- lọc theo deadline, owner, scope và dependency;
- tạo clarification question;
- user xác nhận “đã hiểu” từng thay đổi quan trọng.

### Vì sao không ở Tier A

Problem hợp lý nhưng phải chứng minh đây là accessibility barrier cụ thể chứ không chỉ pain point chung của mọi project team. End-user interview quyết định số phận ý tưởng.

## 7.4. SensoryPlan — Preference-based meeting setup

### Một câu mô tả

SensoryPlan giúp người tham gia mô tả preference cho một buổi họp hoặc workshop, sau đó tạo kế hoạch tổ chức có thể thực hiện được mà không yêu cầu disclose diagnosis.

### Ví dụ preference

- nhận agenda trước;
- biết ai sẽ tham gia;
- không bật nhạc nền;
- có written question song song với lời nói;
- được tắt camera;
- có quiet break;
- báo trước khi đổi hoạt động.

### Sản phẩm hai phía

```text
Participant chọn preference
            ↓
AI chuyển thành request ngắn, trung tính
            ↓
Organizer xem feasibility và chọn phương án
            ↓
Accessible meeting plan
            ↓
Change notification nếu kế hoạch đổi
```

### Giá trị

Điểm hay là không cố đo sensory state bằng camera hoặc wearable. Người dùng tự khai preference và giữ quyền quyết định dữ liệu được chia sẻ.

### Điểm yếu

AI không thật sự khó và sản phẩm nghiêng về process design. Nó chỉ cạnh tranh cao nếu team có partner/doanh nghiệp và chứng minh adoption pathway rất tốt.

---

# 8. Nhóm C — Deaf or Hard of Hearing

Caption là điều kiện cần nhưng chưa đủ. W3C yêu cầu caption thể hiện cả thông tin âm thanh quan trọng và phân biệt người nói. Nghiên cứu về hybrid meeting cho thấy người khuyết tật gặp khó khăn khi xác định ai đang có mặt, ai đang nói, khi caption sai và khi lượt nói chồng lên nhau. Nguồn: [W3C — Media Accessibility User Requirements](https://www.w3.org/TR/media-accessibility-reqs/), [Microsoft Research — Accessibility in Hybrid Meetings](https://www.microsoft.com/en-us/research/publication/accessibility-barriers-conflicts-and-repairs-understanding-the-experience-of-professionals-with-disabilities-in-hybrid-meetings/).

## 8.1. TurnBridge — Participation Layer for Hybrid Meetings

### Một câu mô tả

TurnBridge là lớp hỗ trợ tham gia cuộc họp: ngoài caption, nó làm rõ người nói, phát hiện chồng lời, giữ hàng đợi câu hỏi và cung cấp nút “repair” để yêu cầu lặp lại hoặc xác nhận mà không phải ngắt cuộc họp bằng lời.

### Vì sao không phải Teams clone

Teams đã có transcript, speaker timeline và recap. TurnBridge không cạnh tranh ở “ghi lại sau cuộc họp” mà ở **khả năng tham gia ngay trong lúc cuộc họp đang diễn ra**:

- ai đang nói;
- câu nào có confidence thấp;
- có hai người nói chồng nhau không;
- câu hỏi của tôi đã được nhìn thấy chưa;
- tôi có thể yêu cầu “repeat/rephrase/slow down” bằng một tín hiệu ít ma sát không;
- decision vừa được nói có được cả phòng xác nhận không.

### Luồng kỹ thuật

```text
Meeting audio + participant list
              ↓
Streaming ASR + speaker diarization
              ↓
Overlap/confidence detector
              ↓
Live caption with speaker and uncertainty
              ↓
Participation controls:
question queue | repeat | rephrase | confirm decision
```

### MVP ba ngày

- audio mẫu hoặc microphone với 2–3 người;
- live caption;
- speaker A/B trước, tên người nói có thể gán thủ công;
- đánh dấu đoạn confidence thấp;
- phát hiện overlap đơn giản;
- ba repair button;
- question queue;
- decision card cần xác nhận.

### AI role

- ASR;
- diarization;
- phát hiện câu hỏi, decision và action item;
- rephrase theo yêu cầu;
- confidence/uncertainty presentation.

### Evaluation

- Word Error Rate;
- diarization error rate;
- overlap detection precision/recall;
- time-to-repair một caption sai;
- số câu hỏi được ghi nhận;
- người dùng có biết ai đang nói và decision hiện tại hay không.

### Rủi ro

- tiếng Việt nhiều giọng vùng miền;
- microphone phòng họp không tách được người;
- latency;
- AI “tự xác nhận” decision sai;
- ghi âm mà thiếu consent.

### Scope an toàn

Trong demo, cho phép gán speaker thủ công và dùng audio pre-recorded song song với live mic. Product value phải nằm ở participation/repair, không phụ thuộc việc tự xây ASR tốt hơn các hãng lớn.

## 8.2. CaptionProof — Domain Glossary và Collaborative Repair

### Một câu mô tả

CaptionProof giúp một nhóm xây glossary thuật ngữ riêng trước cuộc họp, hiển thị confidence khi ASR gặp tên riêng/từ chuyên môn và cho người tham gia sửa một lần để hệ thống áp dụng nhất quán về sau.

### Khoảnh khắc người dùng

Caption liên tục viết sai tên dự án, acronym và tên người. Người Điếc/khiếm thính phải đoán từ context, trong khi người nghe gần như không nhận ra rào cản đó.

### Pipeline

```text
Agenda + participant list + project glossary
                   ↓
Contextual vocabulary preparation
                   ↓
Streaming ASR
                   ↓
Term matching + confidence
                   ↓
One-click collaborative correction
                   ↓
Corrected transcript + audit trail
```

### MVP

- upload agenda;
- trích xuất tên riêng/acronym;
- glossary review;
- transcript demo chứa 8–10 thuật ngữ khó;
- correction UI;
- xuất transcript với lịch sử sửa.

### Điểm cạnh tranh

Feasible và đo được rất rõ. Tuy nhiên nó là một feature hẹp; để đạt giải cao, team cần chứng minh rào cản đủ lớn và có adoption story với một tổ chức thật.

## 8.3. SoundScope — Workplace Sound Event Router

### Một câu mô tả

SoundScope nhận biết một tập nhỏ âm thanh không phải lời nói tại nơi làm việc và chuyển chúng thành visual/haptic alert được cá nhân hóa, kèm nguồn và mức chắc chắn.

### Use case khả thi

- chuông cửa khu vực lễ tân;
- timer trong bếp hoặc phòng lab không nguy hiểm;
- tên người dùng được gọi tại quầy;
- notification từ một thiết bị cũ chỉ có âm thanh.

### Pipeline

```text
Microphone
   ↓
On-device audio event classifier
   ↓
Event + confidence + timestamp
   ↓
User routing rules
   ↓
Phone/web visual alert hoặc vibration pattern
```

### Rủi ro lớn

Không nên dùng prototype hackathon cho báo cháy, máy móc nguy hiểm hoặc tình huống sống còn. False negative trong các trường hợp đó có hậu quả nghiêm trọng.

### MVP

Giới hạn ba âm thanh vô hại, xử lý clip cục bộ, không lưu raw audio và cho người dùng tự chọn notification mapping.

### Vì sao xếp thấp

Dataset âm thanh thực tế, nhiễu môi trường và phần haptic làm tăng rủi ro. Demo dễ gây ấn tượng nhưng feasibility ngoài phòng thi khó chứng minh hơn software workflow.

---

# 9. Nhóm D — Mobility Impairment

W3C chỉ ra người khuyết tật vận động có thể dùng keyboard-only, switch, speech input hoặc thiết bị trỏ thay thế; các click target nhỏ, thao tác drag, time limit và luồng không sửa lỗi được là rào cản phổ biến. WCAG 2.2 cũng bổ sung yêu cầu liên quan dragging movement và target size. Nguồn: [W3C — Physical disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/physical/), [W3C — What is new in WCAG 2.2](https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22/).

## 9.1. ActionRail — Intent-to-Action Workflow

### Một câu mô tả

ActionRail cho phép người dùng kích hoạt một workflow công việc nhiều bước bằng switch, giọng nói hoặc một phím; AI ánh xạ intent sang một kế hoạch thao tác trên accessibility tree, nhưng mỗi hành động quan trọng vẫn cần xác nhận.

### Khoảnh khắc người dùng

Một expense claim yêu cầu hàng chục click, dropdown và drag/upload. Người dùng có limited dexterity phải lặp lại thao tác chính xác gây đau hoặc mệt, dù quy trình gần như giống nhau mỗi tuần.

### Không phải Voice Access clone

Voice Access đã cho điều khiển từng thao tác bằng giọng nói. ActionRail tập trung vào:

- workflow doanh nghiệp lặp lại;
- giảm số lượng interaction;
- dùng accessibility tree và semantic control thay vì click tọa độ;
- preview plan trước khi chạy;
- checkpoint, confirm và undo;
- hỗ trợ switch một nút, không chỉ giọng nói.

### Kiến trúc

```text
Voice / switch / single-key intent
               ↓
Intent parser
               ↓
Workflow planner dựa trên action catalog
               ↓
Accessibility-tree selector
               ↓
Step executor
               ↓
Confirmation cho submit/payment/delete
               ↓
Audit + undo khi có thể
```

### MVP ba ngày

Không tự động hóa web bất kỳ. Chỉ xây một expense claim mock app và ba workflow:

- tạo claim mới;
- thêm receipt;
- lưu draft hoặc submit sau xác nhận.

Input có thể là nút switch mô phỏng bằng phím Space và voice optional. Mục tiêu demo là giảm 20 thao tác xuống 4 lần xác nhận.

### AI role

- hiểu intent tự nhiên;
- điền plan từ action catalog;
- hỏi lại khi thiếu thông tin;
- tuyệt đối không tự tạo selector hoặc click ngoài catalog cho MVP.

### Evaluation

- số interaction trước/sau;
- task completion rate;
- wrong-action rate;
- số lần cần undo;
- thời gian và mức mệt tự báo cáo;
- dùng được với keyboard/switch hay không.

### Rủi ro

- browser automation dễ vỡ;
- AI thực hiện hành động không mong muốn;
- form chứa dữ liệu tài chính;
- voice không phù hợp trong văn phòng mở.

### Safeguard

Action catalog whitelist, preview plan, confirmation bắt buộc, audit log và không tự submit khi confidence thấp.

## 9.2. FormPilot — Error-resilient Form Mode

### Một câu mô tả

FormPilot biến một form dài thành chế độ từng bước, có target lớn, không drag, lưu tiến độ, sửa lỗi tại chỗ và cho phép điều khiển bằng keyboard/switch.

### Điểm mới cần có

Chỉ “làm form accessible” chưa đủ mới. AI nên hỗ trợ:

- giải thích yêu cầu field theo context;
- phát hiện dữ liệu lặp có thể tái sử dụng sau khi người dùng cho phép;
- đề xuất cách sửa error message khó hiểu;
- ưu tiên field còn thiếu;
- giữ nguyên giá trị pháp lý của label gốc.

### MVP

Một form tuyển dụng hoặc onboarding giả lập 20 field, so sánh bản gốc và assisted mode. Không scrape website bên thứ ba trong demo.

### Metrics

- số lỗi nhập;
- số lần phải nhập lại;
- số pointer movement/click;
- completion time;
- completion rate;
- keyboard và switch test.

### Vì sao chỉ Tier C

Form accessibility đã có tiêu chuẩn rõ. Ý tưởng chỉ mới nếu team tìm được workflow và failure cụ thể mà các pattern tiêu chuẩn chưa giải quyết.

## 9.3. AccessRoute Desk — Workstation and Route Preview

### Một câu mô tả

AccessRoute Desk giúp nhân viên có nhu cầu vận động xem trước đường đi, cửa, thang máy, bàn làm việc và điểm có thể cần hỗ trợ trước ngày đầu tới văn phòng.

### Luồng

```text
Floor plan + ảnh địa điểm + accessibility metadata
                         ↓
Route graph
                         ↓
Constraint-based route planner
                         ↓
Step-by-step preview + uncertainty + contact point
```

AI có thể trích xuất sơ bộ thông tin từ floor plan và ảnh, nhưng dữ liệu về độ dốc, chiều rộng cửa, mặt sàn và tình trạng thang máy phải được con người xác minh.

### MVP

Một tầng văn phòng mẫu, hai profile preference và một đường đi từ cổng tới bàn/phòng họp. Hiển thị rõ dữ kiện verified và unverified.

### Rủi ro

- cần dữ liệu địa điểm thật;
- thông tin cũ có thể gây nguy hiểm;
- indoor positioning khó;
- dễ mở scope sang bản đồ tổng quát.

Chỉ nên chọn nếu BTC/partner cung cấp site data hoặc end-user xác nhận đây là rào cản chính.

---

# 10. Hai ý tưởng cross-disability

## 10.1. AccessHandoff — Personal Accessibility Handoff

### Một câu mô tả

AccessHandoff giúp một người chuyển preference về cách làm việc thành bản hướng dẫn ngắn, cụ thể và có consent để chia sẻ cho recruiter, manager hoặc event organizer.

### Ví dụ

Người dùng không phải chia sẻ chẩn đoán. Họ có thể chọn:

- “Gửi agenda trước cuộc họp.”
- “Cho phép trả lời bằng chat song song.”
- “Tài liệu cần có heading và alt text.”
- “Tránh task yêu cầu drag; cung cấp nút thay thế.”
- “Cho thêm thời gian đọc trước khi yêu cầu phản hồi.”

AI chuyển preference thành request phù hợp với bối cảnh và tạo checklist cho bên tiếp nhận. Người dùng duyệt từng mục trước khi chia sẻ.

### Điểm mạnh

- hỗ trợ nhiều nhóm;
- privacy và consent có thể trở thành điểm nổi bật;
- employer adoption dễ giải thích;
- prototype nhanh.

### Điểm yếu

AI role không sâu và sản phẩm có thể bị coi là form/template. Chỉ nên ưu tiên nếu partner xác nhận handoff giữa applicant–HR–manager hiện là khoảng trống lớn.

## 10.2. JobPost Mirror — Inclusive Job Requirement Checker

### Một câu mô tả

JobPost Mirror đối chiếu job description với các nhiệm vụ thật, phát hiện yêu cầu có thể loại trừ không cần thiết và giúp recruiter tách “essential function” khỏi thói quen tuyển dụng.

### Ví dụ

- “Excellent verbal communication” có thật sự cần, hay mục tiêu là truyền đạt thông tin rõ bằng nhiều phương thức?
- “Must stand for long hours” có phải chức năng cốt lõi, hay công việc có thể thực hiện ở workstation phù hợp?
- Quy trình phỏng vấn có bắt buộc camera/eye contact dù không liên quan năng lực?

### Pipeline

```text
Job description + actual task list
                 ↓
Requirement extraction
                 ↓
Potential barrier classification
                 ↓
Clarification prompts cho recruiter
                 ↓
Human-approved inclusive rewrite
```

### Rủi ro

- AI không có quyền kết luận yêu cầu nào là bất hợp pháp;
- luật và bối cảnh thay đổi;
- rewrite chung chung rất dễ bị thay thế bởi Copilot/LLM;
- có thể trở thành compliance claim không đủ cơ sở.

Phải định vị là decision-support và education, không phải legal checker.

---

# 11. Những hướng không nên chọn nếu chưa có insight rất mạnh

## 11.1. Generic accessibility super-app

Một app vừa mô tả ảnh, caption, đọc văn bản, nhắc việc, dịch ký hiệu và tìm đường sẽ không làm tốt phần nào trong ba ngày. Nó cũng rất khó giải thích user journey.

## 11.2. Chatbot dành cho “mọi người neurodivergent”

Neurodivergence là một phổ rộng. Một chatbot với system prompt “hãy thân thiện với ADHD và autism” không phải user-centred design.

## 11.3. Interview coach

AI Speech Companion và NeuroAICC đã có vị trí rất mạnh trong lịch sử ADC. Chỉ chọn nếu brief bắt buộc và team có contribution hoàn toàn mới, không phải thêm câu hỏi hoặc chấm giọng nói.

## 11.4. Dịch ngôn ngữ ký hiệu tổng quát

HANDTALK và 7 Rings đã đi theo hướng này. Dataset VSL, continuous signing, non-manual marker và khác biệt vùng miền khiến việc tuyên bố “dịch thời gian thực” rất dễ vượt quá bằng chứng.

## 11.5. Nhận diện cảm xúc

SightSence và InSight đã khai thác tín hiệu xã hội cho người khiếm thị. Ngoài vấn đề trùng, emotion recognition có rủi ro bias và suy diễn trạng thái nội tâm từ biểu hiện bên ngoài.

## 11.6. AI CV screening cho người khuyết tật

Đây là vùng rủi ro cao: bias, dữ liệu nhạy cảm, phân biệt đối xử và yêu cầu pháp lý. Một prototype ba ngày khó chứng minh an toàn.

## 11.7. Medical diagnosis hoặc therapy claim

Không làm hệ thống chẩn đoán ADHD/autism, đo “mức độ tự kỷ”, chữa nói lắp hoặc thay chuyên gia. ADC nói về accessibility và employability, không phải cấp phép thiết bị y tế.

## 11.8. Hardware an toàn cao khi team không có chuyên môn

Phanh xe, cảnh báo cháy, điều khiển máy móc hoặc thiết bị đeo dẫn đường đòi hỏi safety engineering, fabrication và thử nghiệm mà team hiện không có lợi thế.

---

# 12. Cách dùng Codex như một lợi thế khi build

## 12.1. Nguyên tắc phối hợp

Anh không nên đưa một câu duy nhất kiểu “build app này” rồi chờ kết quả. Cách hiệu quả hơn là làm theo vòng lặp ngắn:

```text
Team đưa evidence và quyết định sản phẩm
                    ↓
Anh + Codex chốt contract và vertical slice
                    ↓
Codex triển khai một phần nhỏ có test
                    ↓
Anh review, chạy và thử bằng assistive technology
                    ↓
Linh/Phúc đưa feedback user + AI
                    ↓
Sửa scope hoặc implementation
```

Mỗi vòng nên tạo ra một thứ kiểm tra được trong 30–90 phút.

## 12.2. Codex có thể phụ trách những gì

### Repository và kiến trúc

- scaffold Next.js/React;
- tổ chức feature folder;
- định nghĩa TypeScript type và JSON Schema;
- adapter để đổi AI provider mà không phá UI;
- mock mode để demo không phụ thuộc mạng;
- environment validation;
- Docker khi thực sự có ích.

### Frontend accessible

- semantic heading và landmark;
- focus management;
- keyboard-only flow;
- live region cho tiến độ;
- skip link;
- accessible table;
- dialog/menu đúng pattern;
- reduced motion;
- contrast và responsive zoom;
- loading/error/empty state dễ hiểu.

### Backend và AI integration

- API route;
- schema validation;
- timeout, retry có giới hạn và cancellation;
- structured output;
- provenance/source span;
- rate limit;
- redaction;
- fallback response;
- log không chứa dữ liệu nhạy cảm.

### Evaluation

- tạo test fixture từ case do team duyệt;
- chạy batch evaluation;
- so sánh prompt/model;
- lưu output và failure category;
- test hallucination, latency và schema validity;
- accessibility regression bằng axe, Playwright và manual checklist.

### Pitch và handoff

- architecture diagram;
- README;
- demo script;
- judge Q&A bank;
- limitation và responsible-AI slide;
- checklist trước khi quay video;
- backup demo data.

## 12.3. Những gì team phải giữ quyền quyết định

- lời nào được coi là user insight;
- có được lưu hoặc gửi interview data tới AI hay không;
- scope cuối cùng;
- trade-off ảnh hưởng người dùng;
- claim về impact;
- nội dung pitch;
- quyết định sử dụng thư viện, model và dữ liệu có license phù hợp;
- xác nhận sản phẩm là original work của team.

## 12.4. Quy tắc dữ liệu khi làm việc với Codex và AI service

- Không paste tên, email, số điện thoại hoặc chẩn đoán của người phỏng vấn nếu chưa được phép.
- Ẩn danh transcript trước khi phân tích.
- Không upload tài liệu công ty thật nếu không có quyền.
- Dùng fixture giả lập có cấu trúc tương tự cho development.
- Ghi rõ third-party model, dataset và dependency trong README.
- Review mọi claim do AI soạn trước khi đưa vào deck.

## 12.5. Nhịp build đề xuất trong 72 giờ

### Sau khi chốt problem

Anh gửi cho Codex:

```text
User:
Workplace moment:
Barrier:
Current workaround:
Evidence:
One-sentence solution:
Must-have flow:
AI input/output:
Failure behavior:
```

### Vertical slice đầu tiên

Ưu tiên đường đi ngắn nhất:

```text
Một input thật → một AI call hoặc mock → một output accessible → một action
```

Không làm auth, dashboard quản trị, animation hoặc database trước vertical slice.

### Sau vertical slice

1. Phúc thay mock bằng model/API và chạy evaluation.
2. Anh cùng Codex làm error/fallback và accessibility.
3. Linh test story, wording và user flow.
4. Team đưa prototype cho end-user/mentor.
5. Chỉ giữ feature hỗ trợ trực tiếp cho claim trong pitch.

---

# 13. Kiến trúc nền nên chuẩn bị trước

Không code sẵn solution trước brief, nhưng có thể chuẩn bị cách tổ chức để giảm thời gian.

## 13.1. Kiến trúc mặc định

```text
Next.js / TypeScript
        ↓
Accessible application UI
        ↓
Server route / Node application layer
        ↓
Input validation + redaction
        ↓
AI provider adapter
        ↓
Structured JSON output
        ↓
Schema validation + deterministic post-processing
        ↓
Accessible presentation + source evidence + fallback
```

Python/FastAPI chỉ thêm khi cần:

- OpenCV;
- local computer-vision model;
- audio processing;
- model chỉ có ecosystem Python;
- batch evaluation dùng thư viện ML.

## 13.2. Nguyên tắc contract-first

Anh và Phúc thống nhất schema trước khi chọn model. Ví dụ:

```json
{
  "status": "supported | uncertain | unsupported",
  "summary": "string",
  "items": [],
  "evidence": [],
  "warnings": [],
  "modelMetadata": {
    "provider": "string",
    "latencyMs": 0
  }
}
```

Nhờ vậy:

- Anh build UI bằng mock data;
- Phúc thay model mà không phá frontend;
- Codex viết test schema và adapter độc lập;
- fallback có cùng contract với AI response.

## 13.3. Ba mode bắt buộc

Mọi prototype nên có:

1. **Live mode:** gọi model/API thật.
2. **Fixture mode:** dùng case đã lưu để demo ổn định.
3. **Failure mode:** cố tình cho thấy sản phẩm phản ứng thế nào khi AI timeout hoặc không chắc.

Failure mode là một phần của responsible AI demo, không phải điều cần giấu.

## 13.4. Không over-engineer

Trong ba ngày, thường không cần:

- microservices;
- Kubernetes;
- message queue;
- Redis;
- multi-region deployment;
- custom auth;
- train model từ đầu;
- vector database nếu chỉ có vài tài liệu.

Kỹ thuật sâu nên nằm ở accessibility, data contract, evaluation và failure handling — những phần giám khảo và người dùng thực sự cảm nhận được.

---

# 14. Quy trình chọn một ý tưởng sau khi nhận brief

## Gate 1 — Brief fit, 15 phút

Với mỗi ý tưởng, trả lời:

- có đúng disability area được giao không;
- có đúng employability/workplace không;
- có giải quyết brief hay chỉ gần chủ đề;
- có vi phạm constraint nào không.

Sai một điều cốt lõi thì loại ngay.

## Gate 2 — Evidence, 45–90 phút

Viết ba cột:

| Assumption | Evidence hiện có | Cần hỏi ai/câu gì |
|---|---|---|
| Người dùng gặp vấn đề này thường xuyên | Chưa có | Hỏi về lần gần nhất xảy ra |
| Workaround hiện tại tốn thời gian | Chưa có | Hỏi từng bước cách họ đang làm |
| Output dạng audio hữu ích | Chưa có | So sánh audio, text và structure |

Không có evidence thì chưa gọi đó là insight.

## Gate 3 — Existing alternative, 30 phút

Tìm ít nhất ba alternative:

- công cụ trực tiếp;
- workaround thủ công;
- chức năng trong nền tảng lớn;
- cách người dùng bỏ qua vấn đề.

Điểm khác biệt phải là một câu cụ thể, không dùng từ “AI-powered”, “all-in-one” hoặc “more personalized”.

## Gate 4 — Vertical slice, 20 phút

Viết demo thành tối đa sáu hành động. Nếu cần hơn, scope có khả năng quá rộng.

## Gate 5 — Risk, 20 phút

Chọn ba failure có hậu quả lớn nhất và thiết kế hành vi sản phẩm cho từng failure trước khi code.

## Gate 6 — Vote có điều kiện

Mỗi người chấm độc lập theo bảng 100 điểm. Sau đó thảo luận **lý do chênh điểm**, không tranh luận tên ý tưởng nào nghe hay hơn.

---

# 15. Bộ câu hỏi phỏng vấn end-user

Không hỏi “Anh/chị có thích ý tưởng này không?”. Hỏi về việc thật đã xảy ra.

## 15.1. Câu hỏi mở đầu

1. Anh/chị có thể kể lần gần nhất gặp khó khăn này trong công việc không?
2. Khi đó anh/chị đang muốn hoàn thành việc gì?
3. Bước nào làm anh/chị mất nhiều công sức nhất?
4. Anh/chị đã xử lý bằng cách nào?
5. Có phải nhờ người khác không? Việc đó có bất tiện ở điểm nào?

## 15.2. Câu hỏi về input và output

1. Anh/chị thường nhận thông tin ở dạng nào?
2. Dạng text, audio, bảng, từng bước hay kết hợp sẽ hữu ích hơn?
3. Anh/chị muốn nghe overview trước hay chi tiết trước?
4. Thông tin nào là bắt buộc, thông tin nào gây nhiễu?
5. Anh/chị đang dùng screen reader, zoom, caption, switch hoặc công cụ nào?

## 15.3. Câu hỏi về AI và lỗi

1. Nếu hệ thống sai ở đây, hậu quả thực tế là gì?
2. Dấu hiệu nào giúp anh/chị biết output đáng tin hay không?
3. Anh/chị muốn xem nguồn hoặc xác nhận bước nào?
4. Trường hợp nào AI nên dừng và yêu cầu con người?
5. Dữ liệu nào anh/chị không muốn hệ thống lưu hoặc gửi lên cloud?

## 15.4. Câu hỏi về adoption

1. Ai ngoài anh/chị phải tham gia thì giải pháp mới hoạt động?
2. Employer/manager có cần thay đổi quy trình không?
3. Cài đặt hoặc xin quyền gì sẽ là rào cản?
4. Sản phẩm phải tích hợp với công cụ nào?
5. Điều gì khiến anh/chị bỏ dùng sau một tuần?

## 15.5. Câu hỏi kết thúc

1. Trong những điều vừa nói, phần nào team đang hiểu sai?
2. Nếu chỉ giải quyết được một bước, anh/chị sẽ chọn bước nào?
3. Có ai khác hoặc vai trò nào team nên nói chuyện cùng không?

---

# 16. Cách chứng minh từng tiêu chí chấm

## 16.1. Innovation & Impact

Không nói:

> “Chúng tôi dùng AI tiên tiến để tạo tác động lớn.”

Nên đưa ra:

- một workplace moment;
- current workaround;
- khoảng trống của công cụ hiện có;
- thay đổi trước/sau;
- một outcome có thể đo;
- lý do solution khác bài cũ.

## 16.2. User-Centred Design & Accessibility

Cần có ít nhất:

- một insight có dẫn chứng;
- một giả định bị bác bỏ;
- một thay đổi thiết kế do người dùng;
- một accessibility test thật;
- một preference hoặc control do người dùng quyết định.

Ví dụ slide mạnh:

```text
Ban đầu team định dùng audio-only.
End-user cho biết audio cạnh tranh với giọng người trong meeting.
Team đổi sang structured text + on-demand speech.
Sau thay đổi, task completion nhanh hơn trong test mẫu.
```

## 16.3. Feasibility & Practicality

Chứng minh bằng:

- architecture đơn giản;
- latency đo thật;
- chi phí mỗi lượt dùng ước tính;
- data flow;
- privacy choice;
- integration point;
- roadmap 30/90/180 ngày;
- partner hoặc adopter hợp lý.

## 16.4. Use of AI

Slide AI cần trả lời:

1. Input là gì?
2. Model làm nhiệm vụ gì?
3. Vì sao rule thường không đủ?
4. Output schema là gì?
5. Team test bằng bao nhiêu case?
6. Model sai ở nhóm nào?
7. UI xử lý uncertainty ra sao?
8. Dữ liệu có được lưu không?

NIST khuyến nghị human oversight, tracking, documentation và risk management phù hợp với bối cảnh khi dùng generative AI. Nguồn: [NIST — Generative AI Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence).

## 16.5. Presentation & Communication

Một pitch tốt nên đi theo trật tự:

```text
Người thật / khoảnh khắc thật
        ↓
Rào cản và workaround
        ↓
Điều team học được
        ↓
Demo một luồng
        ↓
AI, safeguard và evidence
        ↓
Impact, feasibility và lời kết
```

Không mở đầu bằng architecture diagram. Giám khảo phải hiểu vì sao sản phẩm cần tồn tại trước khi họ quan tâm model nào đứng sau.

---

# 17. Nguồn và prior art cần đọc

## Cuộc thi

- [RMIT — ADC Hackathon 2026](https://industryhub.rmit.edu.vn/ADC/)
- [Các dự án đoạt giải ADC qua các năm](./ADC_Past_Winners_Technical_Review.md)

## Accessibility nền tảng

- [W3C — Accessibility Principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/)
- [W3C — Visual disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/visual/)
- [W3C — Auditory disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/auditory/)
- [W3C — Cognitive and learning disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/cognitive/)
- [W3C — Physical disabilities and barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/physical/)
- [W3C — Complex Images](https://www.w3.org/WAI/tutorials/images/complex/)
- [W3C — Tables Tutorial](https://www.w3.org/WAI/tutorials/tables/)
- [W3C — Media Accessibility User Requirements](https://www.w3.org/TR/media-accessibility-reqs/)
- [W3C — Description of Visual Information](https://www.w3.org/WAI/media/av/description/)
- [W3C — Cognitive Accessibility](https://www.w3.org/WAI/cognitive/)
- [W3C — What is new in WCAG 2.2](https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22/)

## Research và sản phẩm để tránh làm clone

- [Microsoft Research — Accessibility in Hybrid Meetings](https://www.microsoft.com/en-us/research/publication/accessibility-barriers-conflicts-and-repairs-understanding-the-experience-of-professionals-with-disabilities-in-hybrid-meetings/)
- [Microsoft Research — Neurodivergent Professionals and Remote Work](https://www.microsoft.com/en-us/research/wp-content/uploads/2021/01/ND_CSCW21-MSR-copy-accessible.pdf)
- [Microsoft Research — Chart Reader](https://www.microsoft.com/en-us/research/uploads/prod/2023/04/ChartReader-CHI2023.pdf)
- [MIT — Umwelt, multimodal accessible chart authoring](https://news.mit.edu/2024/umwelt-enables-interactive-accessible-charts-creation-blind-low-vision-users-0327)
- [SeeChart — Interactive natural-language chart access](https://arxiv.org/abs/2302.07742)
- [Rich Screen Reader Experiences for Accessible Data Visualization](https://arxiv.org/abs/2205.04917)
- [Microsoft Teams — Intelligent Recap](https://support.microsoft.com/en-US/teams/meetings/recap-in-microsoft-teams)
- [Google — Voice Access Commands](https://support.google.com/accessibility/android/answer/6151854?hl=en)
- [Goblin Tools](https://goblin.tools/)
- [NIST — AI Risk Management Framework](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10)

---

## Lời nhắc cuối cho team

Danh mục này cho chúng ta điểm xuất phát tốt hơn, không cho chúng ta quyền bỏ qua discovery. Mục tiêu không phải chọn ý tưởng nghe “AI nhất”. Mục tiêu là tìm được một rào cản đủ thật, đủ hẹp và đủ quan trọng để ba người có thể:

1. hiểu nó sâu hơn đối thủ;
2. chứng minh một thay đổi thiết kế từ end-user evidence;
3. build một vertical slice accessible và ổn định;
4. đo được AI thay vì chỉ trình diễn;
5. kể một câu chuyện mà giám khảo nhớ được sau khi xem nhiều đội.

Nếu làm đúng, lợi thế của team không nằm ở số lượng feature. Lợi thế là **Linh giữ problem và pitch, Phúc giữ chất lượng AI, Anh cùng Codex biến cả hai thành một sản phẩm chạy chắc, có test và dùng được bởi chính target user**.
