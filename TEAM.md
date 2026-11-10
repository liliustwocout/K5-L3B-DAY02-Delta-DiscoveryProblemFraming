# Nhóm Delta

## Thông tin nhóm

- Tên nhóm: Delta
- Đề tài đã chọn: Cập nhật MVP realtime.
- Vấn đề nhóm chọn từ [Problem Card #2 của Hiếu](report/individual/2A202603993_CaoTrungHieu.md#problem-card-2): Khi khách góp ý trong buổi pitch, nhóm chưa thể cập nhật giao diện ngay, nên phải chỉnh sửa nội bộ rồi có thể phải hẹn thêm buổi để khách xem và xác nhận bản sửa.
- Quyết định cuối: **Go** cho bản thử nội bộ trên màn hình Lịch tư vấn, giới hạn ở đổi nhãn và vị trí nút Đặt lịch. Cân nhắc thử với khách sau khi đối chiếu với cách sửa trực tiếp trong một buổi pitch mô phỏng.
- Tiêu chí thử: Sửa đúng ít nhất **9/10** yêu cầu rõ, **0/10** lượt sửa nhầm ở nhóm cần giữ nguyên và tối đa **10 giây** cho mỗi lượt sửa đúng. Nếu sửa nhầm, khôi phục bản trước và chuyển sang chỉ ghi nhận yêu cầu. Chi tiết trong [bộ 20 tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md).

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Lê Phạm Thành Đạt | 2A202604027 | Nhóm trưởng, phụ trách research CP4 | `liliustwocout` |
| 2 | Cao Trung Hiếu | 2A202603993 | Đề xuất vấn đề nhóm chọn, đầu mối kiểm chứng theo phân công đề xuất | `HieuCaoTlu` |
| 3 | Cao Thanh Tùng | 2A202603982 | Đề xuất phụ trách quy trình và bộ tiêu chí đánh giá | `TungCTT` |
| 4 | Trần Đức Duy | 2A202604071 | Đề xuất phụ trách Problem Statement và rà soát rủi ro | `tran85122-afk` |

## Phân công theo checkpoint

Đạt đã phụ trách research CP4. Các dòng còn lại là phân công đề xuất để nhóm chốt và hoàn thiện bài.

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
- [ ] **Phân công.** Xác nhận với Hiếu, Tùng và Duy phần việc và thời điểm bàn giao.
- [ ] **CP3.** Cùng cả nhóm hoàn thiện bảng gom vấn đề, cây OST và bảng chấm điểm. Ghi lý do chọn hoặc loại ứng viên theo nội dung đã thống nhất. [Hội tụ nhóm](report/team/group_report.md#2-hội-tụ-nhóm-cp3)
- [ ] **CP4.** Cùng Hiếu và Duy rà lại một buổi pitch đã diễn ra. Ghi riêng thời gian họp, thời gian sửa nội bộ và lý do hẹn lại để đối chiếu với các ước tính hiện có. [Kiểm chứng](report/team/group_report.md#32-kiểm-chứng)
- [ ] **CP5.** Rà quy trình trước/sau với Tùng và Problem Statement v0 với Duy. Kiểm tra cách đo số buổi hẹn lại và cách khôi phục bản xem trước khi sửa sai. [Quy trình trước/sau](report/team/group_report.md#4-quy-trình-trướcsau-cp5)
- [x] **CP6.** Ghi thay đổi từ v0 sang v1, bốn nhóm rủi ro và quyết định Go cho thử nội bộ vào báo cáo nhóm. [Quyết định CP6](report/team/group_report.md#8-quyết-định-cp6)
- [ ] **Rà soát với nhóm.** Xác nhận cách diễn đạt Problem Statement v1 và phạm vi thử với Duy cùng các thành viên trước khi chạy.
- [ ] **Chạy thử nội bộ.** Ghi kết quả từng lượt và đối chiếu với ngưỡng 9/10 yêu cầu rõ, 0/10 lượt sửa nhầm và tối đa 10 giây mỗi lượt sửa đúng. Nếu sửa nhầm, dừng tự cập nhật và khôi phục bản trước. [Mẫu ghi kết quả](report/assets/cp4-bo-tinh-huong-mvp.md#mẫu-ghi-kết-quả-và-ngưỡng-để-nhóm-xem-xét)

## Cá nhân

### LePhamThanhDat-2A202604027

**Phần việc phụ trách.** Nhóm trưởng, phụ trách tìm hiểu các giải pháp đã có ở CP4.

**Đóng góp cụ thể.** Ghi lại vấn đề nhóm chọn ở CP3. Ở CP4, đối chiếu Google Cloud Speech-to-Text, Figma Make và JSON Patch, phác thảo luồng từ lời góp ý đến bản xem trước và chuẩn bị 20 tình huống để thử ở CP5–CP6.

**Bằng chứng.** [Báo cáo nhóm, mục 3.3](report/team/group_report.md#33-research-giải-pháp-đã-có), [bộ tình huống thử](report/assets/cp4-bo-tinh-huong-mvp.md) và [báo cáo cá nhân](report/individual/2A202604027_LePhamThanhDat.md).

**Bài học từ phần làm nhóm**

- Cần ghi riêng thời gian trao đổi mỗi vòng, thời lượng cả buổi pitch và thời gian sửa nội bộ để biết khâu nào tốn thời gian. Mốc 6–9 giờ mỗi MVP là ước tính với giả định có thêm khoảng một giờ chỉnh sửa nội bộ sau mỗi buổi pitch.
- Khi đánh giá bản thử, cần kiểm tra cả lúc giao diện phải thay đổi lẫn lúc cần giữ nguyên. Bộ 20 tình huống gồm 10 yêu cầu rõ và 10 trường hợp như câu hỏi, lời nhận xét hoặc yêu cầu mơ hồ có thể khiến công cụ sửa nhầm.

### CaoTrungHieu-2A202603993

Đề xuất tình huống phải sửa giao diện MVP sau buổi pitch và hẹn thêm buổi để khách xác nhận. Nhóm chọn tình huống này làm đề tài. [Problem Card #2 của Hiếu](report/individual/2A202603993_CaoTrungHieu.md#problem-card-2)

### CaoThanhTung-2A202603982

Chuẩn bị ba Problem Card về rà soát bài nộp, hợp nhất báo cáo nhóm và tìm lại thông tin trên các kênh trao đổi. Card ưu tiên là rà soát bài nộp trước hạn LMS. [Báo cáo cá nhân của Tùng](report/individual/2A202603982_CaoThanhTung.md)

### TranDucDuy-2A202604071

Chuẩn bị ba Problem Card về nhận xét cuối kỳ, chấm bài tự luận và nhập điểm. Card ưu tiên là viết nhận xét cuối kỳ cho từng học sinh. [Báo cáo cá nhân của Duy](report/individual/2A202604071_TranDucDuy.md)
