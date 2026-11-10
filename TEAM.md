# Nhóm Delta

## Thông tin nhóm

- Tên nhóm: Delta
- Đề tài đã chọn: Cập nhật MVP realtime.
- Vấn đề nhóm chọn từ [Problem Card #2 của Hiếu](report/individual/2A202603993_CaoTrungHieu.md#problem-card-2): Khi khách góp ý trong buổi pitch, nhóm chưa thể cập nhật giao diện ngay, nên phải chỉnh sửa nội bộ rồi có thể phải hẹn thêm buổi để khách xem và xác nhận bản sửa.
- Quyết định cuối: **Go thử nội bộ một tháng** sau khi đạt kiểm tra kỹ thuật và đối chiếu với sửa tay trong buổi pitch mô phỏng. Phạm vi chỉ gồm đổi nhãn hoặc vị trí nút Đặt lịch trên màn hình Lịch tư vấn. [Điều kiện thử và ngưỡng dừng](report/team/group_report.md#82-kết-luận)
- Tiêu chí thử: Sửa đúng ít nhất **9/10** yêu cầu rõ, **0/10** lượt sửa nhầm ở nhóm cần giữ nguyên và tối đa **10 giây** cho mỗi lượt sửa đúng. Nếu sửa nhầm, khôi phục bản trước và chuyển sang chỉ ghi nhận yêu cầu. Chi tiết trong [bộ 20 tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md).

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Lê Phạm Thành Đạt | 2A202604027 | Nhóm trưởng, phụ trách research CP4 | `liliustwocout` |
| 2 | Cao Trung Hiếu | 2A202603993 | Đề xuất vấn đề nhóm chọn, phụ trách kiểm chứng CP4 | `HieuCaoTlu` |
| 3 | Cao Thanh Tùng | 2A202603982 | Phụ trách quy trình và bộ tiêu chí đánh giá | `TungCTT` |
| 4 | Trần Đức Duy | 2A202604071 | Phụ trách Problem Statement và rà soát rủi ro | `tran85122-afk` |

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Đạt | Hiếu, Tùng, Duy | Gom nhóm vấn đề, vẽ cây OST và ghi lý do chọn hoặc loại từng ứng viên. |
| CP4 — Kiểm chứng | Hiếu | Duy | Dựng lại một buổi pitch đã diễn ra. Ghi riêng thời gian họp, thời gian sửa nội bộ và lý do phải hẹn lại. |
| CP4 — Research | Đạt | — | [Đối chiếu ba giải pháp ở mục 3.3](report/team/group_report.md#33-research-giải-pháp-đã-có) và chuẩn bị [20 tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md). |
| CP5 — Quy trình trước/sau | Tùng | Đạt, Hiếu | Vẽ hai luồng, ghi bước AI, Rule và người trình bày, kèm cách khôi phục bản xem trước. |
| CP5 — Problem Statement v0 | Duy | Hiếu | Viết vấn đề dựa trên quy trình thực tế, kèm cách đo số buổi hẹn lại để xác nhận bản sửa. |
| CP6 — Mức can thiệp và Problem Statement v1 | Duy | Tùng, Đạt | So sánh bốn mức can thiệp, cập nhật Problem Statement và đối chiếu tiêu chí với bộ tình huống thử. |
| CP6 — Quyết định | Đạt | Hiếu, Tùng, Duy | Ghi bốn nhóm rủi ro, phạm vi thử nội bộ và ngưỡng dừng vào báo cáo nhóm. |

### Checklist điều phối của Đạt

- [x] **CP3.** Ghi vấn đề nhóm chọn là các vòng sửa giao diện MVP sau buổi pitch. [Kết quả chọn ứng viên](report/team/group_report.md#24-chấm-điểm-shortlist-15)
- [x] **CP4.** Đối chiếu ba giải pháp đã có và tách các mốc thời gian trao đổi, họp và chỉnh sửa. [Research CP4](report/team/group_report.md#33-research-giải-pháp-đã-có)
- [x] **Chuẩn bị bản thử.** Lập 20 tình huống, kết quả mong đợi và ngưỡng đánh giá. Ghi phạm vi Go cho thử nội bộ trong TEAM.md. [Bộ tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md)
- [x] **Phân công.** Xác nhận với Hiếu, Tùng và Duy phần việc và thời điểm bàn giao.
- [x] **CP3.** Cùng cả nhóm hoàn thiện bảng gom vấn đề, cây OST và bảng chấm điểm. Ghi lý do chọn hoặc loại ứng viên theo nội dung đã thống nhất. [Hội tụ nhóm](report/team/group_report.md#2-hội-tụ-nhóm-cp3)
- [x] **CP4.** Cùng Hiếu và Duy rà lại một buổi pitch đã diễn ra. Ghi riêng thời gian họp, thời gian sửa nội bộ và lý do hẹn lại để đối chiếu với các ước tính hiện có. [Kiểm chứng](report/team/group_report.md#32-kiểm-chứng)
- [x] **CP5.** Rà quy trình trước/sau với Tùng và Problem Statement v0 với Duy. Kiểm tra cách đo số buổi hẹn lại và cách khôi phục bản xem trước khi sửa sai. [Quy trình trước/sau](report/team/group_report.md#4-quy-trình-trướcsau-cp5)
- [x] **CP6.** Ghi thay đổi từ v0 sang v1, bốn nhóm rủi ro và quyết định Go cho thử nội bộ vào báo cáo nhóm. [Quyết định CP6](report/team/group_report.md#8-quyết-định-cp6)
- [x] **Rà soát với nhóm.** Xác nhận cách diễn đạt Problem Statement v1 và phạm vi thử với Duy cùng các thành viên trước khi chạy.
- [x] **Chốt quy trình chạy thử nội bộ.** Ghi từng lượt và đối chiếu với ngưỡng 9/10 yêu cầu rõ, 0/10 lượt sửa nhầm và tối đa 10 giây mỗi lượt sửa đúng. Nếu sửa nhầm, dừng tự cập nhật và khôi phục bản trước. [Bảng ghi kết quả](report/assets/cp4-bo-tinh-huong-mvp.md#bảng-ghi-kết-quả-và-ngưỡng-đánh-giá)

## Cá nhân

### LePhamThanhDat-2A202604027

**Phần việc phụ trách.** Nhóm trưởng, phụ trách tìm hiểu các giải pháp đã có ở CP4.

**Đóng góp cụ thể.** Ghi lại vấn đề nhóm chọn ở CP3. Ở CP4, đối chiếu Google Cloud Speech-to-Text, Figma Make và JSON Patch, phác thảo luồng từ lời góp ý đến bản xem trước và chuẩn bị 20 tình huống để thử ở CP5–CP6.

**Bằng chứng.** [Báo cáo nhóm, mục 3.3](report/team/group_report.md#33-research-giải-pháp-đã-có), [bộ tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md) và [báo cáo cá nhân](report/individual/2A202604027_LePhamThanhDat.md).

**Bài học từ phần làm nhóm**

- Cần ghi riêng thời gian trao đổi mỗi vòng, thời lượng cả buổi pitch và thời gian sửa nội bộ để biết khâu nào tốn thời gian. Mốc 6–9 giờ mỗi MVP là ước tính nếu mỗi buổi có thêm khoảng một giờ chỉnh sửa nội bộ.
- Khi đánh giá bản thử, cần kiểm tra cả lúc giao diện phải thay đổi lẫn lúc cần giữ nguyên. Bộ 20 tình huống gồm 10 yêu cầu rõ và 10 trường hợp như câu hỏi, lời nhận xét hoặc yêu cầu mơ hồ có thể khiến công cụ sửa nhầm.

### CaoTrungHieu-2A202603993

**Phần việc phụ trách.** Tôi đề xuất vấn đề từ trải nghiệm trình bày MVP và phụ trách kiểm chứng các tình huống khách góp ý trong buổi demo.

**Đóng góp cụ thể.** Ở CP3, tôi trình bày Problem Card #2 về việc khách phải chờ xem bản sửa sau buổi pitch. Khi nhóm hỏi về các yêu cầu phức tạp, tôi tách thay đổi nhỏ có thể xử lý trên bản xem trước khỏi thay đổi nghiệp vụ cần người phụ trách duyệt. Ở CP4, tôi cùng Duy đối chiếu các lý do hẹn lại và trường hợp người trình bày có thể sửa tay ngay. Với CP5–CP6, tôi đề xuất thử trên một màn hình và theo dõi số vòng chỉnh sửa cùng thời gian triển khai MVP.

**Bằng chứng.** [Problem Card #2](report/individual/2A202603993_CaoTrungHieu.md#problem-card-2), [khảo sát CP4](report/team/group_report.md#321-khảo-sát-nhanh) và [quyết định thử nội bộ](report/team/group_report.md#82-kết-luận).

**Bài học từ phần làm nhóm**

- Cần xem khách đang chờ điều gì trước khi quyết định tự động hóa. Khi người trình bày có thể sửa tay ngay, tốc độ của công cụ chỉ có giá trị nếu khách xác nhận bản sửa nhanh hơn mà độ đúng vẫn được giữ.

### CaoThanhTung-2A202603982

**Phần việc phụ trách.** Tôi phụ trách dựng quy trình trước/sau và thống nhất cách bấm giờ cho bài thử.

**Đóng góp cụ thể.** Ở CP3, tôi hỏi khoảng chờ dài nhất nằm trước lúc designer nhận việc hay sau khi bản sửa đã có. Ở CP5, tôi dựng bảng bàn giao để tách thời gian thao tác, chờ designer và chờ người xem mở bản sửa. Với CP6, tôi đề xuất dùng cùng trạng thái ban đầu và cùng lời góp ý khi so sánh Workflow với sửa tay. Tôi cũng đưa lượt khôi phục vào kế hoạch kiểm thử.

**Bằng chứng.** [Báo cáo cá nhân](report/individual/2A202603982_CaoThanhTung.md), [biên bản phản biện](report/team/group_report.md#25-biên-bản-pitch-và-phản-biện-cp3) và [bảng bấm giờ trước/sau](report/team/group_report.md#44-bấm-giờ-bàn-giao-và-so-sánh-trướcsau).

**Bài học từ phần làm nhóm**

- Một thao tác sửa có thể rất ngắn trong khi khách vẫn phải chờ lâu. Tôi sẽ đo cả lúc bản sửa xuất hiện lẫn lúc khách xác nhận để biết đoạn nào còn chậm.

### TranDucDuy-2A202604071

**Phần việc phụ trách.** Tôi rà Problem Statement và rủi ro khi bản xem trước thay đổi sai ý khách.

**Đóng góp cụ thể.** Ở CP3, tôi hỏi về lần góp ý liên quan đến logic nghiệp vụ mà nhóm phải hẹn lại để chốt. Ở CP4, tôi chuẩn bị câu hỏi cho vai người phụ trách sản phẩm phía khách và dùng ca S2 để phân biệt buổi hẹn chốt nghiệp vụ với buổi hẹn chỉ để xem giao diện. Ở CP5, tôi đề xuất tách chỉ số xác nhận khỏi thời gian xuất hiện bản sửa và xác định người trình bày là người chốt ý khách. Ở CP6, tôi rà điều kiện dừng ngay khi tự sửa sai và quyền khôi phục của người trình bày.

**Bằng chứng.** [Báo cáo cá nhân](report/individual/2A202604071_TranDucDuy.md), [tình huống S2](report/team/group_report.md#322-tình-huống-đối-chiếu), [phản biện Problem Statement v0](report/team/group_report.md#5-problem-statement-v0-cp5) và [điều kiện dừng](report/team/group_report.md#82-kết-luận).

**Bài học từ phần làm nhóm**

- Giảm số lần hẹn lại chỉ có ý nghĩa với những buổi hẹn để xác nhận bản sửa nhỏ. Nếu buổi hẹn dùng để chốt nghiệp vụ, nhóm vẫn cần người có thẩm quyền tham gia.
