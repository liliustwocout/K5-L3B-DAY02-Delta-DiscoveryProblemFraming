# Báo cáo cá nhân — 2A202604071_TranDucDuy


## 1. Thông tin học viên

- Họ tên: Trần Đức Duy
- MSSV: 2A202604071
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Delta
- Link repo nhóm: https://github.com/liliustwocout/K5-L3B-DAY02-Delta-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại|Khi có điểm bài kiểm tra, giáo viên muốn chuyển điểm sổ lên hệ thống của trường (vnEdu/SMAS…), để kịp hạn mà không nhập nhầm | GV, HS |4 lớp × 40 HS × 6 cột điểm/kỳ (4 ĐGTX + giữa kỳ + cuối kỳ, môn > 70 tiết/năm [1]) = 960 đầu điểm/kỳ, 160 điểm/đợt nhập; ước lượng 5 lần nhập sai/kỳ |
| 2 |Cần đọc, tổng hợp nhiều thông tin |Khi cuối học kỳ phải viết nhận xét cho từng học sinh, giáo viên muốn nắm nhanh điểm số, bài làm và thái độ cả kỳ của từng em, để viết nhận xét đúng với từng em chứ không dùng câu chung chung |GV, học sinh, phụ huynh |160 HS × 2 kỳ = 320 nhận xét/năm [1]; ước lượng 3 buổi tối/kỳ |
| 3 |Tốn thời gian |Khi ra đề kiểm tra giữa kỳ, giáo viên muốn có đề đúng ma trận và bản đặc tả mà tổ chuyên môn yêu cầu, để không bị trả về sửa |GV, tổ trưởng |Đề định kỳ phải có ma trận và bản đặc tả [4]; 2 đề định kỳ/kỳ [1]; ước lượng 4 giờ/đề, bị trả về 1 lần/kỳ|
| 4 |Tốn thời gian |Khi chấm bài tự luận của nhiều lớp, giáo viên muốn chấm xong trong tuần, để trả bài khi học sinh vẫn còn nhớ nội dung |GV, học sinh | 160 bài/đợt × ước lượng 4 phút/bài = 640 phút/đợt; 3–4 đợt chấm giấy/kỳ (2 bài định kỳ [1] + 1–2 bài ĐGTX trên giấy, ước lượng)|
| 5 |Lặp lại |Khi soạn kế hoạch bài dạy theo mẫu của Bộ/trường, giáo viên muốn điền đúng các mục bắt buộc, để kịp nộp duyệt đầu tuần |GV, tổ trưởng |Mẫu KHBD theo Phụ lục IV [3]; 2 bài/tuần (4 lớp cùng khối), ước lượng 50 phút/bài |
| 6 |Pain từ người khác |Khi tổ chuyên môn hoặc ban giám hiệu cần báo cáo tình hình lớp, giáo viên muốn có sẵn số liệu sĩ số, vắng, điểm, để nộp đúng hạn |GV, BGH | 1 lần/tháng, thêm sơ kết giữa kỳ và cuối kỳ|
| 7 | Pain từ người khác | Khi phụ huynh nhắn Zalo hỏi về kết quả học tập của con, giáo viên muốn trả lời đúng tình hình của từng em, để phụ huynh nắm được và phối hợp kèm con ở nhà | GV, phụ huynh, học sinh | Theo GV: trao đổi với phụ huynh qua Zalo về kết quả học tập nhiều; số tin/tuần: chưa đếm |



