# BÁO CÁO TỔNG HỢP BTN06 

## 1. Mục tiêu
Bài tập đánh giá khả năng sử dụng công cụ AI để tạo và cải tiến prototype cho hai ứng dụng: theo dõi sức khỏe và sàn đấu giá trực tuyến. TV4 chịu trách nhiệm tổng hợp kết quả, so sánh, chuẩn bị báo cáo và đóng gói sản phẩm.

## 2. Công cụ sử dụng
### 2.1 Figma Make
Được sử dụng để tạo prototype ứng dụng theo dõi sức khỏe. Báo cáo TV3 ghi nhận thông tin về gói sử dụng, hạn mức credit và quá trình xuất mã nguồn. Khi kiểm tra trên Windows, ZIP nguyên bản gặp lỗi do các cặp tên tệp chỉ khác chữ hoa/thường; sau khi đổi tên trong bản sao và cập nhật import, build thành công.

### 2.2 Google Stitch
Được sử dụng để tạo prototype sàn đấu giá trực tuyến. Bộ bàn giao có HTML, tài nguyên giao diện và DESIGN.md mô tả design system; TV3 cũng ghi lại thông tin công cụ và cách mở bản xuất.

## 3. Quy trình thực hiện
1. Dùng prompt ban đầu để tạo cấu trúc và các màn hình chính.
2. Đối chiếu yêu cầu và bổ sung thành phần.
3. Thực hiện các yêu cầu chỉnh sửa CS-1, CS-2 và CS-3.
4. Lưu nhật ký prompt, ảnh minh chứng và prototype sau chỉnh sửa.
5. Kiểm tra sản phẩm cuối, sau đó tổng hợp kết quả và đóng gói.

## 4. Kết quả
### 4.1 Ứng dụng theo dõi sức khỏe
Theo nhật ký TV1, prototype đạt 18/24 thành phần ở lượt đầu và 24/24 sau 7 lượt prompt. Các nội dung được bổ sung gồm thông tin hoạt động, calo/độ cao, tốc độ và nhịp tim trung bình, thống kê từng km, biểu đồ theo thời gian, chia sẻ hoạt động và điều hướng.

TV3 đã kiểm tra khả năng build mã nguồn. Bản ZIP nguyên bản gặp vấn đề phân biệt chữ hoa/thường trên Windows; bản sao đã sửa tên tệp và import build thành công. Điều này cho thấy ngoài giao diện, môi trường build cũng là một phần cần được kiểm tra khi bàn giao.

### 4.2 Sàn đấu giá trực tuyến
Prototype được xuất dưới dạng HTML và tài nguyên giao diện, kèm DESIGN.md. Các màn hình bàn giao bao gồm đăng nhập/đăng ký, tìm kiếm, tạo sản phẩm đấu giá, chi tiết sản phẩm, trạng thái ra giá lỗi, kết quả đấu giá, thanh toán và đánh giá/phản hồi. Bộ ảnh lượt đầu, lượt cuối và minh chứng CS-1/CS-2 được sử dụng để minh họa quá trình cải tiến.

## 5. So sánh hai prototype
| Tiêu chí | Theo dõi sức khỏe | Đấu giá trực tuyến |
|---|---|---|
| Công cụ | Figma Make | Google Stitch |
| Số thành phần theo yêu cầu | 24 | 22 |
| Kết quả định lượng đã ghi trong nhật ký | 18/24 → 24/24 sau 7 lượt | Có bộ ảnh lượt đầu/cuối và prototype xuất |
| Sản phẩm bàn giao | Link prototype, ZIP mã nguồn | Link Stitch, HTML, tài nguyên, DESIGN.md |
| Điểm cần lưu ý | Kiểm tra tương thích môi trường build | Kiểm tra thao tác của các luồng nghiệp vụ |

Hai công cụ phục vụ cùng mục tiêu tạo prototype nhưng khác nhau về cách bàn giao và kiểm tra. Nhật ký prompt giúp theo dõi tiến trình cải tiến; ảnh trước/sau giúp quan sát thay đổi; tệp xuất hỗ trợ kiểm tra khả năng sử dụng ngoài môi trường tạo prototype.

## 6. Minh họa
- **Sức khỏe:** tổng quan → chọn hoạt động → xem chi tiết/biểu đồ → thống kê theo km hoặc chia sẻ.
- **Đấu giá:** danh sách → tìm sản phẩm → chi tiết → thao tác đặt giá → trạng thái/kết quả.
- **Chỉnh sửa:** dùng ảnh trước/sau CS-1 và CS-2; bổ sung CS-3 theo tài liệu và màn hình đã bàn giao.

## 7. Giới hạn và khuyến nghị
- Prototype AI có thể tạo giao diện nhanh nhưng không thay thế việc kiểm thử luồng tương tác.
- Mã nguồn xuất ra có thể cần điều chỉnh để tương thích môi trường build.
- Hạn mức credit và trạng thái gói công cụ thay đổi theo thời điểm.

## 8. Kết luận
Figma Make và Google Stitch hỗ trợ rút ngắn thời gian tạo prototype cho hai miền nghiệp vụ khác nhau. Việc lặp prompt và chỉnh sửa giúp cải thiện độ bao phủ thành phần và tính nhất quán giao diện. Tuy nhiên, chất lượng cuối cần được đánh giá bằng giao diện, luồng tương tác, khả năng xuất và tính tương thích môi trường. Vai trò của TV4 là kết nối các kết quả thành một báo cáo thống nhất, minh họa bằng chứng và đóng gói bộ bài nộp rõ ràng.

## Phụ lục
- Nhật ký prompt và ảnh minh chứng của TV1.
- Ảnh lượt đầu/lượt cuối, CS-1/CS-2 và prototype xuất của TV2.
- Báo cáo công cụ, log build và nguồn tham khảo của TV3.
- Video demo dự phòng do TV4 quay/ghép (tối đa 90 giây).
