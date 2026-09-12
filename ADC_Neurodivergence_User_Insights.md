# ADC 2026 — Hiểu neurodivergence trước khi nghĩ giải pháp

Tài liệu này giúp team hiểu sâu hơn cách một số người neurodivergent (có kiểu xử lý thần kinh khác với chuẩn số đông) sinh hoạt, giao tiếp, dùng laptop/điện thoại và tham gia công việc. Trọng tâm không phải chẩn đoán y khoa, mà là những điểm không khớp giữa **cách một người xử lý thông tin** và **cách môi trường làm việc được thiết kế**.

Đây là **desk research (nghiên cứu từ tài liệu)**. Nó không chứng minh một pain point cụ thể chắc chắn đúng với end-user của ADC. Brief chỉ được công bố vào đầu Day 1; mọi hướng giải pháp trong file là hypothesis (giả thuyết), phải được phỏng vấn và kiểm thử trước khi chọn.

---

## Mục lục

1. [Những điều cả team cần hiểu trước](#1-những-điều-cả-team-cần-hiểu-trước)
2. [Neurodivergence gồm những ai?](#2-neurodivergence-gồm-những-ai)
3. [Một ngày sống và làm việc có thể diễn ra thế nào?](#3-một-ngày-sống-và-làm-việc-có-thể-diễn-ra-thế-nào)
4. [Họ tương tác với laptop và phần mềm ra sao?](#4-họ-tương-tác-với-laptop-và-phần-mềm-ra-sao)
5. [Họ dùng điện thoại ra sao?](#5-họ-dùng-điện-thoại-ra-sao)
6. [Công cụ và accommodation hiện có](#6-công-cụ-và-accommodation-hiện-có)
7. [Hành trình công việc và các pain point](#7-hành-trình-công-việc-và-các-pain-point)
8. [Những insight sâu hơn cho ADC](#8-những-insight-sâu-hơn-cho-adc)
9. [Từ pain point tới các hướng ý tưởng](#9-từ-pain-point-tới-các-hướng-ý-tưởng)
10. [Cách phỏng vấn end-user trong Day 1–2](#10-cách-phỏng-vấn-end-user-trong-day-12)
11. [Nguyên tắc thiết kế và kiểm thử prototype](#11-nguyên-tắc-thiết-kế-và-kiểm-thử-prototype)
12. [Cách quyết định có chọn Neurodivergence hay không](#12-cách-quyết-định-có-chọn-neurodivergence-hay-không)
13. [Nguồn tham khảo](#13-nguồn-tham-khảo)

---

# 1. Những điều cả team cần hiểu trước

## 1.1. Neurodiversity và neurodivergence không hoàn toàn giống nhau

**Neurodiversity (đa dạng thần kinh)** mô tả sự đa dạng tự nhiên trong cách bộ não con người hoạt động. Theo nghĩa đó, một nhóm người bao gồm cả neurotypical và neurodivergent đều có neurodiversity.

**Neurodivergent** thường chỉ một người có cách nhận thức, chú ý, học, giao tiếp hoặc xử lý cảm giác khác với kỳ vọng phổ biến. Phạm vi thuật ngữ thay đổi theo cộng đồng và quốc gia; thường có thể bao gồm autism, ADHD, dyslexia, dyspraxia, dyscalculia, Tourette và một số khác. W3C dùng nhóm rộng hơn là cognitive and learning disabilities, trong đó chức năng bị ảnh hưởng có thể là chú ý, trí nhớ, ngôn ngữ, đọc/viết, giải quyết vấn đề hoặc xử lý sensory input (đầu vào giác quan).[^1]

Trong file này, “neurodivergence” được dùng theo Area of Focus của ADC. Team không được suy ra chẩn đoán từ hành vi và không nên thiết kế một “AI phát hiện người neurodivergent”.

## 1.2. Không có “người dùng neurodivergent điển hình”

Hai người cùng có ADHD có thể cần support khác nhau. Một người autistic có thể muốn agenda rất chi tiết; người khác thấy quá nhiều chi tiết làm khó bắt đầu. Dyslexia có thể ảnh hưởng đọc/viết nhưng không nói lên khả năng toán học hoặc tư duy hệ thống. Một người có thể có nhiều neurodivergence cùng lúc, kèm anxiety, disability hoặc tình trạng sức khỏe khác.

Vì vậy thiết kế nên đi theo:

```text
Diagnosis label
        ↓ không đủ
Functional need + task + context + preference
        ↓
Accommodation / product behavior
```

JAN cũng lưu ý workplace challenge và mức độ ảnh hưởng khác nhau mạnh theo từng người; không phải ai cũng cần accommodation, và người cần hỗ trợ cũng có thể chỉ cần một vài thay đổi cụ thể.[^2]

## 1.3. Khó khăn ở một chức năng không đồng nghĩa năng lực tổng thể thấp

Một người có thể:

- hiểu chuyên môn sâu nhưng khó bắt đầu một task mơ hồ;
- nghĩ ra giải pháp tốt nhưng cần thêm thời gian để trả lời câu hỏi bất ngờ;
- đọc chậm nhưng nghe và tổng hợp rất tốt;
- tập trung sâu vào công việc có cấu trúc nhưng kiệt sức vì interruption;
- giao tiếp trực tiếp, ít dùng eye contact nhưng vẫn lắng nghe;
- làm việc tốt ở nhà nhưng bị sensory overload trong văn phòng mở.

Đừng biến một khác biệt về communication style thành kết luận về thái độ, trí tuệ hoặc teamwork.

## 1.4. Điểm mạnh cũng không nên bị biến thành stereotype

Các chương trình tuyển dụng đôi khi quảng bá người neurodivergent như luôn có pattern recognition, sáng tạo, chú ý chi tiết hoặc hyperfocus. Một cá nhân có thể có các điểm mạnh ấy, nhưng chúng không phải “siêu năng lực” mặc định của chẩn đoán.

Cách tôn trọng hơn là hỏi:

- công việc nào người này làm tốt;
- điều kiện nào giúp họ làm tốt;
- cách nhận brief, giao tiếp và feedback nào phù hợp;
- môi trường nào làm mất năng lực đó.

## 1.5. Có diagnosis, self-identification và disclosure là ba chuyện khác nhau

Một người có thể tự nhận là neurodivergent nhưng chưa có chẩn đoán chính thức vì chi phí, access hoặc hệ thống y tế. Người có chẩn đoán có thể không muốn nói với employer. Người khác thấy không cần disclosure nhưng vẫn hưởng lợi từ giao tiếp rõ và môi trường linh hoạt.

Trong khảo sát UK của CIPD với 1.047 người đi làm, 790 người tự nhận neurodivergent. Trong số các lý do không nói với manager/HR, người trả lời nêu tính riêng tư, lo người khác áp stereotype, stigma và ảnh hưởng sự nghiệp.[^3] Đây không phải dữ liệu Việt Nam, nhưng cho thấy sản phẩm buộc người dùng khai diagnosis để được dùng có thể tạo barrier mới.

## 1.6. Language preference thuộc về người dùng

Một số người thích identity-first language như “autistic person”; người khác thích “person with autism”. Hãy hỏi cách họ muốn được mô tả. Không dùng các từ mang tính thương hại, “bình thường/bất thường”, “mắc bệnh” hoặc tự gắn nhãn chức năng.

---

# 2. Neurodivergence gồm những ai?

Bảng dưới là bản đồ định hướng, không phải checklist chẩn đoán. Mỗi biểu hiện chỉ là **khả năng có thể gặp**, không phải đặc điểm bắt buộc.

| Nhóm/khác biệt | Chức năng có thể bị ảnh hưởng trong một số bối cảnh | Support có thể hữu ích | Không được suy diễn |
|---|---|---|---|
| ADHD | Duy trì/chuyển chú ý, working memory, ước lượng thời gian, bắt đầu/dừng task, impulse control | Task rõ, checkpoint, timer tự chọn, giảm interruption, written follow-up | “Lười”, “không quan tâm”, luôn hyperactive |
| Autism | Sensory processing, uncertainty/change, một số dạng social communication, nhu cầu predictability | Agenda trước, giao tiếp rõ, không gian cảm giác phù hợp, choice về kênh giao tiếp | Thiếu đồng cảm, không teamwork, có cùng một mức support |
| Dyslexia | Độ trôi chảy khi đọc, spelling, xử lý text dày, đôi khi working memory | TTS, font/spacing tùy chỉnh, plain language, thêm thời gian, dictation | Trí tuệ thấp, không thể viết hay học ngôn ngữ |
| Dyspraxia/DCD | Lập kế hoạch và phối hợp vận động, sequence, handwriting, tổ chức | Keyboard/voice input, checklist, ergonomics, thêm thời gian | Cẩu thả hoặc không luyện tập |
| Dyscalculia | Xử lý số, magnitude, phép tính, đọc một số dạng bảng | Calculator, visual/structured representation, validation, thêm thời gian | Không thể tư duy logic hoặc làm mọi task dữ liệu |
| Tourette | Tic vận động/âm thanh, stress và nỗ lực suppress tic | Break, remote/flexible work, không gian riêng, culture không kỳ thị | Tic thể hiện ý định hoặc thái độ |
| Khác biệt xử lý cảm giác | Nhạy hoặc ít nhạy với âm thanh, ánh sáng, chạm, mùi, nhiệt độ | Headphone, lighting, seating, quiet space, personalization | “Khó tính” hoặc một setup phù hợp tất cả |

### Thay vì persona theo nhãn, dùng functional profile

| Functional need | Ví dụ trong công việc | Câu cần hỏi |
|---|---|---|
| Cần giảm ambiguity | Brief dùng “sớm”, “đẹp”, “làm nhanh” | Thông tin nào cần rõ trước khi bắt đầu? |
| Cần giữ context | Bị gọi giữa lúc làm báo cáo | Khi quay lại, điều gì khó khôi phục nhất? |
| Cần xử lý tuần tự | Form dài, nhiều dependency | Overview hay one-step-at-a-time tốt hơn? |
| Cần kiểm soát sensory input | Office mở, đèn sáng, họp dài | Yếu tố nào gây quá tải? Có thay đổi theo ngày không? |
| Cần thêm processing time | Câu hỏi bất ngờ trong meeting | Written question hoặc pause có giúp không? |
| Cần kênh đọc/viết khác | Email dài, spelling pressure | Text-to-speech, dictation hay summary nào hữu ích? |
| Cần predictability | Lịch/brief đổi mà lý do không rõ | Cần báo trước và giải thích mức nào? |

W3C nhấn mạnh thường chỉ một số chức năng bị ảnh hưởng trong khi các chức năng khác không bị ảnh hưởng.[^1] Functional profile giúp team không đánh đồng một difficulty với toàn bộ con người.

---

# 3. Một ngày sống và làm việc có thể diễn ra thế nào?

Không có routine chung. Phần này mô tả những strategy thường gặp để team nhìn thấy phần “cognitive and emotional labor” — công sức nhận thức và cảm xúc mà người ngoài có thể không thấy.

## 3.1. Tạo external structure thay cho việc giữ mọi thứ trong đầu

Người dùng có thể dùng:

- calendar với nhiều reminder;
- checklist theo từng bước;
- sticky note, notebook hoặc whiteboard;
- đặt đồ ở vị trí cố định;
- alarm để bắt đầu/dừng hoạt động;
- visual timer hoặc đồng hồ rung;
- template cho routine buổi sáng, chuẩn bị đi làm hoặc kết thúc ngày;
- chia task lớn thành block nhỏ;
- body doubling — làm việc cùng sự hiện diện của một người khác để dễ bắt đầu/duy trì.

Đây không phải bằng chứng họ “không tự quản lý được”. Externalizing (đưa thông tin ra ngoài đầu) là một strategy hiệu quả để giảm working-memory load.

## 3.2. Quản lý năng lượng, không chỉ quản lý thời gian

Một lịch còn trống 60 phút không có nghĩa người dùng còn đủ khả năng cho một meeting khó. Sensory load, social interaction, task switching và masking có thể tiêu tốn năng lượng khác nhau.

Một số người:

- gom meeting vào một khoảng rồi dành block yên tĩnh;
- cần recovery time sau tương tác xã hội;
- làm deep work tốt vào giờ riêng;
- dùng remote/hybrid work để kiểm soát môi trường;
- luân phiên task nặng/nhẹ;
- cần biết trước duration và format để chuẩn bị.

Một productivity tool tối ưu kín lịch có thể làm tình hình tệ hơn nếu chỉ coi thời gian là tài nguyên.

## 3.3. Điều chỉnh sensory environment

Môi trường văn phòng có nhiều input đồng thời: hội thoại, tiếng điều hòa, mùi, đèn huỳnh quang, người đi lại và notification. Với một số người, lọc bỏ input không liên quan đòi hỏi nỗ lực lớn hoặc không thực hiện được.

Strategy có thể gồm:

- noise-cancelling headphone hoặc earplug;
- ghế xa lối đi/loa/máy lạnh;
- giảm độ sáng, dark mode, kính/lọc màu;
- trang phục hoặc vật liệu dễ chịu;
- quiet room;
- remote work;
- tắt notification và animation;
- break trước khi overload.

Nghiên cứu phỏng vấn 36 neurodivergent professionals tại Mỹ cho thấy làm việc ở nhà có thể giúp kiểm soát sensory stimuli và interruption, nhưng lại tạo thách thức mới từ không gian gia đình và công cụ cộng tác số.[^4] Remote work không phải thuốc chữa chung.

## 3.4. Chuẩn bị trước giao tiếp

Một người có thể muốn:

- agenda và câu hỏi trước meeting;
- written instruction sau cuộc gọi;
- đủ pause trước khi trả lời;
- dùng chat/email thay cuộc gọi bất ngờ;
- có cấu trúc cho feedback;
- biết ai tham gia và họ giữ vai trò gì;
- script hoặc note cho cuộc gọi khó;
- nói thẳng, ít small talk.

Electronic communication có thể cho người dùng thêm thời gian xử lý và tạo record để xem lại. Trong một khảo sát sơ bộ với 140 người autistic, electronic communication được đánh giá cao; flexible time, remote work, app hỗ trợ ưu tiên task và personalization của không gian cũng được đánh giá tích cực.[^5] Kết quả này chỉ phản ánh mẫu nghiên cứu cụ thể, không phải preference của mọi người autistic.

## 3.5. Masking và phần việc xã hội vô hình

Masking có thể là việc ép eye contact, kiềm tic/stim, bắt chước cách nói, giấu nhu cầu nghỉ hoặc liên tục tự kiểm tra xem hành vi có bị xem là “khác thường”. Việc này có thể giúp vượt qua kỳ vọng tức thời nhưng tiêu tốn năng lượng và làm người quản lý không thấy nhu cầu support.

Sản phẩm không nên chấm điểm “professional behavior” từ camera, giọng nói hoặc emotion recognition. Nó dễ củng cố đúng chuẩn hành vi đang tạo barrier.

## 3.6. Khi kế hoạch thay đổi

Không phải mọi người neurodivergent đều ghét thay đổi. Vấn đề thường là thay đổi **không có đủ context, thời gian chuẩn bị hoặc tác động rõ ràng**. Một calendar event đổi giờ có thể kéo theo transport, medication, childcare, sensory setup và thứ tự task khác.

Thông báo “Meeting updated” chưa đủ. Người dùng có thể cần biết:

- cái gì đổi;
- vì sao;
- phần nào của kế hoạch cũ vẫn đúng;
- việc nào bị ảnh hưởng;
- có cần phản hồi không;
- deadline mới là gì.

---

# 4. Họ tương tác với laptop và phần mềm ra sao?

## 4.1. Laptop có thể là công cụ tự chủ mạnh

Text có thể được đọc, nghe, tìm kiếm, sửa và cấu trúc lại. Calendar, task manager, notes, TTS, dictation và automation giúp externalize memory và chọn kênh phù hợp. Nhưng cùng lúc, laptop cũng tập trung email, chat, meeting, notification, file và deadline vào một nơi — rất dễ tạo overload và context switching.

## 4.2. Reading và information processing

Một người có thể:

- dùng text-to-speech để nghe document/email;
- tăng spacing, đổi font, màu nền hoặc chiều rộng dòng;
- dùng reading ruler/focus mode;
- ẩn sidebar, quảng cáo và phần không liên quan;
- đọc summary trước rồi drill down;
- cần heading rõ và paragraph ngắn;
- dùng spellcheck, word prediction hoặc dictation;
- nghe và nhìn đồng thời để giữ vị trí.

Microsoft liệt kê Immersive Reader, Read Aloud, text suggestion, font/spacing customization và focus tools như các công cụ accessibility cho neurodiversity.[^6] Android Reading Mode cho phép đổi contrast, màu, font, spacing và đọc thành tiếng, nhưng hiện không hỗ trợ mọi loại nội dung như PDF, email, chat hoặc social feed.[^7]

Insight cho team: đừng làm thêm một summarizer chung. Hãy tìm format hoặc workflow mà công cụ hiện tại không giữ được goal, source, uncertainty hoặc quyền điều chỉnh presentation.

## 4.3. Executive function và task initiation

Executive functions liên quan lập kế hoạch, tổ chức, ghi nhớ chi tiết, bắt đầu/dừng hành động và điều chỉnh khi tình huống đổi. JAN gợi ý các accommodation như chia assignment lớn, checklist, timer, organizer và cấu trúc transition.[^8]

Pain có thể xuất hiện khi task nói:

> “Em xem lại tài liệu rồi làm giúp anh một bản tốt hơn, gửi sớm nhé.”

Người nhận phải tự suy ra audience, phạm vi, nguồn, priority, deadline và definition of done. Một task manager chỉ tạo checkbox không giải quyết ambiguity từ người giao việc.

## 4.4. Notification và interruption

Notification không chỉ lấy vài giây. Người dùng phải:

1. dừng goal hiện tại;
2. đánh giá alert;
3. chuyển application;
4. xử lý hoặc ghi nhớ sẽ làm sau;
5. quay lại;
6. khôi phục trạng thái, logic và next step.

Nếu working memory hoặc task switching đang khó, bước 6 có thể tốn nhiều phút. Do đó “tắt mọi notification” không phải luôn đúng — một số reminder chính là assistive tool. Cần phân biệt **helpful cue** và **unplanned interruption** theo context của người dùng.

## 4.5. Nhiều tab/file và việc giữ context

Nhiều tab có thể là hỗn loạn với người này nhưng là external memory với người khác. Tự động đóng, nhóm hoặc đổi tên tab mà không hỏi có thể phá hệ thống cá nhân.

Một công cụ recovery tốt cần cho người dùng chủ động xác định:

- goal;
- tài liệu đang dùng;
- đoạn reasoning dở;
- điều đã quyết định;
- điều chưa chắc;
- next action.

Nó không cần ghi toàn bộ màn hình hoặc keystroke.

## 4.6. UI không nhất quán và overload

W3C COGA khuyến nghị purpose rõ, layout quen thuộc, content ngắn/rõ, tránh distraction, hỗ trợ quay lại context, không dựa quá nhiều vào memory và cho phép personalization.[^9] Những rào cản thường gặp gồm:

- control đổi vị trí sau refresh;
- animation hoặc content tự chạy;
- quá nhiều lựa chọn ngang cấp;
- error message mơ hồ;
- process dài không cho biết còn bao nhiêu bước;
- countdown tạo áp lực;
- icon/thuật ngữ mới không giải thích;
- form mất dữ liệu sau lỗi;
- autosave không rõ;
- màu và density không tùy chỉnh được.

## 4.7. Meeting và video call

Video call kết hợp lời nói, gương mặt, slide, chat, reaction và self-view. Một người có thể phải vừa xử lý nội dung vừa quyết định lúc nào nói, có cần nhìn camera, chat có gì và cue xã hội nào vừa xảy ra.

Strategy có thể là:

- tắt self-view/camera;
- captions/transcript;
- agenda và slide trước;
- written questions;
- hand-raise rõ;
- người điều phối turn-taking;
- recording/note;
- break giữa các meeting.

Microsoft Research ghi nhận autistic participants dùng nhiều coping strategy trong video call để điều tiết sensory input, dựng mental model về người đối thoại và đáp ứng expectation neurotypical; quá trình này tăng stress và cognitive load.[^10]

## 4.8. AI trong laptop: hữu ích nhưng có thể thêm ambiguity

AI có thể tóm tắt, rewrite, trích task hoặc đề xuất bước tiếp theo. Nhưng output dài, thay đổi mỗi lần, không chỉ source và tự tin quá mức có thể tạo thêm việc kiểm tra.

Thiết kế nên có:

- format ổn định;
- phân biệt fact, assumption và suggestion;
- source span;
- user chọn độ chi tiết;
- explicit next action;
- không gửi/thay đổi task tự động;
- dễ sửa và hoàn tác.

---

# 5. Họ dùng điện thoại ra sao?

## 5.1. Điện thoại thường là external memory và transition tool

Các cách dùng có thể gồm:

- calendar, reminder, alarm, timer;
- capture nhanh note/voice note/photo;
- navigation và transport planning;
- checklist mua sắm/routine;
- medication reminder;
- communication bằng text thay call;
- đọc text bằng TTS;
- dictation;
- focus mode hoặc app blocking;
- shortcut/widget một chạm.

Điện thoại có lợi thế luôn mang theo, nhưng notification, home screen dày và nhiều app lại tăng distraction.

## 5.2. Các tính năng accessibility có sẵn

Android cung cấp Reading Mode, Select to Speak, dictation, giảm animation, dark theme và Action Blocks cho một số nhu cầu cognitive/learning.[^7] Apple cung cấp Focus, Guided Access, Safari Reader, Background Sounds, Dictation, Accessibility Reader, Assistive Access và Shortcuts ở các thiết bị/phiên bản tương thích.[^11]

Nhưng “feature tồn tại” không có nghĩa người dùng biết, có thiết bị hỗ trợ, hoặc feature làm việc trong app họ cần. Ví dụ Reading Mode của Android không hoạt động với một số format phổ biến.[^7]

## 5.3. Reminder vừa là hỗ trợ vừa có thể thành tiếng ồn

Quá ít cue dẫn tới quên. Quá nhiều cue làm tất cả mất priority. Một reminder tốt có thể cần:

- đúng thời điểm;
- nói rõ hành động;
- có snooze/reschedule không phạt;
- liên kết context cần thiết;
- không tạo guilt;
- phân biệt hard deadline với suggestion;
- tránh stack 20 alert chưa xử lý.

Không nên dùng gamification bắt buộc, streak hoặc thông báo mang tính phán xét nếu chưa được người dùng chọn.

## 5.4. Chuyển từ điện thoại sang laptop

Người dùng có thể capture task trên điện thoại nhưng làm trên laptop. Pain point tiềm năng:

- note nằm trong app khác;
- voice memo chưa thành action;
- link/file không sync;
- reminder chỉ nói “làm báo cáo” nhưng không có trạng thái;
- khi tới laptop phải dựng lại goal và next step.

Đây là cơ hội cho task handoff, nhưng không nhất thiết cần camera hay agent. Một structured checkpoint nhẹ có thể đủ. Brief và end-user phải quyết định.

---

# 6. Công cụ và accommodation hiện có

Assistive technology không chỉ là phần mềm đặc biệt. Accommodation có thể là thay đổi về communication, schedule, environment, job design hoặc support từ con người.

| Nhu cầu | Công cụ/strategy hiện có | Giá trị | Giới hạn/rủi ro |
|---|---|---|---|
| Ghi nhớ | Calendar, reminder, note, checklist, voice memo | Externalize memory | Quá nhiều hệ thống và alert |
| Quản lý thời gian | Timer, visual timer, time blocking, alarm | Thấy thời gian trôi, tạo mốc chuyển task | Ước lượng sai; countdown gây stress |
| Bắt đầu task | Chia nhỏ bước, template, body doubling, first-action cue | Giảm activation energy | Tool tạo quá nhiều bước hoặc infantilize |
| Giữ focus | Focus mode, app blocker, headphone, quiet room | Giảm distraction | Có thể chặn alert cần thiết; không xử lý root cause |
| Phục hồi sau interruption | Checkpoint, note “đang làm gì”, tab group | Khôi phục goal/context | Tracking nền có thể thành surveillance |
| Đọc | TTS, Immersive Reader, Reading Mode, spacing/theme | Đổi presentation và kênh tiếp nhận | Không hỗ trợ mọi format; summary có thể mất nuance |
| Viết | Dictation, spellcheck, word prediction, template | Giảm spelling/motor load | Privacy, lỗi tên riêng/thuật ngữ |
| Hiểu task | Written instruction, example, definition of done, follow-up | Giảm ambiguity | Manager phải tham gia; không thể AI tự đoán |
| Meeting | Agenda trước, captions, transcript, chat, break | Tăng predictability và processing time | Meeting vẫn quá dài; transcript không thay facilitation |
| Sensory | Lighting, seating, headphone, remote work, break | Điều chỉnh môi trường | Preference thay đổi; policy/culture cản trở |
| Change | Báo trước, diff, lý do, affected tasks | Giảm công sức ráp context | Không phải thay đổi nào cũng báo sớm được |
| Social/communication | Mentor, job coach, communication agreement | Làm expectation rõ | Không nên ép disclosure hoặc “dạy diễn neurotypical” |
| Recruitment | Questions trước, ít interviewer, work sample, thêm time | Đo skill gần công việc hơn | Quy trình cũ và bias tổ chức |

JAN gợi ý trong recruitment có thể giảm số interviewer, cung cấp instruction/câu hỏi trước và dùng actual job-skill demonstration. Để duy trì việc làm, họ nêu mentoring, feedback thường xuyên, flexible break, remote work, job restructuring và điều chỉnh ánh sáng/tiếng ồn/nhiệt độ.[^2]

### Lesson cho product team

Nếu một thay đổi quy trình miễn phí giải quyết pain tốt hơn một AI app, hãy chọn thay đổi quy trình hoặc tích hợp nó vào product. ADC chấm impact và feasibility, không chấm số lượng model.

---

# 7. Hành trình công việc và các pain point

## 7.1. Tìm việc và đọc job description

Barrier có thể gồm:

- JD dài, nhiều buzzword và requirement mơ hồ;
- “excellent communication” không nói behavior nào thực sự cần;
- application form dài, timed và mất dữ liệu;
- không rõ cách yêu cầu accommodation;
- lo disclosure sớm ảnh hưởng đánh giá;
- quy trình giả định người nộp có executive function và reading style giống nhau.

Opportunity không phải AI chẩn đoán ứng viên. Có thể là giúp employer viết requirement cụ thể, hoặc cung cấp application flow rõ và adaptable cho mọi người.

## 7.2. Phỏng vấn

Traditional interview thường thưởng cho xử lý verbal tức thời, eye contact, small talk và khả năng đoán câu hỏi hơn là actual job skill. Buckland Review tại Anh tập trung mạnh vào thay đổi employer behavior, quy trình tuyển dụng và support mà không buộc autistic staff phải disclose.[^12]

Accommodation có thể là:

- câu hỏi trước;
- written alternative;
- thêm processing time;
- lịch trình và thành phần rõ;
- work sample;
- ít interviewer;
- không chấm eye contact/body language không liên quan công việc.

Một AI “luyện người dùng nhìn vào camera và cư xử bình thường” đi ngược mục tiêu inclusion.

## 7.3. Onboarding

- lượng thông tin lớn trong vài ngày;
- process và policy nằm rải ở nhiều nơi;
- training dài, không có chapter/checkpoint;
- từ viết tắt và convention ngầm;
- không rõ ai hỏi việc gì;
- lịch thay đổi liên tục;
- phải yêu cầu accommodation khi chưa có psychological safety.

Pain sâu hơn là người mới phải tự xây mental model của tổ chức trong khi input thiếu cấu trúc.

## 7.4. Nhận việc và làm rõ expectation

Một instruction mơ hồ gây khó cho mọi người, nhưng có thể là barrier lớn hơn khi người nhận cần explicit structure hoặc lo social cost của việc hỏi lại. Các từ “nhanh”, “đẹp”, “linh hoạt”, “chủ động” không phải acceptance criteria.

Current workaround:

- nhắn hỏi nhiều lần;
- nhìn bài cũ để đoán;
- bắt đầu một phiên bản rồi chờ correction;
- nhờ đồng nghiệp diễn giải;
- làm nhiều hơn mức cần để tránh thiếu;
- trì hoãn vì không xác định first action.

Hidden cost gồm rework, anxiety, overtime và hiểu lầm thái độ.

## 7.5. Lập kế hoạch, ưu tiên và deadline

- task ở nhiều hệ thống;
- priority thay đổi không giải thích;
- deadline giả và deadline thật trộn lẫn;
- task lớn không có milestone;
- calendar kín không để transition/recovery;
- estimate dựa vào người khác;
- tool hiện tại tạo thêm công việc quản lý tool.

Không nên mặc định AI biết priority tốt hơn người dùng. Priority có dependency, stakeholder và consequence mà model không thấy.

## 7.6. Interruption và quay lại task

Interruption từ message, meeting, đồng nghiệp hoặc chính dependency của công việc có thể làm mất goal stack (chuỗi mục tiêu đang giữ trong đầu). Mở lại tab không đồng nghĩa khôi phục lý do tại sao tab đó quan trọng.

Opportunity là user-controlled checkpoint, không phải continuous employee monitoring.

## 7.7. Meeting và giao tiếp nhóm

- agenda đến muộn hoặc không có;
- turn-taking không rõ;
- câu hỏi bất ngờ yêu cầu trả lời ngay;
- slide, chat và lời nói cùng lúc;
- sarcasm/implicit request;
- action item không được xác nhận bằng text;
- quá nhiều cuộc họp liên tiếp;
- camera-on policy;
- office/video sensory load.

Một meeting summary sau cùng không sửa được việc người dùng không có cơ hội tham gia đúng lúc. Product có thể cần hỗ trợ cả organizer và participant.

## 7.8. Feedback và performance review

Feedback như “hãy proactive hơn” hoặc “cải thiện stakeholder management” không chỉ ra behavior, example hay next action. Người nhận phải giải mã kỳ vọng ngầm. Ngược lại, feedback quá dồn dập hoặc trước đám đông có thể gây overload.

Một format tốt:

```text
Tình huống cụ thể
→ hành vi quan sát được
→ tác động
→ expectation
→ ví dụ đạt yêu cầu
→ quyền hỏi lại
```

AI có thể draft lại cho rõ, nhưng manager chịu trách nhiệm về nội dung và fairness.

## 7.9. Thay đổi kế hoạch, owner hoặc scope

Thông tin thay đổi thường rải trong email/chat/calendar. Người dùng phải so sánh bằng trí nhớ:

- deadline nào mới;
- phần nào bị hủy;
- ai đổi role;
- dependency nào bị ảnh hưởng;
- có cần làm lại không.

Deterministic diff + semantic explanation có thể hữu ích hơn một summary không chỉ source.

## 7.10. Sensory environment và hybrid work

Văn phòng mở có thể khó; ở nhà có thể dễ kiểm soát ánh sáng/âm thanh nhưng tăng isolation, domestic interruption hoặc communication ambiguity. Nghiên cứu remote work cho thấy neurodivergent professionals phải tự tạo accessible physical/digital workspace và thương lượng practice giao tiếp, đồng thời cân bằng productivity với wellbeing.[^4]

Do đó “cho remote work” là một option, không phải giải pháp đầy đủ. Team cần thiết kế flexibility và shared expectation.

## 7.11. Disclosure và accommodation

Pain point thường không chỉ là thiếu tool:

- không biết gọi nhu cầu bằng từ gì;
- không muốn chia diagnosis;
- lo stereotype và career impact;
- manager không biết hỏi functional need;
- process HR yêu cầu nhiều bằng chứng;
- support được duyệt một lần nhưng không review khi task đổi;
- đồng nghiệp xem accommodation là ưu ái.

CIPD báo cáo neurodivergent respondents có mức exhaustion và loneliness cao hơn nhóm neurotypical trong mẫu UK; 33% nói trải nghiệm công việc liên quan neurodivergence có tác động tiêu cực tới mental wellbeing.[^3] Không nên dùng số liệu này để suy ra causal effect hoặc tỷ lệ tại Việt Nam, nhưng nó cho thấy social/organizational layer không thể bị bỏ khỏi solution.

## 7.12. Career progression

Một người có thể làm core work tốt nhưng bị chặn ở activity được dùng làm tín hiệu thăng tiến: networking, presentation bất ngờ, people management theo style duy nhất, training inaccessible hoặc self-promotion. Giải pháp chỉ giúp “hoàn thành checklist hằng ngày” chưa chắc cải thiện employability dài hạn.

---

# 8. Những insight sâu hơn cho ADC

## Insight 1 — Ambiguity là dữ liệu của hệ thống, không phải lỗi của employee

Khi manager giao task thiếu deadline, audience và definition of done, một chatbot tự đoán rồi chia task có thể làm sai nhanh hơn. Giải pháp tốt phải hiển thị missing information và tạo vòng xác nhận hai phía.

**Cơ hội:** facts/ambiguities/assumptions/confirmation thay vì “AI hiểu hộ”.

## Insight 2 — Nhiều pain point nằm ở interface giữa hai người

Task clarity, feedback, meeting và change management đều có sender lẫn receiver. Nếu app chỉ sửa employee, tổ chức tiếp tục giao tiếp inaccessible.

**Cơ hội:** shared work agreement, manager-side guidance và communication contract.

## Insight 3 — Predictability không đồng nghĩa cứng nhắc

Người dùng không nhất thiết cần mọi thứ bất biến; họ có thể cần biết cái gì sắp xảy ra, vì sao đổi và phần nào cần hành động.

**Cơ hội:** change diff, affected-task map và advance notice.

## Insight 4 — Reminder có thể là accessibility hoặc distraction

Cùng một notification có thể cứu task hoặc phá focus. Hành vi đúng phụ thuộc goal, urgency, state và preference — không thể chỉ tăng số reminder.

**Cơ hội:** user-defined interruption policy; “pause with checkpoint” trước khi chuyển.

## Insight 5 — Năng lượng và recovery là tài nguyên ẩn

Calendar planner thường chỉ tối ưu thời gian. Meeting, sensory load và task switching có thể tiêu hao năng lượng không thể hiện trên lịch.

**Cơ hội:** schedule preference và transition buffer do người dùng kiểm soát, không dùng camera để đo emotion/stress.

## Insight 6 — Personalization quan trọng hơn một “neurodivergent mode”

Người này muốn overview, người khác muốn từng bước; người này cần animation off, người khác cần visual cue. Một preset theo diagnosis sẽ sai với nhiều người.

**Cơ hội:** preference profile theo output/interaction, lưu cục bộ và chỉnh được theo task.

## Insight 7 — Disclosure-free design làm giải pháp dễ được dùng hơn

Nếu tính năng chỉ mở khi employee khai diagnosis với employer, adoption và privacy trở thành barrier. Nhiều practice như agenda rõ, written follow-up và flexible presentation có thể cung cấp cho mọi người.

**Cơ hội:** offer choices by default; không xây database chẩn đoán.

## Insight 8 — AI inconsistency có thể chính là accessibility barrier

Một prompt giống nhau nhưng output thay format, thêm bớt trường và không phân biệt fact/suggestion làm người dùng phải học lại mỗi lần.

**Cơ hội:** structured output, stable schema, deterministic diff, source link và explicit uncertainty.

## Insight 9 — Productivity và wellbeing không được tách rời

Một tool tăng số task hoàn thành nhưng tăng pressure, surveillance hoặc masking chưa chắc tạo employability bền vững.

**Cơ hội:** metric gồm confidence, cognitive load, perceived control và willingness to continue, không chỉ speed.

## Insight 10 — Có những vấn đề công nghệ không nên giải bằng AI

Quiet room, câu hỏi phỏng vấn trước, break linh hoạt và manager viết brief rõ đôi khi hiệu quả hơn model. AI chỉ hợp lý khi cần xử lý input không cấu trúc, phát hiện thiếu/mâu thuẫn, cá nhân hóa presentation hoặc giữ context ở quy mô mà rule đơn giản khó làm.

---

# 9. Từ pain point tới các hướng ý tưởng

Các hướng này liên kết với [`ADC_2026_Competitive_Idea_Portfolio.md`](./ADC_2026_Competitive_Idea_Portfolio.md). Chúng chỉ được kích hoạt nếu brief và end-user evidence phù hợp.

## 9.1. ClarityLoop — Shared Work Agreement

### Pain point phù hợp

Yêu cầu công việc mơ hồ khiến employee phải đoán scope, deadline, audience và tiêu chí hoàn thành; hỏi lại nhiều lần có social cost.

### Giải pháp giả thuyết

```text
Email/chat/task
→ extract facts
→ mark ambiguities and assumptions
→ employee chọn câu hỏi
→ manager trả lời/xác nhận
→ shared definition of done + change history
```

### Tại sao AI có ý nghĩa?

Input là natural language nhiều format. AI có thể trích field và gợi ý câu hỏi, nhưng không được tự biến assumption thành fact. Confirmation là phần cốt lõi.

### Cần xác nhận

- Ambiguity nào thực sự làm task chậm?
- Người dùng đang hỏi lại bằng cách nào?
- Manager có chấp nhận một confirmation step không?
- Format agreement có làm quy trình nặng hơn không?
- Người dùng có muốn dùng mà không disclose diagnosis không?

### Loại ý tưởng nếu

- brief chỉ nói focus cá nhân, không có giao việc hai phía;
- end-user nói task đã rất rõ;
- AI task decomposition phổ thông giải quyết đủ;
- không demo được manager loop.

## 9.2. ReturnPoint — phục hồi context sau interruption

### Pain point phù hợp

Sau một interruption, người dùng mất mục tiêu, đoạn reasoning và next action dù tab/file vẫn mở.

### Giải pháp giả thuyết

Người dùng bấm Pause, chọn context được phép, AI tạo checkpoint có cấu trúc; khi quay lại, Resume view trả lời “đang làm gì — đã tới đâu — vướng gì — bước tiếp theo”.

### Privacy boundary

- opt-in;
- không keylogging;
- không chụp nền liên tục;
- không dashboard cho manager;
- xóa checkpoint dễ dàng;
- AI chỉ đọc resource được chọn.

### Cần xác nhận

- Loại interruption nào gây mất context nhất?
- Người dùng có nhớ bấm Pause không?
- Auto-suggestion hay manual note tốt hơn?
- Checkpoint tối thiểu gồm trường gì?
- Việc tạo checkpoint có tốn hơn lợi ích phục hồi không?

## 9.3. ChangeMap — hiểu thay đổi và tác động

### Pain point phù hợp

Brief, lịch hoặc task đổi nhiều phiên bản; người dùng phải tự ráp “cái gì đổi và tôi cần làm gì”.

### Giải pháp giả thuyết

```text
Old + new
→ deterministic diff
→ LLM phân loại deadline/owner/scope/dependency
→ affected tasks + unknown reasons
→ user acknowledgment / clarification
```

### Nguyên tắc

Diff nguyên văn do code xác định. AI giải thích nhưng không sửa lịch sử. Mỗi kết luận link về before/after.

### Rủi ro

Đây có thể chỉ là productivity pain chung. Team phải chứng minh mức ảnh hưởng cụ thể tới target end-user và accessibility outcome.

## 9.4. SensoryPlan — meeting setup theo preference

### Pain point phù hợp

Người tham gia cần agenda, written question, camera choice, quiet break, lighting/noise setup hoặc advance notice nhưng không muốn disclose diagnosis.

### Giải pháp giả thuyết

Participant chọn preference → AI draft request ngắn và trung tính → organizer xác nhận option khả thi → shared meeting plan → báo rõ nếu đổi.

### Điểm mạnh

Không camera emotion detection, không biometric stress score và không chẩn đoán. Người dùng tự nói điều kiện làm việc hiệu quả.

### Điểm yếu

AI necessity thấp hơn; impact phụ thuộc adoption của organizer. Có thể mạnh nếu brief nhấn vào process/attitude và team demo được hai phía.

## 9.5. Hai hướng bổ sung để giữ trong idea bank

### BriefBack — feedback rõ và actionable

Biến feedback mơ hồ thành draft có situation, behavior, impact, expectation, example và next check-in; manager chịu trách nhiệm xác nhận. Không chấm cảm xúc hoặc “độ chuyên nghiệp” của employee.

**Chỉ làm nếu:** brief liên quan career progression/manager communication và end-user xác nhận ambiguous feedback là barrier lặp lại.

### OnboardMap — mental model cho tuần đầu

Biến policy, role map, glossary và training thành journey theo task: cần biết gì bây giờ, hỏi ai, prerequisite nào, đã hoàn thành gì. Có progressive disclosure và presentation preference.

**Chỉ làm nếu:** brief nhấn onboarding; team có một workflow và bộ tài liệu mẫu đủ hẹp. Tránh làm generic RAG chatbot.

## 9.6. Bảng đối chiếu nhanh

| Hướng | Barrier chính | Hai phía? | AI necessity | Scope 3 ngày | Rủi ro lớn nhất |
|---|---|---:|---:|---:|---|
| ClarityLoop | Task ambiguity | Có | Cao | Tốt | Thành task chatbot chung |
| ReturnPoint | Mất context sau interruption | Không bắt buộc | Vừa–cao | Tốt | Surveillance/tracking |
| ChangeMap | Không hiểu tác động của thay đổi | Có thể | Cao | Tốt | Pain quá phổ thông |
| SensoryPlan | Preference meeting không được biết/tôn trọng | Có | Thấp–vừa | Tốt | AI gượng ép, adoption yếu |
| BriefBack | Feedback mơ hồ | Có | Vừa | Tốt | AI che vấn đề quản lý |
| OnboardMap | Quá tải thông tin tuần đầu | Có thể | Vừa–cao | Vừa | Generic RAG, scope lớn |

---

# 10. Cách phỏng vấn end-user trong Day 1–2

## 10.1. Tạo điều kiện tham gia trước khi hỏi insight

- Gửi mục tiêu, chủ đề, câu hỏi chính và thời lượng trước nếu có thể.
- Cho phép trả lời bằng nói, chat hoặc text sau buổi.
- Không yêu cầu eye contact/camera-on.
- Cho phép pause hoặc nghỉ.
- Tránh phòng quá ồn/sáng nếu có thể.
- Hỏi người dùng cần format nào.
- Xin phép trước khi ghi âm, dùng quote hoặc lưu dữ liệu.

User research không accessible sẽ làm mẫu bị lệch về những người có thể chịu được format của team.

## 10.2. Mở đầu

- Anh/chị muốn chúng em dùng từ nào khi nói về trải nghiệm của anh/chị?
- Anh/chị thích buổi trao đổi diễn ra theo format nào?
- Có điều gì về môi trường hoặc cách hỏi giúp anh/chị trả lời thoải mái hơn không?
- Trong công việc, điều kiện nào giúp anh/chị làm tốt nhất?

## 10.3. Hỏi về một sự kiện thật

- Lần gần nhất một task gây khó để bắt đầu/hiểu/hoàn thành là khi nào?
- Ai gửi task, qua kênh nào, câu chữ chính là gì?
- Anh/chị đã hiểu chắc phần nào và phải đoán phần nào?
- Anh/chị đã dùng workaround nào?
- Mất bao lâu? Có rework hoặc phải hỏi ai không?
- Nếu được thay một điểm trong workflow, anh/chị sẽ thay gì?

## 10.4. Hỏi về laptop và điện thoại

- Anh/chị dùng app/tool nào để note, reminder, focus, đọc hoặc viết?
- Tool nào thực sự giúp? Tool nào tạo thêm việc?
- Notification nào cần và notification nào phá focus?
- Khi bị gián đoạn, anh/chị dựa vào dấu vết gì để quay lại?
- Anh/chị có thường capture trên phone rồi làm trên laptop không? Context nào bị mất?
- Presentation preference có thay đổi theo task hoặc mức năng lượng không?

## 10.5. Hỏi về communication và sensory context

- Agenda trước có hữu ích không? Trước bao lâu?
- Spoken, written hay combination nào phù hợp cho instruction/feedback?
- Thay đổi kế hoạch cần được mô tả thế nào?
- Yếu tố môi trường nào ảnh hưởng nhiều nhất?
- Anh/chị hiện điều chỉnh chúng bằng cách nào?
- Có accommodation nào hữu ích nhưng khó yêu cầu không? Vì sao?

## 10.6. Hỏi về AI và quyền kiểm soát

- AI được phép gợi ý điều gì và không được quyết định điều gì?
- Output sai kiểu nào nguy hiểm hoặc tạo thêm stress?
- Anh/chị muốn fact, assumption và suggestion được phân biệt ra sao?
- Dữ liệu task/email/meeting nào không được gửi lên cloud?
- Có chấp nhận tool ghi context tự động không? Nếu có, phạm vi nào?
- Ai được xem data? Bao lâu thì xóa?

## 10.7. Tránh những câu này

- “ADHD có làm anh/chị mất tập trung suốt không?”
- “Người autistic có thích routine đúng không?”
- “Anh/chị có siêu năng lực gì nhờ neurodivergence?”
- “App này giúp anh/chị bình thường hơn chứ?”
- “Anh/chị có thể đại diện cho cộng đồng neurodivergent đánh giá không?”
- “AI nhìn camera để biết lúc nào anh/chị stress nhé?”

Chúng dẫn dắt, stereotype, medicalize hoặc xâm phạm quyền riêng tư.

## 10.8. Template ghi insight

| Trường | Nội dung |
|---|---|
| Context | Role, task, channel, environment; không lưu diagnosis nếu không cần |
| Trigger | Điều gì bắt đầu barrier? |
| Observable event | Chuyện gì thực sự xảy ra? |
| Current workaround | Tool/strategy/human support nào? |
| Cost | Time, rework, fatigue, stress, social/privacy cost |
| Preference | Cách người dùng muốn nhận/điều khiển support |
| Need | Outcome chưa gắn feature |
| Hypothesis | Ý tưởng team muốn kiểm tra |
| Counter-evidence | Điều gì cho thấy idea có thể sai? |
| Design change | Prototype phải thêm/bỏ/sửa gì? |
| Confidence | Thấp/vừa/cao; số người/số tình huống |

---

# 11. Nguyên tắc thiết kế và kiểm thử prototype

## 11.1. Không yêu cầu diagnosis để personalization

Hỏi preference trực tiếp:

- concise hay step-by-step;
- text, audio hay cả hai;
- notification ngay hay digest;
- animation on/off;
- expected time và số bước có hiển thị không;
- confirmation ở action nào;
- theme, font, spacing.

Không tạo “ADHD mode”, “autism score” hoặc hồ sơ gửi cho manager.

## 11.2. UI phải rõ, ổn định và có thể đoán trước

Checklist:

- một purpose rõ cho mỗi screen;
- hierarchy và label nhất quán;
- tối đa vài primary action;
- progressive disclosure;
- control không tự đổi vị trí;
- không animation/flashing không cần thiết;
- cho biết task có bao nhiêu bước và trạng thái hiện tại;
- save/resume;
- error nói rõ chuyện gì, giữ dữ liệu và cách sửa;
- deadline/time rõ, không dùng “soon”;
- không streak/guilt/countdown mặc định;
- keyboard và screen reader vẫn hoạt động;
- font/spacing/zoom/theme không làm vỡ layout.

W3C COGA xem clear purpose, familiar design, focus support, memory support và personalization là các mục tiêu cốt lõi.[^9]

## 11.3. AI phải phân biệt fact, ambiguity, assumption và suggestion

Ví dụ contract cho ClarityLoop:

```json
{
  "facts": [
    {
      "field": "deliverable",
      "value": "presentation deck",
      "sourceSpan": "làm deck"
    }
  ],
  "ambiguities": [
    {
      "field": "deadline",
      "sourceSpan": "sớm nhé",
      "question": "Anh cần bản đầu tiên vào ngày và giờ nào?"
    }
  ],
  "assumptions": [],
  "suggestions": [
    "Ask who the audience is"
  ],
  "status": "awaiting_confirmation"
}
```

Format phải ổn định qua nhiều lần chạy. User sửa được, và output cuối chỉ đánh dấu “confirmed” sau khi bên có thẩm quyền xác nhận.

## 11.4. Không biến hỗ trợ thành giám sát

Tránh:

- emotion/attention detection bằng webcam;
- chấm điểm focus;
- log tab/app/keystroke mặc định;
- dashboard năng suất gửi manager;
- suy chẩn đoán từ hành vi;
- tự đổi lịch/task mà user không biết.

Nếu cần context:

- opt-in theo session/task;
- data minimization;
- xem trước thứ sẽ được gửi;
- local processing khi khả thi;
- retention rõ;
- delete/export;
- không dùng lại cho đánh giá nhân sự.

## 11.5. Metrics phải đo outcome và agency

| Nhóm metric | Ví dụ |
|---|---|
| Task understanding | Người dùng nói đúng goal, deadline, output, next step |
| Completion | Hoàn thành đúng task, ít rework |
| Efficiency | Time-to-start, resumption lag, số clarification turn |
| Cognitive load | Rating sau task, không suy từ camera |
| Confidence | “Tôi biết phải làm gì tiếp theo” |
| Agency | Biết AI đã suy luận gì; sửa/tắt/xóa được |
| Communication | Hai phía đồng thuận definition of done |
| Safety/privacy | Không unauthorized action/data exposure |
| Adoption | Employee và manager có sẵn sàng dùng lại? |

So sánh prototype với current workaround, không chỉ demo happy path. Có test failure: thiếu deadline, hai nguồn mâu thuẫn, model timeout, output sai schema và user không muốn share context.

## 11.6. Co-design thay vì chỉ usability test cuối

End-user nên tham gia ở ba điểm:

1. chọn barrier đáng giải quyết;
2. quyết định interaction/output;
3. đánh giá prototype và trade-off.

W3C khuyến nghị đưa người có cognitive/learning disabilities vào research, design và testing vì họ là chuyên gia về điều gì phù hợp với mình.[^9]

---

# 12. Cách quyết định có chọn Neurodivergence hay không

Sau khi nhận brief, chấm mỗi câu 0–2:

| Câu hỏi | 0 | 1 | 2 |
|---|---|---|---|
| Target user/functional need có cụ thể? | “Người ND” chung chung | Có nhóm rộng | Profile + task rõ |
| Workplace moment rõ? | Không | Có nhưng dài | Một khoảnh khắc cụ thể |
| Có end-user evidence? | Không | Một tín hiệu | Lặp lại/quan sát được |
| Workaround có cost? | Không rõ | Nhẹ | Đo được/ảnh hưởng participation |
| Solution tránh stereotype/diagnosis? | Không | Một phần | Preference-based |
| Giải quyết cả system khi cần? | Chỉ sửa employee | Có nhắc employer | Workflow hai phía rõ |
| AI thật sự cần? | Không | Có thể | Vai trò riêng và measurable |
| Có MVP 3 ngày? | Không | Rủi ro | Một vertical slice chắc chắn |
| Privacy/surveillance boundary? | Không | Còn gap | Rõ và demo được |
| Có thể đo task + agency? | Không | Một phần | Baseline và metrics rõ |

### Quy tắc

- **17–20:** đáng shortlist.
- **12–16:** tiếp tục discovery và cắt scope.
- **0–11:** bỏ hoặc đổi problem.

Team không chọn Neurodivergence chỉ vì LLM dễ làm chatbot/task planner. Hãy chọn khi team tìm thấy một barrier cụ thể mà công cụ hiện tại và thay đổi quy trình đơn giản chưa giải quyết đủ.

---

# 13. Nguồn tham khảo

[^1]: W3C Web Accessibility Initiative. “[Cognitive and learning disabilities — Diverse Abilities and Barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/cognitive/).” Truy cập 12/09/2026.
[^2]: Job Accommodation Network. “[Neurodiversity](https://askjan.org/disabilities/Neurodiversity.cfm)” và “[Autism Spectrum](https://askjan.org/disabilities/Autism-Spectrum.cfm).” Truy cập 12/09/2026. JAN là nguồn hướng dẫn accommodation trong bối cảnh Mỹ; suggestion phải được cá nhân hóa và không tự động áp dụng cho Việt Nam.
[^3]: Thompson, Ed và Jill Miller, CIPD/Uptimize. “[Neuroinclusion at work report 2024](https://www.cipd.org/globalassets/media/knowledge/knowledge-hub/reports/2024-pdfs/2024-neuroinclusion-at-work-report-8545.pdf).” 20/02/2024. Employee sample tại UK gồm 1.047 người, 790 tự nhận neurodivergent; không đại diện Việt Nam và có đối tác chuyên về neuroinclusion tham gia báo cáo.
[^4]: Das, Maitraye và cộng sự. “[Towards Accessible Remote Work: Understanding Work-from-Home Practices of Neurodivergent Professionals](https://www.microsoft.com/en-us/research/publication/towards-accessible-remote-work-understanding-work-from-home-practices-of-neurodivergent-professionals/).” *Proceedings of the ACM on Human-Computer Interaction*, CSCW 2021. Phỏng vấn 36 professionals tại Mỹ trong bối cảnh đại dịch.
[^5]: Tomczak, Michał T. và cộng sự. “[Autistic Employees’ Technology-Based Workplace Accommodation Preferences Survey—Preliminary Findings](https://pmc.ncbi.nlm.nih.gov/articles/PMC10218232/).” *International Journal of Environmental Research and Public Health*, 2023. N=140; là khảo sát preference sơ bộ, không chứng minh hiệu quả của solution và không đại diện mọi người autistic.
[^6]: Microsoft Support. “[Accessibility tools for neurodiversity](https://support.microsoft.com/en-us/accessibility/accessibility-tools-for-neurodiversity).” Truy cập 12/09/2026. Nguồn nhà sản xuất dùng để xác nhận feature, không phải đánh giá hiệu quả độc lập.
[^7]: Google Android Accessibility Help. “[Use accessibility features on Android](https://support.google.com/accessibility/android/answer/16323943?hl=en)” và “[Use Reading mode](https://support.google.com/accessibility/android/answer/13026948?hl=en).” Truy cập 12/09/2026.
[^8]: Job Accommodation Network. “[Executive Functioning Deficits](https://askjan.org/articles/Executive-Functioning-Deficits.cfm).” Truy cập 12/09/2026.
[^9]: W3C Cognitive and Learning Disabilities Accessibility Task Force. “[Making Content Usable for People with Cognitive and Learning Disabilities](https://www.w3.org/TR/coga-usable/).” Working Group Note, 29/04/2021. Đây là supplemental guidance vượt ngoài WCAG và không phải normative conformance standard.
[^10]: Microsoft Research. “[How research can enable more effective remote work](https://www.microsoft.com/en-us/research/blog/how-research-can-enable-more-effective-remote-work/).” 09/04/2020; phần tóm tắt nghiên cứu video communication với người autistic.
[^11]: Apple. “[Accessibility Features](https://www.apple.com/accessibility/features/).” Truy cập 12/09/2026. Feature và availability thay đổi theo thiết bị, hệ điều hành, ngôn ngữ và khu vực.
[^12]: UK Department for Work and Pensions. “[The Buckland Review of Autism Employment](https://www.gov.uk/government/publications/the-buckland-review-of-autism-employment-report-and-recommendations/the-buckland-review-of-autism-employment-report-and-recommendations).” 28/02/2024. Đây là review về autism và employment tại UK, không phải toàn bộ neurodivergence hoặc bối cảnh Việt Nam.

---

## Lời nhắc cuối

Đừng bắt đầu Day 1 bằng câu “chúng ta sẽ làm task planner cho người ADHD”. Hãy bắt đầu bằng:

> Người này muốn hoàn thành outcome nào, mismatch nằm ở instruction, interruption, sensory environment, communication hay process; họ đã tự thích nghi ra sao; và thay đổi nào tăng quyền tham gia mà không buộc disclosure hoặc surveillance?

Chỉ sau khi có câu trả lời từ brief và end-user, team mới quyết định dùng quy trình, UI thông thường hay AI.