**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tôi chọn bối cảnh công việc của một GV cấp 2 rồi nhờ AI (Claude) gợi ý problem theo 4 lăng kính. AI gợi ý 3 ý.
- Giữ lại 2 ý (dòng 5–6) vì đều là việc GV làm thường xuyên và có quy trình rõ.
- Ban đầu bỏ ý "phụ huynh nhắn Zalo hỏi về kết quả học tập" vì nghĩ GV ít dùng Zalo với phụ huynh. Sau khi hỏi GV thì biết thực tế GV trao đổi với phụ huynh qua Zalo về kết quả học tập nhiều, nên thêm lại (dòng 7).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Viết nhận xét cuối kỳ cho từng học sinh (CP1 #2) | Lặp lại 2 lần/năm; tốn 3 buổi tối cho 160 HS; bước khó là tổng hợp nhiều nguồn về từng em nên so sánh được Rule / Workflow / Agent | Thông tin "thái độ, bài làm cả kỳ" có được ghi lại ở đâu không, hay chỉ nằm trong trí nhớ GV? Trường có cho đưa dữ liệu học sinh vào công cụ AI không? |
| 2 | Chấm bài tự luận nhiều lớp (CP1 #4) | Tốn thời gian nhất: 160 bài × 4 phút ≈ 10,7 giờ/đợt; ảnh hưởng trực tiếp tới học sinh (trả bài chậm) | Bài viết tay nên khó số hóa; chấm điểm cần công bằng, có thể không phù hợp để AI tham gia |
| 3 | Nhập điểm từ sổ lên hệ thống của trường (CP1 #1) | Khối lượng lớn: 960 đầu điểm/kỳ [1], ước lượng 5 lần nhập sai/kỳ; quy trình ngắn, dễ vẽ; dễ so sánh với phương án No AI / Rule | Có thể hệ thống đã có chức năng nhập từ Excel nên chỉ cần đổi quy trình, không cần AI |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cuối học kỳ phải viết nhận xét cho từng học sinh, giáo viên muốn nắm nhanh điểm số, bài làm và thái độ cả kỳ của từng em, để viết nhận xét đúng với từng em chứ không dùng câu chung chung |
| Actor | GV bộ môn Ngữ văn hoặc Toán THCS (4 tiết/tuần/lớp), dạy 4 lớp cùng khối: 16 tiết/tuần + kiêm nhiệm, trong định mức 19 tiết/tuần [5]; 4 × 40 = 160 HS (sĩ số ≤ 45 HS/lớp [2]). Người nhận: học sinh, phụ huynh |
| Thời điểm / bối cảnh | Cuối mỗi học kỳ (2 lần/năm) [1], trước hạn khóa sổ của trường, thường làm buổi tối; 320 nhận xét/năm |
| Quy trình hiện tại (3–7 bước) | 1. Mở sổ điểm xem điểm cả kỳ của học sinh.  2. Nhớ lại / xem ghi chú về bài làm, thái độ  3. Viết nhận xét  4. Nhập vào hệ thống  5. Rà lại cả lớp, sửa các câu bị trùng nhiều lần.|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: nhớ lại / xem ghi chú từng em và viết nhận xét riêng cho em đó|
| Impact (nếu không giải thì sao) | 3 buổi tối mỗi kỳ; về cuối, nhận xét dễ thành câu chung chung, phụ huynh không biết con cần cải thiện gì |
| Success metric (baseline → target) | Thời gian: từ 3 buổi tối (9 giờ = 540 phút ≈ 3,4 phút/HS, ước lượng) xuống 1 buổi tối (3 giờ = 180 phút ≈ 1,1 phút/HS). Chất lượng: tỉ lệ nhận xét có ít nhất 1 chi tiết riêng của em đó |
| Phương án không dùng AI | Ghi chú ngắn về từng em ngay trong kỳ (1 dòng/tuần); dùng bộ câu mẫu theo mức điểm, rồi thêm 1 chi tiết riêng |
| Giả thuyết về AI (nếu có) | AI đọc điểm + ghi chú của GV và gợi ý bản nháp nhận xét; GV sửa và duyệt từng câu. AI không tự gửi, không tự đánh giá thái độ. Boundary: HS 11–15 tuổi là trẻ em, dữ liệu cá nhân của trẻ em cần bảo vệ riêng [6]; không đưa tên thật, mã định danh HS lên công cụ AI công cộng nếu chưa ẩn danh |
| Cảm nhận nhanh | Workflow |


```text
HIỆN TẠI — 3 buổi tối = 9 giờ (540') / kỳ / 160 HS ≈ 3,4'/HS

[Xem điểm cả kỳ] → [Nhớ lại bài làm, thái độ] ← BOTTLENECK
→ [Viết nhận xét] ← BOTTLENECK → [Nhập hệ thống] → [Rà cả lớp]

(Chưa bấm giờ từng bước; bước 2–3 là giả định về bottleneck, chưa kiểm chứng. Đo bổ sung ở CP4.)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chấm bài tự luận của nhiều lớp, giáo viên muốn chấm xong trong tuần, để trả bài khi học sinh vẫn còn nhớ nội dung |
| Actor | GV bộ môn Ngữ văn hoặc Toán THCS dạy 4 lớp cùng khối (160 HS). Người nhận: học sinh |
| Thời điểm / bối cảnh | 3–4 đợt chấm giấy/kỳ: 2 bài kiểm tra định kỳ (giữa kỳ, cuối kỳ) [1] + 1–2 bài ĐGTX trên giấy (ước lượng); chấm bài giấy ở nhà |
| Quy trình hiện tại (3–7 bước) | 1. Nhận bài, xếp theo lớp. 2. Đọc bài, đối chiếu barem, cho điểm. 3. Ghi lời phê. 4. Cộng điểm, ghi vào sổ. 5. Trả bài, chữa bài trên lớp *(nháp, cần kiểm lại với GV)* |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2: đọc và cho điểm từng bài, nằm trong khoảng 4 phút/bài (chưa tách thời gian từng bước) |
| Impact (nếu không giải thì sao) | 640 phút ≈ 10,7 giờ/đợt; trả bài chậm thì học sinh quên nội dung, chữa bài kém hiệu quả |
| Success metric (baseline → target) | Thời gian từ lúc thu bài đến lúc trả bài: chưa đo, mục tiêu ≤ 7 ngày (theo Job Story "chấm xong trong tuần"); thời gian chấm: khoảng 4 phút/bài (640'/đợt), mục tiêu đặt sau khi đo baseline |
| Phương án không dùng AI | Barem chi tiết hơn; chấm theo câu (chấm câu 1 cho cả xấp, rồi mới sang câu 2); lời phê dùng ký hiệu thống nhất |
| Giả thuyết về AI (nếu có) | Chưa rõ: bài viết tay khó số hóa, và việc chấm điểm cần GV quyết định. Có thể AI chỉ hỗ trợ tổng hợp lỗi sai phổ biến để chuẩn bị chữa bài |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 160 bài × 4' ≈ 640' (10,7 giờ) / đợt

[Xếp bài] → [Đọc + cho điểm] ← BOTTLENECK
→ [Ghi lời phê] → [Cộng điểm, vào sổ] → [Trả + chữa bài]

(4'/bài là tổng cả bước 2–4, chưa tách từng bước.)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi có điểm bài kiểm tra, giáo viên muốn chuyển điểm từ sổ lên hệ thống của trường (vnEdu/SMAS…), để kịp hạn mà không nhập nhầm |
| Actor | GV bộ môn Ngữ văn hoặc Toán THCS dạy 4 lớp cùng khối (160 HS). Bị ảnh hưởng: học sinh, phụ huynh xem điểm trên hệ thống |
| Thời điểm / bối cảnh | Sau mỗi đợt kiểm tra, trước hạn nhập điểm của trường; 6 cột điểm/HS/kỳ (4 ĐGTX + giữa kỳ + cuối kỳ) [1] = 960 đầu điểm/kỳ |
| Quy trình hiện tại (3–7 bước) | 1. Điểm nằm trong sổ chấm / trên bài. 2. Mở hệ thống, chọn lớp và cột điểm. 3. Gõ tay từng em. 4. Rà lại. 5. Lưu / khóa điểm *(nháp, cần kiểm lại với GV)* |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: gõ tay 160 điểm/đợt (chưa bấm giờ); đây là bước dễ gây lỗi nhập sai |
| Impact (nếu không giải thì sao) | Ước lượng 5 lần nhập sai/kỳ, phải sửa lại và phụ huynh thấy điểm sai |
| Success metric (baseline → target) | Số lần nhập sai: từ 5/kỳ (ước lượng) xuống 0/kỳ; thời gian nhập: chưa đo (mục tiêu chính là hết sai, không phải nhanh hơn) |
| Phương án không dùng AI | Nhập điểm vào Excel theo mẫu rồi import lên hệ thống (cần kiểm tra hệ thống của trường có hỗ trợ không); hoặc in danh sách đã nhập ra để đối chiếu với sổ |
| Giả thuyết về AI (nếu có) | Có lẽ không cần. Chỉ cân nhắc nếu phải đọc điểm từ ảnh chụp sổ viết tay |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 4 lớp × 40 HS = 160 điểm / đợt, 960 đầu điểm / kỳ (chưa bấm giờ)

[Mở hệ thống, chọn lớp] → [Gõ tay từng em] ← BOTTLENECK (ước lượng 5 lỗi/kỳ)
→ [Rà lại] → [Lưu / khóa]
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Bước khó là tổng hợp nhiều thông tin về từng em, có thể so sánh rõ giữa không dùng AI (ghi chú + câu mẫu) và Workflow (AI gợi ý nháp, GV duyệt); metric đo được; boundary rõ (AI không tự đánh giá học sinh)
- Câu hỏi muốn nhóm phản biện: Nếu GV không ghi chú gì trong kỳ thì AI lấy dữ liệu từ đâu, và khi đó phương án không dùng AI (ghi chú hằng tuần) có phải đã giải quyết gần hết vấn đề rồi không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: "thái độ cả kỳ" có thể không được ghi lại ở đâu cả, nên bottleneck thật có thể là thiếu dữ liệu chứ không phải viết chậm |Một phần: GV có ghi chú nhưng không đều |Thêm vào "Điều còn chưa chắc"; sẽ hỏi GV ghi chú ở đâu, bao lâu một lần |
| Card #1: mới hỏi 1 GV. Chưa biết GV khác có mất 3 buổi tối như vậy không | Có | Số "3 buổi tối" hiện là ước lượng, chưa có nguồn và chưa hỏi GV nào; ghi rõ "ước lượng" trong card, sẽ hỏi 2–3 GV THCS ở CP4 |
| Card #1: đưa điểm và nhận xét học sinh vào công cụ AI bên ngoài có thể vi phạm quy định bảo mật dữ liệu của trường |Có |Sẽ kiểm lại quy định Bộ cũng như Trường |
| Card #3: hệ thống có thể đã hỗ trợ import Excel, nếu vậy thì đổi quy trình là đủ (No AI) |Có |Đổi "Cảm nhận nhanh" thành No AI nếu kiểm tra thấy có import |
| Card #2: 4 phút/bài là số ước lượng hay đã bấm giờ? Cần tách ra thời gian từng bước | Có | Lần tới sẽ đo và tính trung bình trên từng bài |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Không thuyết trình | - |
| Phản biện bài của bạn khác |  Hỏi nhóm Malto khi họ thuyết trình: "Nếu biết con vật nào là nguyên nhân nhưng không biết chủ của nó thì sao?" |  Nhóm bạn trả lời: sẽ trang bị cho thú cưng trong khu dân cư vòng cổ có chip hoặc ghi thông tin chủ. |
| Nhận phản biện | Câu hỏi tôi nhận được: Nhóm Delta nhận câu hỏi từ nhóm Malto : "Nếu khách hàng yêu cầu sửa chức năng phức tạp mà Agent không làm nhanh được để khách xem luôn thì sao?" Hiếu trả lời: Agent chỉ sửa MVP để khách xem nhanh. | Giúp làm rõ giới hạn phạm vi xử lý của giải pháp trong bài nhóm |
| Quy trình nhóm | Đưa ra một số phản biện | Giúp làm tránh một số rủi ro với dữ liệu dự án có thể xảy ra |


---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sau khi tự scan 4 ý (dòng 1–4), dùng Claude để gợi ý thêm, | Gợi ý phần chưa nghĩ tới | Số liệu trong các gợi ý chỉ là ví dụ minh họa, không dùng được trực tiếp | Ban đầu bỏ ý "phụ huynh hỏi qua Zalo", sau khi hỏi GV thì thêm lại (dòng 7) vì thực tế GV trao đổi với phụ huynh qua Zalo về kết quả học tập nhiều. Với cột "Dấu hiệu thật": bỏ số minh họa của AI, đối chiếu với văn bản của Bộ GD&ĐT [1]–[5]; số thời gian và số lỗi (5 lần nhập sai, 3 buổi tối, 4 giờ/đề, 4 phút/bài, 50 phút/bài) là ước lượng, **chưa có nguồn kiểm chứng và chưa phỏng vấn GV** |
| CP2 Problem Card | Dùng Claude để soạn nháp bảng top 3, đồng thời phản biện card | Gợi ý cách xếp hạng theo tiêu chí của worksheet; chỉ ra điểm yếu (thiếu dữ liệu về thái độ HS, mới hỏi 1 GV, rủi ro bảo mật dữ liệu HS, khả năng chỉ cần import Excel) | Bản nháp đầu có quy trình từng bước chưa kiểm chứng và một mục tiêu chất lượng "≥ 90%" không có baseline | Bỏ mục tiêu chất lượng không có baseline; các số chưa có ghi rõ "chưa đo". Bổ sung actor và số liệu khung theo văn bản của Bộ GD&ĐT [1]–[5] và boundary bảo vệ dữ liệu trẻ em [6]; số thời gian, số lỗi ghi rõ "ước lượng"; quy trình từng bước của cả 3 card **chưa kiểm chứng với GV thật** |
| CP4 Research | Nhờ AI gợi ý các lỗ hổng bảo mật có thể xảy ra | Giúp chỉ ra một số lỗ hổng ít bị để ý | Chưa đưa ra rõ phương án giải quyết hoàn toàn | Lỗ hổng có thể bỏ qua nên chỉ lưu ý và tìm cách cải thiện sau |
| CP5 Quy trình | Giải thích rõ hơn quy trình của nhóm | Giải thích rất chi tiết| Không có | Tôi dùng để hiểu rõ quy trình hơn, không sửa gì |
| CP5–6 Problem Statement | Không dùng AI | Không dùng AI | Không dùng AI | Không dùng AI |
| CP6 Mức can thiệp / quyết định | Nhờ AI hỗ trợ câu hỏi phản biện |Từ ý tưởng của tôi đưa ra được câu hỏi phản biện mạch lạc| Tôi hỏi câu trả lời thì chưa trả lời chính xác | Phản biện cùng nhóm |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Khi lắng nghe các bạn trình bày, tôi mở rộng được góc nhìn sang nhiều lĩnh vực khác nhau ngoài bối cảnh giáo dục mà mình đã chọn. Tôi học được cách các nhóm khác quan sát công việc thực tế, định lượng nỗi đau bằng con số cụ thể và bóc tách quy trình để tìm đúng điểm nghẽn, từ đó nhìn lại và cải thiện cách đặt vấn đề của bản thân.
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
- Nhóm tôi có rơi vào bẫy "solution-first" ở giai đoạn đầu khi muốn áp dụng ngay một AI Agent tự động sửa toàn bộ giao diện sản phẩm cho khách hàng. Khi bị đặt câu hỏi phản biện và trao đổi lại cùng AI, cả nhóm mới nhận ra mình chưa làm rõ điểm nghẽn thực sự nằm ở đâu. Chúng tôi đã dừng lại để vẽ chi tiết từng bước của quy trình hiện tại, xác định bước tốn thời gian nhất là khâu họp chốt thay đổi kéo dài 2 tiếng mỗi ngày, rồi mới điều chỉnh giải pháp về mức vừa đủ.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
- Có, tôi đã thay đổi hẳn suy nghĩ sau phần phản biện. Ban đầu ở bài toán nhập điểm lên hệ thống trường (Card #3), tôi định dùng AI để đọc và tổng hợp điểm tự động. Tuy nhiên, sau khi nhận phản biện, tôi nhận ra nhiều việc không nhất thiết phải lạm dụng AI: nếu giáo viên nhập điểm vào file Excel theo mẫu rồi import thẳng lên hệ thống (hoặc dùng quy tắc kiểm tra cơ bản) thì đã giải quyết triệt để lỗi nhập sai mà tốn ít chi phí, an toàn hơn rất nhiều.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
- Tôi không quá bất ngờ về mặt quy trình chung vì đã tìm hiểu trước các văn bản quy định của ngành, nhưng có một chi tiết thực tế làm tôi chú ý khi hỏi chuyện giáo viên: ban đầu tôi định bỏ qua việc phụ huynh nhắn tin hỏi thăm vì nghĩ giáo viên ít trao đổi riêng, nhưng thực tế giáo viên lại nhận và trả lời tin nhắn Zalo về kết quả học tập của học sinh rất thường xuyên.
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
- Điều khó nhất đối với tôi là thực hiện kỹ thuật 5 Whys để đào sâu tìm ra nguyên nhân gốc rễ. Nếu không hỏi đủ sâu, người viết rất dễ dừng lại ở bề nổi của triệu chứng hoặc đổ lỗi cho yếu tố con người làm chậm, dẫn đến việc xác định sai điểm nghẽn và chọn lệch mức độ can thiệp của công nghệ.
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
- Nếu làm lại từ đầu, tôi sẽ thay đổi tư duy sử dụng AI: chỉ dùng AI như công cụ gợi ý và phản biện chứ tuyệt đối không lạm dụng hay lấy số liệu giả định của AI làm dữ liệu thật, đồng thời dành thời gian bấm giờ, khảo sát người dùng thực tế sớm hơn. Khi làm việc nhóm, tôi sẽ phản biện quyết liệt hơn ở khâu kiểm chứng các con số baseline và đặt câu hỏi kỹ hơn về rủi ro bảo mật dữ liệu dự án cũng như giới hạn kỹ thuật khi khách hàng yêu cầu thay đổi các chức năng phức tạp ngay trong cuộc họp. 
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
- Problem: Đội làm sản phẩm khi làm việc và trình bày bản nháp với khách hàng  phải mất tới 2–3 vòng chỉnh sửa cho mỗi MVP và tốn trung bình 2 tiếng chỉ để họp bàn đi bàn lại.
- Quy trình: Khách hàng đưa đề xuất -> Họp chốt thay đổi -> Thiết kế lại giao diện/luồng -> Trình bày lại vào một ngày khác.
- Bottleneck: Một bước cụ thể làm chậm cả quy trình -> Bước họp chốt thay đổi có thể lặp lại, 2 tiếng mỗi ngày kéo dài thời gian sang dự án mới.
- Metric: Giảm số vòng lặp từ 2–3 vòng/MVP  xuống còn 1 vòng/MVP, đo lường qua số lần phải hẹn họp lại và tỷ lệ khách hàng chốt mua MVP thành công.
- Boundary: Đối với các chức năng lớn, AI không được tự ý thiết kế lại màn hình mà chỉ trích xuất yêu cầu từ nội dung cuộc họp, nhân sự phụ trách bắt buộc phải kiểm tra và duyệt mọi thay đổi trước khi xuất bản cho khách xem.
- Mức can thiệp: Workflow -> AI tham gia vào luồng để lắng nghe cuộc họp và đồng thời tinh chỉnh MVP trực tiếp theo mức độ thay đổi
- Quyết định: Go -> Triển khai thử nghiệm ngay cho quy trình pitching sản phẩm nội bộ trong công ty; nếu sau 1 tháng mà tổng thời gian triển khai sản phẩm không giảm đạt mức 30–40% thì sẽ dừng dự án.
---

## 7. Tài liệu tham khảo

1. **Bộ Giáo dục và Đào tạo (2021).** *Thông tư số 22/2021/TT-BGDĐT ngày 20/7/2021 quy định về đánh giá học sinh trung học cơ sở và trung học phổ thông.* (Căn cứ quy định về viết nhận xét sự tiến bộ, thái độ học tập cuối mỗi học kỳ tại Điều 6, Điều 8 và số cột điểm đánh giá thường xuyên, định kỳ tại Điều 7).
2. **Bộ Giáo dục và Đào tạo (2020).** *Thông tư số 32/2020/TT-BGDĐT ngày 15/9/2020 ban hành Điều lệ trường trung học cơ sở, trường trung học phổ thông và trường phổ thông có nhiều cấp học.* (Căn cứ quy định sĩ số lớp cấp THCS không quá 45 học sinh/lớp tại Điều 16 và hồ sơ quản lý hoạt động giáo dục điện tử tại Điều 21).
3. **Bộ Giáo dục và Đào tạo (2020).** *Công văn số 5512/BGDĐT-GDTrH ngày 18/12/2020 về việc xây dựng và tổ chức thực hiện kế hoạch giáo dục của nhà trường.* (Căn cứ quy định khung Kế hoạch bài dạy tại Phụ lục IV).
4. **Bộ Giáo dục và Đào tạo (2024).** *Công văn số 7991/BGDĐT-GDTrH ngày 17/12/2024 về việc thực hiện kiểm tra, đánh giá đối với cấp THCS, THPT.* (Cập nhật hướng dẫn xây dựng ma trận và bản đặc tả đề kiểm tra định kỳ theo chương trình GDPT 2018).
5. **Bộ Giáo dục và Đào tạo (2009, 2017).** *Thông tư số 28/2009/TT-BGDĐT (sửa đổi, bổ sung bởi Thông tư số 15/2017/TT-BGDĐT) quy định về chế độ làm việc đối với giáo viên phổ thông.* (Căn cứ định mức tiết dạy 19 tiết/tuần đối với giáo viên THCS).
6. **Chính phủ (2023).** *Nghị định số 13/2023/NĐ-CP ngày 17/4/2023 về bảo vệ dữ liệu cá nhân.* (Căn cứ pháp lý về boundary bảo mật dữ liệu cá nhân và dữ liệu trẻ em từ 11–15 tuổi ở cấp THCS tại Điều 19, Điều 20 khi đưa dữ liệu điểm số/nhận xét lên công cụ AI bên thứ ba).
7. **Trao đổi trực tiếp với 1 GV THCS (tháng 11/2026):** xác nhận GV trao đổi với phụ huynh qua Zalo về kết quả học tập (CP1 dòng 7). Chưa phỏng vấn về thời gian chấm bài, viết nhận xét, nhập điểm.
