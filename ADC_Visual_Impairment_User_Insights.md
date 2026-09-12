# ADC 2026 — Hiểu người khiếm thị trước khi nghĩ giải pháp

Tài liệu này giúp team hình dung người mù và người có thị lực kém sinh hoạt, học tập và làm việc với công nghệ như thế nào. Mục tiêu không phải “học thuộc đặc điểm của người khiếm thị”, mà là nhận ra những điểm trong một hành trình công việc nơi thông tin hoặc hành động bị chặn bởi thiết kế.

Đây là **desk research (nghiên cứu từ tài liệu)**, chưa phải bằng chứng rằng một vấn đề cụ thể chắc chắn tồn tại với end-user của ADC. Competition brief chỉ xuất hiện vào đầu Day 1. Mọi hướng giải pháp ở cuối file vẫn là hypothesis (giả thuyết), phải được kiểm tra với người dùng thật rồi mới chọn.

---

## Mục lục

1. [Những điều cả team cần hiểu trước](#1-những-điều-cả-team-cần-hiểu-trước)
2. [“Khiếm thị” không phải một kiểu người dùng](#2-khiếm-thị-không-phải-một-kiểu-người-dùng)
3. [Họ tổ chức cuộc sống hằng ngày như thế nào?](#3-họ-tổ-chức-cuộc-sống-hằng-ngày-như-thế-nào)
4. [Họ sử dụng laptop ra sao?](#4-họ-sử-dụng-laptop-ra-sao)
5. [Họ sử dụng điện thoại ra sao?](#5-họ-sử-dụng-điện-thoại-ra-sao)
6. [Bản đồ các công cụ hỗ trợ hiện có](#6-bản-đồ-các-công-cụ-hỗ-trợ-hiện-có)
7. [Hành trình công việc và các pain point](#7-hành-trình-công-việc-và-các-pain-point)
8. [Những insight sâu hơn cho ADC](#8-những-insight-sâu-hơn-cho-adc)
9. [Từ pain point tới các hướng ý tưởng](#9-từ-pain-point-tới-các-hướng-ý-tưởng)
10. [Cách phỏng vấn end-user trong Day 1–2](#10-cách-phỏng-vấn-end-user-trong-day-12)
11. [Nguyên tắc thiết kế và kiểm thử prototype](#11-nguyên-tắc-thiết-kế-và-kiểm-thử-prototype)
12. [Cách quyết định có chọn Visual Impairment hay không](#12-cách-quyết-định-có-chọn-visual-impairment-hay-không)
13. [Nguồn tham khảo](#13-nguồn-tham-khảo)

---

# 1. Những điều cả team cần hiểu trước

## 1.1. Người khiếm thị không đồng nghĩa với người hoàn toàn không nhìn thấy

Visual impairment (suy giảm thị lực) trải từ low vision (thị lực kém) tới blindness (mù). Một người có thể:

- nhìn được vật ở gần nhưng khó đọc xa;
- mất thị lực trung tâm nhưng còn thị lực ngoại vi;
- chỉ thấy một vùng hẹp như “đường ống”;
- khó phân biệt độ tương phản hoặc một số màu;
- nhạy với ánh sáng;
- nhìn được một phần nhưng thị lực thay đổi theo thời điểm, môi trường hoặc mức mệt mỏi;
- không có thị lực hữu dụng và chủ yếu tiếp nhận thông tin bằng âm thanh hoặc Braille.

W3C nhấn mạnh các khác biệt về độ rõ, trường nhìn, tương phản, màu và độ nhạy sáng có thể tạo ra nhu cầu rất khác nhau.[^1] Vì vậy “thêm giọng đọc” chưa chắc giúp người low vision, còn “phóng chữ thật to” chưa chắc giúp người dùng screen reader.

## 1.2. Năng lực của con người và khả năng truy cập của môi trường là hai chuyện khác nhau

Một nhân viên không đọc được dashboard dạng ảnh không có nghĩa họ không hiểu dữ liệu. Một người phải nhờ đồng nghiệp bấm hộ không có nghĩa họ thiếu kỹ năng công việc. Rào cản có thể nằm ở file PDF không có cấu trúc, nút không có accessible name (tên mà công nghệ hỗ trợ đọc được), phần mềm không dùng được bằng bàn phím hoặc quy trình IT không cho cài screen reader.

Cách nhìn hữu ích cho team là:

```text
Năng lực thực hiện công việc
≠
Khả năng truy cập giao diện hiện tại
```

Nếu sản phẩm chỉ “bù” cho một giao diện vốn được thiết kế kém, team cần nói rõ tại sao không sửa trực tiếp giao diện đó. Đôi khi giải pháp tốt nhất là quy trình, tiêu chuẩn tài liệu hoặc accessibility fix (sửa khả năng tiếp cận), không phải một lớp AI mới.

## 1.3. Độc lập không có nghĩa là không bao giờ nhận hỗ trợ

Trong đời sống, ai cũng kết hợp kỹ năng cá nhân, công cụ và hỗ trợ từ người khác. Người khiếm thị có thể dùng gậy, chó dẫn đường, screen reader, OCR, dịch vụ hỗ trợ thị giác từ xa hoặc hỏi một người bên cạnh. Điều quan trọng là họ **được chọn** khi nào cần hỗ trợ, chia sẻ dữ liệu gì và ai được quyền hành động thay mình.

Một giải pháp tốt không nên thay sự phụ thuộc vào đồng nghiệp bằng sự phụ thuộc mù quáng vào AI. Nó phải tăng quyền kiểm soát, giảm công sức không cần thiết và nói rõ khi hệ thống không chắc.

## 1.4. “Truy cập được” chưa chắc “làm việc hiệu quả”

Một tài liệu có thể đọc được từng chữ nhưng vẫn rất khó dùng nếu:

- không có heading để nhảy nhanh;
- bảng không giữ quan hệ hàng–cột;
- chart chỉ có một đoạn mô tả chung;
- người dùng phải nghe hàng trăm mục trước khi tới phần cần thiết;
- trạng thái vừa thay đổi nhưng screen reader không thông báo;
- phải chuyển qua nhiều ứng dụng mà không giữ được context.

Đây là khoảng trống quan trọng cho ADC: đi từ **access** tới **efficient, confident task completion** — hoàn thành việc nhanh, đúng và có kiểm soát.

## 1.5. Bằng chứng hiện có chủ yếu không đến từ Việt Nam

Các số liệu chi tiết trong tài liệu này phần lớn đến từ nghiên cứu ở Mỹ, Anh và các nền tảng công nghệ toàn cầu. Báo cáo UNDP tại Việt Nam cho thấy người khuyết tật còn gặp bottleneck (điểm nghẽn) trong tiếp cận việc làm, phát triển nghề nghiệp và điều chỉnh hợp lý tại nơi làm việc, nhưng không cho phép suy ra mọi hành vi công nghệ của người khiếm thị Việt Nam.[^2]

Do đó team phải kiểm tra lại:

- người dùng Việt Nam đang dùng Android hay iPhone;
- có dùng NVDA, JAWS, VoiceOver hay công cụ khác;
- tiếng Việt của TTS/OCR hoạt động tốt tới đâu;
- thiết bị và Internet thực tế;
- quy định IT tại nơi làm việc;
- văn hóa nhờ hỗ trợ, disclosure (tiết lộ tình trạng khuyết tật) và quyền riêng tư.

---

# 2. “Khiếm thị” không phải một kiểu người dùng

Thay vì chia người dùng bằng chẩn đoán y khoa, team nên chia theo **functional profile (hồ sơ khả năng sử dụng)**. Cách này gần với thiết kế sản phẩm hơn.

| Functional profile | Cách truy cập thường gặp | Rào cản dễ xuất hiện | Điều cần hỏi trực tiếp |
|---|---|---|---|
| Không có thị lực hữu dụng | Screen reader, bàn phím, Braille, giọng nói | Nội dung không có semantic, visual-only, focus sai, thao tác kéo-thả | Screen reader nào? Tốc độ đọc? Có dùng Braille không? |
| Low vision, dùng phóng đại | Zoom, magnifier, chữ lớn, con trỏ lớn, contrast/theme riêng | Mất overview, phải pan nhiều, popup ngoài viewport, layout vỡ | Mức zoom? Thiết lập màu/ánh sáng? Khi nào kết hợp giọng đọc? |
| Thị trường hẹp | Phóng đại vừa, bố cục ổn định, landmark | Khó tìm vị trí, nội dung đổi chỗ, nhiều cột | Vùng màn hình hữu dụng? Cách giữ orientation? |
| Khó phân biệt màu/tương phản | High contrast, color filter, label/text thay màu | Trạng thái chỉ biểu đạt bằng màu, chart nhiều màu gần nhau | Cặp màu nào khó? Có dùng theme hệ điều hành không? |
| Nhạy sáng | Dark mode, giảm sáng, kính/lọc màu | Nền trắng sáng, flashing, không tôn trọng theme | Môi trường nào gây khó? Thiết lập quen dùng? |
| Thị lực thay đổi hoặc dễ mỏi | Luân phiên nhìn, phóng đại, speech | Một UI dùng được buổi sáng nhưng gây mệt về sau | Mức mệt thay đổi ra sao? Output nào giúp giảm tải? |

Các profile có thể chồng lên nhau. Một người low vision có thể dùng magnifier cho bố cục quen thuộc nhưng bật screen reader khi đọc tài liệu dài. WHO cũng lưu ý vision rehabilitation (phục hồi chức năng thị giác) nhằm tối đa hóa khả năng hoạt động và tham gia xã hội, chứ không chỉ điều trị mắt.[^3]

### Không nên dựng persona như thế này

> Minh, 25 tuổi, bị mù nên rất khó dùng máy tính và luôn cần người giúp.

Persona trên gộp tình trạng thị lực với năng lực, không cho biết công cụ đang dùng, nhiệm vụ, môi trường hoặc rào cản.

### Một proto-persona hữu ích hơn

> Minh dùng NVDA và bàn phím trên laptop Windows. Minh đọc email và tài liệu tốt nếu nội dung có heading, nhưng mất nhiều thời gian khi dashboard được gửi dưới dạng screenshot. Trong cuộc họp, Minh phải đợi đồng nghiệp mô tả chart nên khó đặt câu hỏi đúng thời điểm. Đây là giả thuyết cần phỏng vấn, chưa phải người dùng thật.

---

# 3. Họ tổ chức cuộc sống hằng ngày như thế nào?

Không có một “ngày điển hình” chung cho người khiếm thị. Phần này mô tả các strategy (chiến lược thích nghi) thường gặp để team hiểu rằng nhiều hoạt động đã có cách làm hiệu quả; đừng vội xây lại một công cụ họ không cần.

## 3.1. Tạo trật tự và vị trí ổn định

Nhiều việc trở nên nhanh hơn khi đồ vật có vị trí nhất quán: chìa khóa ở một khay cố định, gia vị theo thứ tự, quần áo được phân nhóm, thư mục số có naming convention (quy ước đặt tên). Nhãn nổi, băng dính có texture, chữ lớn hoặc Braille giúp phân biệt vật dụng.

Đây không phải “sự cứng nhắc”; đó là một hệ thống giảm chi phí tìm kiếm bằng thị giác. Một sản phẩm tự động thay đổi vị trí nút, tự sắp xếp danh sách hoặc đổi layout có thể phá hệ thống ấy.

## 3.2. Dùng xúc giác, âm thanh và kỹ thuật thay thế

Trong nhà, sản phẩm hỗ trợ có thể gồm đồng hồ và cân nói, timer xúc giác, dụng cụ có vạch nổi, thiết bị phóng đại và các vật dụng chữ lớn. AFB liệt kê cả sản phẩm gia dụng có tactile marking (dấu xúc giác), speech output (phản hồi bằng giọng nói) và công cụ orientation and mobility.[^4]

Điều đáng chú ý không phải số lượng gadget, mà là người dùng thường ghép nhiều kênh:

- sờ để xác định hình dạng;
- nghe để nhận trạng thái;
- dùng mốc vị trí để tìm đồ;
- dùng camera/OCR khi thông tin chỉ có trên nhãn in;
- gọi hỗ trợ khi độ chắc chắn chưa đủ.

## 3.3. Đọc chữ in, nhãn, hóa đơn và tài liệu

Người low vision có thể dùng kính lúp quang học, camera magnifier hoặc phóng ảnh trên điện thoại. Người dùng khác chụp bằng OCR để chuyển chữ in thành text rồi nghe bằng TTS. Braille hữu ích khi cần chính tả, ký hiệu, code, sự yên tĩnh hoặc kiểm tra chính xác mà âm thanh khó thể hiện.

Camera app hiện nay có thể đọc text, tài liệu và nhãn sản phẩm. Tuy nhiên việc “chỉ camera đúng chỗ” vẫn là một task: ánh sáng, blur, góc chụp, vật bị che và việc không biết toàn bộ trang đã lọt vào khung hình đều ảnh hưởng kết quả. Google công khai cảnh báo chất lượng mô tả của Lookout bị ảnh hưởng bởi ánh sáng kém, blur, độ phân giải thấp và occlusion (che khuất); chế độ Explore vẫn là beta và kém chính xác hơn các chế độ chuyên biệt.[^5]

## 3.4. Di chuyển và định hướng

Một người có thể dùng orientation and mobility training (huấn luyện định hướng và di chuyển), gậy trắng, chó dẫn đường, mốc âm thanh/xúc giác, bản đồ, GPS hoặc hỏi người xung quanh. Công cụ nào phù hợp phụ thuộc kỹ năng, tuyến đường, môi trường và sở thích.

Team phải phân biệt:

- **nhận biết thông tin phụ trợ**, ví dụ “biển tên phòng họp ghi B2.04”; và
- **chỉ dẫn an toàn**, ví dụ “hãy bước sang trái để tránh xe”.

Prototype AI trong hackathon không nên tự nhận vai trò mobility aid an toàn. Chính Apple cũng cảnh báo không dựa vào nhận diện trực tiếp của VoiceOver trong tình huống có thể gây thương tích, tình huống rủi ro cao hoặc navigation.[^6]

## 3.5. Giao tiếp và thông tin xã hội

Một cuộc trò chuyện có nhiều dữ liệu thị giác: ai vừa giơ tay, ai đang nhìn vào slide nào, phòng họp im vì đang đọc hay vì mất kết nối, một đồng nghiệp chỉ vào ô nào trên bảng. Người khiếm thị có thể hỏi trực tiếp, dựa vào lời nói và tên người phát biểu, dùng mô tả từ người khác hoặc công cụ meeting accessible.

Không phải mọi tín hiệu thị giác đều cần AI mô tả. Output liên tục có thể che giọng người thật và tạo cognitive load (tải nhận thức). Cần hỏi người dùng: thông tin nào **thay đổi quyết định hoặc khả năng tham gia** của họ?

## 3.6. Khi cần giúp đỡ từ người khác

Hỗ trợ từ người khác có thể nhanh và chính xác, nhưng có chi phí ẩn:

- phải chờ người rảnh;
- phải giải thích task và chia sẻ context;
- có thể lộ thông tin cá nhân hoặc dữ liệu công ty;
- bị ngắt dòng suy nghĩ;
- mất quyền tự quyết nếu người giúp hành động thay vì mô tả;
- ngại hỏi nhiều lần vì sợ làm phiền hoặc bị đánh giá.

Vì vậy metric đáng đo không chỉ là “AI trả lời đúng bao nhiêu”, mà còn là **số lần cần nhờ người khác, thời gian chờ và mức kiểm soát**.

---

# 4. Họ sử dụng laptop ra sao?

## 4.1. Screen reader không “nhìn màn hình rồi đọc từ trái sang phải”

Screen reader lấy thông tin từ accessibility tree (cây ngữ nghĩa mà hệ điều hành/trình duyệt cung cấp): role, name, state, value và quan hệ của các thành phần. Người dùng có thể:

- di chuyển focus tới control kế tiếp/trước;
- nhảy theo heading, landmark, link, button, form field hoặc table;
- đọc theo ký tự, từ, dòng hay đoạn;
- dùng phím tắt để tìm và thao tác nhanh;
- nghe speech hoặc đọc bằng refreshable Braille display;
- tăng tốc giọng đọc cao hơn mức người mới nghe quen.

Trong khảo sát WebAIM 2024 với 1.539 người trả lời, cách phổ biến nhất để khám phá một trang là đi qua headings; trên desktop/laptop, JAWS và NVDA là hai screen reader chính được báo cáo nhiều nhất. Khảo sát là mẫu tự chọn nên không đại diện toàn bộ cộng đồng, nhưng cho thấy cấu trúc heading có giá trị thực tế.[^7]

### Mental model khác với người nhìn màn hình

Người nhìn có thể lướt cả trang, thấy tiêu đề, chart và nút cùng lúc. Người nghe thường nhận thông tin theo chuỗi. Họ dùng cấu trúc để bỏ qua phần không cần thiết. Nếu cấu trúc mất, quá trình biến thành:

```text
Nghe → bỏ qua → nghe → bỏ qua → đoán vị trí → quay lại
```

Do đó một trang “đọc được mọi chữ” nhưng không có heading, label hoặc thứ tự focus hợp lý vẫn gây tốn thời gian lớn.

## 4.2. Các screen reader và cách dùng phổ biến

- **NVDA:** miễn phí, mã nguồn mở, chạy trên Windows 10 trở lên theo thông tin hiện tại của NV Access.[^8]
- **JAWS:** screen reader thương mại trên Windows, có nhiều chức năng cho môi trường doanh nghiệp và OCR với tài liệu/ảnh khó truy cập.[^9]
- **Narrator:** tích hợp sẵn trong Windows.
- **VoiceOver:** tích hợp trong macOS; có rotor, Item Chooser, Quick Nav, bàn phím và Braille. Rotor cho phép nhảy theo headings, links, controls, tables và landmarks thay vì đọc tuần tự toàn bộ trang.[^10]

Không nên hỏi “Anh/chị có dùng screen reader không?” rồi dừng. Cần hỏi cả **screen reader + browser + application + thiết lập + trình độ** vì cùng một trang có thể hoạt động khác theo tổ hợp.

## 4.3. Người low vision dùng laptop theo cách khác

Họ có thể dùng:

- browser zoom hoặc tăng text size;
- Windows Magnifier, ZoomText, macOS Zoom hoặc phần mềm tương tự;
- màn hình lớn, độ phân giải riêng, con trỏ lớn;
- high contrast/dark theme hoặc màu tự cấu hình;
- screen reader kết hợp magnification;
- nhiều khoảng nghỉ để giảm mỏi mắt.

Ở zoom cao, viewport chỉ còn một phần màn hình. Người dùng phải pan theo chiều ngang/dọc, có thể bỏ lỡ popup hoặc notification ngoài vùng nhìn, mất tiêu đề cột khi đọc bảng và khó biết mình đang ở section nào. W3C nêu rõ người dùng magnification dựa nhiều vào visual cue (dấu hiệu định hướng) và thiết kế nhất quán để giữ vị trí.[^1]

## 4.4. Những tác vụ văn phòng nào thường gây khó?

### Tài liệu và PDF

- PDF scan chỉ là ảnh;
- heading chỉ được làm to/bold nhưng không có semantic;
- reading order sai;
- bảng thiếu header;
- comment, track changes hoặc footnote khó khám phá;
- file được khóa khiến OCR/copy không dùng được.

### Spreadsheet

- bảng quá rộng;
- nhiều sheet và vùng merge;
- chart không có bảng dữ liệu tương đương;
- màu là cách duy nhất thể hiện trạng thái;
- screen reader phải đọc từng cell để dựng lại quan hệ;
- macro hoặc control tùy chỉnh không accessible.

### Presentation và shared screen

- người nói “như mọi người thấy ở đây”;
- slide là ảnh;
- chart thiếu data table hoặc description;
- shared screen không truyền semantic cho người tham gia;
- nội dung đổi nhanh hơn tốc độ khám phá bằng screen reader.

### Video training

- transcript chỉ chứa lời thoại, không chứa hành động trên màn hình;
- con trỏ bấm mà không nói tên control;
- “làm theo hình dưới”;
- không có audio description hoặc bản hướng dẫn text tương đương.

### Phần mềm doanh nghiệp

- control tùy chỉnh không có role/name/state;
- keyboard trap;
- focus nhảy sai sau khi dialog đóng;
- virtualized list không công bố đủ item;
- trạng thái loading/error không được thông báo;
- app update làm hỏng workflow và phím tắt đã học.

## 4.5. Dữ liệu workplace cho thấy đây không phải vấn đề nhỏ

AFB khảo sát 323 người lao động mù, low vision hoặc deafblind và phỏng vấn 25 người trong năm 2021. Khoảng một phần ba số người phải làm automated hiring test báo cáo khó khăn accessibility; 59% gặp khó với onboarding form giấy và 48% với form điện tử. Khoảng một phần tư không thể truy cập đầy đủ training bắt buộc; 21% từng cân nhắc không yêu cầu accommodation vì lo phản ứng tiêu cực.[^11]

Người tham gia dùng công nghệ văn phòng giống đồng nghiệp: email, web, word processing, video conference, PDF, spreadsheet, file sharing và instant messaging. Vấn đề là mainstream software và assistive technology đôi khi không tương thích, tài liệu từ đồng nghiệp không được định dạng accessible, còn IT staff không phải lúc nào cũng hiểu công cụ hỗ trợ.[^12]

Một nghiên cứu tiếp theo trên dữ liệu người dùng workplace cho thấy screen reader, smartphone/tablet và OCR là ba nhóm assistive technology được người mù/low vision báo cáo dùng nhiều; với nhóm còn thị lực hữu dụng, magnification, tính năng accessibility có sẵn và video magnifier nổi bật hơn.[^13] Không được biến các tỷ lệ này thành dự đoán cho Việt Nam, nhưng chúng giúp team tránh giả định rằng một công cụ duy nhất phục vụ tất cả.

---

# 5. Họ sử dụng điện thoại ra sao?

## 5.1. Với screen reader: chạm để khám phá, vuốt để di chuyển, double-tap để kích hoạt

Trên Android, TalkBack có thể đọc item dưới ngón tay; vuốt trái/phải chuyển focus; double-tap kích hoạt item đang focus. Khi TalkBack bật, một số gesture một ngón thông thường chuyển thành hai ngón.[^14]

Trên iPhone/iPad, VoiceOver có mô hình tương tự và thêm rotor — thao tác xoay hai ngón như một núm ảo để chọn cách di chuyển theo ký tự, từ, heading, landmark hoặc loại control.[^6]

Điều này dẫn tới một lỗi demo rất thường gặp: team kiểm thử bằng mắt, tap đúng tọa độ rồi nghĩ app accessible. Người dùng screen reader lại đi theo focus order và accessible label. Hai trải nghiệm có thể hoàn toàn khác.

## 5.2. Với low vision

Người dùng có thể:

- tăng font/display size;
- dùng screen magnification;
- chỉnh contrast, color correction, inversion hoặc dark theme;
- dùng Select to Speak/Read & Speak cho đoạn dài;
- dùng camera magnifier để nhìn nhãn, bảng và vật ở xa;
- kết hợp external keyboard.

Nếu app khóa orientation, không reflow khi chữ lớn, đặt button sát nhau hoặc che nội dung khi zoom, tính năng hệ điều hành không cứu được thiết kế.

## 5.3. Camera đã là một assistive tool mạnh, nhưng chưa giải quyết mọi thứ

Các sản phẩm hiện có đã làm được nhiều việc:

- Google Lookout đọc text/tài liệu, nhận dạng một số vật/nhãn và mô tả hình ảnh; tiếng Việt nằm trong danh sách ngôn ngữ được hỗ trợ hiện tại.[^5]
- Microsoft Seeing AI đọc short text, tài liệu, barcode, currency và mô tả scene/photo; một số phiên bản còn cho phép hỏi tài liệu sau khi scan.[^15]
- Apple Magnifier và VoiceOver Recognition hỗ trợ đọc text, nhận biết scene/UI trong các cấu hình tương thích.[^6]
- Dịch vụ remote visual assistance kết nối người dùng với tình nguyện viên hoặc nhân viên hỗ trợ khi cần judgment của con người.

Khoảng trống không nên được mô tả là “người khiếm thị chưa có app nhìn hộ”. Một nghiên cứu diary tại Ấn Độ về object-recognition app ghi nhận cả bài toán camera placement, stigma khi dùng nơi công cộng, quyền riêng tư của người xung quanh, an toàn thiết bị và độ tin cậy.[^16]

## 5.4. Notification và chuyển ứng dụng

Screen reader có thể đọc notification, nhưng vấn đề là:

- notification đến khi TTS đang đọc nội dung khác;
- nhiều alert chen vào làm mất vị trí;
- text notification thiếu context;
- bấm vào notification mở một màn hình mới và người dùng phải dựng lại mental model;
- task bắt đầu ngoài đời nhưng bước tiếp theo nằm trên laptop hoặc ngược lại.

Đây là nơi ý tưởng “handoff” có thể có giá trị, nhưng chỉ khi end-user xác nhận việc chuyển context là rào cản lớn hơn những vấn đề cơ bản như file inaccessible.

---

# 6. Bản đồ các công cụ hỗ trợ hiện có

| Nhu cầu | Công cụ/strategy hiện có | Làm tốt điều gì? | Khoảng trống còn lại |
|---|---|---|---|
| Đọc giao diện số | NVDA, JAWS, Narrator, VoiceOver, TalkBack | Đọc semantic, điều hướng control, nhập liệu | Phụ thuộc app được code đúng; visual phức tạp thường nghèo thông tin |
| Đọc chính xác/yên lặng | Refreshable Braille display, Braille keyboard | Chính tả, code, ký hiệu, đọc không dùng loa | Giá cao, cần kỹ năng, app phải hỗ trợ tốt |
| Phóng đại | OS magnifier, ZoomText, browser zoom, màn hình lớn | Giữ kênh thị giác, đọc chi tiết | Mất overview, pan nhiều, dễ bỏ lỡ thay đổi |
| Điều chỉnh hiển thị | Text size, contrast, dark mode, color filter, pointer size | Giảm mỏi, tăng khả năng phân biệt | App có thể không tôn trọng setting hoặc layout bị vỡ |
| Đọc chữ in | OCR, camera magnifier, Seeing AI, Lookout | Chuyển nhãn/tài liệu thành text/speech | Góc chụp, ánh sáng, layout, privacy, lỗi OCR |
| Hiểu ảnh/scene | VLM app, human visual assistance | Mô tả nhanh, trả lời câu hỏi thị giác | Hallucination, thiếu bằng chứng, quá dài, không an toàn cho navigation |
| Di chuyển | Gậy trắng, chó dẫn đường, O&M, GPS, tactile paving | Phát hiện/né vật, định hướng, tuyến đường | Indoor context, môi trường thay đổi; công cụ AI không thay training an toàn |
| Viết và giao tiếp | Dictation, keyboard shortcut, TTS, Braille | Soạn email/tin nhắn, làm việc nhanh | Tên riêng, thuật ngữ, privacy, lỗi dictation |
| Họp | Accessible meeting app, transcript, agenda, verbal description | Theo dõi lời nói và cấu trúc buổi họp | Shared visual, ai đang chỉ vào đâu, nhịp cập nhật realtime |
| Nhận hỗ trợ | Đồng nghiệp, IT, human visual assistance | Judgment và xử lý tình huống mới | Chờ đợi, disclosure, privacy, mất tính độc lập |

WHO lưu ý phần lớn người dùng assistive technology cần nhiều hơn một sản phẩm, nên interoperability (khả năng hoạt động cùng nhau) và service/support quan trọng không kém bản thân thiết bị.[^17]

---

# 7. Hành trình công việc và các pain point

## 7.1. Trước khi được tuyển

| Khoảnh khắc | Rào cản có thể gặp | Workaround hiện tại | Chi phí ẩn |
|---|---|---|---|
| Tìm việc | Job board hoặc filter không dùng được bằng bàn phím | Nhờ người khác, dùng site khác | Bỏ lỡ cơ hội |
| Đọc JD | PDF scan, infographic, bảng không semantic | OCR hoặc yêu cầu bản text | Mất thời gian, lộ việc cần hỗ trợ sớm |
| Online assessment | Timer, drag-drop, canvas, proctoring không accessible | Xin accommodation hoặc bỏ bài | Stress, bị đánh giá sai năng lực |
| Phỏng vấn | Tài liệu/whiteboard chỉ chia sẻ bằng hình | Yêu cầu mô tả bằng lời | Khó tham gia cùng nhịp |

Vấn đề cốt lõi: quy trình đang đo khả năng vượt qua giao diện inaccessible thay vì năng lực thực hiện công việc.

## 7.2. Onboarding

- form giấy hoặc điện tử inaccessible;
- training video “watch and click”;
- sơ đồ văn phòng, sơ đồ tổ chức và process map chỉ là ảnh;
- thiết bị được cấp nhưng screen reader/magnifier chưa được cài hoặc IT policy chặn;
- tài khoản và MFA setup phụ thuộc QR/visual code;
- phải tự giải thích nhu cầu với nhiều bộ phận.

AFB cho thấy hiring và onboarding là hai điểm barrier rõ trong dữ liệu của họ.[^11] Với ADC, đây là khu vực dễ tạo demo vì có before/after cụ thể, nhưng phải chọn một bước đủ hẹp.

## 7.3. Nhận và hiểu task

Task có thể nằm rải trong email, chat, meeting và screenshot. Người dùng vẫn đọc được text, nhưng các tham chiếu như “ô màu đỏ”, “chart bên phải” hoặc “làm giống ảnh” làm mất phần quan trọng. Nếu phải hỏi lại, họ có thể bị hiểu sai là không chú ý.

Pain point không phải “không hiểu task” mà là **task được mã hóa bằng tín hiệu thị giác không có phương án tương đương**.

## 7.4. Làm việc với chart, dashboard và spreadsheet

Đây là tình huống giàu tiềm năng nhưng cũng dễ bị làm hời hợt. Một caption kiểu “biểu đồ doanh thu tăng” không đủ để:

- kiểm tra con số;
- so sánh hai vùng;
- tìm ngoại lệ;
- đặt câu hỏi ngược lại;
- biết kết luận đến từ đâu.

Người dùng cần nhiều tầng: overview → cấu trúc → dữ liệu → quan hệ → evidence. Nếu AI mô tả sai một trục, toàn bộ quyết định có thể sai.

## 7.5. Họp và cộng tác

- shared screen không semantic;
- người nói phụ thuộc vào pointer;
- chat, raised hand và slide cùng cạnh tranh audio channel;
- screen reader speech chồng lên lời họp;
- whiteboard không accessible;
- đồng nghiệp gửi screenshot thay vì text/data source;
- không có thời gian khám phá visual trước khi cuộc thảo luận chuyển chủ đề.

Insight ở đây là **latency (độ trễ tiếp cận thông tin)**. Cuối cùng nghe được mô tả sau cuộc họp không tương đương với việc có dữ liệu đúng lúc để phát biểu.

## 7.6. Dùng phần mềm nội bộ

Người dùng có thể xây workflow hiệu quả bằng phím tắt và mental map. Một bản cập nhật nhỏ làm focus order đổi, button mất label hoặc popup mới xuất hiện có thể phá workflow. Người dùng đôi khi tự troubleshooting vì IT không quen assistive technology.[^11]

Giải pháp cần cân nhắc:

- sửa app gốc;
- accessible guide theo phiên bản;
- regression testing (kiểm thử hồi quy accessibility);
- fallback và kênh báo lỗi;
- không chỉ “AI bấm thay” vì agent cũng có thể sai và che mất nguyên nhân gốc.

## 7.7. Yêu cầu accommodation và làm việc với IT/HR

Đây là problem mang tính hệ thống:

- không biết được yêu cầu công cụ gì;
- quy trình mua/cài phần mềm kéo dài;
- lo bị nhìn là tốn kém hoặc kém năng suất;
- công cụ cá nhân xung đột security policy;
- HR, IT và manager giữ các phần context khác nhau;
- employee phải trở thành chuyên gia hỗ trợ kỹ thuật cho chính mình.

Đừng thiết kế một “medical profile” chia sẻ rộng. Tốt hơn là lưu preference và requirement theo task, với quyền kiểm soát của employee.

## 7.8. Phát triển nghề nghiệp

Nếu training, dashboard và công cụ mới không accessible, tác động không dừng ở một task. Người dùng có thể mất cơ hội học kỹ năng, nhận nhiệm vụ khó hoặc thăng tiến. Khi đo impact, team nên hỏi “giải pháp này thay đổi quyền tham gia vào công việc có giá trị như thế nào?” thay vì chỉ “tiết kiệm mấy cú click?”.

---

# 8. Những insight sâu hơn cho ADC

## Insight 1 — Rào cản lớn thường là mất cấu trúc, không phải mất chữ

OCR có thể lấy được text nhưng không biết đoạn nào là heading, label nào thuộc value nào, mũi tên nối hai node gì hoặc cell thuộc hàng/cột nào. AI hữu ích khi khôi phục cấu trúc, nhưng output phải giữ source reference và uncertainty.

**Cơ hội:** structured visual extraction, accessible navigator, evidence-linked Q&A.

## Insight 2 — Information latency có thể gây loại trừ dù nội dung cuối cùng vẫn truy cập được

Trong meeting, nghe mô tả chart sau 10 phút là quá muộn để tham gia thảo luận. Trong onboarding, đợi IT sửa file hai ngày làm employee chậm ngay tuần đầu.

**Cơ hội:** ưu tiên output vừa đủ, đúng lúc; đo time-to-answer và khả năng tham gia.

## Insight 3 — Accessibility là một chuỗi; một mắt xích hỏng có thể chặn toàn task

Screen reader tốt không giúp nếu PDF scan; app accessible không giúp nếu MFA inaccessible; AI mô tả tốt không giúp nếu nút gửi không có label. Hãy map end-to-end journey thay vì tối ưu một màn hình.

**Cơ hội:** chọn một vertical slice từ input tới outcome và kiểm thử bằng chính assistive technology.

## Insight 4 — Workaround có thể hiệu quả nhưng tiêu tốn “phần việc vô hình”

Người dùng có thể hoàn thành việc bằng OCR, copy qua app khác, đổi browser, tự sửa file hoặc nhờ đồng nghiệp. Nếu chỉ hỏi “có làm được không?”, team bỏ lỡ thời gian, mệt mỏi, privacy và social cost.

**Cơ hội:** đo số chuyển app, số lần retry, số lần nhờ giúp và confidence.

## Insight 5 — Người mù và người low vision có thể cần hai interaction model khác nhau

Một audio-only assistant không giải quyết bài toán zoom/orientation. Một visual breadcrumb không đủ cho screen reader. Cùng một backend có thể cần presentation mode khác nhau.

**Cơ hội:** preference-based output thay vì một “accessible mode” chung.

## Insight 6 — Mô tả càng nhiều chưa chắc càng hữu ích

Audio là kênh nối tiếp. Mô tả dài có thể che lời họp và buộc người dùng nghe nội dung không liên quan. Người dùng cần quyền chọn overview, drill-down và mức verbosity.

**Cơ hội:** progressive disclosure bằng audio/semantic structure.

## Insight 7 — AI phải biết từ chối ở nơi sai một chi tiết có hậu quả lớn

Sai màu áo trong mô tả ảnh có thể ít rủi ro; đọc sai deadline, con số tài chính hoặc hướng di chuyển lại nghiêm trọng. Cùng một model nhưng cần guardrail khác theo task.

**Cơ hội:** confidence, source evidence, deterministic calculation, human confirmation và risk-tiered behavior.

## Insight 8 — Agency quan trọng hơn “AI làm hết”

Employee có thể muốn AI chuẩn bị draft, tìm control hoặc mô tả context, nhưng vẫn tự quyết định gửi, sửa, xóa hay xác nhận. Automation không được biến thành surveillance hoặc hành động không thể hoàn tác.

**Cơ hội:** preview → confirm → execute → verify → undo.

## Insight 9 — Điểm chuyển giữa vật lý và số là một hypothesis đáng nghiên cứu, chưa phải kết luận

Ví dụ: đọc nhãn hồ sơ giấy rồi mở record tương ứng trên laptop; tìm phòng họp rồi truy cập agenda; nhận biết thiết bị rồi mở đúng manual. Nếu người dùng phải nhập lại context ở mỗi thiết bị, handoff có thể giảm bước.

Nhưng nếu brief chỉ tập trung vào một tài liệu số, việc thêm camera và computer-use agent sẽ làm scope phình mà không tăng impact.

---

# 9. Từ pain point tới các hướng ý tưởng

Các ý tưởng dưới đây liên kết với [`ADC_2026_Competitive_Idea_Portfolio.md`](./ADC_2026_Competitive_Idea_Portfolio.md). Chúng không phải quyết định build.

## 9.1. EvidenceLens — khám phá shared visual có bằng chứng

### Pain point phù hợp

Nhân viên nhận chart/dashboard/screenshot trong meeting nhưng không thể truy cập dữ liệu và quan hệ đủ nhanh để tham gia.

### Giải pháp giả thuyết

```text
Visual input
→ OCR + layout/chart extraction
→ evidence graph có region/value/relation/confidence
→ overview
→ điều hướng theo section/data point
→ Q&A chỉ dựa trên evidence
```

### Tại sao AI có ý nghĩa?

Input không có schema cố định và cần hiểu quan hệ thị giác. Tuy nhiên con số sau extraction phải được tính bằng code; model không được tự bịa phép tính.

### Cần xác nhận với người dùng

- Họ thường nhận visual ở format nào?
- Pain nằm ở data access, timing hay interaction với meeting?
- Output table, audio summary hay keyboard explorer hữu ích hơn?
- Họ cần hỏi loại câu nào?
- Sai một số có hậu quả gì?

### Loại ý tưởng nếu

- brief không có visual workplace artifact;
- người dùng luôn có data source accessible;
- một data table chuẩn giải quyết đủ tốt;
- team không thể chứng minh grounding và uncertainty.

## 9.2. ScreenTrail — chuyển manual phụ thuộc screenshot thành step player

### Pain point phù hợp

Training/onboarding guide có câu “click như hình” và chuỗi screenshot không dùng được bằng screen reader.

### Giải pháp giả thuyết

Biến manual thành goal → prerequisites → control name/role → action → expected state → recovery, kèm source page và confidence.

### Điểm mạnh

- workplace moment rõ;
- demo before/after dễ hiểu;
- đo được completion time và assistance;
- không cần điều khiển toàn hệ điều hành.

### Cần xác nhận

- Đây có phải barrier thường xuyên hơn tài liệu text/PDF nói chung?
- Người dùng muốn nghe từng bước hay đọc trên Braille?
- Khi UI khác manual, họ phục hồi thế nào?
- Trainer có sẵn sàng duyệt/sửa output không?

## 9.3. QuietDescribe — audio description cho training video

### Pain point phù hợp

Video có hành động quan trọng chỉ xuất hiện trên màn hình trong khi transcript chỉ ghi lời nói.

### Giải pháp giả thuyết

ASR + scene detection + VLM tạo description candidate; hệ thống gắn source frame, giới hạn theo khoảng lặng và bắt buộc reviewer duyệt trước xuất bản.

### Cần thận trọng

Output realtime không cần thiết cho video đã ghi. Một authoring tool cho trainer có thể thực tế và an toàn hơn auto-description không kiểm duyệt.

## 9.4. ZoomAnchor — giữ orientation khi phóng đại

### Pain point phù hợp

Người low vision zoom 200–400%, chỉ thấy một vùng và bỏ lỡ section, column hoặc notification ngoài viewport.

### Giải pháp giả thuyết

Spatial breadcrumb, anchor để quay lại, summary về thay đổi ngoài vùng nhìn và chế độ preview toàn cảnh.

### Câu hỏi sống còn

AI có thực sự cần không? Nếu layout và state management thông thường giải quyết được, không nên gắn AI cho đủ tiêu chí.

## 9.5. WorkBridge — companion xuyên ngữ cảnh, hiện chỉ ở idea bank

### Hạt nhân

Camera giúp lấy context từ vật thể/môi trường; structured task state được chuyển sang laptop; client mở đúng resource và chuẩn bị bước số tiếp theo.

### Chỉ đưa lại shortlist khi

1. Brief thuộc Visual Impairment và có journey qua cả vật lý lẫn số.
2. End-user xác nhận mất context khi đổi thiết bị là pain thật.
3. Có một golden path duy nhất.
4. Camera không thay gậy/chó dẫn đường hay đưa chỉ dẫn an toàn.
5. Laptop action bị allowlist, có preview, confirmation, verification và undo.
6. Giá trị vượt rõ ràng so với “chụp ảnh rồi mở app thủ công”.

### Một golden path đủ hẹp để hình dung

```text
Nhân viên scan nhãn một hồ sơ vật lý
→ hệ thống đọc mã và cho xác nhận
→ gửi task state sang laptop
→ mở record giả lập tương ứng
→ chuẩn bị form cập nhật
→ người dùng nghe lại và xác nhận lưu
```

Đây chỉ là ví dụ để đánh giá architecture, không phải project đã chọn.

## 9.6. Bảng đối chiếu nhanh

| Hướng | Barrier chính | AI necessity | Scope 3 ngày | Rủi ro lớn nhất |
|---|---|---:|---:|---|
| EvidenceLens | Shared visual mất cấu trúc/dữ liệu | Cao | Vừa | Bịa hoặc gắn sai số |
| ScreenTrail | Manual phụ thuộc screenshot | Cao | Tốt nếu chỉ một manual | UI thực tế khác hướng dẫn |
| QuietDescribe | Video thiếu thông tin thị giác | Vừa–cao | Vừa | Timing và description sai |
| ZoomAnchor | Mất orientation khi zoom | Thấp–vừa | Tốt | AI bị gắn khi không cần |
| WorkBridge | Mất context vật lý → laptop | Cao | Khó nếu không siết scope | Safety, privacy, agent làm sai |

---

# 10. Cách phỏng vấn end-user trong Day 1–2

## 10.1. Mục tiêu của buổi nói chuyện

Không phải chứng minh idea hay. Team cần hiểu:

1. task thực tế;
2. barrier xuất hiện ở bước nào;
3. workaround hiện tại;
4. chi phí của workaround;
5. điều gì đủ đáng để thay đổi;
6. lỗi nào người dùng không chấp nhận.

## 10.2. Câu mở đầu

- Anh/chị muốn chúng em xưng hô và mô tả về thị lực của anh/chị như thế nào?
- Khi dùng laptop/điện thoại, anh/chị thường dùng công cụ và thiết lập nào?
- Có task công việc nào anh/chị làm rất trơn tru mà mọi người thường tưởng là khó không?
- Gần đây nhất khi một công cụ hoặc tài liệu chặn công việc của anh/chị là lúc nào?

## 10.3. Hỏi theo một sự kiện đã xảy ra

- Anh/chị có thể dẫn chúng em qua từng bước từ lúc nhận task tới lúc hoàn thành không?
- Input đến từ đâu: email, chat, cuộc họp, file hay vật thể?
- Bước nào bắt đầu tốn thời gian?
- Khi đó anh/chị đã thử gì?
- Có phải đổi app/browser/device không?
- Có nhờ ai hỗ trợ không? Chờ bao lâu?
- Cuối cùng task có hoàn thành không? Có sai hoặc bỏ sót gì không?

## 10.4. Hỏi về laptop và điện thoại

- Screen reader/magnifier nào? Phiên bản và tổ hợp browser/app nào?
- Anh/chị dùng keyboard, touch, voice hay Braille ở bước nào?
- Mức zoom và speech rate thường dùng?
- Output nào dễ dùng trong môi trường có người khác: audio, Braille, text lớn hay haptic?
- Notification ảnh hưởng tới vị trí/focus ra sao?
- Khi đổi từ điện thoại sang laptop, context nào thường bị mất?

## 10.5. Hỏi về AI

- Với task này, sai ở điểm nào chỉ gây phiền và sai ở điểm nào có hậu quả lớn?
- Anh/chị muốn thấy/nghe evidence dưới dạng nào?
- Khi model không chắc, hệ thống nên hỏi, dừng hay đưa nhiều khả năng?
- Hành động nào luôn phải xác nhận?
- Dữ liệu nào không được gửi lên cloud?
- Anh/chị muốn hệ thống lưu lịch sử trong bao lâu?

## 10.6. Tránh những câu này

- “Người mù có dùng smartphone được không?”
- “Anh/chị chắc sẽ thích app này đúng không?”
- “Điều gì khó nhất khi bị mù?”
- “Nếu AI làm mọi thứ thay anh/chị thì có tốt hơn không?”
- “Anh/chị đại diện cho người khiếm thị thấy sao?”

Chúng quá rộng, dẫn dắt hoặc đặt người trả lời thành đại diện cho cả cộng đồng.

## 10.7. Cách ghi insight sau phỏng vấn

| Trường | Nội dung cần ghi |
|---|---|
| Observed fact | Người dùng kể/biểu diễn điều gì đã xảy ra? |
| Quote ngắn | Câu nào diễn tả trade-off rõ? |
| Barrier | Thiết kế, format, quy trình hay môi trường chặn ở đâu? |
| Current workaround | Họ đang làm gì để vượt qua? |
| Hidden cost | Thời gian, lỗi, mệt, privacy, social cost? |
| Need | Outcome họ cần, chưa gắn với feature |
| Hypothesis | Team nghĩ giải pháp nào có thể giúp? |
| Confidence | Thấp/vừa/cao; đã nghe từ bao nhiêu người? |
| Design change | Prototype phải đổi gì? |

Không ghi chẩn đoán hoặc dữ liệu cá nhân không cần thiết. Xin phép trước khi ghi âm, chụp màn hình hoặc dùng quote trong pitch.

---

# 11. Nguyên tắc thiết kế và kiểm thử prototype

## 11.1. Prototype phải tự accessible

Một sản phẩm “cho người khiếm thị” nhưng bản thân không dùng được bằng screen reader sẽ mất độ tin cậy ngay lập tức.

Checklist tối thiểu:

- HTML semantic; heading theo hierarchy;
- mỗi control có accessible name;
- dùng được hoàn toàn bằng bàn phím;
- focus visible và focus order hợp lý;
- sau action, focus đi tới nơi có nghĩa;
- loading, success, error và dynamic update được announce;
- không dùng màu làm tín hiệu duy nhất;
- text resize/reflow không mất chức năng;
- contrast đủ và tôn trọng reduced motion/theme nếu có;
- chart có data table hoặc alternative phù hợp;
- output AI có heading, list và source reference;
- không auto-play speech chồng lên screen reader;
- kiểm thử với NVDA + Chrome/Firefox ít nhất một tổ hợp;
- kiểm thử zoom 200% và keyboard-only.

## 11.2. AI output phải có cấu trúc và độ chắc chắn

Ví dụ contract:

```json
{
  "summary": "North region decreased 12%",
  "evidence": [
    {
      "label": "North, Q2",
      "value": 88,
      "sourceRegion": "chart-1-bar-2",
      "confidence": 0.94
    }
  ],
  "uncertainties": [],
  "recommendedAction": "review"
}
```

UI không nên chỉ đọc confidence 0.94. Hãy chuyển thành hành vi có nghĩa: “Đã xác minh từ hai data point” hoặc “Số này mờ; cần kiểm tra trước khi dùng”.

## 11.3. Hành động có hậu quả phải có quyền kiểm soát

- Draft trước, gửi sau.
- Preview trước, ghi file sau.
- Xác nhận recipient, filename, deadline và dữ liệu quan trọng.
- Có history và undo nếu khả thi.
- Không mở rộng permission ngầm.
- Không thu camera/screen liên tục nếu task chỉ cần một frame hoặc một file.

## 11.4. Metrics phải đo task, không chỉ model

| Nhóm metric | Ví dụ |
|---|---|
| Outcome | Completion rate, task đúng/sai |
| Efficiency | Thời gian, số thao tác, số lần chuyển app |
| Independence | Số lần cần nhờ người khác, thời gian chờ |
| AI quality | Extraction accuracy, unsupported claim rate |
| Accessibility | Keyboard success, screen-reader announcement lỗi |
| Agency | Người dùng phát hiện uncertainty không? Có biết action sắp xảy ra không? |
| Experience | Confidence, fatigue, perceived control |

So sánh ít nhất hai điều kiện: current workaround và prototype. Ba người test nội bộ không thay thế end-user evaluation.

---

# 12. Cách quyết định có chọn Visual Impairment hay không

Sau khi nhận brief, team chấm từng câu 0–2:

| Câu hỏi | 0 | 1 | 2 |
|---|---|---|---|
| Có một workplace moment cụ thể? | Không | Còn rộng | Rất rõ |
| Có end-user evidence? | Không | Một dấu hiệu | Lặp lại/quan sát được |
| Current workaround có chi phí đáng kể? | Không rõ | Có nhưng nhỏ | Rõ và đo được |
| Existing tools chưa giải quyết đủ? | Chưa kiểm tra | Có gap nhỏ | Gap rõ theo workflow |
| AI thật sự cần? | Không | Có thể | Cần cho input/scale/structure |
| Có vertical slice 3 ngày? | Không | Rủi ro | Chắc chắn |
| Có thể demo bằng assistive technology? | Không | Một phần | End-to-end |
| Safety/privacy kiểm soát được? | Không | Còn lỗ hổng | Có boundary rõ |

### Quy tắc

- **13–16:** đáng shortlist.
- **9–12:** chỉ tiếp tục nếu phỏng vấn tiếp có thể giải quyết điểm yếu.
- **0–8:** bỏ, dù công nghệ nghe hấp dẫn.

Team không chọn Visual chỉ vì Phúc mạnh computer vision/VLM. Hãy chọn khi brief, người dùng, workflow và năng lực team cùng giao nhau.

---

# 13. Nguồn tham khảo

[^1]: W3C Web Accessibility Initiative. “[Visual Disabilities — Diverse Abilities and Barriers](https://www.w3.org/WAI/people-use-web/abilities-barriers/visual/).” Cập nhật 25/06/2024.
[^2]: UNDP Viet Nam. “[Improving Employment Opportunities for Persons with Disabilities in Viet Nam](https://www.undp.org/vietnam/publications/report-improving-employment-opportunities-persons-disabilities-viet-nam).” 29/12/2020. Nghiên cứu bối cảnh chính sách, việc làm và phát triển nghề nghiệp tại Việt Nam; dữ liệu đã cũ hơn cuộc thi nên cần kiểm tra lại.
[^3]: World Health Organization. “[Blindness and vision impairment](https://www.who.int/news-room/fact-sheets/detail/blindness-and-visual-impairment).” 10/02/2026.
[^4]: American Foundation for the Blind. “[Household, Personal and Other Independent Living Products](https://afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/independent-living-products).” Truy cập 12/09/2026.
[^5]: Google Android Accessibility Help. “[Use Lookout to explore your surroundings](https://support.google.com/accessibility/android/answer/9031274?hl=en).” Truy cập 12/09/2026.
[^6]: Apple Support. “[About the VoiceOver rotor on iPhone or iPad](https://support.apple.com/en-us/111796).” 20/03/2025. Trang cũng nêu giới hạn an toàn của Live Recognition.
[^7]: WebAIM. “[Screen Reader User Survey #10 Results](https://webaim.org/blog/screen-reader-user-survey-10-results/).” Khảo sát 12/2023–01/2024, 1.539 người trả lời. Đây là self-selected survey, không phải thống kê đại diện toàn cầu.
[^8]: NV Access. “[Download NVDA](https://www.nvaccess.org/download/).” Truy cập 12/09/2026.
[^9]: Freedom Scientific. “[JAWS Screen Reader Product Flyer](https://support.freedomscientific.com/Content/Documents/ProductFlyers/JAWS_Flyer.pdf).” Tài liệu sản phẩm; dùng để xác nhận chức năng, không dùng làm bằng chứng hiệu quả độc lập.
[^10]: Apple Support. “[Intro to advanced navigation with VoiceOver on Mac](https://support.apple.com/en-ca/guide/voiceover/vo27974/mac).” Truy cập 12/09/2026.
[^11]: American Foundation for the Blind. “[Workplace Technology Study — Executive Summary](https://afb.org/research-and-initiatives/employment/workplace-tech-study/executive-summary).” 2022. Survey 323 người và phỏng vấn 25 người tại Mỹ; một số trang tóm tắt của AFB diễn giải tỷ lệ training khác nhau, nên tài liệu này dùng con số thận trọng từ executive summary.
[^12]: American Foundation for the Blind. “[Workplace Technology Study — Accommodations and Accessibility](https://afb.org/research-and-initiatives/employment/workplace-tech-study/accommodations-and-accessibility).” 2022.
[^13]: Rosenblum và cộng sự. “[Assistive Technology Use in the Workplace by People with Blindness and Low Vision: Perceived Skill Level, Satisfaction, and Challenges](https://pmc.ncbi.nlm.nih.gov/articles/PMC10703993/).” *Assistive Technology*, 2023.
[^14]: Google Android Accessibility Help. “[Use TalkBack gestures](https://support.google.com/accessibility/android/answer/6151827?hl=en).” Truy cập 12/09/2026.
[^15]: Microsoft Accessibility Blog. “[Seeing AI App Launches on Android](https://blogs.microsoft.com/accessibility/seeing-ai-app-launches-on-android-including-new-and-updated-features-and-new-languages/).” 04/12/2023. Tài liệu của nhà sản xuất, dùng để xác nhận feature chứ không chứng minh độ chính xác trong mọi bối cảnh.
[^16]: Microsoft Research và cộng sự. “[Exploring the Experiences of Individuals Who are Blind or Low-Vision Using Object-Recognition Technologies in India](https://www.microsoft.com/en-us/research/wp-content/uploads/2025/02/CHI-OR-diary-final.pdf).” CHI 2025.
[^17]: World Health Organization. “[Assistive technology](https://www.who.int/news-room/fact-sheets/detail/assistive-technology).” 02/01/2024.

---

## Lời nhắc cuối

Đừng tới Day 1 với câu hỏi “chúng ta sẽ làm AI gì cho người mù?”. Hãy tới với khả năng quan sát một workflow và hỏi:

> Người này đang muốn hoàn thành việc gì, thông tin hoặc hành động bị chặn ở bước nào, họ đang khắc phục ra sao, và giải pháp nào giúp họ nhanh hơn mà vẫn giữ quyền kiểm soát?

Khi trả lời được câu đó bằng evidence, team mới chọn công nghệ.
