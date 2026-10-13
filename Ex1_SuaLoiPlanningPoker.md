# SS7 Ex1 - Sửa lỗi Planning Poker

## Phân tích
| PBI | Kết luận | Quy tắc | Hậu quả |
|---|---|---|---|
| P1 Đăng nhập số điện thoại | Chưa hợp lý | Kết quả 4 không nằm trong thang điểm; không lấy trung bình | Khó so sánh và dự báo sai |
| P2 Thanh toán RikkeiPay | Chưa hợp lý | PO không được chọn SP | Đội nhận phạm vi không do Developers thống nhất |
| P3 Hủy chuyến | Hợp lý | Có chênh lệch, người chọn 3 và 8 giải thích, sau đó đồng thuận 5 | Có thể dùng để lập kế hoạch |
| P4 Theo dõi vị trí | Chưa hợp lý ở ghi chú | SP là tương đối, không đổi cố định sang giờ | Dễ biến SP thành chỉ tiêu giờ |
| P5 Mã giới thiệu | Chưa hợp lý | PBI chưa rõ nhưng vẫn chốt theo đa số | Có thể bỏ sót rủi ro khuyến mãi |

## Cách sửa
- P1: chọn lại trên thang 1,2,3,5,8,13,21; người chọn 3 và 5 giải thích khác biệt rồi cả đội bỏ phiếu lại.
- P2: Developers tự ước lượng lại; PO chỉ làm rõ phạm vi và giá trị, không chọn số.
- P4: giữ 13 SP nếu đội đồng thuận, xóa ghi chú “52 giờ”.
- P5: PO làm rõ việc dùng mã cùng khuyến mãi khác, sau đó Developers ước lượng lại.
