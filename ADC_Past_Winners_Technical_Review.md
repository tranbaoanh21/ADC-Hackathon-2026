# Các dự án đoạt giải ADC qua các năm — Phân tích sản phẩm và kỹ thuật

> **Mục đích của tài liệu:** tập hợp những thông tin công khai đáng tin cậy về các dự án từng đoạt giải Accessibility Design Competition (ADC), sau đó phân tích cách mỗi sản phẩm có thể được xây dựng về mặt kỹ thuật. Đây là tài liệu tham khảo để cả nhóm hiểu mặt bằng cuộc thi trước khi bàn và chọn ý tưởng cho ADC Hackathon 2026; tài liệu này **chưa phải quyết định chọn đề tài**.
>
> **Cập nhật lần cuối:** 03/09/2026.

---

## Mục lục

1. [Cách đọc tài liệu này](#1-cách-đọc-tài-liệu-này)
2. [Tổng quan các dự án được công bố](#2-tổng-quan-các-dự-án-được-công-bố)
3. [ADC 2020 — Thiết bị hỗ trợ vận động, nhạc Braille và ngôn ngữ ký hiệu](#3-adc-2020--thiết-bị-hỗ-trợ-vận-động-nhạc-braille-và-ngôn-ngữ-ký-hiệu)
4. [ADC 2022 — HANDTALK, Accesstant và HTV3](#4-adc-2022--handtalk-accesstant-và-htv3)
5. [ADC 2023 — AI Speech Companion và bộ khớp cơ khí đa năng](#5-adc-2023--ai-speech-companion-và-bộ-khớp-cơ-khí-đa-năng)
6. [ADC 2024 — The Great Musica, Lexopia, CommuniCare và Vista](#6-adc-2024--the-great-musica-lexopia-communicare-và-vista)
7. [Microsoft AI for Accessibility 2024 — SightSence](#7-microsoft-ai-for-accessibility-2024--sightsence)
8. [ADC 2025 — AllStep, NeuroAICC, 7 Rings và InSight](#8-adc-2025--allstep-neuroaicc-7-rings-và-insight)
9. [So sánh kỹ thuật giữa các thế hệ dự án](#9-so-sánh-kỹ-thuật-giữa-các-thế-hệ-dự-án)
10. [Những bài học có thể dùng khi phân tích ý tưởng sau này](#10-những-bài-học-có-thể-dùng-khi-phân-tích-ý-tưởng-sau-này)
11. [Những thông tin vẫn chưa thể xác nhận](#11-những-thông-tin-vẫn-chưa-thể-xác-nhận)
12. [Nguồn tham khảo](#12-nguồn-tham-khảo)

---

# 1. Cách đọc tài liệu này

ADC không có một kho lưu trữ chung chứa source code (mã nguồn), model card (hồ sơ mô hình), dataset (tập dữ liệu) và báo cáo kỹ thuật của tất cả đội thắng. Phần lớn bài viết của RMIT chỉ công bố:

- đối tượng người dùng;
- vấn đề mà đội muốn giải quyết;
- các chức năng nổi bật;
- kết quả hoặc thứ hạng;
- đôi khi có tên một số công nghệ.

Vì vậy, tài liệu sử dụng ba nhãn sau để tránh biến phỏng đoán thành sự thật:

- **Thông tin đã công bố:** có nguồn chính thức hoặc nguồn trực tiếp từ trường, sản phẩm hay thành viên của đội.
- **Phân tích kỹ thuật:** kiến trúc hợp lý nếu xây dựng một sản phẩm có chức năng như mô tả. Đây không phải xác nhận đội đã dùng đúng kiến trúc đó.
- **Chưa được công bố:** chi tiết hiện chưa có đủ bằng chứng, chẳng hạn model, dataset, cloud service (dịch vụ đám mây), giao thức hoặc chỉ số đánh giá.

Các con số do đội tự công bố cũng được giữ đúng ngữ cảnh. Ví dụ, “độ chính xác 92%” không tự động chứng minh một hệ thống đã hoạt động tốt ngoài thực tế nếu chưa biết số lớp, cách chia tập kiểm thử, số người tham gia và điều kiện đo.

ADC được tổ chức lần đầu năm 2020. Mùa thứ hai diễn ra năm 2022, vì vậy chuỗi các mùa công khai trước ADC 2026 là **2020, 2022, 2023, 2024 và 2025**, không có một mùa ADC 2021 riêng được RMIT công bố.

---

# 2. Tổng quan các dự án được công bố

| Năm | Thành tích | Đội/dự án | Nhóm người dùng hoặc vấn đề chính |
|---|---|---|---|
| 2020 | Quán quân | Team Eccentrics | Thiết bị cảm biến không dây và nhận dạng giọng nói cho người khuyết tật vận động |
| 2020 | Á quân | Team Bibbidi Bobbidi Boo | Giúp nhạc sĩ khiếm thị truy cập nốt nhạc qua Braille/screen reader |
| 2020 | Hạng ba | Tên đội không được nêu rõ | Dịch ngôn ngữ ký hiệu và web portal |
| 2022 | Quán quân | HDK — HANDTALK | Giao tiếp giữa người dùng ngôn ngữ ký hiệu và người nghe |
| 2022 | Á quân | KINTSUGI — Accesstant | Ghi chú và hỗ trợ xử lý thông tin cho người có khác biệt giác quan/thần kinh |
| 2022 | Hạng ba | HTV3 | Phát triển tài năng và thu nhập cho người ADHD |
| 2023 | Quán quân | ATP — AI Speech Companion | Chuẩn bị giao tiếp, họp, thuyết trình và phỏng vấn cho người nói lắp |
| 2023 | Á quân | 4D BonDe — Versatile Mechanical Joint System | Thao tác công cụ làm việc cho người khuyết tật chi trên |
| 2024 | Quán quân | The Great Musica | Thư viện và chuyển đổi bản nhạc Braille Việt Nam |
| 2024 | Á quân | Lexopia | Đọc và viết tại nơi làm việc cho người mắc chứng khó đọc |
| 2024 | Đồng hạng ba | HiWin — CommuniCare | Giải pháp kết hợp AI, phần cứng và IoT |
| 2024 | Đồng hạng ba | Vista | Chi tiết sản phẩm công khai còn thiếu |
| 2025 | Quán quân | AllStep | Walker thông minh cho người bại não |
| 2025 | Á quân | Powerpuff Girls — NeuroAICC | Luyện phỏng vấn và tài nguyên việc làm cho người tự kỷ |
| 2025 | Đồng hạng ba | 7 Rings | Dịch thời gian thực giữa Ngôn ngữ ký hiệu Việt Nam và lời nói |
| 2025 | Đồng hạng ba | InSight | Tín hiệu xã hội và tương tác tại nơi làm việc cho người khiếm thị |

Danh sách trên chỉ thể hiện những thứ hạng và dự án tìm được bằng nguồn công khai đủ tin cậy. Không nên hiểu bảng này là kho lưu trữ chính thức, đầy đủ mọi giải phụ của từng mùa.

---

# 3. ADC 2020 — Thiết bị hỗ trợ vận động, nhạc Braille và ngôn ngữ ký hiệu

## 3.1. Quán quân: Team Eccentrics

### Thông tin đã công bố

Team Eccentrics gồm Utkarsh Sarbahi, Huy Luong và Dushan Puhuwellage. Đội hợp tác với Schaeffler Vietnam và phát triển một **thiết bị cảm biến không dây kết hợp cơ chế nhận dạng giọng nói** dành cho người khuyết tật vận động.

Nguồn công khai không mô tả rõ người dùng điều khiển máy tính, thiết bị công nghiệp hay một loại giao diện khác. Nó cũng không cho biết sản phẩm mới ở mức proof of concept (bản chứng minh khả thi) hay đã được thử nghiệm trong dây chuyền thực tế.

### Phân tích kỹ thuật

Với mô tả được công bố, hệ thống có thể được tách thành bốn lớp:

```text
Giọng nói hoặc chuyển động mà người dùng còn thực hiện được
                            ↓
             Microphone / sensor node
                            ↓
      Xử lý tín hiệu và nhận dạng lệnh có chủ đích
                            ↓
               Kết nối không dây
                            ↓
        Thiết bị, máy tính hoặc giao diện cần điều khiển
```

Một implementation (cách hiện thực) thực tế phải giải quyết:

- **Input calibration (hiệu chỉnh đầu vào):** ngưỡng cảm biến phải phù hợp với khả năng vận động khác nhau của từng người.
- **False activation (kích hoạt nhầm):** tiếng ồn hoặc chuyển động vô ý không được biến thành lệnh nguy hiểm.
- **Command confirmation (xác nhận lệnh):** lệnh quan trọng nên có bước xác nhận bằng âm thanh, hình ảnh hoặc rung.
- **Latency (độ trễ):** phản hồi chậm sẽ khiến thao tác khó dự đoán và gây mệt mỏi.
- **Wireless reliability (độ ổn định kết nối không dây):** hệ thống phải có hành vi an toàn khi mất kết nối.
- **Fallback (phương án dự phòng):** người dùng cần một cách dừng hoặc hủy thao tác không phụ thuộc vào AI.

### Chi tiết chưa được công bố

- Loại cảm biến và vi điều khiển.
- Bluetooth, Wi-Fi hay giao thức riêng.
- Model hoặc dịch vụ speech recognition (nhận dạng giọng nói).
- Vocabulary (tập lệnh) và ngôn ngữ hỗ trợ.
- Độ chính xác, độ trễ và kết quả thử nghiệm với người dùng.

### Vì sao bài này đáng chú ý

Đây là ví dụ sớm cho tư duy **alternative input (đầu vào thay thế)**: hệ thống không yêu cầu người dùng thích nghi với giao diện tiêu chuẩn mà biến khả năng hiện có của họ thành lệnh thao tác được trong công việc.

## 3.2. Á quân: Team Bibbidi Bobbidi Boo

### Thông tin đã công bố

Đội xây dựng phần mềm chuyển đổi hoặc biểu diễn thông tin âm nhạc để nhạc sĩ khiếm thị có thể tiếp cận nốt nhạc bằng Braille và screen reader (trình đọc màn hình). Cách diễn đạt khác nhau giữa các bài viết của RMIT, nhưng điểm chung là sản phẩm giúp người khiếm thị truy cập bản nhạc theo định dạng số dễ tiếp cận hơn.

### Phân tích kỹ thuật

Bản nhạc in là một biểu diễn không gian hai chiều. Braille và screen reader lại trình bày nội dung theo chuỗi tuyến tính. Vì vậy phần quan trọng nhất không phải chỉ là đổi ký tự, mà là bảo toàn cấu trúc âm nhạc.

Một pipeline (chuỗi xử lý) phù hợp có thể là:

```text
Bản nhạc ở định dạng có cấu trúc
              ↓
     Music notation parser
              ↓
Biểu diễn trung gian: cao độ, trường độ, ô nhịp,
dấu lặng, bè, hợp âm, dấu hóa, lặp, sắc thái...
              ↓
       Braille music rule engine
              ↓
Braille text / BRF / screen reader / Braille display
```

Nếu sản phẩm nhận ảnh scan hoặc ảnh chụp bản nhạc, cần thêm Optical Music Recognition — OMR (nhận dạng ký hiệu âm nhạc quang học):

```text
Ảnh bản nhạc
     ↓
Phát hiện khuông nhạc và ký hiệu
     ↓
Nhận dạng quan hệ giữa các ký hiệu
     ↓
Khôi phục dữ liệu nhạc có cấu trúc
```

Tuy nhiên, không có nguồn nào xác nhận đội đã triển khai OMR. Vì vậy không nên mô tả OCR/OMR là công nghệ chắc chắn của sản phẩm.

### Những bài toán kỹ thuật khó

- Nhiều bè xuất hiện song song nhưng phải chuyển thành một thứ tự đọc hợp lý.
- Một ký hiệu có thể phụ thuộc vào ngữ cảnh trước và sau nó.
- Screen reader phải đọc theo nhóm có nghĩa thay vì phát ra một chuỗi ký tự khó hiểu.
- Một lỗi cao độ hoặc trường độ nhỏ cũng làm bản nhạc sai về chuyên môn.
- Cần kiểm thử với người thực sự đọc Braille music, không chỉ với người phát triển.

## 3.3. Hạng ba: phần mềm dịch ngôn ngữ ký hiệu và web portal

### Thông tin đã công bố

RMIT cho biết bài hạng ba là phần mềm dịch ngôn ngữ ký hiệu đi kèm một cổng thông tin web. Tên đội, phạm vi ngôn ngữ và chi tiết kỹ thuật không được công bố rõ.

### Phân tích kỹ thuật

Nếu hệ thống nhận ngôn ngữ ký hiệu qua camera, luồng cơ bản có thể là:

```text
Camera
  ↓
Phát hiện bàn tay, cơ thể và khuôn mặt
  ↓
Trích xuất đặc trưng theo thời gian
  ↓
Nhận dạng ký hiệu hoặc dịch chuỗi ký hiệu
  ↓
Văn bản
  ↓
Text-to-Speech / web portal
```

Cần phân biệt hai mức bài toán:

- **Sign classification (phân loại ký hiệu):** nhận ra một động tác đơn lẻ trong tập từ vựng cố định.
- **Sign-language translation (dịch ngôn ngữ ký hiệu):** xử lý câu liên tục, ngữ pháp, ngữ cảnh, nét mặt và chuyển động cơ thể.

Mức thứ hai khó hơn rất nhiều và không thể suy ra chỉ từ việc demo một số ký hiệu đơn.

---

# 4. ADC 2022 — HANDTALK, Accesstant và HTV3

## 4.1. Quán quân: HDK — HANDTALK

### Thông tin đã công bố

HANDTALK có hai chức năng chính:

1. Chuyển ngôn ngữ ký hiệu của người dùng thành lời nói.
2. Hiển thị thành văn bản lời nói của người đối diện.

Đội sử dụng một camera hồng ngoại kết nối với điện thoại để theo dõi bàn tay. Đội công bố độ chính xác có thể đạt **92%** và cho rằng hệ thống hoạt động tốt trong nhiều điều kiện.

### Phân tích kỹ thuật: chiều ngôn ngữ ký hiệu sang lời nói

```text
Camera hồng ngoại
        ↓
Hand tracking / landmark extraction
(theo dõi tay / trích xuất các điểm mốc)
        ↓
Chuỗi tọa độ bàn tay theo thời gian
        ↓
Temporal classifier
(mô hình phân loại dữ liệu tuần tự)
        ↓
Nhãn ký hiệu hoặc chuỗi văn bản
        ↓
Text-to-Speech
```

Camera hồng ngoại có thể giúp hệ thống ít phụ thuộc hơn vào màu da, nền và ánh sáng nhìn thấy. Tùy loại camera, nó có thể cung cấp ảnh hồng ngoại hoặc depth map (bản đồ độ sâu), thuận lợi cho việc tách bàn tay khỏi nền.

Sau khi lấy chuỗi landmark (điểm mốc), một hệ thống tương tự có thể dùng:

- LSTM/GRU cho chuỗi chuyển động;
- Temporal Convolutional Network;
- Transformer theo thời gian;
- hoặc classifier nhẹ nếu mỗi ký hiệu là một tư thế tĩnh.

Đây chỉ là các lựa chọn kỹ thuật khả dĩ. Nguồn không công bố HANDTALK dùng model nào.

### Phân tích kỹ thuật: chiều lời nói sang văn bản

```text
Microphone điện thoại
        ↓
Voice activity detection
        ↓
Streaming Speech-to-Text
        ↓
Văn bản lớn, tương phản rõ và cập nhật theo thời gian thực
```

Ở chiều này, UI (giao diện người dùng) cũng quan trọng như model. Transcript cần ổn định, dễ đọc, phân biệt người nói nếu có thể, cho phép xem lại và không thay đổi cả câu quá nhiều trong lúc người dùng đang đọc.

### Cách hiểu đúng con số 92%

Để biết 92% có ý nghĩa hay không, cần ít nhất các thông tin:

- số lượng ký hiệu;
- số người thực hiện ký hiệu;
- có tách người giữa tập train và test hay không;
- ký hiệu tĩnh hay ký hiệu động;
- kiểm thử câu liên tục hay từng từ riêng lẻ;
- accuracy (độ chính xác tổng thể), macro-F1 hay top-k accuracy;
- điều kiện nền, góc quay, khoảng cách và che khuất.

Nếu cùng một người xuất hiện ở cả train và test, model có thể học đặc điểm cá nhân và cho kết quả đẹp hơn khả năng tổng quát hóa thật. Ngoài ra, Ngôn ngữ ký hiệu Việt Nam có khác biệt vùng miền; một vocabulary nhỏ không đồng nghĩa hệ thống đã “dịch được VSL”.

### Ghi chú về mã nguồn trên Internet

Có repository công khai trùng tên HandTalk sử dụng Flutter, MediaPipe, Bi-LSTM, Flask/Socket.IO và TensorFlow. Tuy nhiên, không có bằng chứng đủ mạnh cho thấy repository đó thuộc đội HDK tại ADC 2022. Vì vậy tài liệu này **không gán** stack đó cho dự án.

## 4.2. Á quân: KINTSUGI — Accesstant

### Thông tin đã công bố

Accesstant là ứng dụng ghi chú có thể tùy biến cho người có khác biệt về giác quan hoặc thần kinh. Các chức năng được công bố gồm:

- chuyển âm thanh thành văn bản theo thời gian thực;
- tạo flashcard (thẻ ghi nhớ);
- tạo lời nhắc;
- hỗ trợ tiếng Việt và tiếng Anh;
- hoạt động trên Android và iOS.

Sofitel Saigon Plaza đã chấp nhận thử nghiệm sản phẩm. Đây là một tín hiệu feasibility (tính khả thi) đáng chú ý vì giải pháp được đặt vào bối cảnh tổ chức thật.

### Phân tích kỹ thuật

```text
Âm thanh cuộc họp, lớp học hoặc hướng dẫn công việc
                         ↓
             Streaming Speech-to-Text
                         ↓
        Transcript có timestamp và phân đoạn
                         ↓
      Chọn ý chính / chuyển thành đơn vị thông tin
                         ↓
           Note / flashcard / reminder
                         ↓
        Lưu trữ, tìm kiếm và notification
```

Một phiên bản tốt không nên tự động biến mọi câu nói thành flashcard. Người dùng cần quyền kiểm soát:

- đánh dấu đoạn quan trọng;
- chỉnh nội dung nhận dạng sai;
- chọn thời điểm và cách nhắc;
- quyết định dữ liệu nào được lưu;
- xóa audio sau khi tạo transcript.

Nếu dùng AI để tóm tắt, sản phẩm cần liên kết mỗi ý tóm tắt với đoạn transcript gốc để người dùng kiểm chứng. Với dữ liệu họp tại doanh nghiệp, privacy (quyền riêng tư), consent (sự đồng thuận) và retention policy (chính sách lưu giữ) là phần kỹ thuật bắt buộc chứ không chỉ là câu chữ pháp lý.

### Vì sao sản phẩm mạnh

Accesstant không dừng ở Speech-to-Text. Nó nối việc tiếp nhận thông tin với ghi nhớ và hành động sau cuộc họp. Chính workflow (quy trình sử dụng) hoàn chỉnh này tạo ra giá trị sản phẩm.

## 4.3. Hạng ba: HTV3

### Thông tin đã công bố

HTV3 đề xuất chương trình phát triển tài năng nhằm giúp người ADHD cải thiện cơ hội và thu nhập. Nguồn công khai không mô tả một hệ thống AI, ứng dụng hoặc stack cụ thể.

### Ý nghĩa đối với cách hiểu ADC

HTV3 cho thấy ADC không chỉ trao giải cho phần mềm hay phần cứng. Một service design (thiết kế dịch vụ), chương trình đào tạo hoặc quy trình doanh nghiệp vẫn có thể đạt thứ hạng nếu tạo được tác động rõ và có cách triển khai khả thi.

---

# 5. ADC 2023 — AI Speech Companion và bộ khớp cơ khí đa năng

## 5.1. Quán quân: ATP — AI Speech Companion

### Thông tin đã công bố

AI Speech Companion hỗ trợ người nói lắp chuẩn bị cho các tình huống giao tiếp trực tiếp như:

- phỏng vấn;
- họp;
- thuyết trình;
- trao đổi tại nơi làm việc.

Sản phẩm có ba nhóm chức năng chính.

#### Active Memo

Người dùng nhập kịch bản. AI phân tích và chia nội dung thành các bước dựa trên phương pháp C.O.D.E hoặc “second brain” (hệ thống tổ chức tri thức cá nhân).

#### Active Mockup

Sản phẩm mô phỏng tình huống giao tiếp có giới hạn thời gian. Người dùng luyện tập với AI và nhận phản hồi sau buổi tập.

#### SOS

Sản phẩm cá nhân hóa bốn nhóm chiến lược hỗ trợ bình tĩnh tức thời: màu sắc, đọc, âm nhạc và hình ảnh.

### Phân tích kỹ thuật

```text
Hồ sơ người dùng + mục tiêu giao tiếp
                    ↓
             Script / prompt
                    ↓
Phân đoạn, sắp xếp và viết lại nội dung bằng NLP
                    ↓
          Kịch bản luyện tập từng bước
                    ↓
        Microphone → Speech-to-Text
                    ↓
Phân tích tiến độ, thời lượng, khoảng dừng và mức hoàn thành
                    ↓
             Feedback cá nhân hóa
```

Active Memo có thể dùng rule-based processing (xử lý theo quy tắc), Large Language Model — LLM (mô hình ngôn ngữ lớn), hoặc kết hợp cả hai để:

- chia nội dung dài thành từng đoạn;
- rút gọn câu nhưng không thay đổi ý;
- đánh dấu từ khóa;
- sắp xếp thành cue card (thẻ gợi ý);
- tạo nhiều mức chi tiết.

Active Mockup cần một state machine (máy trạng thái) để quản lý cuộc luyện tập: bắt đầu, đưa câu hỏi, đếm thời gian, nhận câu trả lời, phản hồi và chuyển lượt. AI có thể tạo câu hỏi hoặc phản hồi, nhưng các chỉ số như thời gian nói và mức hoàn thành nên được tính bằng logic xác định để dễ giải thích.

SOS không nhất thiết cần một model phức tạp. Một recommendation engine dựa trên lựa chọn và phản hồi trước đó của người dùng có thể an toàn, dễ kiểm soát và phù hợp hơn.

### Chi tiết chưa được công bố

Microsoft cho biết các đội trong chương trình AI for Accessibility đã xây dựng ứng dụng có sử dụng Azure, nhưng không xác nhận ATP dùng chính xác Azure service nào. Các mô tả Azure Cognitive Services, Translator hoặc AI chat trong cùng bài viết có thể thuộc đội khác; không nên gán chúng cho ATP.

### Vì sao bài này mạnh

Sản phẩm không tuyên bố “chữa” nói lắp. Nó hỗ trợ cả một hành trình:

```text
Chuẩn bị → luyện tập → tham gia tình huống → hỗ trợ khi căng thẳng
```

Điều này vừa thực tế hơn, vừa giảm rủi ro của một medical claim (tuyên bố mang tính y khoa) không có bằng chứng.

## 5.2. Á quân: 4D BonDe — Versatile Mechanical Joint System

### Thông tin đã công bố

Đội phát triển một bộ khớp cơ khí gắn vào cẳng tay cho người khuyết tật chi trên. Đầu còn lại của khớp có thể kết nối với nhiều functional attachment (đầu công cụ chức năng) để người dùng:

- giữ thìa, dao hoặc vật hình trụ;
- gõ tổ hợp ba phím;
- sử dụng chuột;
- đổi đầu công cụ theo nhiệm vụ.

Thiết kế có lớp đệm xốp thoáng khí tùy chỉnh theo cẳng tay, có thể tích hợp khóa tự động và đã trải qua khoảng mười lần tinh chỉnh sau cuộc thi. Đội đồng thiết kế cùng hai người khuyết tật.

### Phân tích kỹ thuật

```text
Cẳng tay người dùng
        ↓
Forearm cuff + lớp đệm tùy chỉnh
        ↓
Khớp cơ khí + cơ chế khóa
        ↓
Chuẩn giao tiếp module
        ↓
Đầu cầm chuột / bàn phím / thìa / vật hình trụ
```

Các quyết định kỹ thuật cốt lõi gồm:

- **Fit (độ vừa):** cuff không được trượt nhưng cũng không gây điểm tì quá lớn.
- **Load path (đường truyền lực):** lực từ công cụ phải truyền đều lên vùng cẳng tay chịu lực được.
- **Degrees of freedom (bậc tự do):** đủ linh hoạt để thao tác nhưng không khiến khớp mất ổn định.
- **Locking mechanism (cơ cấu khóa):** dễ kích hoạt, ít lực và không tự mở ngoài ý muốn.
- **Attachment interface (chuẩn gắn đầu công cụ):** thay nhanh, không lắp sai chiều và có thể mở rộng.
- **Material (vật liệu):** nhẹ, bền, dễ vệ sinh, giá hợp lý và không kích ứng da.

### Các bài kiểm thử cần thiết

- tải trọng và mô-men cực đại;
- số chu kỳ đóng/mở trước khi mỏi vật liệu;
- thời gian đổi attachment;
- áp lực lên da tại các điểm tiếp xúc;
- mức mỏi sau một phiên làm việc;
- độ chính xác khi click, kéo chuột hoặc bấm tổ hợp phím;
- khả năng tự lắp và tháo bằng năng lực còn lại của người dùng.

### Vì sao bài này quan trọng

Đây là bằng chứng rõ rằng ADC không ưu tiên AI một cách máy móc. Một thiết kế cơ khí đơn giản, giá phù hợp, đã thử với người dùng và giải quyết đúng thao tác công việc có thể cạnh tranh rất mạnh.

---

# 6. ADC 2024 — The Great Musica, Lexopia, CommuniCare và Vista

## 6.1. Quán quân: The Great Musica

### Thông tin đã công bố

The Great Musica phát triển:

- một thư viện bản nhạc Braille Việt Nam;
- chức năng chuyển bản nhạc thông thường sang Braille;
- chức năng upload (tải lên) và quản lý nội dung;
- cộng đồng “Blind Music Lovers”.

Ý tưởng xuất phát từ trải nghiệm của một thành viên khiếm thị trong đội. Nhóm hợp tác với Sao Mai Center for the Blind và Fulbright Digital Humanities Lab. Tại thời điểm Fulbright đăng bài, đội vẫn tập trung phát triển chức năng lõi, UI/UX, chuyển đổi và upload; vì vậy không nên mặc định mọi phần của hệ thống đã ở mức sản phẩm hoàn thiện.

### Phân tích kỹ thuật: hướng dữ liệu có cấu trúc

Đây là hướng đáng tin cậy nhất nếu đầu vào là MusicXML, MIDI hoặc một định dạng ký âm số:

```text
MusicXML / MIDI / định dạng ký âm có cấu trúc
                         ↓
                  Music parser
                         ↓
Biểu diễn chuẩn hóa:
pitch, duration, voice, measure, rest,
dynamic, articulation, repeat, fingering...
                         ↓
             Braille music rule engine
                         ↓
       BRF / Braille display / accessible text
                         ↓
             Metadata, library và search
```

Rule engine phải hiểu ngữ cảnh. Cùng một ký hiệu có thể được viết khác tùy octave (quãng tám), nhịp, bè hoặc thành phần đứng trước. Với bản nhạc nhiều bè, engine phải xác định thứ tự tuyến tính để người đọc vẫn hiểu quan hệ đồng thời.

### Phân tích kỹ thuật: nếu nhận ảnh bản nhạc

Nếu đầu vào là ảnh hoặc PDF scan, hệ thống cần thêm OMR:

```text
Ảnh/PDF scan
     ↓
Image preprocessing
     ↓
Phát hiện khuông, nốt, dấu lặng, khóa nhạc và ký hiệu
     ↓
Khôi phục quan hệ không gian
     ↓
MusicXML hoặc biểu diễn trung gian
     ↓
Braille conversion
```

Nguồn công khai chỉ nói “standard music scores” và không cho biết định dạng đầu vào. Do đó OMR là một khả năng kiến trúc, không phải công nghệ đã được xác nhận của đội.

### Những vấn đề ngoài model

- **Correctness:** bản chuyển đổi phải được người đọc Braille music kiểm tra.
- **Provenance (nguồn gốc):** người dùng cần biết bản nhạc đến từ đâu và ai đã xác minh.
- **Versioning (quản lý phiên bản):** khi sửa một lỗi chuyển đổi, thư viện phải lưu lịch sử.
- **Copyright:** không phải bản nhạc nào cũng có thể tự do tải lên và phân phối.
- **Accessible search:** bộ lọc, kết quả và trình phát phải dùng được hoàn toàn bằng bàn phím và screen reader.

### Vì sao bài này mạnh

The Great Musica kết hợp ba giá trị trong cùng một sản phẩm:

1. Công cụ chuyển đổi chuyên biệt.
2. Kho nội dung tiếng Việt còn khan hiếm.
3. Cộng đồng và đối tác có chuyên môn để kiểm chứng chất lượng.

## 6.2. Á quân: Lexopia

### Thông tin đã công bố

Lexopia là ứng dụng hỗ trợ nhân viên mắc chứng khó đọc cải thiện khả năng đọc và viết. RMIT cho biết sản phẩm sử dụng Microsoft Azure AI services và Copilot, nhưng không công bố tên từng service hoặc kiến trúc backend.

### Phân tích kỹ thuật

```text
Text / document / ảnh scan
              ↓
Text extraction hoặc OCR
              ↓
Phân đoạn và phân tích độ phức tạp
              ↓
Simplification / summarization / writing support
              ↓
Trình bày tùy biến:
font, spacing, độ dài dòng, màu, read-aloud
```

Các tính năng nên được coi là lựa chọn, không phải một giao diện “tối ưu cho mọi người mắc dyslexia”. Nhu cầu của mỗi người có thể khác nhau. Người dùng nên tùy chỉnh:

- font và cỡ chữ;
- khoảng cách chữ, từ và dòng;
- độ dài mỗi dòng;
- màu nền và độ tương phản;
- chia nội dung thành từng phần;
- highlight đồng bộ với giọng đọc;
- mức độ đơn giản hóa văn bản.

Nếu AI viết lại nội dung, cần hiển thị bản gốc cạnh bản đơn giản hóa. Đối với email, quy định hoặc hợp đồng lao động, việc tóm tắt sai có thể thay đổi ý nghĩa quan trọng.

### Mức độ hoàn thiện chưa rõ

Thông tin công khai từ thành viên đề cập công việc về feature prototype (nguyên mẫu tính năng), hình ảnh, mascot, logo và market research. Điều này cho thấy đội đầu tư đáng kể vào product concept và trải nghiệm, nhưng không đủ bằng chứng để kết luận backend AI đã ở mức production.

## 6.3. Đồng hạng ba: HiWin — CommuniCare

### Thông tin đã công bố

Một bài đăng công khai của thành viên HiWin mô tả CommuniCare có:

- nền tảng AI;
- thiết kế phần cứng;
- kết nối IoT;
- vi điều khiển ESP32;
- Flutter;
- thiết kế 3D.

### Phân tích kỹ thuật

Với các thành phần trên, kiến trúc tổng quát có thể là:

```text
Sensors / nút điều khiển
          ↓
ESP32 firmware
          ↓
Bluetooth hoặc Wi-Fi
          ↓
Flutter mobile application
          ↓
Backend / AI service / dữ liệu người dùng
```

ESP32 phù hợp cho prototype vì có Wi-Fi, Bluetooth, nhiều chân giao tiếp sensor và hệ sinh thái thư viện lớn. Những điểm cần quan tâm gồm reconnect khi mất mạng, tiêu thụ pin, cập nhật firmware và xử lý an toàn khi mobile app không phản hồi.

Tuy nhiên, nguồn hiện có không mô tả đủ chức năng và nhóm người dùng để phân tích sâu hơn mà không suy đoán quá mức.

## 6.4. Đồng hạng ba: Vista

RMIT xác nhận Vista đồng hạng ba, với thành viên từ Thang Long University, National Economics University và Hanoi University of Science and Technology. Các nguồn công khai tìm được chưa mô tả đủ sản phẩm, đối tượng người dùng hoặc stack. Vì vậy tài liệu không tự dựng một kiến trúc cho dự án này.

---

# 7. Microsoft AI for Accessibility 2024 — SightSence

## Vì sao dự án này được đưa vào tài liệu?

Microsoft AI for Accessibility Hackathon 2024 được tổ chức trong hệ sinh thái hoạt động liên quan đến ADC. SightSence không nên được ghi nhầm thành quán quân chung của ADC 2024 — vị trí đó thuộc The Great Musica — nhưng đây vẫn là một tiền lệ rất gần về chủ đề, tiêu chí và người tham gia.

## Thông tin đã công bố

Đội RespectAbility phát triển SightSence gồm:

- kính có camera;
- gậy tích hợp cảm biến;
- AI nhận biết tín hiệu thị giác và xã hội;
- màn hình Braille tùy biến có chi phí thấp;
- đầu ra xúc giác giúp người khiếm thị nhận thông tin về môi trường và tương tác.

Ý tưởng được truyền cảm hứng từ một người bạn khiếm thị của thành viên đội, người gặp khó khăn khi không nhìn được nét mặt và ngôn ngữ cơ thể trong giao tiếp.

## Phân tích kỹ thuật

```text
Camera trên kính
        ↓
Person / face / scene detection
        ↓
Tracking và nhận biết tín hiệu quan sát được
        ↓
Semantic event
        ↓
Nén thành thông tin ngắn, có mức ưu tiên
        ↓
Braille encoding
        ↓
Microcontroller → tactile/Braille actuator
```

Gậy cảm biến có thể hoạt động như một kênh riêng cho chướng ngại vật:

```text
Distance/obstacle sensor
          ↓
Risk threshold
          ↓
Rung, âm thanh hoặc cảnh báo xúc giác
```

### Các giới hạn cần nhìn thẳng

- **Emotion inference (suy đoán cảm xúc):** nét mặt không cho biết chắc trạng thái nội tâm.
- **Bias (thiên lệch):** model có thể kém chính xác với nhóm khuôn mặt, văn hóa hoặc điều kiện ánh sáng khác dữ liệu huấn luyện.
- **Privacy:** camera có thể ghi lại đồng nghiệp và khách hàng không chủ động đồng ý.
- **Latency:** cảnh báo đến muộn làm thông tin mất giá trị.
- **Tactile bandwidth:** người dùng chỉ có thể tiếp nhận một lượng nhỏ tín hiệu xúc giác trong thời gian ngắn.
- **Information overload:** hệ thống mô tả mọi thứ sẽ gây nhiễu hơn là hỗ trợ.

Một thiết kế có trách nhiệm nên ưu tiên sự kiện quan sát được — ví dụ “người đối diện quay sang trái” — thay vì khẳng định “người đối diện đang khó chịu”.

---

# 8. ADC 2025 — AllStep, NeuroAICC, 7 Rings và InSight

## 8.1. Quán quân: AllStep

### Thông tin đã công bố

AllStep là walker (khung tập đi) thông minh dành cho người bại não. RMIT mô tả sản phẩm kết hợp **smart braking (phanh thông minh)** và **computer vision (thị giác máy tính)** nhằm tăng an toàn, tính độc lập và khả năng thích nghi.

Nguồn không công bố loại camera, cảm biến, vi điều khiển, model thị giác hoặc cơ cấu phanh.

### Phân tích kỹ thuật

```text
Camera hướng về phía di chuyển
              ↓
Obstacle detection / free-space estimation
              ↓
Ước lượng khoảng cách và mức rủi ro
              ↓
Safety controller
              ↓
Electromechanical brake
```

Nếu chỉ dùng một camera RGB, việc ước lượng khoảng cách tuyệt đối có thể không ổn định. Một hệ thống thực tế có thể kết hợp depth camera, ultrasonic sensor, wheel encoder hoặc IMU. Nhưng đây là phương án kỹ thuật nên cân nhắc, không phải xác nhận AllStep đã sử dụng các thiết bị đó.

### Phần khó nhất là safety engineering

Computer vision không nên trực tiếp là lớp quyết định duy nhất cho phanh. Kiến trúc an toàn hơn:

```text
AI perception
      ↓
Risk proposal
      ↓
Deterministic safety rules
      ↓
Brake controller có giới hạn và manual override
```

Cần kiểm thử ít nhất:

- false negative: bỏ sót chướng ngại vật;
- false positive: phanh nhầm;
- độ trễ từ camera đến cơ cấu phanh;
- hành vi khi camera bị che hoặc thiếu sáng;
- hành vi khi pin yếu, mất điện hoặc model crash;
- các bề mặt dốc, trơn và không bằng phẳng;
- nhiều tốc độ, tải trọng và dáng đi;
- khả năng người dùng chủ động ghi đè quyết định của hệ thống.

### Vì sao bài này mạnh

AllStep gắn AI với một hành động vật lý có giá trị rất rõ. Demo “nhận ra nguy cơ và hỗ trợ phanh” dễ hiểu, nhưng sản phẩm vẫn phải chứng minh được rằng AI được dùng có trách nhiệm trong một hệ thống có rủi ro an toàn cao.

## 8.2. Á quân: Powerpuff Girls — NeuroAICC

### Thông tin đã công bố

NeuroAICC là nền tảng web song ngữ dành cho người tự kỷ, caregiver (người chăm sóc) và employer (nhà tuyển dụng). Sản phẩm cung cấp:

- luyện phỏng vấn với AI;
- hướng dẫn cá nhân hóa theo cách bình tĩnh và dễ dự đoán;
- interactive storytelling (câu chuyện tương tác);
- tài nguyên thực hành cho nhà tuyển dụng;
- nội dung hỗ trợ caregiver.

Dự án được đồng phát triển với người tự kỷ, caregiver và chuyên gia, sau đó được chọn vào chương trình Spark Hub của RMIT.

### Dấu vết kỹ thuật có thể kiểm tra từ website công khai

Trong phiên bản website public được kiểm tra, frontend cho thấy:

- React được bundle bằng Vite;
- Tailwind CSS được tải qua CDN;
- EmailJS;
- font Be Vietnam Pro;
- giao diện tiếng Việt và tiếng Anh;
- theme màu khác nhau;
- hỗ trợ `prefers-reduced-motion` để giảm chuyển động theo thiết lập hệ điều hành;
- `localStorage` cho progress, câu hỏi, job và một số trạng thái;
- lazy loading (tải từng phần khi cần) cho một số route/component;
- gamification bằng XP và ngưỡng tiến độ.

Các API endpoint xuất hiện trong frontend bundle gồm:

```text
/api/interview-feedback
/api/improvement-suggestion
/api/clean-question
/api/story-feedback
```

Payload JSON có các trường liên quan đến:

```text
question
answer
language
componentToImprove
userSelections
story
```

Frontend sử dụng `AbortController` với timeout khoảng 35 giây cho một số AI request và có thông báo fallback khi lời gọi thất bại.

### Kiến trúc quan sát được

```text
React/Vite SPA
      ↓
Trạng thái luyện tập và lựa chọn người dùng
      ↓
JSON API request
      ↓
AI feedback service
      ↓
Phản hồi coaching có cấu trúc
      ↓
Progress / XP / lưu trạng thái cục bộ
```

### Ghi chú về cấu hình deployment

Tại snapshot public được kiểm tra, frontend bundle có `API_BASE` trỏ tới `http://localhost:3001`. Trừ khi có proxy hoặc runtime configuration khác xử lý phía ngoài bundle, cấu hình này có thể khiến lời gọi AI từ website production thất bại.

Đây không phải bằng chứng rằng prototype ở thời điểm chấm giải bị lỗi. Website có thể đã thay đổi sau cuộc thi, và cấu hình cuộc thi có thể khác bản đang public. Tuy vậy, nó cho thấy rõ sự khác nhau giữa một prototype đạt giải và một hệ thống production được vận hành lâu dài.

### Điểm kỹ thuật và sản phẩm đáng học

- AI output được đặt trong một luồng luyện tập cụ thể, không phải chatbot trống.
- Song ngữ giúp sản phẩm gần với bối cảnh Việt Nam.
- Reduced motion, theme và cách chia từng bước thể hiện accessibility ngay trong giao diện.
- Nội dung dành cho cả ứng viên, caregiver và employer tạo thành một hệ sinh thái hỗ trợ thay vì bắt một mình ứng viên phải thích nghi.

### Rủi ro cần quản lý

- AI không nên đánh giá người dùng tự kỷ theo một hình mẫu “giao tiếp bình thường” duy nhất.
- Feedback cần cụ thể, không phán xét và cho phép bỏ qua.
- Không nên biến eye contact (giao tiếp bằng mắt), biểu cảm hoặc giọng nói thành thước đo bắt buộc.
- Dữ liệu câu trả lời phỏng vấn có thể chứa thông tin cá nhân và cần chính sách lưu/xóa rõ ràng.

## 8.3. Đồng hạng ba: 7 Rings

### Thông tin đã công bố

7 Rings xây dựng nền tảng web dùng AI để dịch theo thời gian thực giữa Ngôn ngữ ký hiệu Việt Nam — VSL và lời nói.

RMIT không công bố model, dataset, framework hoặc phạm vi từ vựng.

### Phân tích kỹ thuật: VSL sang lời nói

```text
Camera / WebRTC frames
          ↓
Phát hiện hand, pose và facial landmarks
          ↓
Chuỗi đặc trưng không gian-thời gian
          ↓
Sign segmentation
          ↓
Sign recognition / sequence translation
          ↓
Văn bản tiếng Việt
          ↓
Text-to-Speech
```

Một hệ thống nhẹ có thể dùng MediaPipe hoặc một pose estimator để lấy landmark, sau đó chạy LSTM/Transformer. Một hệ thống giàu thông tin hơn có thể dùng video encoder hoặc multimodal model, đổi lại sẽ tốn compute và khó chạy thời gian thực trên trình duyệt.

### Phân tích kỹ thuật: lời nói sang phía người dùng VSL

```text
Microphone
    ↓
Streaming Speech-to-Text
    ↓
Văn bản tiếng Việt
    ↓
Text, video từ điển ký hiệu hoặc avatar ký hiệu
```

Nguồn nói “dịch giữa VSL và speech” nhưng không cho biết đầu ra VSL là video, avatar 3D, chuỗi clip hay chỉ là text. Đây là một khác biệt kỹ thuật lớn và không nên tự suy đoán.

### Những vấn đề khó nhất

- xác định điểm bắt đầu và kết thúc của một ký hiệu trong chuỗi liên tục;
- nhận dạng được người ký hiệu chưa xuất hiện trong dữ liệu train;
- xử lý nét mặt, hướng đầu và thân người — các dấu hiệu mang nghĩa ngôn ngữ;
- giải quyết khác biệt vùng miền của VSL;
- chuyển đổi ngữ pháp thay vì dịch từng từ;
- giảm độ trễ nhưng vẫn giữ đủ số frame;
- xây dựng dataset có consent và annotation đáng tin cậy.

## 8.4. Đồng hạng ba: InSight

### Thông tin đã công bố

InSight là ứng dụng AI cho nhân viên khiếm thị, hỗ trợ tương tác thời gian thực, nhận biết tín hiệu cảm xúc và nâng cao social awareness (nhận thức về tình huống xã hội).

Model, stack và thiết bị đầu vào không được RMIT công bố.

### Phân tích kỹ thuật

```text
Camera + microphone
          ↓
Phát hiện và theo dõi người/khuôn mặt
          ↓
Phân tích tín hiệu quan sát được
          ↓
Chọn sự kiện có ích trong ngữ cảnh hiện tại
          ↓
Tóm tắt ngắn
          ↓
Audio hoặc haptic feedback
```

Một phiên bản dùng Vision-Language Model — VLM (mô hình thị giác-ngôn ngữ) có thể mô tả linh hoạt hơn classifier cố định, nhưng cũng có nguy cơ hallucination (bịa hoặc suy diễn thông tin không có trong đầu vào). Một classifier cảm xúc truyền thống dễ benchmark hơn nhưng lại đơn giản hóa cảm xúc con người thành vài nhãn.

### Rủi ro cốt lõi

- Một nét mặt không cho biết chắc cảm xúc hoặc ý định.
- Việc gắn nhãn “giận dữ”, “buồn” hoặc “không quan tâm” có thể gây hiểu lầm trong quan hệ công việc.
- Camera liên tục tại nơi làm việc đặt ra vấn đề consent và bảo mật.
- Audio feedback quá dài sẽ chiếm kênh nghe mà người dùng đang cần cho cuộc trò chuyện.
- AI phải phân biệt thông tin khẩn cấp và thông tin chỉ mang tính tham khảo.

Thiết kế có trách nhiệm nên mô tả dữ kiện quan sát được và confidence (độ tin cậy), đồng thời tránh khẳng định nội tâm của người khác.

---

# 9. So sánh kỹ thuật giữa các thế hệ dự án

## 9.1. Nhóm input modality — Dạng đầu vào

| Dạng đầu vào | Dự án tiêu biểu | Bài toán kỹ thuật chính |
|---|---|---|
| Giọng nói | Eccentrics, Accesstant, AI Speech Companion, 7 Rings | Speech-to-Text, phân đoạn, tiếng ồn, độ trễ |
| Video/camera | HANDTALK, SightSence, AllStep, 7 Rings, InSight | Detection, tracking, chuỗi thời gian, quyền riêng tư |
| Tài liệu/ký âm | The Great Musica, Lexopia | Parsing, OCR/OMR, bảo toàn ngữ nghĩa, accessible rendering |
| Cảm biến vật lý | Eccentrics, CommuniCare, SightSence, AllStep | Firmware, connectivity, calibration, fail-safe |
| Thao tác cơ học | Versatile Mechanical Joint | Ergonomics, tải trọng, vật liệu, modularity |
| Văn bản người dùng | AI Speech Companion, NeuroAICC | NLP/LLM, personalization, feedback có cấu trúc |

## 9.2. Nhóm output modality — Dạng đầu ra

| Đầu ra | Dự án tiêu biểu | Điều cần kiểm thử |
|---|---|---|
| Văn bản thời gian thực | HANDTALK, Accesstant, 7 Rings | Độ trễ, ổn định transcript, cỡ chữ, khả năng xem lại |
| Giọng nói | HANDTALK, 7 Rings | Phát âm, tốc độ, quyền kiểm soát âm lượng và phát lại |
| Braille/xúc giác | Các dự án nhạc Braille, SightSence | Chuẩn mã hóa, tốc độ đọc, quá tải thông tin |
| Phản hồi coaching | AI Speech Companion, NeuroAICC | Tính cụ thể, không phán xét, kiểm chứng và personalization |
| Hành động vật lý | Versatile Mechanical Joint, AllStep | An toàn, độ bền, manual override, lỗi phần cứng |
| Nội dung đã đơn giản hóa | Lexopia | Không đổi nghĩa, so sánh với bản gốc, tùy chỉnh cá nhân |

## 9.3. Mức độ AI

Các dự án cho thấy ít nhất bốn cách dùng AI khác nhau:

1. **Perception AI (AI nhận biết):** hiểu video, cử chỉ, vật cản hoặc tín hiệu xã hội.
2. **Language AI (AI ngôn ngữ):** nhận dạng giọng nói, tổ chức nội dung, tạo phản hồi và đơn giản hóa văn bản.
3. **Personalization (cá nhân hóa):** điều chỉnh kịch bản, chiến lược hỗ trợ hoặc cách trình bày cho từng người.
4. **AI-assisted control (điều khiển có AI hỗ trợ):** AI đề xuất hành động cho thiết bị vật lý, như phanh walker.

Mức rủi ro tăng dần khi AI đi từ “gợi ý nội dung” sang “điều khiển hành động vật lý”. Hệ thống càng ảnh hưởng tới an toàn thì càng cần rule cố định, fail-safe và quyền ghi đè của con người.

## 9.4. Prototype đoạt giải không đồng nghĩa production system

Một prototype trong hackathon có thể chứng minh:

- người dùng thực hiện được một luồng chính;
- AI API hoạt động với một số tình huống mẫu;
- phần cứng phản ứng đúng trong demo;
- ý tưởng có cơ sở từ user research.

Production system còn cần:

- authentication và authorization;
- bảo mật dữ liệu;
- logging có kiểm soát;
- monitoring;
- đánh giá model trên dữ liệu đại diện;
- cơ chế rollback và fallback;
- accessibility testing có hệ thống;
- vận hành, bảo trì và hỗ trợ người dùng;
- tuân thủ pháp lý và quản lý consent.

Không nên đánh giá thấp một đội vì họ dùng API hoặc prototype đơn giản; đồng thời cũng không nên diễn giải thứ hạng hackathon thành bằng chứng rằng sản phẩm đã sẵn sàng thương mại.

---

# 10. Những bài học có thể dùng khi phân tích ý tưởng sau này

Phần này chỉ rút ra nguyên tắc, chưa lựa chọn chủ đề cho team.

## 10.1. Bắt đầu từ một khoảnh khắc công việc cụ thể

Các bài mạnh không chỉ nói “giúp người khuyết tật”. Chúng gắn với một hành động rõ:

- đọc bản nhạc;
- tham gia hội thoại;
- ghi lại cuộc họp;
- luyện phỏng vấn;
- cầm chuột hoặc bấm bàn phím;
- di chuyển an toàn bằng walker.

Một problem statement (phát biểu vấn đề) tốt cần trả lời được:

```text
Ai gặp rào cản?
Trong hoạt động công việc nào?
Rào cản xảy ra ở bước nào?
Hiện họ đang xử lý bằng cách gì?
Hậu quả về thời gian, sự độc lập hoặc cơ hội việc làm là gì?
```

## 10.2. AI phải nằm trong một workflow hoàn chỉnh

Mẫu chung của nhiều bài thắng:

```text
Đầu vào mà người dùng có thể cung cấp
                  ↓
      Xử lý xác định + AI khi cần
                  ↓
      Đầu ra đúng modality người dùng cần
                  ↓
         Một hành động công việc hoàn thành được
```

Chỉ có một chatbot hoặc model demo thường chưa đủ. Accesstant nối transcript với flashcard và reminder; AI Speech Companion nối chuẩn bị với luyện tập và SOS; The Great Musica nối chuyển đổi với thư viện và cộng đồng.

## 10.3. Accessibility không phải lớp trang trí sau cùng

Một ứng dụng cho người khiếm thị nhưng không dùng được bằng bàn phím và screen reader là mâu thuẫn ngay từ kiến trúc. Tương tự, một sản phẩm cho người đa dạng thần kinh nhưng có animation bắt buộc, luồng bất ngờ và feedback phán xét sẽ tự tạo ra rào cản mới.

Cần kiểm thử accessibility trong chính luồng demo, không chỉ ghi nó vào slide.

## 10.4. User co-design tạo lợi thế rõ rệt

Những trường hợp nổi bật:

- The Great Musica có thành viên khiếm thị và đối tác chuyên môn.
- Versatile Mechanical Joint được đồng thiết kế với người khuyết tật.
- NeuroAICC làm việc với người tự kỷ, caregiver và chuyên gia.
- SightSence bắt nguồn từ một khó khăn giao tiếp có người thật phía sau.

Trong pitch, “chúng tôi đã đổi thiết kế sau khi nghe người dùng” thuyết phục hơn “chúng tôi nghĩ người dùng sẽ thích tính năng này”.

## 10.5. Metric phải đo được khả năng hoàn thành việc

Accuracy hoặc F1 vẫn hữu ích, nhưng chưa đủ. Tùy sản phẩm, nên đo thêm:

- task completion rate (tỉ lệ hoàn thành nhiệm vụ);
- thời gian hoàn thành;
- số lần cần nhờ người khác;
- số lần cần sửa output của AI;
- độ trễ đầu-cuối;
- mức tải nhận thức;
- tỉ lệ cảnh báo sai hoặc bỏ sót;
- mức độ tin tưởng phù hợp, không phải tin tuyệt đối;
- khả năng sử dụng bằng assistive technology (công nghệ hỗ trợ).

## 10.6. Demo nên có một “moment of value” rõ ràng

Các dự án trên đều có thể được tóm tắt bằng một khoảnh khắc dễ nhìn thấy:

- một ký hiệu trở thành lời nói;
- một bản nhạc trở thành Braille;
- một người luyện xong tình huống phỏng vấn;
- một attachment giúp người dùng thao tác chuột;
- walker phát hiện rủi ro và hỗ trợ phanh.

Một demo tốt không cần nhiều feature, nhưng người xem phải thấy ngay rào cản nào vừa được gỡ bỏ.

## 10.7. Responsible AI thay đổi theo mức độ rủi ro

| Tình huống AI | Rủi ro chính | Cơ chế nên có |
|---|---|---|
| Tóm tắt/viết lại | Sai hoặc đổi nghĩa | Hiển thị nguồn, so sánh bản gốc, cho phép sửa |
| Coaching | Phán xét hoặc áp chuẩn hành vi | Feedback tùy chọn, trung tính, do người dùng kiểm soát |
| Dịch ký hiệu | Dịch sai trong hội thoại | Confidence, yêu cầu lặp lại, transcript để xác nhận |
| Nhận biết xã hội | Suy đoán cảm xúc sai | Mô tả quan sát, tránh khẳng định nội tâm |
| Cảnh báo vật cản/phanh | Nguy hiểm vật lý | Sensor redundancy, rule cố định, fail-safe, manual override |

---

# 11. Những thông tin vẫn chưa thể xác nhận

Đây là danh sách để team không vô tình lặp lại một khẳng định không có nguồn:

- Stack, model, dataset và giao thức của dự án quán quân 2020.
- Tên và kiến trúc của đội hạng ba ADC 2020.
- Model, dataset, vocabulary và protocol đánh giá 92% của HANDTALK.
- Cloud service và model cụ thể của Accesstant.
- Thành phần kỹ thuật của HTV3.
- Azure service cụ thể mà ATP sử dụng.
- Định dạng đầu vào của The Great Musica và việc đội đã triển khai OMR hay chưa.
- Kiến trúc backend thực tế của Lexopia.
- Use case chi tiết của CommuniCare.
- Sản phẩm và stack của Vista.
- Camera, cảm biến, controller, model và cơ cấu phanh của AllStep.
- Model/backend tạo feedback của NeuroAICC.
- Model, dataset, từ vựng và dạng đầu ra VSL của 7 Rings.
- Model, thiết bị và protocol kiểm thử của InSight.

Nếu sau này có pitch deck, video demo, repository hoặc bài viết trực tiếp từ đội, những phần này nên được cập nhật bằng bằng chứng mới thay vì suy luận.

---

# 12. Nguồn tham khảo

## Nguồn chung và ADC 2020

- [RMIT — RMIT students provide innovative solutions for workplace inequality](https://www.rmit.edu.vn/news/all-news/2021/jan/rmit-students-provide-innovative-solutions-for-workplace-inequality)
- [RMIT — Inclusive support brings out potential in graduates](https://www.rmit.edu.vn/news/all-news/2024/may/rmit-inclusive-support-brings-out-potential-in-graduates)
- [RMIT — Mùa ADC thứ hai và thiết kế hòa nhập](https://www.rmit.edu.vn/news/all-news/2022/jul/university-students-propose-solutions-to-promote-diversity-and-inclusion)

## ADC 2022

- [RMIT — University students propose solutions to promote diversity and inclusion](https://www.rmit.edu.vn/news/all-news/2022/jul/university-students-propose-solutions-to-promote-diversity-and-inclusion)
- [VietnamNet — Sinh viên đề xuất giải pháp công nghệ thúc đẩy hòa nhập nơi công sở](https://vietnamnet.vn/sinh-vien-de-xuat-giai-phap-cong-nghe-thuc-day-hoa-nhap-noi-cong-so-i414906.html)
- [LinkedIn — ACCESSTANT](https://vn.linkedin.com/in/dang-khoa-pham-nguyen)

## ADC 2023

- [RMIT — Accessibility Design Competition ideates the future of workplace equality](https://www.rmit.edu.vn/news/all-news/2023/jun/accessibility-design-competition-ideates-the-future-of-workplace-equality)
- [Microsoft Vietnam — ATP chiến thắng Microsoft APAC AI for Accessibility Hackathon Vietnam 2023](https://news.microsoft.com/source/asia/2023/06/25/atp-xuat-sac-gianh-chien-thang-cuoc-thi-microsoft-apac-ai-for-accessibility-hackathon-viet-nam-2023/?lang=vi)
- [RMIT Showcase — AI Speech Companion](https://www.rmitvn-showcase.com/scd/student-awards/en/ai-speech-companion)
- [Microsoft APAC — Winners of Microsoft AI for Accessibility Hackathon 2023](https://news.microsoft.com/apac/2023/07/03/winners-of-the-microsoft-ai-for-accessibility-hackathon-2023-showcase-how-inclusion-is-innovation-in-asia-pacific/)
- [Văn Lang University — Bộ khớp đa năng đạt giải nhì ADC 2023](https://www.vlu.edu.vn/news/san-pham-bo-khop-da-nang-cua-sinh-vien-van-lang-dat-giai-nhi-cuoc-thi-thiet-ke-san-pham-cho-nguoi-khiem-khuyet-noi-lam-viec-nam-2023)
- [RMIT Alumni — Melvin Fernando và Versatile Mechanical Joint System](https://alumninetwork.rmit.edu.vn/livebrary/melvin-fernando/)

## ADC 2024 và Microsoft AI for Accessibility 2024

- [RMIT — RMIT Vietnam drives the employability of people with disabilities](https://www.rmit.edu.vn/news/all-news/2024/jun/rmit-vietnam-drives-the-employability-of-people-with-disabilities)
- [Fulbright University Vietnam — The Great Musica wins ADC 2024](https://fulbright.edu.vn/the-great-musica-wins-accessibility-design-competition-2024/)
- [LinkedIn — Thông tin thành viên Lexopia](https://vn.linkedin.com/in/nhunguyenphucquynh)
- [LinkedIn — HiWin/CommuniCare tại ADC 2024](https://www.linkedin.com/posts/dinhphongnguyen-vietnam_2nd-runner-up-accessibility-design-competition-activity-7213903672236212225-45xH)
- [Microsoft — RespectAbility wins AI challenge for people with disabilities](https://news.microsoft.com/source/asia/2024/08/08/respectability-wins-microsofts-ai-challenge-for-people-with-disabilities/)

## ADC 2025

- [RMIT — Designing a future for all](https://www.rmit.edu.vn/news/all-news/2025/oct/designing-a-future-for-all)
- [RMIT — NeuroAICC: Enhancing autistic interview accessibility](https://www.rmit.edu.vn/students/student-news-and-events/student-news/2025/neuroaicc-autistic-interview-accessibility-design-competition)
- [RMIT Spark Hub — Student start-up and NeuroAICC](https://www.rmit.edu.vn/about-us/who-we-are/our-commitments/vietnam-country-commitment/strategic-innovation-challenge/spark-hub/student-start-up)
- [NeuroAICC — Website sản phẩm](https://neuroaicc.com/)

---

## Ghi chú cuối

Tài liệu này nên được xem như một **evidence base (nền bằng chứng)** cho buổi chọn ý tưởng sau. Khi bàn đề tài, nhóm có thể dùng nó để kiểm tra ba câu hỏi:

1. Ý tưởng có đang lặp lại một sản phẩm từng đoạt giải không?
2. Nếu cùng nhóm vấn đề, điểm khác biệt về người dùng, tình huống công việc hoặc workflow nằm ở đâu?
3. Nhóm có thể chứng minh tác động bằng một prototype và một bài kiểm thử rõ ràng hay không?

Chưa nên chọn công nghệ chỉ vì một đội trước từng dùng nó. Điều đáng học từ các bài thắng là cách họ nối **nhu cầu thật → giải pháp → prototype → kiểm chứng → tác động**.
