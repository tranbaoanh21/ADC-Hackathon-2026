# ADC Hackathon 2026 — Handbook chuẩn bị thi dành cho team Software × Business × Applied AI

> **Mục tiêu của tài liệu:** giúp team hiểu đúng bản chất ADC Hackathon 2026, biết cuộc thi thực sự chấm gì, AI/ML và software cần sâu đến đâu, nên chọn teammate và sản phẩm như thế nào, và có một playbook thực chiến từ trước ngày thi đến vòng Finale.
>
> **Cách ghi thuật ngữ:** các thuật ngữ tiếng Anh quan trọng sẽ đi kèm **(chú thích tiếng Việt)** ngay bên cạnh.

---

## Mục lục

1. [Executive Summary — Tóm tắt quan trọng nhất](#1-executive-summary--tóm-tắt-quan-trọng-nhất)
2. [ADC 2026 thực chất là cuộc thi gì?](#2-adc-2026-thực-chất-là-cuộc-thi-gì)
3. [Thông tin chính thức và timeline](#3-thông-tin-chính-thức-và-timeline)
4. [Có cần proposal trước cuộc thi không?](#4-có-cần-proposal-trước-cuộc-thi-không)
5. [Bốn nhóm disability mà ADC 2026 tập trung](#5-bốn-nhóm-disability-mà-adc-2026-tập-trung)
6. [Ba nhóm solution được chấp nhận](#6-ba-nhóm-solution-được-chấp-nhận)
7. [Năm tiêu chí chấm và cách hiểu thực chiến](#7-năm-tiêu-chí-chấm-và-cách-hiểu-thực-chiến)
8. [AI/ML có cần sâu không?](#8-aiml-có-cần-sâu-không)
9. [Software có cần sâu không?](#9-software-có-cần-sâu-không)
10. [Hardware có lợi thế hơn software không?](#10-hardware-có-lợi-thế-hơn-software-không)
11. [Bài học từ các đội mạnh ADC 2024–2025](#11-bài-học-từ-các-đội-mạnh-adc-20242025)
12. [Team composition phù hợp với team hiện tại](#12-team-composition-phù-hợp-với-team-hiện-tại)
13. [Người thứ ba nên là Applied AI teammate như thế nào?](#13-người-thứ-ba-nên-là-applied-ai-teammate-như-thế-nào)
14. [Cách chọn problem và product](#14-cách-chọn-problem-và-product)
15. [Các hướng sản phẩm phù hợp với software + AI](#15-các-hướng-sản-phẩm-phù-hợp-với-software--ai)
16. [Kiến trúc technical nên dùng cho hackathon](#16-kiến-trúc-technical-nên-dùng-cho-hackathon)
17. [Accessibility cho web/app cần biết gì?](#17-accessibility-cho-webapp-cần-biết-gì)
18. [Playbook Day 1 → Day 3](#18-playbook-day-1--day-3)
19. [Pitch Deck, Video và Prototype nên chuẩn bị thế nào?](#19-pitch-deck-video-và-prototype-nên-chuẩn-bị-thế-nào)
20. [Các bẫy dễ khiến team mất điểm](#20-các-bẫy-dễ-khiến-team-mất-điểm)
21. [Kế hoạch chuẩn bị trước Hackathon](#21-kế-hoạch-chuẩn-bị-trước-hackathon)
22. [Checklist nhanh cho team](#22-checklist-nhanh-cho-team)
23. [Glossary — Thuật ngữ quan trọng](#23-glossary--thuật-ngữ-quan-trọng)
24. [Nguồn tham khảo](#24-nguồn-tham-khảo)

---

# 1. Executive Summary — Tóm tắt quan trọng nhất

## ADC 2026 không phải cuộc thi Machine Learning thuần

ADC là **Accessibility Design Competition (Cuộc thi Thiết kế Tiếp cận)**. Format năm 2026 là một **3-day innovation hackathon (hackathon đổi mới sáng tạo trong 3 ngày)** tập trung vào:

- **Accessibility (khả năng tiếp cận)**
- **Inclusion (sự hòa nhập)**
- **Employability (khả năng tham gia, duy trì và phát triển trong việc làm)**
- **AI — Artificial Intelligence (Trí tuệ nhân tạo)**

Bản chất cuộc thi gần với:

> **Product/Innovation Hackathon (hackathon sản phẩm/đổi mới)** cho bài toán người khuyết tật trong môi trường làm việc, trong đó AI là một công cụ quan trọng.

Nó **không phải**:

- Kaggle competition
- cuộc thi accuracy model
- cuộc thi research AI
- cuộc thi robotics bắt buộc hardware
- cuộc thi software architecture production

## Công thức tư duy nên nhớ

```text
USER
(người dùng)
   ↓
WORKPLACE CONTEXT
(bối cảnh làm việc)
   ↓
BARRIER / PAIN POINT
(rào cản / nỗi đau thực tế)
   ↓
USER INSIGHT
(hiểu biết rút ra từ người dùng)
   ↓
SOLUTION
(giải pháp)
   ↓
WHY AI?
(tại sao cần AI?)
   ↓
PROTOTYPE
(nguyên mẫu chạy được)
   ↓
VALIDATION
(kiểm chứng)
   ↓
IMPACT
(tác động)
   ↓
PITCH
(thuyết trình)
```

**Không nên đảo ngược thành:**

```text
YOLO / LLM / RAG / STM32
          ↓
"Giờ kiếm problem nào để nhét công nghệ này vào?"
```

## Team hiện tại phù hợp với ADC

Cấu hình team hiện tại:

### Member 1 — Software / HCMUT

Vai trò phù hợp:

**Software / AI Integration Engineer (Kỹ sư phần mềm và tích hợp AI)**

Có thể phụ trách:

- frontend
- backend
- database
- API integration
- system architecture ở mức hackathon
- build prototype
- deploy demo
- nối application với AI service/model

### Member 2 — Business / Product / Pitch / FTU2

Vai trò phù hợp:

**Product / Business / Pitch Lead (phụ trách sản phẩm, business và thuyết trình)**

Có thể phụ trách:

- research
- tìm insight
- problem framing
- phát triển direction
- feasibility/business thinking
- deck
- storytelling
- pitch
- Q&A
- hỗ trợ user research và accessibility research

### Member 3 nên tìm

Ưu tiên:

**Applied AI / ML Engineer hoặc AI Prototyper  
(Kỹ sư AI ứng dụng / người tạo prototype AI nhanh)**

Không cần AI researcher.

Nên có:

- base Python + AI/ML
- biết dùng AI API hoặc pretrained model
- có khả năng thử model nhanh và đưa vào prototype
- Computer Vision / NLP / Speech / Multimodal là điểm cộng
- từng làm project AI thực tế là lợi thế

## Kết luận technical

### ML research sâu?

**Không bắt buộc.**

### AI integration?

**Rất phù hợp.**

### Software?

**Cần đủ tốt để làm end-to-end working prototype (nguyên mẫu chạy xuyên suốt quy trình).**

### Production cloud / Kubernetes / scaling?

**Không phải ưu tiên.**

### Hardware?

**Không bắt buộc.**

### User understanding + accessibility?

**Bắt buộc phải coi trọng.**

---

# 2. ADC 2026 thực chất là cuộc thi gì?

Trang chính thức mô tả ADC là cuộc thi thường niên nhằm tạo ra các giải pháp sáng tạo cho **more inclusive workplaces (môi trường làm việc hòa nhập hơn)**.

Năm 2026, ADC chuyển sang format hackathon 3 ngày. Các team phải:

1. hiểu **real challenges (thách thức thực tế)**
2. phát triển **inclusive solutions (giải pháp hòa nhập)**
3. test ideas **(kiểm thử ý tưởng)**
4. pitch to judges **(thuyết trình trước ban giám khảo)**

Theme năm 2026 là:

> **AI & Employability (AI và khả năng tham gia/phát triển trong việc làm)**

Điều này cho thấy hai từ khóa phải luôn đi cùng nhau:

```text
AI
+
WORKPLACE / EMPLOYABILITY
+
DISABILITY / ACCESSIBILITY
```

Một project AI rất hay nhưng không liên quan rõ tới **employment/workplace accessibility (khả năng tiếp cận trong việc làm/nơi làm việc)** sẽ lệch trọng tâm.

---

# 3. Thông tin chính thức và timeline

## Điều kiện tham gia

- Sinh viên bậc đại học/cao đẳng trở lên, từ 18 tuổi.
- Hoặc **early-career professional (người mới bắt đầu sự nghiệp)** tốt nghiệp từ năm 2024 trở về sau.
- Mỗi team **đúng 3 thành viên**.
- Ít nhất **1 thành viên phải là sinh viên hiện tại**.
- Không nhận đăng ký cá nhân.
- Có thể lập **cross-university team (team liên trường)**.
- Có thể lập **cross-discipline team (team liên ngành)**.
- Không thu phí tham dự.

## Các mốc chính

| Mốc | Thời gian | Ý nghĩa |
|---|---:|---|
| Registration Deadline (hạn đăng ký) | **13/09/2026** | Chốt team 3 người và nộp form |
| Shortlist Notification (thông báo team được chọn) | **chậm nhất 16/09/2026** | BTC thông báo các team được tham dự |
| Online Briefing (briefing trực tuyến) | **19/09/2026** | Phổ biến trước hackathon |
| Hackathon Day 1 | **21/09/2026** | Competition brief được công bố |
| Hackathon Day 2 | **22/09/2026** | User/mentor/technical feedback |
| Hackathon Day 3 | **23/09/2026** | Submission + Top 8 Finale |

Địa điểm:

**RMIT Saigon South Campus, 702 Nguyễn Văn Linh, TP.HCM.**

---

# 4. Có cần proposal trước cuộc thi không?

## Không có yêu cầu nộp proposal trong form đăng ký công khai

Form registration hiện yêu cầu chuẩn bị:

- thông tin cá nhân của 3 thành viên
- student/graduate status
- trường và ngành
- thông tin có ở TP.HCM trong thời gian diễn ra cuộc thi hay không
- accessibility/event support needs nếu có
- **2 câu motivation**

Hai câu motivation:

1. **Why does your team want to join ADC Hackathon 2026?**  
   *(Tại sao team muốn tham gia ADC 2026?)*  
   **100–120 words**

2. **What does your team hope to learn or gain from this hackathon?**  
   *(Team mong muốn học hỏi/nhận được gì từ hackathon?)*  
   **80–100 words**

Không thấy yêu cầu công khai về:

- proposal
- product idea
- technical architecture
- prototype
- business model
- dataset
- AI model
- pitch deck ở vòng đăng ký

## Khi nào mới nhận đề?

Agenda chính thức ghi:

### Day 1 — Morning

> **Competition brief release (công bố đề/brief chính thức)**

Vì vậy về chiến thuật:

### Trước 21/09 nên chuẩn bị

- team
- skill
- workflow
- accessibility fundamentals
- rapid prototyping
- AI toolbox
- coding starter
- pitch/storytelling
- problem spaces

### Không nên khóa chết

- một product cụ thể
- một disability cụ thể
- một loại hardware cụ thể
- một model cụ thể

## Tư duy đúng trước cuộc thi

Không chuẩn bị:

> “Chúng ta chắc chắn sẽ làm smart glasses.”

Nên chuẩn bị:

> “Nếu brief cần vision, team biết dùng multimodal model/CV.  
> Nếu cần speech, biết pipeline STT/LLM.  
> Nếu cần workflow app, biết build React/Node nhanh.”

Tức là chuẩn bị **capability (năng lực)** thay vì chuẩn bị một solution đóng đinh.

---

# 5. Bốn nhóm disability mà ADC 2026 tập trung

ADC 2026 nêu bốn nhóm chính.

> **Lưu ý:** các ví dụ dưới đây là problem space để brainstorm, không được xem là giả định rằng mọi người trong cùng một nhóm disability có nhu cầu giống nhau. Team cần validate với end-user.

---

## 5.1 Visual Impairment (khiếm thị / suy giảm thị lực)

Workplace barriers có thể gồm:

- dashboard/chart khó tiếp cận
- slide chứa nhiều hình ảnh
- camera/screen-sharing content không được mô tả
- UI không tương thích screen reader
- thông tin phụ thuộc màu sắc
- physical navigation trong workplace
- biểu đồ/tài liệu scan thiếu text alternative

### Công nghệ có thể dùng

- **Computer Vision (thị giác máy tính)**
- **OCR — Optical Character Recognition (nhận dạng ký tự từ hình ảnh)**
- **Multimodal AI (AI đa phương thức: xử lý text + hình + audio...)**
- **Text-to-Speech — TTS (chuyển văn bản thành giọng nói)**
- screen reader compatible UI

### Ví dụ product direction

```text
Shared dashboard
      ↓
Screenshot
      ↓
Vision model
      ↓
Chart understanding
      ↓
Structured accessible explanation
      ↓
Screen reader / audio
```

---

## 5.2 Deaf or Hard of Hearing (người điếc hoặc suy giảm thính lực)

Workplace barriers có thể gồm:

- meeting tốc độ nhanh
- caption chưa đủ context
- khó xác định speaker
- âm thanh notification
- các cuộc trao đổi spontaneous
- video/training không có caption tốt

### Công nghệ có thể dùng

- **Speech-to-Text — STT (chuyển giọng nói thành văn bản)**
- **Speaker Diarization (phân tách/xác định các lượt người nói)**
- **NLP — Natural Language Processing (xử lý ngôn ngữ tự nhiên)**
- summarization
- sign-language related CV nếu thật sự khả thi

### Một cách nghĩ tốt hơn transcript đơn thuần

```text
Meeting audio
      ↓
STT
      ↓
Speaker context
      ↓
AI detects:
- question
- decision
- action item
- topic change
      ↓
Accessible meeting interface
```

---

## 5.3 Mobility Impairment (khuyết tật vận động)

Workplace barriers có thể gồm:

- thao tác chuột/bàn phím
- hand dexterity limitations
- workstation không phù hợp
- physical controls
- di chuyển
- thiết bị không thể điều khiển bằng input thay thế

### Công nghệ có thể dùng

- **Embedded Systems (hệ thống nhúng)**
- sensor
- adaptive controller
- voice control
- gesture control
- switch input
- mechanical assistive product
- AI personalization

Đây là nhóm mà Mechanical / Mechatronics / Electronics có lợi thế rõ hơn nếu team chọn physical product.

---

## 5.4 Neurodivergence (đa dạng thần kinh)

Có thể liên quan tới autism, ADHD và nhiều profile khác nhau.

Không được giả định:

> “Người neurodivergent đều cần một kiểu giao diện.”

Nên research cụ thể.

Potential workplace barriers:

- instruction mơ hồ
- overload thông tin
- unclear expectation
- task prioritization
- context switching
- interview communication
- sensory load
- communication structure

### Công nghệ phù hợp với software-first team

- LLM
- structured task assistant
- communication clarification
- personalized interface
- interview preparation
- cognitive accessibility features

Ví dụ:

```text
Manager message
      ↓
AI interpretation
      ↓
Goal
Definition of Done
Priority
Deadline
Dependencies
Questions to clarify
```

---

# 6. Ba nhóm solution được chấp nhận

Trang 2026 công bố ba nhóm.

---

## 6.1 Attitudinal & Communication Solutions  
*(Giải pháp về thái độ, chính sách và giao tiếp)*

Ví dụ:

- inclusive hiring practice
- wellbeing check-in
- communication workflow
- corporate tools
- workplace processes

Điểm quan trọng:

**ADC không chỉ nhận sản phẩm vật lý.**

Một quy trình hoặc công cụ digital được thiết kế tốt vẫn hợp lệ.

---

## 6.2 Architectural & Industrial Solutions  
*(Giải pháp kiến trúc và sản phẩm công nghiệp)*

Ví dụ:

- adaptive workstation
- accessible signage
- wayfinding
- assistive device
- physical workplace redesign

Phù hợp với:

- Mechanical Engineering
- Industrial Design
- Mechatronics
- Electronics

---

## 6.3 Technological Solutions  
*(Giải pháp công nghệ)*

Ví dụ chính thức:

- **AI-powered assistive tools (công cụ hỗ trợ có AI)**
- **accessible remote/hybrid platforms (nền tảng làm việc từ xa/hybrid dễ tiếp cận)**

Đây là vùng phù hợp nhất với team Software + Business + Applied AI.

---

# 7. Năm tiêu chí chấm và cách hiểu thực chiến

ADC 2026 công bố 5 tiêu chí.

---

## 7.1 Innovation & Impact  
*(Tính đổi mới và tác động)*

Official meaning:

> Solution có tính mới và tạo tác động đến bài toán accessibility/employability như thế nào?

### Judge có thể quan tâm

- barrier có thật không?
- barrier có đủ đáng giải quyết không?
- solution khác gì hiện có?
- improvement cho user là gì?
- tác động có đo được không?

### Innovation không đồng nghĩa với phát minh model mới

Một solution vẫn có thể innovative nếu:

```text
Existing AI
+
specific overlooked problem
+
better workflow
+
good accessibility design
=
valuable innovation
```

### Câu hỏi team nên tự hỏi

> Nếu bỏ hết buzzword AI, solution này còn giải được một vấn đề đáng kể không?

---

## 7.2 User-Centred Design & Accessibility  
*(Thiết kế lấy người dùng làm trung tâm và khả năng tiếp cận)*

Đây là tiêu chí rất quan trọng.

### User-Centred Design là gì?

Đừng bắt đầu:

> “Tụi mình nghĩ người dùng chắc cần X.”

Hãy có evidence:

```text
Interview / end-user conversation
          ↓
Observation
          ↓
Pain point
          ↓
Assumption
          ↓
Validation
          ↓
Design decision
```

### “Nothing about us without us”

Bài học từ team NeuroAICC 2025:

> Product cho cộng đồng disability nên được xây dựng **cùng** cộng đồng, không chỉ xây **cho** họ.

### Evidence có thể đưa vào pitch

- “3/4 users nói X là pain point lớn hơn Y.”
- “Ban đầu team nghĩ A, sau fireside chat chúng tôi đổi sang B.”
- “User testing cho thấy bước này gây cognitive load nên chúng tôi rút xuống 2 clicks.”

Đây là thứ tạo credibility (độ tin cậy).

---

## 7.3 Feasibility & Practicality  
*(Tính khả thi và tính thực tiễn)*

Judge không chỉ muốn ý tưởng “wow”.

Họ muốn:

> Có triển khai thật được không?

### Feasibility gồm

- technical feasibility
- cost
- hardware availability
- latency
- API limitation
- privacy
- deployment
- user adoption
- workplace integration

### Ví dụ pitch yếu

> “AI sẽ hiểu mọi thứ xung quanh user với 100% accuracy.”

### Pitch tốt hơn

> “Prototype dùng smartphone camera và multimodal API. Các tình huống uncertainty (AI không chắc chắn) sẽ được đánh dấu thay vì khẳng định chắc chắn.”

---

## 7.4 Use of AI  
*(Cách sử dụng AI)*

Officially, AI được đánh giá theo:

- **effectively (hiệu quả)**
- **appropriately (phù hợp)**
- **responsibly (có trách nhiệm)**

Website còn nhấn mạnh AI phải:

- responsible
- ethical
- meaningful

### Ba câu hỏi phải trả lời được

1. **Why AI? (Tại sao cần AI?)**
2. **Why this AI? (Tại sao chọn loại/model AI này?)**
3. **What can go wrong? (AI có thể sai ở đâu và team giảm rủi ro thế nào?)**

### AI meaningful

AI nên xử lý task như:

- unstructured text understanding
- visual understanding
- speech processing
- pattern recognition
- personalization
- summarization
- classification
- context extraction

### AI không meaningful

Dùng LLM chỉ để:

> “Powered by AI”

trong khi một rule-based function đơn giản đã đủ.

---

## 7.5 Presentation & Communication  
*(Trình bày và giao tiếp — chỉ áp dụng Finale)*

Chỉ được ghi rõ cho **Finale**.

Judge xem:

- problem có rõ không
- story có thuyết phục không
- demo có dễ hiểu không
- team có trả lời Q&A tốt không
- argument có logic không

Đây là vùng Member 2 FTU có thể tạo lợi thế lớn.

---

# 8. AI/ML có cần sâu không?

## Ba level AI có thể thấy trong hackathon

### Level 1 — AI API / Pretrained Model  
*(API AI / model đã train sẵn)*

Ví dụ:

- Gemini/OpenAI multimodal
- Hugging Face pretrained model
- STT service
- TTS service
- object detection pretrained model

**Hoàn toàn phù hợp.**

---

### Level 2 — Applied AI Engineering  
*(Kỹ thuật AI ứng dụng)*

Ví dụ:

- RAG pipeline
- embeddings
- CV pipeline
- STT → NLP → output workflow
- multimodal orchestration
- lightweight fine-tuning nếu có lý do

**Rất phù hợp với ADC.**

---

### Level 3 — ML Research / Custom Training  
*(Nghiên cứu ML / tự huấn luyện model)*

Ví dụ:

- collect dataset lớn
- train CNN/Transformer from scratch
- optimize architecture
- research model mới

**Chỉ nên dùng nếu problem thật sự đòi hỏi.**

Trong 3 ngày, level này có risk cao.

---

## Applied AI > AI research đối với team hiện tại

Một teammate hackathon rất hữu ích là người có thể làm:

```text
Problem
  ↓
"Need visual recognition"
  ↓
Find suitable model/API
  ↓
Test with sample input
  ↓
Wrap inference
  ↓
Expose API
  ↓
Integrate into product
```

Không nhất thiết cần:

```text
New neural architecture
+
custom dataset
+
long training
+
research paper
```

---

# 9. Software có cần sâu không?

## Cần ở mức product engineering, không cần production infrastructure sâu

Software của team cần làm được:

```text
User
 ↓
Accessible UI
 ↓
Backend
 ↓
AI / Data / Device
 ↓
Useful result
```

## Nên ưu tiên

- stable demo
- clean user flow
- accessibility
- API integration
- error handling cơ bản
- responsive UI
- meaningful state
- low friction
- demo data fallback nếu external API fail

## Không phải ưu tiên

- Kubernetes
- microservice architecture chỉ để khoe
- complex event streaming
- multi-region deployment
- production autoscaling
- elaborate observability stack
- heavy CI/CD

### Lý do

Hackathon chỉ có 3 ngày.

Mỗi giờ dành cho infrastructure không tạo user value là một giờ không dành cho:

- problem
- validation
- prototype
- pitch
- testing

---

# 10. Hardware có lợi thế hơn software không?

## Không có tiêu chí chính thức cộng điểm cho hardware

ADC cho phép cả:

- communication/process
- physical/industrial
- technological/software

Lịch sử cuộc thi cũng cho thấy cả software lẫn hardware đều thắng/top cao.

## Vì sao hardware thường trông “wow”?

Demo:

```text
User presses / wears / moves
       ↓
Sensor detects
       ↓
Device responds
```

Judge thấy tác động vật lý ngay.

## Nhưng hardware có risk

- sensor fail
- firmware bug
- wiring
- battery
- mechanical fabrication
- 3D printing
- integration
- transport
- calibration

## Software cũng phải là “sản phẩm thật”

Một software prototype tốt không phải:

```text
Figma only
+
slide
+
chatbot mockup
```

Mà là:

```text
Real user action
      ↓
Real processing
      ↓
AI/model/API
      ↓
Accessible output
      ↓
User finishes workplace task
```

Nếu demo được end-to-end, software là một product prototype hoàn toàn hợp lệ.

---

# 11. Bài học từ các đội mạnh ADC 2024–2025

Lịch sử ADC là bằng chứng rõ nhất rằng không tồn tại một “tech stack bắt buộc”.

---

## ADC 2024 — Champion: The Great Musica

Solution:

- website thư viện nhạc cho người mù/khiếm thị
- Vietnamese music score in Braille
- chuyển standard music sheet sang dạng tiếp cận được

### Bài học

Quán quân không cần robot hay hardware.

**Website vẫn thắng** nếu:

- user need rõ
- accessibility rất cụ thể
- product có tác động
- technology phục vụ user

---

## ADC 2024 — Runner-up: Lexopia

Team gồm ba sinh viên Business.

Solution:

- ứng dụng hỗ trợ người dyslexia (chứng khó đọc) trong workplace
- dùng Microsoft Azure AI/Copilot
- hỗ trợ reading/writing comprehension

### Bài học

Ngay cả team Business cũng có thể dùng existing AI service để xây solution mạnh.

Không có yêu cầu:

> phải train model riêng.

---

## ADC 2025 — Champion: AllStep

Solution:

- smart walker cho người cerebral palsy
- smart braking
- computer vision

Idea xuất phát từ trải nghiệm thật của gia đình thành viên team.

### Bài học quan trọng nhất

Không phải:

> “Computer vision làm team thắng.”

Mà là:

```text
Personal / real user insight
       ↓
Clear mobility problem
       ↓
Purposeful technology
       ↓
Prototype
       ↓
Community impact
```

---

## ADC 2025 — First Runner-up: NeuroAICC

Team:

- 2 Software Engineering
- 1 Digital Communications / Multimedia Design

Solution:

- bilingual web platform
- hỗ trợ autistic adults chuẩn bị job interview
- personalized guidance
- resource cho caregiver và employer

Đội co-create cùng:

- autistic individuals
- caregivers
- professionals

### Bài học

Team composition rất giống tư duy nên có:

```text
Technical
+
Technical
+
Communication / Design
```

Và yếu tố nổi bật là **co-creation (đồng sáng tạo với cộng đồng)**.

---

## ADC 2025 — 7 Rings

Solution:

- web platform
- real-time AI translation
- Vietnamese sign language ↔ speech
- hỗ trợ communication workplace

### Bài học

Web + AI có thể đạt top.

---

## ADC 2025 — InSight

Solution:

- AI-powered app
- hỗ trợ visually impaired employees
- social awareness
- emotional cue recognition
- real-time workplace interaction

### Bài học

Mobile/app + AI cũng có thể đạt top.

---

## Pattern tổng hợp

```text
2024 Champion → Website / Braille
2024 Runner-up → App + Azure AI

2025 Champion → Hardware + Computer Vision
2025 Runner-up → Web + AI + UX
2025 3rd → Web + Sign Language AI
2025 3rd → AI App
```

### Kết luận

Không có:

> “Muốn thắng phải Mechanical.”

Không có:

> “Muốn thắng phải tự train ML.”

Không có:

> “Website thì yếu.”

Pattern đúng hơn là:

> **Specific user + real barrier + appropriate technology + working prototype + validation + impact.**

---

# 12. Team composition phù hợp với team hiện tại

## Member 1 — Software / HCMUT

### Core role

**Software / AI Integration Engineer**

### Responsibility

- frontend
- backend
- DB nếu cần
- application flow
- AI/API integration
- deploy
- prototype engineering
- system architecture
- accessibility implementation cùng team

### Không cần gánh

- model research sâu
- toàn bộ user research
- toàn bộ pitch

---

## Member 2 — FTU2 Business / Product / Pitch

### Core role

**Product / Research / Pitch Lead**

### Responsibility

- user research
- problem framing
- competitor scan
- business/practical feasibility
- story
- deck
- impact framing
- pitch
- Q&A
- synthesize mentor/end-user feedback

### Nên học thêm

- accessibility fundamentals
- design thinking
- user interview
- inclusive design

---

## Member 3 — Applied AI / ML

### Core role

**Applied AI Engineer / AI Prototyper**

### Responsibility

- evaluate AI feasibility
- choose model/API
- Python inference
- CV/NLP/Speech/Multimodal nếu cần
- test model quality
- expose AI component
- work cùng Software member để integrate

---

## Team capability map

```text
                   USER PROBLEM
                        │
                        ↓
              PRODUCT / RESEARCH
                    FTU2
                        │
                        ↓
                    SOLUTION
                 ↙             ↘
                ↙               ↘
           SOFTWARE            AI
            HCMUT           MEMBER 3
                ↘               ↙
                 ↘             ↙
                 WORKING PROTOTYPE
                        │
                        ↓
                 VALIDATION / DEMO
                        │
                        ↓
                      PITCH
```

---

# 13. Người thứ ba nên là Applied AI teammate như thế nào?

## Must-have vừa đủ

- Python cơ bản/khá
- hiểu nền AI/ML
- biết dùng AI API hoặc pretrained model
- có khả năng prototype nhanh
- chủ động học tool mới

## Nice-to-have

Một trong các mảng:

- **Computer Vision (thị giác máy tính)**
- **NLP (xử lý ngôn ngữ tự nhiên)**
- **Speech AI (AI xử lý tiếng nói)**
- **Multimodal AI (AI đa phương thức)**
- RAG
- embeddings
- Hugging Face
- OpenCV / YOLO
- PyTorch/TensorFlow

## Không cần tuyển unicorn

Không cần một người biết toàn bộ:

```text
CV
+ NLP
+ Speech
+ RAG
+ TensorFlow
+ PyTorch
+ MLOps
+ FastAPI
```

### Câu hỏi tốt khi tìm teammate

> “Bạn từng dùng AI/model để làm project nào chạy được end-to-end chưa?”

Tốt hơn:

> “Bạn có biết 10 framework không?”

## Green flag

Ứng viên nói được:

- problem là gì
- model/API nào đã dùng
- input/output
- cách integrate
- limitation
- demo

## Yellow flag

Chỉ học theory:

- KNN
- Decision Tree
- Linear Regression

nhưng chưa từng đưa model vào application.

Không có nghĩa là không tốt, nhưng cần xem khả năng prototype thực tế.

---

# 14. Cách chọn problem và product

## Framework: One Person → One Moment → One Barrier → One Solution

Đừng chọn:

> “Làm AI hỗ trợ người khiếm thị.”

Quá rộng.

Nên chọn:

> “Một nhân viên khiếm thị đang trong weekly business review và đồng nghiệp share dashboard có nhiều chart. Screen reader không truyền tải được cấu trúc visual đủ nhanh, khiến nhân viên mất context.”

Cụ thể hơn rất nhiều.

---

## Problem Statement Template

```text
[USER]
gặp khó khăn khi

[WORKPLACE MOMENT]

vì

[SPECIFIC BARRIER]

dẫn đến

[MEASURABLE / MEANINGFUL CONSEQUENCE].
```

Ví dụ:

> A visually impaired analyst struggles to follow data-heavy screen sharing during live meetings because charts are not described in a structured, timely way, causing them to lose context and participate later than sighted colleagues.

---

## 5 câu hỏi trước khi build

### 1. User là ai?

Không chỉ:

> disabled person

Mà:

> visually impaired analyst / deaf intern / autistic candidate / employee with limited hand mobility

### 2. Moment nào?

- interview
- onboarding
- meeting
- training
- writing email
- dashboard review
- workstation interaction
- daily task management

### 3. Barrier cụ thể?

Một pain point.

### 4. Existing solution thiếu gì?

Đừng reinvent chức năng đã quá phổ biến nếu không có improvement rõ.

### 5. Vì sao AI?

Nếu không trả lời được, có thể solution không cần AI.

---

## Impact equation

```text
Impact
≈
Severity of problem
×
Frequency of problem
×
Number of users affected
×
Improvement from solution
```

Hackathon không cần tính chính xác, nhưng tư duy này giúp chọn problem.

---

# 15. Các hướng sản phẩm phù hợp với software + AI

> Đây là **problem-space inspiration**, không phải đề ADC 2026 đã công bố.

---

## 15.1 Accessible Meeting Visual Assistant

### User

Visually impaired employee.

### Moment

Online/offline meeting có screen sharing.

### Barrier

Chart, diagram, UI screenshot không được mô tả đúng context.

### Pipeline

```text
Screen / image
      ↓
Multimodal AI
      ↓
Detect chart/UI context
      ↓
Structured explanation
      ↓
Screen-reader-friendly UI / speech
```

### Điểm mạnh

- software first
- meaningful AI
- clear demo
- workplace context rõ

---

## 15.2 Meeting Participation Assistant for Deaf/HoH

Không chỉ speech-to-text.

### Pain point sâu hơn

Transcript có thể tồn tại nhưng user vẫn khó:

- biết ai đang nói
- biết câu hỏi hướng tới ai
- bắt kịp decision/action item
- theo topic changes

### Pipeline

```text
Meeting audio
      ↓
STT
      ↓
Speaker / context processing
      ↓
LLM
      ↓
- current topic
- decision
- question
- action item
      ↓
Accessible live UI
```

---

## 15.3 Structured Work Instruction Assistant

### User

Một nhóm neurodivergent professionals có difficulty với ambiguous instruction — cần validate cụ thể.

### Pipeline

```text
Manager message
      ↓
LLM
      ↓
Goal
Definition of Done
Priority
Deadline
Dependencies
Ambiguities
Clarification questions
```

### Lợi thế

- rất hợp React + Node + LLM
- không cần ML research
- dễ prototype

### Risk

Phải tránh generalization (khái quát hóa) về neurodivergence.

---

## 15.4 Accessible Document/Training Transformation

### Input

- slide
- PDF
- training material
- internal document

### AI

- structure extraction
- image descriptions
- plain-language conversion
- caption/transcript generation

### Output

Các mode phù hợp user.

### Challenge

Cần scope cụ thể để tránh biến thành “AI accessibility super app”.

---

## 15.5 Hybrid Assistive Input Device

Nếu team sau này có hardware skill.

```text
Physical input
      ↓
Sensor/device
      ↓
Embedded processing
      ↓
Software/AI
      ↓
Personalized control
```

Phù hợp mobility impairment.

---

# 16. Kiến trúc technical nên dùng cho hackathon

## Pattern A — Software + AI API

```text
React / Web UI
      ↓
Node.js / Express
      ↓
AI API
      ↓
Result
```

Dùng khi:

- LLM
- multimodal API
- text transformation
- summarization

### Ưu điểm

Nhanh nhất.

---

## Pattern B — Node application + Python AI service

```text
React
  ↓
Node / Express
  ↓
Python / FastAPI
  ↓
Pretrained Model
```

Dùng khi:

- Hugging Face
- OpenCV
- YOLO
- local inference
- custom preprocessing

### Phân role

Software member:

- app/backend/frontend

AI member:

- Python/model

---

## Pattern C — AI-first lightweight

```text
React / Next-style frontend
      ↓
Server/API
      ↓
External AI
```

Nếu deadline gấp, đừng tạo thêm service không cần thiết.

---

## Database có phải cần?

Chỉ dùng nếu workflow cần:

- user profile
- history
- saved result
- feedback
- preference

Đừng thêm PostgreSQL chỉ để architecture trông “xịn”.

---

## Deploy

Mục tiêu:

> judge truy cập được, demo ổn.

Không phải:

> production scale.

Ưu tiên platform team quen.

---

## Demo fallback

External API có thể fail.

Nên có:

- cached sample
- pre-recorded backup video
- stable demo input
- fallback result

Nhưng demo chính vẫn nên chạy thật nếu có thể.

---

# 17. Accessibility cho web/app cần biết gì?

ADC không bắt buộc người dự thi có accessibility experience từ trước. Day 1 có workshop về Universal Design.

Tuy vậy, team software nên học trước các nguyên tắc cơ bản.

## WCAG

**WCAG — Web Content Accessibility Guidelines  
(Hướng dẫn về khả năng tiếp cận nội dung web)**

W3C tổ chức WCAG theo 4 nguyên tắc gọi tắt là **POUR**:

---

## P — Perceivable  
*(Có thể cảm nhận được)*

User phải có cách tiếp nhận thông tin.

Ví dụ:

- image có text alternative
- video có caption
- contrast đủ
- không truyền information chỉ bằng màu

---

## O — Operable  
*(Có thể thao tác được)*

Ví dụ:

- dùng keyboard được
- không bị keyboard trap
- focus rõ
- target dễ bấm
- không bắt buộc interaction mà user không thực hiện được

---

## U — Understandable  
*(Dễ hiểu)*

Ví dụ:

- wording rõ
- flow predictable
- error message dễ hiểu
- consistent UI
- tránh cognitive overload

---

## R — Robust  
*(Tương thích bền vững)*

UI/code nên tương thích với:

- screen reader
- assistive technology
- browser/user agent khác nhau

---

## Checklist hackathon cho web

### HTML/structure

- semantic HTML
- heading hierarchy
- button thật thay vì clickable div
- label cho form
- alt text meaningful

### Keyboard

- Tab navigation
- Enter/Space activation
- visible focus
- không keyboard trap

### Visual

- contrast tốt
- không dùng màu là tín hiệu duy nhất
- text resize không vỡ layout

### Screen reader

- button/link name rõ
- status changes có thể được đọc
- icon-only control có accessible label

### Cognitive accessibility

- ít bước
- wording trực tiếp
- hierarchy rõ
- predictable layout
- tránh unnecessary animation
- không dồn quá nhiều information một màn hình

---

# 18. Playbook Day 1 → Day 3

# Day 1 — Learn & Frame  
*(Học và xác định vấn đề)*

Morning chính thức:

- competition brief release
- accessibility/universal design workshop
- AI prototyping workshop
- design thinking workshop

Afternoon:

- teamwork

## Mục tiêu Day 1

**Không phải code càng nhiều càng tốt.**

Mục tiêu:

1. hiểu brief
2. chọn user
3. chọn workplace moment
4. chọn barrier
5. đưa ra 2–3 solution
6. kill idea yếu
7. chọn 1 vertical slice
8. bắt đầu prototype

## Phân công

### FTU member

- đọc brief
- problem research
- map user journey
- competitor scan
- prepare interview questions

### Software member

- assess build feasibility
- create app skeleton
- define demo flow
- API/interface planning

### AI member

- test 2–3 AI options
- measure latency/quality
- decide simplest viable AI

## Cuối Day 1 phải có

```text
1 user
1 barrier
1 solution
1 demo workflow
1 technical plan
1 list assumptions to validate
```

---

# Day 2 — Test & Refine  
*(Kiểm thử và tinh chỉnh)*

Morning:

- Fireside Chat with End-Users
- Express Mentoring
- Technical Consultation

Đây có thể là ngày quan trọng nhất.

## Nguyên tắc

**Đừng bảo vệ idea bằng mọi giá.**

Nếu user nói:

> “Problem này không quan trọng bằng X.”

thì consider pivot.

## User questions nên hỏi

Không hỏi:

> “Bạn có thích app tụi em không?”

Hỏi:

- “Trong situation X, bước nào khó nhất?”
- “Hiện bạn giải quyết bằng cách nào?”
- “Điều gì khiến cách hiện tại khó chịu?”
- “Nếu tool tự động làm Y, bạn có lo điều gì?”
- “Output dạng text/audio/visual nào hữu ích nhất?”
- “Trường hợp AI trả lời sai có hậu quả gì?”

## Sau feedback

Tạo bảng:

| Assumption | Evidence | Decision |
|---|---|---|
| User cần X | Không mạnh | Bỏ |
| Y xảy ra thường xuyên | Có | Giữ |
| AI output nên dài | User muốn ngắn | Rút |

### Đây là User-Centred Design evidence rất mạnh cho pitch.

---

# Day 3 — Evaluate & Pitch  
*(Đánh giá và thuyết trình)*

Morning:

- submit pitch deck
- submit solution video <5 phút

Afternoon:

- Top 8 Finale

## Mục tiêu kỹ thuật

**Feature freeze sớm.**

Đừng thêm feature mới sát submission.

Ưu tiên:

- stable demo
- video
- deck
- rehearsal
- Q&A

---

# 19. Pitch Deck, Video và Prototype nên chuẩn bị thế nào?

## Official deliverables Day 3

### Solution Pitch Deck

Phải trình bày ít nhất:

- problem statement
- proposed solution
- prototype demonstration
- expected impact

### Solution Video

- dưới 5 phút
- giới thiệu solution
- showcase how it works

---

## Suggested Deck Structure  
*(Cấu trúc deck gợi ý — không phải template bắt buộc của BTC)*

### Slide 1 — Human Story / Hook

Một workplace moment.

### Slide 2 — Problem

Specific barrier.

### Slide 3 — Evidence / User Insight

Quote, interview insight, observation.

### Slide 4 — Existing Gap

Tại sao cách hiện tại chưa đủ.

### Slide 5 — Solution

Một câu.

### Slide 6 — How It Works

Workflow.

### Slide 7 — Prototype Demo

Screenshot / live demo.

### Slide 8 — Why AI

AI làm task nào và tại sao cần nó.

### Slide 9 — Accessibility by Design

Design decisions.

### Slide 10 — Feasibility

- technology
- cost
- deployment
- risk
- implementation

### Slide 11 — Impact

Before vs after.

### Slide 12 — Vision / Closing

Human outcome.

---

## Storytelling formula

```text
PERSON
  ↓
MOMENT
  ↓
BARRIER
  ↓
CONSEQUENCE
  ↓
INSIGHT
  ↓
SOLUTION
  ↓
DEMO
  ↓
IMPACT
```

Tốt hơn:

```text
Slide 1: AI
Slide 2: Architecture
Slide 3: Tech stack
Slide 4: 17 features
```

---

## Video <5 phút

### Nên có

1. problem
2. user
3. product in use
4. AI processing
5. accessible output
6. impact

### Không nên

- 4 phút nói
- 30 giây demo

Video phải làm judge **thấy solution hoạt động**.

---

# 20. Các bẫy dễ khiến team mất điểm

## Bẫy 1 — Generic disability chatbot

> “Chatbot hỗ trợ người khuyết tật.”

Judge có thể hỏi:

> Tại sao không dùng ChatGPT?

Cần specific workflow.

---

## Bẫy 2 — Tech-first

> “Bọn mình biết YOLO nên làm camera.”

Không tốt nếu problem không cần CV.

---

## Bẫy 3 — AI for AI's sake  
*(dùng AI chỉ để có AI)*

Một if/else giải được thì đừng gọi LLM.

---

## Bẫy 4 — Super App

```text
Chatbot
+ CV
+ TTS
+ RAG
+ Job board
+ Calendar
+ Interview
+ Social
```

3 ngày không đủ.

---

## Bẫy 5 — Tự tưởng tượng user needs

Đây là competition accessibility.

Assumption không validate là risk lớn.

---

## Bẫy 6 — Product inaccessible

App cho người khiếm thị nhưng:

- không keyboard navigation
- button thiếu label
- contrast thấp

Rất phản tác dụng.

---

## Bẫy 7 — Over-engineering

Microservices/Kubernetes không tạo điểm nếu user không hưởng lợi.

---

## Bẫy 8 — Demo fragile

20 dependency, 3 service, 2 API unstable.

Simplicity wins.

---

## Bẫy 9 — Ignore AI risk

AI hỗ trợ disability có thể gây harm nếu output sai.

Pitch nên có:

- uncertainty
- human confirmation
- fallback
- privacy
- scope limitation

---

## Bẫy 10 — Không giải employability/workplace

Đừng chỉ giải accessibility nói chung.

Luôn nối về:

> work / hiring / onboarding / communication / performance / workplace participation.

---

# 21. Kế hoạch chuẩn bị trước Hackathon

## Priority 1 — Chốt teammate

Team cần:

```text
Software
+
Product/Business/Pitch
+
Applied AI
```

---

## Priority 2 — Accessibility fundamentals

Cả team học:

- 4 disability categories
- universal design
- WCAG basics
- respectful user research
- assistive technologies

---

## Priority 3 — AI toolbox

Không cần học ML theory rộng.

Nên rehearsal:

### Text

- LLM structured output
- prompt
- basic RAG nếu cần

### Vision

- multimodal image understanding
- OCR
- simple CV model

### Speech

- STT
- TTS

AI teammate không cần master tất cả, chỉ cần team biết capability hiện có.

---

## Priority 4 — Hackathon starter repo

Chuẩn bị sẵn:

- frontend skeleton
- component library
- API pattern
- env configuration
- deployment workflow
- authentication chỉ nếu thật sự cần
- reusable accessible components

Không code solution trước brief.

---

## Priority 5 — Practice one mini-hackathon

Tự đặt fake brief:

> “Improve participation of visually impaired employees in a team meeting.”

Cho team 3–4 giờ:

1. research
2. choose pain point
3. prototype
4. pitch 3 phút

Mục đích là test teamwork.

---

## Priority 6 — Pitch rehearsal

Cả team đều phải hiểu:

- problem
- solution
- AI
- feasibility

Dù FTU member pitch chính, judge có thể hỏi technical member trực tiếp.

---

# 22. Checklist nhanh cho team

## Trước đăng ký

- [ ] Đủ đúng 3 người
- [ ] Ít nhất 1 current student
- [ ] Cả team đủ eligibility
- [ ] Hoàn thiện 2 motivation answers
- [ ] Có thể tham dự 21–23/09
- [ ] Chốt communication channel
- [ ] Chốt expectation “không ghost/drop”

## Trước 21/09

- [ ] Học accessibility basics
- [ ] Test AI API
- [ ] Test Python/model flow
- [ ] Starter repo chạy
- [ ] Deploy workflow chạy
- [ ] Practice Figma/user flow
- [ ] Practice pitch
- [ ] Chuẩn bị research template
- [ ] Chuẩn bị interview questions
- [ ] Hiểu 5 judging criteria

## Day 1

- [ ] Chọn 1 user
- [ ] Chọn 1 workplace moment
- [ ] Chọn 1 barrier
- [ ] Xác định why AI
- [ ] Chọn vertical slice
- [ ] Test technical feasibility
- [ ] Ghi assumption cần validate

## Day 2

- [ ] Talk/listen to end-users
- [ ] Ghi evidence
- [ ] Pivot nếu cần
- [ ] Test prototype
- [ ] Mentor feedback
- [ ] Technical consultation
- [ ] Chốt MVP

## Day 3

- [ ] Feature freeze
- [ ] Stable demo
- [ ] Record video
- [ ] Final deck
- [ ] Rehearse
- [ ] Prepare Q&A
- [ ] Backup demo
- [ ] Submit đúng yêu cầu

---

# 23. Glossary — Thuật ngữ quan trọng

| English term | Chú thích tiếng Việt |
|---|---|
| Accessibility | Khả năng tiếp cận: mức độ sản phẩm/môi trường có thể được sử dụng bởi người có các khả năng khác nhau |
| Inclusion | Sự hòa nhập |
| Employability | Khả năng tham gia, duy trì và phát triển trong việc làm |
| Disability | Khuyết tật |
| Visual Impairment | Khiếm thị / suy giảm thị lực |
| Deaf or Hard of Hearing | Người điếc hoặc suy giảm thính lực |
| Mobility Impairment | Khuyết tật/hạn chế vận động |
| Neurodivergence | Đa dạng thần kinh |
| Universal Design | Thiết kế phổ quát, hướng tới sử dụng bởi nhiều nhóm người nhất có thể |
| Inclusive Design | Thiết kế hòa nhập |
| User-Centred Design | Thiết kế lấy người dùng làm trung tâm |
| End User | Người dùng cuối |
| Pain Point | Vấn đề/nỗi đau thực tế của người dùng |
| Barrier | Rào cản |
| User Insight | Hiểu biết có giá trị rút ra từ research/quan sát người dùng |
| Problem Framing | Cách xác định và đóng khung vấn đề |
| Design Thinking | Tư duy thiết kế dựa trên việc hiểu người dùng, định nghĩa vấn đề, tạo ý tưởng, prototype và test |
| Prototype | Nguyên mẫu |
| MVP — Minimum Viable Product | Sản phẩm khả dụng tối thiểu, đủ để kiểm chứng giá trị cốt lõi |
| Vertical Slice | Một luồng nhỏ nhưng chạy end-to-end từ input tới output |
| Validation | Kiểm chứng giả định/giải pháp |
| Feasibility | Tính khả thi |
| Practicality | Tính thực tiễn |
| Impact | Tác động |
| Innovation | Tính đổi mới |
| Pitch Deck | Bộ slide trình bày giải pháp |
| Storytelling | Cách kể câu chuyện có logic và cảm xúc |
| Q&A | Phần hỏi đáp |
| Applied AI | AI ứng dụng |
| AI Prototyping | Tạo prototype sử dụng AI nhanh |
| Pretrained Model | Model đã được huấn luyện trước |
| Inference | Quá trình model xử lý input để tạo output |
| Fine-tuning | Huấn luyện tinh chỉnh model có sẵn cho task/domain cụ thể |
| RAG — Retrieval-Augmented Generation | Kỹ thuật lấy dữ liệu liên quan trước rồi cung cấp cho model để tạo câu trả lời grounded hơn |
| Embedding | Vector số biểu diễn semantic meaning của dữ liệu |
| Computer Vision | Thị giác máy tính |
| NLP — Natural Language Processing | Xử lý ngôn ngữ tự nhiên |
| Speech-to-Text | Chuyển giọng nói thành văn bản |
| Text-to-Speech | Chuyển văn bản thành giọng nói |
| Multimodal AI | AI xử lý nhiều dạng dữ liệu như text, image, audio |
| OCR | Nhận dạng chữ từ hình ảnh |
| Speaker Diarization | Phân tách/xác định ai nói ở thời điểm nào |
| API Integration | Tích hợp một dịch vụ qua API |
| FastAPI | Framework Python thường dùng để expose API nhanh |
| Screen Reader | Phần mềm đọc nội dung màn hình cho người dùng, đặc biệt hữu ích với người khiếm thị |
| Assistive Technology | Công nghệ hỗ trợ người khuyết tật |
| Keyboard Navigation | Điều hướng giao diện bằng bàn phím |
| Semantic HTML | HTML dùng đúng ý nghĩa các phần tử để trình duyệt và assistive technology hiểu cấu trúc |
| ARIA | Bộ thuộc tính hỗ trợ mô tả UI cho assistive technology khi HTML native chưa đủ |
| WCAG | Bộ hướng dẫn về khả năng tiếp cận nội dung web của W3C |
| POUR | 4 nguyên tắc WCAG: Perceivable, Operable, Understandable, Robust |
| Co-creation | Đồng sáng tạo với chính cộng đồng/người dùng |
| Human-in-the-loop | Có con người tham gia xác nhận/kiểm soát trong workflow AI |
| Hallucination | AI tạo thông tin không đúng hoặc không được grounded |
| Fallback | Phương án dự phòng khi hệ thống/model/API lỗi |
| Responsible AI | AI có trách nhiệm: cân nhắc fairness, privacy, reliability, harm, transparency |
| Ethical AI | AI được sử dụng phù hợp với các nguyên tắc đạo đức |
| Tech Stack | Bộ công nghệ dùng để xây hệ thống |
| Over-engineering | Thiết kế kỹ thuật phức tạp hơn mức bài toán thực sự cần |

---

# 24. Nguồn tham khảo

## Nguồn chính thức ADC 2026

1. **ADC Hackathon 2026 — RMIT Industry Hub**  
   https://industryhub.rmit.edu.vn/ADC/

2. **ADC Hackathon 2026 — Registration**  
   https://industryhub.rmit.edu.vn/ADC/register/

## Lịch sử và case study ADC

3. **Designing a future for all — ADC 2025, RMIT University**  
   https://www.rmit.edu.vn/news/all-news/2025/oct/designing-a-future-for-all

4. **Students’ vision toward a future for autistic job candidates — NeuroAICC, RMIT University**  
   https://www.rmit.edu.vn/students/student-news-and-events/student-news/2025/neuroaicc-autistic-interview-accessibility-design-competition

5. **RMIT Vietnam drives the employability of people with disabilities — ADC 2024**  
   https://www.rmit.edu.vn/news/all-news/2024/jun/rmit-vietnam-drives-the-employability-of-people-with-disabilities

6. **Designing for everyone: the Accessibility Design Competition kicks off — ADC 2025**  
   https://www.rmit.edu.vn/news/all-news/2025/aug/designing-for-everyone-the-accessibility-design-competition-kicks-off

## Accessibility technical reference

7. **W3C — Web Content Accessibility Guidelines (WCAG) 2.2**  
   https://www.w3.org/TR/WCAG22/

8. **W3C — WCAG Overview**  
   https://www.w3.org/WAI/standards-guidelines/wcag/

9. **W3C — How People with Disabilities Navigate and Interact with the Web**  
   https://www.w3.org/WAI/people-use-web/tools-techniques/navigation/

---

# Final Takeaway

Nếu chỉ giữ một mental model duy nhất trước ADC, hãy dùng:

```text
DO NOT BUILD "AI FOR DISABILITY"

BUILD:

A SPECIFIC SOLUTION
FOR A SPECIFIC PERSON
IN A SPECIFIC WORKPLACE MOMENT
WHERE A SPECIFIC BARRIER EXISTS

THEN USE
THE SIMPLEST APPROPRIATE TECHNOLOGY
TO REMOVE THAT BARRIER.
```

Với team:

```text
SOFTWARE / HCMUT
        +
PRODUCT-BUSINESS-PITCH / FTU2
        +
APPLIED AI / ML
```

hướng hợp lý nhất không phải cố chứng minh rằng team có thể train model phức tạp nhất.

Hướng hợp lý là:

> **Hiểu đúng user → chọn đúng problem → dùng AI có lý do → build một prototype thật sự chạy → chứng minh accessibility và feasibility → kể câu chuyện thật rõ.**

Đó là cách các tiêu chí chính thức của ADC 2026 và pattern các đội mạnh ADC 2024–2025 cùng chỉ về một hướng.
