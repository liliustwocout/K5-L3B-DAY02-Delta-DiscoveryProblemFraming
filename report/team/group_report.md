# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: Delta
- Thành viên: [Lê Phạm Thành Đạt, Cao Trung Hiếu, Cao Thanh Tùng và Trần Đức Duy](../../TEAM.md#thành-viên).
- Đề tài đã chọn: Cập nhật MVP realtime.
- Vấn đề nhóm chọn: Khi khách góp ý trong buổi pitch, nhóm chưa thể cập nhật giao diện ngay, nên phải chỉnh sửa nội bộ rồi có thể phải hẹn thêm buổi để khách xem và xác nhận bản sửa.
- Quyết định cuối: **Go cho bản thử nội bộ** trên màn hình Lịch tư vấn, giới hạn ở đổi nhãn hoặc vị trí nút Đặt lịch. [Phạm vi và ngưỡng dừng](#8-quyết-định-cp6)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Bảng tổng hợp 12 card từ báo cáo cá nhân. Cột cuối ghi câu hỏi dùng khi rà lại bài. Chưa có biên bản đầy đủ để xác nhận câu nào đã được hỏi và ai hỏi trong buổi pitch.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi rà soát |
| ---: | --- | --- | --- | --- | --- |
| 1 | Đạt | Khi kiểm hồ sơ HR, cần tìm mục lệch giữa bản giấy và bản mềm để bổ sung đúng chỗ. | Nhân sự phụ trách hồ sơ | Đối chiếu từng cặp bản. Khoảng một ngày tính cho cả đợt. | Tìm hồ sơ, đối chiếu hay bổ sung mất thời gian nhất? |
| 2 | Đạt | Khi đăng ký nhiều sự kiện, cần xem lại tên và giờ để sắp lịch. | Người đăng ký sự kiện | Tìm lại thông tin của 4 sự kiện. | Tra lại lịch mất bao lâu? Đã bỏ lỡ sự kiện nào chưa? |
| 3 | Đạt | Khi thông báo thực tập chưa rõ, cần biết câu trả lời và mốc cập nhật để chuẩn bị. | Sinh viên chuẩn bị thực tập | Khoảng hai tháng chờ thông báo kế tiếp. | Thông báo mới đã giải đáp câu hỏi ban đầu chưa? |
| 4 | Hiếu | Sau họp khách hàng, cần cô đọng quyết định và việc cần làm để gửi nhóm. | BA | Đọc lại và cô đọng ghi chú sau họp. | Mốc khoảng 30 phút gồm đọc lại, viết hay cả hai? |
| 5 | Hiếu | Khi khách góp ý về MVP, cần cho khách thấy bản sửa sớm để xác nhận đúng ý. | Người phụ trách demo MVP | Ước tính 15–20 phút trao đổi lại và cập nhật mỗi vòng. | Buổi nào chỉ hẹn lại để xem bản sửa nhỏ, buổi nào vì yêu cầu còn chưa rõ? |
| 6 | Hiếu | Khi xây hồ sơ trên nhiều nền tảng, cần chuẩn bị nội dung nhất quán để thể hiện đúng thế mạnh. | Người xây hồ sơ cá nhân | Tìm hiểu từng nền tảng, khoảng một tuần theo card. | Phần nào lặp lại giữa các nền tảng và phần nào cần tự tìm hiểu? |
| 7 | Tùng | Trước khi nộp lab, cần soát tên tệp, cấu trúc và tiêu chí để tránh lỗi. | Học viên hoặc nhóm học viên | Soát mục còn thiếu và đối chiếu rubric, khoảng 10–12 phút theo card. | Checklist hoặc Rule đã xử lý được những lỗi nào? |
| 8 | Tùng | Khi ghép bài của nhiều thành viên, cần tìm mâu thuẫn số liệu và ý lặp để biên tập bản chung. | Người tổng hợp báo cáo | Soát mâu thuẫn và chỉnh giọng văn, khoảng 30–40 phút theo card. | Bảng số liệu chung có tránh được mâu thuẫn từ đầu không? |
| 9 | Tùng | Khi cần tra lại hướng dẫn học tập, cần tìm đúng câu trả lời cũ để làm đúng yêu cầu. | Học viên | Cuộn tin nhắn khi từ khóa không khớp, khoảng 8–12 phút theo card. | Trường hợp nào có thể giải quyết bằng FAQ ghim đầu kênh? |
| 10 | Duy | Cuối kỳ, cần nắm quá trình học của từng em để viết nhận xét riêng. | Giáo viên bộ môn | Nhớ lại và tổng hợp thông tin từng em. Khoảng ba buổi tối cho cả đợt theo card. | Dữ liệu nào đã được ghi lại và dữ liệu nào chỉ có trong trí nhớ? |
| 11 | Duy | Khi chấm tự luận nhiều lớp, cần chấm kịp để trả bài khi học sinh còn nhớ nội dung. | Giáo viên bộ môn | Đọc và cho điểm. Khoảng 4 phút mỗi bài cho cả quy trình theo card. | Bao nhiêu thời gian dành cho đọc bài và bao nhiêu cho quyết định điểm? |
| 12 | Duy | Khi có điểm, cần chuyển từ sổ lên hệ thống đúng hạn và hạn chế nhập nhầm. | Giáo viên bộ môn | Gõ tay khoảng 160 điểm mỗi lượt theo card. | Hệ thống hiện tại có nhập từ bảng tính được không? |

Trong báo cáo cá nhân, Hiếu ghi nhận nhóm khác chất vấn giá trị của cách cập nhật MVP bằng AI. Phản hồi này dẫn đến việc phân biệt thay đổi nhỏ có thể thử ngay và thay đổi chức năng cần phân tích trước. Bản thử của Delta giới hạn ở thay đổi nhỏ trên bản xem trước. [Nhật ký và reflection của Hiếu](../individual/2A202603993_CaoTrungHieu.md)

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
| --- | --- | --- |
| A — Tổng hợp và đối chiếu | #1, #4, #8, #10 | Thông tin nằm ở nhiều nguồn. Người làm phải tìm và đối chiếu rồi mới quyết định. |
| B — Theo dõi và xác nhận bước tiếp theo | #2, #3, #5, #9 | Lịch, phản hồi hoặc hướng dẫn chưa sẵn có đúng lúc, khiến người dùng phải tra lại, chờ hoặc hẹn lại. |
| C — Thao tác lặp và kiểm soát sai sót | #6, #7, #11, #12 | Thao tác lặp trên nhiều nền tảng, tệp hoặc bản ghi. Kết quả cuối vẫn cần chính xác. |

### 2.3. Opportunity Solution Tree rút gọn

Từ ba cụm trên, cây dưới đây thu hẹp vào tình huống MVP được chọn.

```text
OUTCOME: Giảm số buổi hẹn lại chỉ để khách xác nhận bản sửa giao diện MVP.
├── Hiểu đúng khách muốn đổi phần nào và muốn đổi ra sao.
├── Có bản sửa nhỏ để xem khi hai bên vẫn đang trao đổi.
└── Biết ngay bản sửa đã đúng ý hay còn cần làm rõ.
```

Các ý “chép lời realtime”, “dùng AI để hiểu yêu cầu” và “tự áp thay đổi” được đưa sang phần giải pháp để so sánh sau.

### 2.4. Chấm điểm shortlist (1–5)

Điểm dưới đây được chấm lại từ các card để giải thích lựa chọn. Chưa có biên bản ghi điểm từng thành viên.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| #5 — Vòng sửa giao diện MVP | 5 | 5 | 3 | 5 | 5 | 5 | 4 | **32** |
| #7 — Rà soát bài nộp lab | 5 | 5 | 3 | 5 | 5 | 3 | 5 | **31** |
| #10 — Viết nhận xét cuối kỳ | 5 | 4 | 3 | 4 | 3 | 4 | 3 | **26** |

**Ứng viên được chọn.** [Problem Card #2 của Hiếu](../individual/2A202603993_CaoTrungHieu.md#problem-card-2). Vòng lặp có điểm bắt đầu và kết thúc rõ, từ lúc khách góp ý đến lúc xác nhận bản sửa. Có thể thử một thay đổi nhỏ trên một màn hình và so sánh với cách sửa tay.

**Lý do chưa chọn hai ứng viên còn lại.** Với rà soát bài nộp, checklist và Rule đã có thể xử lý nhiều lỗi hình thức, nên giá trị tăng thêm của AI ở phần đó chưa rõ. Với nhận xét cuối kỳ, cần kiểm tra nguồn dữ liệu về từng học sinh và quyền sử dụng trước khi thử trên tình huống thật.

**Điểm cần thống nhất khi rà lại.** Hai ứng viên đầu chỉ chênh một điểm. Nếu kiểm chứng cho thấy các buổi hẹn lại chủ yếu do đổi phạm vi, cần xem lại mức ưu tiên của bài MVP.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Cách kiểm chứng |
| ---: | --- | --- | ---: | ---: | --- |
| 1 | Có buổi hẹn lại chỉ để khách xác nhận một thay đổi nhỏ trên giao diện. | Value | 5 | 2 | Dựng lại một MVP đã làm và phân loại lý do hẹn lại. |
| 2 | Đổi nhãn và vị trí nút là hai thao tác đủ để kiểm tra giả thuyết trong phạm vi lab. | Value | 4 | 2 | Đối chiếu với các góp ý thực tế. |
| 3 | Công cụ phân biệt được yêu cầu rõ với câu hỏi, phủ định và yêu cầu đã rút lại. | Feasibility | 5 | 1 | Chạy bộ 20 tình huống bằng lời nói. |
| 4 | Bản sửa đúng xuất hiện trong 10 giây từ lúc người nói kết thúc câu. | Feasibility | 4 | 1 | Bấm giờ trong bộ thử. |
| 5 | Người trình bày nhận ra bản sửa sai và khôi phục được trong buổi demo. | Usability | 5 | 1 | Thử thao tác quay lại với người điều khiển demo. |
| 6 | Nhóm có thể xử lý âm thanh và vận hành trong giới hạn chi phí và quyền sử dụng dữ liệu. | Viability | 4 | 1 | Đo chi phí nội bộ. Xác nhận quyền xử lý âm thanh trước khi thử với khách. |

Ưu tiên giả định 1 để xem việc sửa ngay có thể giảm buổi hẹn lại hay không. Giả định 3–5 quyết định bản thử có đủ tin cậy để đưa vào buổi pitch mô phỏng.

### 3.2. Kiểm chứng

**Cách đã dùng.** Đối chiếu Problem Card của người phụ trách demo với luồng và các mốc thời gian trên slide nhóm. Hai tài liệu cùng mô tả tình huống của nhóm, nên chỉ tính là một nguồn nội bộ về vấn đề. Chưa có bản ghi phỏng vấn, survey, lịch họp hoặc ticket để xác nhận tần suất và thời gian.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác hoặc giới hạn |
| --- | ---: | --- | --- |
| [Problem Card #2 của Hiếu](../individual/2A202603993_CaoTrungHieu.md#problem-card-2) | 1 ghi chép cá nhân | Có vòng lặp làm rõ yêu cầu, chỉnh giao diện và trình bày lại. Card ước tính 2–3 vòng cho một MVP. | Card nêu có thể sửa trực tiếp trong buổi pitch nếu thao tác đủ đơn giản. Cần xác định phần nào thực sự phải dời sang buổi khác. |
| [Slide nhóm](../assets/cp4-cac-vong-chinh-sua-mvp.html#slide-2) | 1 tài liệu diễn giải cùng tình huống | Tách thời gian họp khỏi thời gian chỉnh sửa nội bộ. | Khoảng 2 giờ là thời lượng cả buổi. Số này chưa cho biết thời gian nào có thể giảm nhờ cập nhật tại chỗ. |
| [Reflection của Hiếu](../individual/2A202603993_CaoTrungHieu.md) | 1 ghi chép về trao đổi trong lớp | Có phản hồi về phạm vi tự động hóa cần làm rõ. | Một số bạn chưa thấy rõ mức độ ảnh hưởng theo ghi nhận của Hiếu. Phản hồi này chưa xác nhận vấn đề ở nhóm thường xuyên demo cho khách. |

**Kế hoạch kiểm chứng tiếp.** Trao đổi với 2–3 người từng tham gia demo hoặc xem demo. Đối chiếu với lịch họp, ghi chú hoặc lịch sử bản sửa nếu có. Mỗi cuộc trao đổi tập trung vào một lần đã xảy ra.

- Lần gần nhất khách góp ý về giao diện, khách yêu cầu đổi phần nào? Nhóm đã làm gì ngay trong buổi đó?
- Ai thực hiện bản sửa, sửa trong bao lâu và khách xác nhận ở thời điểm nào?
- Nếu phải hẹn lại, buổi sau dùng để xem bản sửa nhỏ hay để bàn thêm yêu cầu hoặc thay đổi phạm vi?

**Điều chỉnh sau khi đối chiếu.** Thu hẹp từ “cập nhật MVP realtime” sang việc cho khách xem và xác nhận ngay các thay đổi giao diện nhỏ đã rõ yêu cầu. Ghi riêng những buổi hẹn lại do đổi phạm vi để xem trường hợp nào bản sửa nhanh vẫn chưa giải quyết được.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| --- | --- | --- | --- | --- | --- |
| Google Cloud Speech-to-Text | [Streaming recognition](https://docs.cloud.google.com/speech-to-text/docs/streaming-recognize) và [kết quả tạm thời, kết quả cuối](https://docs.cloud.google.com/speech-to-text/docs/v1/speech-to-text-requests#streaming_speech-to-text_api_recognition_requests) | Chuyển lời nói trong buổi pitching thành văn bản. | Trả kết quả trong lúc nhận âm thanh và phân biệt bản chép tạm với kết quả cuối. | Văn bản chưa cho biết câu nào là yêu cầu sửa. Kết quả tạm có thể thay đổi khi người nói nói tiếp. | Chỉ đưa đoạn nhận dạng cuối vào bước phân loại yêu cầu. Đo độ trễ từ lúc người nói kết thúc câu đến lúc giao diện đổi. |
| Figma Make | [Chỉnh sửa tệp Figma Make](https://help.figma.com/hc/en-us/articles/42009840449175-Edit-a-Figma-Make-file) và [FAQ](https://help.figma.com/hc/en-us/articles/31722591905559-Figma-Make-FAQs) | Dùng prompt hoặc công cụ chỉnh sửa để thay đổi bản xem trước. | Tài liệu mô tả cập nhật preview khi người dùng gửi prompt và có hỗ trợ nhập prompt bằng giọng nói. | Luồng được tài liệu mô tả bắt đầu từ một prompt hoặc thao tác chỉnh sửa có chủ đích. Nguồn chưa xác nhận khả năng tự phát hiện yêu cầu trong cuộc hội thoại rồi áp dụng ngay. | Dùng làm mốc so sánh với phương án có người nhập yêu cầu. Thử xem tự nhận yêu cầu có giảm thao tác mà vẫn giữ đúng ý khách hay không. |
| JSON Patch (RFC 6902) | [RFC 6902, mục 4–5](https://www.rfc-editor.org/rfc/rfc6902.html#section-4) | Áp thay đổi có cấu trúc lên trạng thái bản xem trước nếu giao diện biểu diễn được bằng JSON. | Cho phép sửa đúng trường và kiểm tra giá trị hiện tại trước khi áp dụng. | Chuẩn chỉ mô tả thao tác trên dữ liệu. Nhóm vẫn cần ánh xạ yêu cầu nói thành phần tử giao diện, kiểm tra phạm vi và lưu bản trước khi sửa. | Thử trên một màn hình, với thao tác đổi nhãn hoặc vị trí nút đã định sẵn. Giữ bản trước để có thể khôi phục nếu kết quả sai ý. |

#### Sơ đồ khoảng trống cần thử nghiệm

Sơ đồ nối các bước tham khảo thành luồng đề xuất cho **một màn hình MVP**. Các công cụ trong bảng là nguồn đối chiếu cho từng bước.

```mermaid
flowchart LR
    speech["Cuộc trao đổi khi pitching"]
    transcript["Chép lời realtime<br/>Tham khảo Google Cloud Speech-to-Text"]
    intent{"Có yêu cầu sửa rõ ràng<br/>và đúng phạm vi?"}
    listen["Tiếp tục nghe<br/>Giao diện giữ nguyên"]
    patch["Áp thay đổi có cấu trúc<br/>Tham khảo JSON Patch"]
    preview["Bản xem trước tự cập nhật"]
    comparison["Figma Make<br/>Mốc so sánh khi người dùng chủ động gửi prompt"]

    speech --> transcript --> intent
    intent -->|Chưa rõ hoặc chỉ trao đổi| listen
    intent -->|Có| patch --> preview
    comparison -.-> preview

    classDef source fill:#e6f1ff,stroke:#5c83be,color:#10254a
    classDef experiment fill:#d4e6ff,stroke:#1e55b5,color:#10254a
    class transcript,patch,comparison source
    class intent,preview experiment
```

**Điểm cần kiểm chứng.** Chuyển lời nói thành văn bản và áp thay đổi có cấu trúc là hai bước có tài liệu tham khảo. Phần cần thử là liệu hệ thống có nhận đúng **ý định sửa giao diện trong cuộc trao đổi tự nhiên** và áp dụng đủ nhanh để bản sửa xuất hiện ngay trong lúc pitching.

**Tình huống để bàn giao cho CP5–CP6**

- **Yêu cầu rõ:** Khách nói “Đưa nút Đặt lịch lên đầu màn hình”. Bản xem trước tự đổi đúng vị trí. Đo từ lúc khách nói xong đến lúc nút xuất hiện ở vị trí mới.
- **Trao đổi thông thường:** Khách hỏi “Nút Đặt lịch hiện nằm ở đâu?”. Giao diện giữ nguyên.
- **Yêu cầu mơ hồ:** Khách nói “Chỗ này nhìn chưa ổn”. Công cụ tiếp tục nghe cho đến khi xác định được phần tử và thay đổi cụ thể.

**Bàn giao kiểm thử.** [Bộ 20 tình huống cho bản thử](../assets/cp4-bo-tinh-huong-mvp.md) có trạng thái ban đầu, kết quả mong đợi và mẫu ghi thời gian. Số liệu kiểm thử sẽ được điền khi nhóm có bản chạy thực tế.

**Đối chiếu số liệu trước khi chốt baseline**

- [Problem Card #2 của Hiếu](../individual/2A202603993_CaoTrungHieu.md#problem-card-2) ghi khoảng **15–20 phút trao đổi lại và cập nhật mỗi vòng**, khoảng 2–3 vòng mỗi MVP. Tổng **30–60 phút** là ước tính cho phần trao đổi lại và cập nhật theo vòng, chưa tính thời gian thiết kế lại.
- [Slide Vấn đề](../assets/cp4-cac-vong-chinh-sua-mvp.html#slide-2) dùng ước tính khoảng **2 giờ cho toàn bộ một buổi pitching**, 2–3 buổi mỗi MVP, tức **4–6 giờ họp**. Con số **6–9 giờ** chỉ áp dụng nếu nhóm dành thêm khoảng **1 giờ chỉnh sửa nội bộ sau mỗi buổi**.
- Ở mục 3.2, ghi riêng tổng thời lượng buổi họp, số phút dành riêng cho việc làm rõ phản hồi, và số lần thực sự phải chỉnh sửa sau họp. Khi tính tổng, cộng thời lượng họp với thời gian chỉnh sửa nội bộ thực tế. Thời gian trao đổi đã nằm trong buổi họp cần được ghi riêng để tránh cộng hai lần.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

``` text
Khách góp ý trong buổi demo
→ Người phụ trách ghi lại và làm rõ thay đổi
→ Nhóm sửa nội bộ sau buổi họp
→ Gửi bản sửa hoặc hẹn buổi khác để trình bày
→ Khách xác nhận hoặc góp ý tiếp
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | --- | --- | --- | --- | --- |
| 1. Nhận góp ý | Khách, người trình bày | Màn hình MVP đang demo | Góp ý về giao diện | Trong buổi pitch. Slide ước tính khoảng 2 giờ cho cả buổi. | Chưa có số phút riêng cho góp ý. |
| 2. Ghi và làm rõ | Người trình bày, nhóm dự án | Góp ý và ghi chú | Yêu cầu chỉnh sửa đã hiểu | Card ước tính 15–20 phút cho phần trao đổi lại và cập nhật mỗi vòng. | Ước tính gộp, chưa tách riêng bước 2. |
| 3. Sửa nội bộ | Người chỉnh prototype | Yêu cầu đã hiểu, bản hiện tại | Bản xem trước đã sửa | Slide dùng giả định khoảng một giờ nếu có đợt sửa nội bộ sau buổi. | Cần đo riêng phần thực sự thao tác. |
| 4. Cho khách xem lại | Người trình bày | Bản xem trước đã sửa | Bản sửa được gửi hoặc trình bày lại | Có thể sang buổi khác. Chưa đo thời gian chờ. | Ghi lý do nếu phải đặt lịch lại. |
| 5. Xác nhận | Khách, người trình bày | Bản sửa | Xác nhận hoặc phản hồi mở vòng mới | Card ước tính 2–3 vòng cho mỗi MVP. | Chưa rõ bao nhiêu vòng chỉ để xem bản sửa nhỏ. |

**Điểm nghẽn.** Bước 3 và 4 nối tiếp nhau sau buổi pitch. Khách phải chờ đến khi nhóm có bản sửa để xác nhận, kể cả khi thay đổi chỉ là nhãn hoặc vị trí nút. Cần đo từ lúc yêu cầu được nêu đến lúc khách thấy bản sửa để tách thời gian thao tác khỏi thời gian chờ.

### 4.2. Quy trình tương lai

``` text
1. [Con người] Người trình bày bật chế độ thử và chọn màn hình Lịch tư vấn.
2. [AI] Chép lời, ghép các đoạn đã chốt và đợi hết lượt nói. Sau đó mới phân loại và trích thao tác, nút, giá trị mới.
3. [Rule] Kiểm tra yêu cầu rõ, đúng màn hình, đúng nút và thao tác được phép.
   ├─ Chưa rõ, ngoài phạm vi hoặc có lỗi → giữ nguyên; người trình bày làm rõ khi cần.
   └─ Hợp lệ → lưu bản trước, áp thay đổi lên bản xem trước và ghi kết quả.
4. [Con người] Đối chiếu bản sửa với ý khách và ghi nhận xác nhận.
   └─ Sai ý → khôi phục bản trước, tắt tự áp dụng và ghi yêu cầu để sửa tay.
```

**Phạm vi.** Chỉ sửa nhãn hoặc vị trí đầu/cuối của nút Đặt lịch trên bản xem trước. Rule xác minh giá trị hợp lệ trước khi áp. Công cụ không xuất bản, sửa tệp nguồn hoặc đổi màn hình khác. Người trình bày có thể tạm dừng luồng và quyết định yêu cầu nào cần xử lý tay.

Một đoạn nhận dạng đã chốt vẫn có thể chỉ là một phần của lượt nói. Cần đợi hết lượt trước khi áp thay đổi để xử lý trường hợp khách nói tiếp “khoan, giữ nguyên”. Kiểm tra điều này ở lượt B09. [Kết quả nhận dạng theo luồng](https://docs.cloud.google.com/speech-to-text/docs/v1/speech-to-text-requests#streaming_speech-to-text_api_recognition_requests)

### 4.3. Before / after

| Chỉ số | Trước | Sau (mục tiêu thử) | Cách đo / ghi chú |
| --- | --- | --- | --- |
| Số bước chính | 5 bước | 4 bước trên nhánh yêu cầu rõ | Đếm theo hai quy trình trên, gồm cả bước xác nhận. |
| Số bước có người thao tác | 5 bước | 2 bước chính trên nhánh hợp lệ | Bật chế độ thử một lần mỗi phiên và kiểm tra bản sửa. Nhánh làm rõ hoặc sửa tay được ghi riêng. |
| Thời gian từ lúc khách nêu yêu cầu đến lúc thấy bản sửa | Chưa đo riêng. Mốc 15–20 phút mỗi vòng là ước tính rộng hơn. | Bản sửa đúng xuất hiện trong tối đa 10 giây ở bản thử. | Cùng bấm giờ từ lúc kết thúc câu đến lúc bản xem trước hiện đúng. So với cách sửa tay trên cùng tình huống. |
| Số buổi hẹn lại chỉ để xem bản sửa | Chưa xác định. Card ghi 2–3 vòng cho toàn MVP. | Giảm ít nhất một buổi trên mỗi MVP có ít nhất một buổi hẹn lại vì yêu cầu trong phạm vi, nếu thử thực tế sau này. | Ghi lý do từng buổi. Phần mô phỏng chỉ đo tỷ lệ xác nhận trong phiên. |
| Rủi ro trong thao tác | Hiểu sai phản hồi và chỉ phát hiện ở buổi sau. | Có thể hiểu sai câu nói và cập nhật trước mặt khách. | Kiểm tra câu phủ định, câu rút lại yêu cầu và khả năng khôi phục. |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
| --- | --- |
| **Actor** | Người phụ trách trình bày MVP và tiếp nhận phản hồi từ khách. |
| **Quy trình** | Demo → khách góp ý → nhóm làm rõ và chỉnh sửa → cho khách xem lại → xác nhận. |
| **Bottleneck** | Khoảng chờ giữa góp ý và bản sửa khách có thể xem. Việc sửa thường diễn ra sau buổi pitch. |
| **Impact** | Có thể phải thêm vòng làm rõ hoặc buổi trình bày, khiến việc xác nhận phiên bản MVP kéo dài. |
| **Success Metric** | Card của Hiếu ước tính 2–3 vòng mỗi MVP. Mục tiêu ban đầu là còn một vòng cho phần giao diện đang xét. Đếm số vòng từ góp ý đến xác nhận và ghi thời gian từng vòng. |
| **Boundary** | Thử trên bản xem trước. Người trình bày xác nhận thay đổi với khách và xử lý yêu cầu chưa rõ hoặc vượt phạm vi. |

**Phản biện khi rà v0.** Mốc 2–3 vòng bao gồm cả việc làm rõ yêu cầu hoặc đổi phạm vi. Nếu dùng số này để kết luận công cụ giảm số vòng, sẽ dễ tính cả những buổi cần diễn ra vì lý do khác. V1 tách chỉ số số buổi hẹn lại do cần xem bản sửa khỏi thời gian và độ đúng của prototype.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Độ mơ hồ cao, độ phức tạp thao tác thấp trong phạm vi thử.** Một câu có nhắc tên nút có thể là yêu cầu, câu hỏi, lời nhắc lại hoặc phủ định. Khi ý định đã rõ, chỉ có hai thuộc tính được sửa trên một nút. Các bước còn lại có thể định trước.

### 6.2. So sánh 4 mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Vai trò trong bản thử |
| --- | --- | --- | --- | --- |
| **No AI** | Người trình bày xác nhận yêu cầu rồi đổi nhãn hoặc vị trí ngay trên bản xem trước. | Ít góp ý và có người chỉnh giao diện tại chỗ. | Người trình bày phải vừa nói vừa thao tác hoặc nhờ người khác. | Đối chứng và phương án quay về. |
| **Rule** | Dùng nút điều khiển hoặc lệnh theo mẫu như “đổi nhãn thành …”. | Người dùng chấp nhận lệnh cố định và mục cần sửa đã rõ. | Luật theo từ khóa có thể nhầm câu hỏi hoặc phủ định với yêu cầu. | Kiểm phạm vi và thực thi thao tác hợp lệ. |
| **Workflow** | Chép lời → nhận diện ý định → Rule kiểm thao tác → cập nhật bản xem trước → con người xác nhận. | Khách nói tự nhiên, còn hành động và giới hạn được định sẵn. | Có thể nghe hoặc hiểu sai. Cần đo độ đúng, độ trễ và thử khôi phục. | **Chọn để thử nội bộ.** |
| **Agent** | Tự chọn màn hình, công cụ và chuỗi thao tác để sửa giao diện. | Yêu cầu trải qua nhiều màn hình hoặc cần tự lập kế hoạch. | Khó giới hạn và kiểm tra thay đổi trong buổi demo. | Ngoài phạm vi bản thử. |

**Lý do chọn Workflow.** No AI có thể đủ nếu thao tác tay vừa nhanh vừa chính xác. Rule theo mẫu phù hợp khi người dùng chịu nói theo lệnh. Workflow cho phép thử xem việc hiểu lời nói tự nhiên có giảm thao tác mà vẫn giữ đúng ý khách hay không. Hai thao tác được phép có thể liệt kê trước nên chưa cần Agent.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
| --- | --- |
| **Prediction** | Từ bản chép đã chốt của cả lượt nói, phân loại thành yêu cầu rõ, cần làm rõ hoặc giữ nguyên. Với yêu cầu rõ, trích thành phần, thuộc tính và giá trị mới. |
| **Judgment** | Người trình bày kiểm tra bản sửa có đúng ý khách. Nếu câu thiếu thông tin, hỏi lại phần tử hoặc giá trị còn thiếu. |
| **Action** | Rule kiểm phạm vi, lưu trạng thái cũ và chỉ áp thay đổi hợp lệ lên bản xem trước. Người trình bày xác nhận hoặc khôi phục. |
| **Outcome** | Đo số buổi hẹn lại theo lý do, tỷ lệ xác nhận trong phiên, tỷ lệ sửa đúng, số lần sửa nhầm và độ trễ. |
| **Input** | Âm thanh nói thử, bản chép cuối, màn hình đang hoạt động, nhãn và vị trí hiện tại. Nhóm đã có 20 câu tổng hợp và trạng thái ban đầu của từng lượt. |
| **Feedback** | Người quan sát ghi kết quả mong đợi, kết quả thấy được và thời gian. Khi sai, ghi lỗi do bản chép, hiểu ý hay áp thay đổi, rồi chạy lại sau khi sửa. |

### 6.4. Hai câu hỏi của Google PAIR

- **Hỗ trợ hay giao hẳn việc?** Thiết kế bản thử theo hướng hỗ trợ. Công cụ thực hiện thay đổi đã giới hạn. Người trình bày và khách vẫn chốt ý nghĩa của phản hồi và quyết định bản sửa đã đạt chưa. Card của Hiếu mô tả nhu cầu cho khách thấy bản sửa sớm, còn mức tự động hóa người dùng chấp nhận vẫn cần kiểm chứng.
- **Sai kiểu nào tệ hơn?** Sửa nhầm dễ làm gián đoạn buổi pitch vì khách thấy màn hình đổi dù chưa yêu cầu. Bỏ sót có thể xử lý bằng xác nhận lại rồi sửa tay. Luồng giữ nguyên khi chưa chắc, lưu bản trước và cho người trình bày tắt tự áp dụng.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
| --- | --- |
| **Actor** | Người trình bày MVP đang demo màn hình Lịch tư vấn cho khách. |
| **Quy trình** | Khách góp ý → người trình bày ghi nhận → nhóm sửa nhãn hoặc vị trí nút → khách xem và xác nhận. Khi chưa sửa tại chỗ, hai bước cuối có thể dời sang sau buổi pitch. |
| **Bottleneck** | Phải đợi nhóm sửa và đưa bản xem trước cho khách, kể cả khi thay đổi nhỏ đã rõ. |
| **Impact** | Nếu buổi hẹn tiếp theo chỉ để xem bản sửa, việc chờ bản sửa làm tăng thời gian chốt giao diện và số buổi cả hai bên phải sắp xếp. |
| **Success Metric** | **Quy trình thực tế:** baseline là số buổi hẹn lại chỉ để xem bản sửa trong phạm vi, chưa có số đo riêng. Mốc tham chiếu 2–3 vòng/MVP tính cho toàn bộ MVP. Mục tiêu sau này là giảm ít nhất một buổi trên mỗi MVP có ít nhất một buổi hẹn lại vì yêu cầu trong phạm vi. **Bản thử:** ≥9/10 yêu cầu rõ sửa đúng, 0/10 trường hợp cần giữ nguyên bị sửa, mỗi lượt sửa đúng ≤10 giây. **Pitch mô phỏng:** so với sửa tay bằng tỷ lệ xác nhận trong phiên và thời gian đến lúc xác nhận. |
| **Boundary** | Chỉ đổi nhãn hoặc vị trí đầu/cuối của nút Đặt lịch trên bản xem trước. Câu hỏi, yêu cầu mơ hồ, phủ định, rút lại hoặc ngoài phạm vi giữ nguyên. Người trình bày xác nhận ý khách và xử lý phần vượt phạm vi. |
| **AI intervention point** | Sau khi có bản chép đã chốt của cả lượt nói và trước bước Rule kiểm phạm vi. AI nhận diện ý định và đề xuất giá trị sửa. |
| **Mức chọn** | Workflow. |
| **Rủi ro và người kiểm tra** | Sai bản chép hoặc sai ý định có thể gây sửa nhầm. Người trình bày kiểm bản sửa ngay trong phiên, có quyền dừng và khôi phục. Một thành viên quan sát ghi sai lệch trong lúc thử. |

**Thay đổi so với v0**

| Trường | v0 | v1 | Lý do đổi |
| --- | --- | --- | --- |
| Phạm vi | Giao diện MVP nói chung trên bản xem trước. | Một nút, hai thuộc tính và danh sách trường hợp giữ nguyên. | Đủ hẹp để đặt kết quả mong đợi cho từng câu và xác định sửa nhầm. |
| Chỉ số | Tổng số vòng chỉnh sửa MVP. | Tách buổi hẹn lại vì bản sửa nhỏ, tỷ lệ xác nhận trong phiên và các chỉ số của prototype. | Một vòng họp có thể bao gồm thay đổi phạm vi hoặc quyết định nghiệp vụ khác. |
| Trách nhiệm | Người trình bày xác nhận bản sửa. | AI trích yêu cầu, Rule kiểm và áp, người trình bày xác nhận hoặc khôi phục. | Xác định chỗ phát sinh lỗi và người xử lý khi sai. |

**Tiêu chí đánh giá đầu ra**

| # | Tiêu chí | Đạt khi | Không đạt khi |
| ---: | --- | --- | --- |
| 1 | Đúng yêu cầu rõ | Ít nhất 9/10 lượt nhóm A đổi đúng nút, đúng thuộc tính và giá trị. Thuộc tính còn lại giữ nguyên. | Dưới 9/10 lượt đúng, kể cả trường hợp bỏ sót hoặc sửa thêm thuộc tính. |
| 2 | Giữ nguyên đúng lúc | Cả 10 lượt nhóm B giữ nguyên trong 10 giây quan sát sau khi nói xong. Thay đổi thoáng qua trong lượt cũng tính là sửa nhầm. | Có bất kỳ thay đổi nào trong một lượt nhóm B. |
| 3 | Độ trễ | Mỗi lượt A sửa đúng xuất hiện và ổn định trong tối đa 10 giây tính từ lúc người nói kết thúc câu. | Có lượt đúng nhưng vượt 10 giây. |
| 4 | Khôi phục | Trong một lượt thử riêng có thay đổi sai, người trình bày khôi phục đúng nhãn và vị trí trước đó, rồi chuyển sang chỉ ghi nhận. | Không khôi phục đủ trạng thái hoặc chế độ vẫn tự áp dụng. |

Bộ thử và ngưỡng trên là kế hoạch chấm. Kết quả thực tế sẽ được ghi theo từng ID khi có bản chạy.

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Mức | Lý do và cách kiểm tra |
| --- | --- | --- |
| **Value** | Cao | Card mô tả có nhiều vòng chỉnh sửa, nhưng chưa biết bao nhiêu buổi hẹn lại chỉ để xem bản sửa nhỏ. Dựng lại một MVP đã làm và ghi lý do từng buổi. |
| **Usability** | Trung bình | Thao tác sai có thể làm gián đoạn buổi pitch. Thử việc nhận ra bản sửa, tắt tự áp dụng và khôi phục ngay trên bản xem trước. |
| **Feasibility** | Trung bình | Chép lời và cập nhật có tài liệu tham khảo. Độ đúng khi nhận diện ý định và độ trễ của cả luồng cần kiểm tra bằng lời nói. |
| **Viability** | Trung bình | Bản thử dùng lời thoại tổng hợp, giới hạn một màn hình và do nhóm vận hành. Trước khi dùng với khách, cần xác nhận quyền xử lý âm thanh, chi phí theo phiên và người phụ trách vận hành. |

### 8.2. Kết luận

**Quyết định.** **Go cho bản thử nội bộ**, theo phạm vi trong [TEAM.md](../../TEAM.md#thông-tin-nhóm). Một màn hình và hai thao tác đủ để kiểm tra giả thuyết mà nhóm có thể quay lại quy trình thủ công ngay khi sai.

**Bản thử nhỏ nhất.** Chạy bộ 20 tình huống bằng lời nói trên màn hình Lịch tư vấn và thử khôi phục một lần riêng. Đặt lại trạng thái theo từng tình huống, ghi thời gian và kết quả trong [mẫu kiểm thử](../assets/cp4-bo-tinh-huong-mvp.md#mẫu-ghi-kết-quả-và-ngưỡng-để-nhóm-xem-xét).

**Ngưỡng dừng.** Khi có lượt tự sửa sai, khôi phục bản trước, tắt tự áp dụng và ghi nguyên nhân trước khi thử lại. Nếu cả đợt có dưới 9/10 lượt A đúng, có sửa nhầm nhóm B, có lượt đúng vượt 10 giây hoặc không khôi phục được, quay về cách xác nhận và sửa tay.

**Điều kiện sang bước tiếp theo.** Khi đạt các ngưỡng, so sánh Workflow với cách xác nhận và sửa trực tiếp trong một buổi pitch mô phỏng. Dùng cùng yêu cầu và trạng thái ban đầu, đổi thứ tự hai cách giữa các lượt. Ghi thời gian từ lúc nói xong đến lúc hai bên xác nhận, số yêu cầu chưa xác nhận và số lần phải sửa tay. Chỉ cân nhắc thử với khách khi Workflow giữ được ít nhất tỷ lệ xác nhận của cách sửa tay, giảm thời gian xác nhận trên các lượt cả hai cách đều làm đúng, và có bằng chứng rằng các buổi hẹn lại trong phạm vi thực sự xảy ra.

---

## 9. Hạn chế và hướng tiếp theo

- Các mốc 15–20 phút, 2–3 vòng và 2 giờ là ước tính ở các cấp khác nhau. Việc tiếp theo là dựng lại lịch của một MVP đã làm và tách thời gian họp, thời gian sửa và thời gian chờ khách xem lại.
- Slide hiện tại minh họa một lời thoại và thay đổi đã định trước. Bộ 20 câu tổng hợp giúp thử luồng nhưng chưa đo được tiếng ồn, lời nói chồng nhau hoặc các cách diễn đạt ngoài bộ mẫu. Sau lượt thử đầu, bổ sung các cách diễn đạt mới và giữ chúng riêng để chấm lại. [Slide minh họa](../assets/cp4-cac-vong-chinh-sua-mvp.html#slide-5)

## 10. Tài liệu tham khảo

- Báo cáo cá nhân của [Đạt](../individual/2A202604027_LePhamThanhDat.md), [Hiếu](../individual/2A202603993_CaoTrungHieu.md), [Tùng](../individual/2A202603982_CaoThanhTung.md) và [Duy](../individual/2A202604071_TranDucDuy.md).
- Nhóm Delta. [Thông tin nhóm và phân công](../../TEAM.md), [slide minh họa quy trình MVP](../assets/cp4-cac-vong-chinh-sua-mvp.html) và [bộ 20 tình huống thử](../assets/cp4-bo-tinh-huong-mvp.md).
- [Google Cloud Speech-to-Text, nhận dạng luồng âm thanh](https://docs.cloud.google.com/speech-to-text/docs/streaming-recognize).
- [Figma Learn, chỉnh sửa tệp Figma Make](https://help.figma.com/hc/en-us/articles/42009840449175-Edit-a-Figma-Make-file).
- [IETF, RFC 6902 — JSON Patch](https://www.rfc-editor.org/rfc/rfc6902.html#section-4).
