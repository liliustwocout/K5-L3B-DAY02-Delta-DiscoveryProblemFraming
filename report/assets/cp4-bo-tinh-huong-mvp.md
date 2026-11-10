# Bộ 20 tình huống thử cập nhật MVP realtime

**Chuẩn bị cho CP5–CP6.** Dùng sau khi nhóm thống nhất phạm vi prototype. Đây là dữ liệu thử tổng hợp, kết quả bên dưới là kỳ vọng để chấm.

## Cách chạy

1. Mở bản xem trước màn hình **Lịch tư vấn**. Phạm vi thử gồm hai thuộc tính của nút CTA: nhãn và vị trí đầu/cuối màn hình. Đặt lại nhãn thành **Đặt lịch** và vị trí thành **cuối màn hình** trước mỗi lượt, trừ dòng ghi vị trí ban đầu khác.
2. Đọc nguyên câu như đang nói chuyện trong buổi pitching. Để đo luồng realtime, chạy bằng lời nói và bắt đầu bấm giờ khi người nói kết thúc câu. Dùng cùng bộ câu ở chế độ văn bản nếu cần tách lỗi nhận giọng nói khỏi lỗi hiểu yêu cầu.
3. Quan sát bản xem trước. Ghi đúng thay đổi đã xảy ra và thời điểm giao diện ổn định. Với câu có kỳ vọng giữ nguyên, quan sát 10 giây sau khi nói xong. Sau mỗi lượt, đặt lại giao diện để lượt sau bắt đầu từ trạng thái đã chỉ định.

## A. Yêu cầu rõ và trong phạm vi

| ID | Lời nói | Kết quả mong đợi |
|---|---|---|
| A01 | Đưa nút Đặt lịch lên đầu màn hình giúp tôi. | Nút lên đầu. Nhãn giữ nguyên. |
| A02 | Nút Đặt lịch đổi thành “Đặt lịch tư vấn” nhé. | Đổi nhãn thành **Đặt lịch tư vấn**. Vị trí giữ nguyên. |
| A03 | Cho nút Đặt lịch nằm trên cùng để dễ thấy hơn. | Nút lên đầu. Nhãn giữ nguyên. |
| A04 | Rút gọn chữ trên nút Đặt lịch còn “Đặt hẹn”. | Đổi nhãn thành **Đặt hẹn**. Vị trí giữ nguyên. |
| A05 | Mình muốn để nút Đặt lịch ở đầu màn hình, ngay khi khách mở trang. | Nút lên đầu. Nhãn giữ nguyên. |
| A06 | Thay chữ “Đặt lịch” trên nút bằng “Chọn giờ tư vấn”. | Đổi nhãn thành **Chọn giờ tư vấn**. Vị trí giữ nguyên. |
| A07 | Trên màn hình Lịch tư vấn, chuyển nút Đặt lịch xuống cuối trang. | Bắt đầu với nút ở **đầu**. Chuyển nút xuống cuối. Nhãn giữ nguyên. |
| A08 | Để nút Đặt lịch ở cuối màn hình giúp mình nhé. | Bắt đầu với nút ở **đầu**. Chuyển nút xuống cuối. Nhãn giữ nguyên. |
| A09 | Nút vẫn ở chỗ cũ, đổi tên thành “Giữ chỗ”. | Đổi nhãn thành **Giữ chỗ**. Vị trí giữ nguyên. |
| A10 | Sửa dòng chữ trên nút Đặt lịch thành “Hẹn tư vấn”. | Đổi nhãn thành **Hẹn tư vấn**. Vị trí giữ nguyên. |

## B. Trao đổi thông thường, mơ hồ hoặc ngoài phạm vi

| ID | Lời nói | Kết quả mong đợi |
|---|---|---|
| B01 | Nút Đặt lịch hiện nằm ở đâu? | Giữ nguyên. Đây là câu hỏi về hiện trạng. |
| B02 | Chỗ này nhìn chưa ổn. | Giữ nguyên. Chưa rõ phần tử và thao tác. |
| B03 | Hôm trước khách từng bảo đưa nút lên đầu. | Giữ nguyên. Đây là nhắc lại một tình huống. |
| B04 | Đừng chuyển nút Đặt lịch lên đầu nhé. | Giữ nguyên. Câu nói phủ định thao tác. |
| B05 | Nếu đổi nút lên đầu thì có dễ thấy hơn không? | Giữ nguyên. Hai bên đang cân nhắc một phương án. |
| B06 | Sửa chữ trên nút giúp tôi. | Giữ nguyên. Chưa có nhãn mới. |
| B07 | Đổi màu nút Đặt lịch sang đỏ. | Giữ nguyên. Màu nằm ngoài phạm vi thử. |
| B08 | Đưa nút Đặt lịch trên màn hình Thanh toán lên đầu. | Giữ nguyên. Yêu cầu nhắm vào màn hình khác. |
| B09 | Đưa nút lên đầu… khoan, giữ nguyên giúp tôi. | Giữ nguyên. Người nói rút yêu cầu trong cùng lượt nói. |
| B10 | Nút Đặt lịch để thế này là được rồi. | Giữ nguyên. Đây là nhận xét về trạng thái hiện tại. |

## Bảng ghi kết quả và ngưỡng đánh giá

| ID | Thay đổi quan sát được | Số giây từ lúc nói xong | Đạt / Chưa đạt | Ghi chú |
|---|---|---:|---|---|
| | | | | |

- **Độ đúng đề xuất:** Ít nhất 9/10 lượt nhóm A có đúng thuộc tính và giá trị mong đợi.
- **Sửa nhầm đề xuất:** 0/10 lượt nhóm B làm đổi giao diện. Ghi cả thay đổi xuất hiện rồi tự quay lại.
- **Độ trễ đề xuất:** Mỗi lượt A xử lý đúng xuất hiện trong tối đa 10 giây sau khi người nói kết thúc câu.
- **Khi có lần tự sửa sai:** Khôi phục bản xem trước, chuyển sang chế độ chỉ ghi nhận và rà soát nguyên nhân trước khi thử lại.
