# BÁO CÁO PHÂN TÍCH CÔNG CỤ

## Tìm hiểu và kiểm chứng Figma Make, Google Stitch

**Bài tập tuần 6:** Công cụ phác thảo prototype bằng AI  
**Ngày đọc tài liệu và kiểm tra:** 19/10/2026

---

## 1. Phạm vi thực hiện

| Bài | Công cụ | Nhà phát hành | Sản phẩm cần bàn giao |
|---|---|---|---|
| Ứng dụng theo dõi sức khỏe | Figma Make | Figma, Inc. | Prototype tương tác, liên kết hoặc tệp xuất |
| Sàn đấu giá trực tuyến | Google Stitch | Google Labs | Thiết kế/prototype trên canvas, liên kết và tệp xuất |

Phạm vi phân tích gồm điều kiện truy cập, hạn mức, mô hình hiển thị; tài liệu và điều khoản quyền sử dụng; khả năng chia sẻ, xuất và mở lại sản phẩm; nội dung công cụ dùng trong báo cáo chung.

## 2. Quy ước bằng chứng

- **Đã chạy:** nhóm đã thao tác hoặc quan sát trên giao diện/tệp thực tế và có minh chứng.
- **Theo tài liệu:** thông tin được trích từ tài liệu chính thức của nhà phát triển.

## 3. Kết quả kiểm tra công cụ

### 3.1. Figma Make

| Nội dung | Kết quả | Nhãn | Minh chứng |
|---|---|---|---|
| Loại sản phẩm | Công cụ prompt-to-app trên web, tạo functional prototype, web app và giao diện tương tác | Theo tài liệu | [F1] |
| Gói thực tế | Education plan | Đã chạy | `FM-01-education-balance.png` |
| Hạn mức tháng | Education plan có 3.000 AI credit mỗi tháng | Đã chạy | `FM-01-education-balance.png` |
| Số dư sau khi sử dụng | 2.066 credit còn lại; reset ngày 01/11 | Đã chạy | `FM-01-education-balance.png` |
| Credit đã dùng trong chu kỳ | 3.000 − 2.066 = **934 credit**, tính từ hạn mức tháng và số dư hiển thị | Đã chạy | `FM-01-education-balance.png`, `FM-00-ket-qua-quan-sat.md` |
| Truy cập file được chia sẻ | Đã mở được file “Health Tracking App Prototype” với quyền View và có thể xem giao diện | Đã chạy | `FM-01-education-balance.png` |
| Xuất mã nguồn | Đã nhận ZIP chứa dự án React/Vite, mã TypeScript, CSS, cấu hình và lockfile | Đã chạy | `FM-02-health-prototype-export.zip` |
| Kiểm tra ZIP nguyên bản trên Windows | Giải nén và cài dependency thành công; build thất bại do hai cặp tệp chỉ khác chữ hoa/thường | Đã chạy | `FM-03-build-log.txt` |
| Kiểm tra bản tương thích Windows | Sau khi đổi tên hai tệp dữ liệu trên bản sao tạm và cập nhật import, dự án build thành công và mở được bằng Chrome | Đã chạy | `FM-03-build-log.txt`, `FM-04-build-sau-sua-tuong-thich.png` |
| Chia sẻ preview | Figma hỗ trợ chia sẻ fullscreen preview và đặt quyền truy cập | Theo tài liệu | [F4] |
| Copy sang Figma Design | Có thể chép preview thành layer; layer sửa được nhưng là snapshot, không giữ tương tác và không đồng bộ ngược | Theo tài liệu | [F6] |

**Nhận xét:** Education plan có hạn mức 3.000 credit mỗi tháng và ảnh kiểm tra hiển thị còn 2.066 credit, tương ứng 934 credit đã dùng trong chu kỳ. Đây không phải số credit của một prompt riêng lẻ. Bộ tệp bàn giao có ZIP mã nguồn thực tế. ZIP mở và cài dependency được nhưng không build nguyên trạng trên Windows do xung đột tên tệp chỉ khác chữ hoa/thường; bản sao đã sửa hai tên tệp build và hiển thị thành công.

### 3.2. Google Stitch

| Nội dung | Kết quả | Nhãn | Minh chứng |
|---|---|---|---|
| Loại sản phẩm | Canvas thiết kế giao diện AI trên web, hỗ trợ tạo và nối luồng prototype | Theo tài liệu | [G1] |
| Trạng thái sản phẩm | Giao diện hiển thị “Stitch – BETA”; ảnh không hiển thị tên gói thuê bao | Đã chạy | `minh-chung/stitch/ST-01-beta-quota.jpg` |
| Hạn mức | Usage Today hiển thị 56/400 Daily Credits: hạn mức ngày 400 credit, đã dùng 56 tại thời điểm chụp | Đã chạy | `ST-01-beta-quota.jpg` |
| Mô hình | Speed – Gemini 3.5 Flash-Lite; Balanced – Gemini 3.8 Flash; dự án đang chọn Balanced | Đã chạy | `ST-02-model.png` |
| Chia sẻ | Đã bật “Enable sharing & remixing”; giao diện ghi người có liên kết có thể truy cập dự án | Đã chạy | `ST-03-share.png` |
| Link prototype | Đã nhận liên kết dự án đấu giá | Đã chạy | `ST-04-link-prototype.txt` |
| Loại tệp xuất | Đã nhận `code.html`, `screen.png` và `DESIGN.md` | Đã chạy | `ST-05-DESIGN.md`, `ST-06-prototype-exported.zip` |
| Nội dung DESIGN.md | Có token màu, font Inter, kích thước chữ, khoảng cách, bo góc và quy tắc component | Đã chạy | `ST-05-DESIGN.md` |
| Mở lại HTML trong trình duyệt | Đã mở tệp HTML xuất bằng Chrome; giao diện đăng ký/đăng nhập hiển thị được | Đã chạy | `ST-06-html-mo-lai.png` |

**Nhận xét:** Bộ dữ liệu Stitch chứng minh được trạng thái Beta, hạn mức, mô hình, cấu hình Share, các định dạng đã xuất và khả năng mở lại tệp HTML.

## 4. Quyền sở hữu và sử dụng sản phẩm

### 4.1. Figma

Figma AI Terms, mục 2 “Input, Output, and Ownership”, hiệu lực 24/06/2026 [F7]:

> “Input and Output are Customer Content. As between Customer and Figma, Customer retains all right, title, and interest in Customer’s Input and Output...”

**Theo tài liệu:** Trong quan hệ giữa khách hàng và Figma, input và output là Customer Content và khách hàng giữ quyền đối với input/output. Tuy nhiên, Figma cảnh báo Make có thể sử dụng font, mã hoặc ảnh bên thứ ba; người dùng phải bảo đảm có quyền phù hợp trước khi xuất bản [F1].

### 4.2. Google Stitch

Google Terms of Service, bản Việt Nam hiệu lực 30/07/2026 [G6], nêu:

> “Your content remains yours, which means that you retain any intellectual property rights that you have in your content.”

Và:

> “Some of our services allow you to generate original content. Google won’t claim ownership over that content.”

**Theo tài liệu:** Google không tuyên bố sở hữu nội dung gốc do người dùng tạo; người dùng vẫn cấp giấy phép cần thiết để Google vận hành và cải thiện dịch vụ theo điều khoản. Nhóm vẫn phải kiểm tra quyền đối với ảnh, font, mã và nội dung bên thứ ba.

## 5. Cách bàn giao sản phẩm

### Figma Make – prototype sức khỏe

1. Bàn giao link file hoặc fullscreen preview.
2. Đặt quyền xem phù hợp và kiểm tra lại bằng trình duyệt không đăng nhập.
3. Bàn giao `FM-02-health-prototype-export.zip`; khi chạy trên Windows cần xử lý hai cặp tên tệp phân biệt chữ hoa/thường theo `FM-03-build-log.txt`.
4. Có thể chép preview sang Figma Design để sửa layer; không coi bản layer là prototype tương tác.

### Google Stitch – prototype đấu giá

1. Bàn giao link dự án trong `ST-04-link-prototype.txt`.
2. Duy trì cấu hình Share cho người có liên kết nếu bài nộp cần truy cập công khai.
3. Bàn giao bộ xuất gồm HTML, PNG và DESIGN.md.
4. Khi trình bày trực tiếp, dùng Play; chuẩn bị video dự phòng nếu liên kết yêu cầu đăng nhập hoặc mạng không ổn định.

## 6. Giới hạn quan sát được

1. **Số credit Figma là mức tiêu hao toàn phiên, không phải từng prompt.** Balance giảm từ 3.000 xuống 2.066, tương ứng 934 credit; Figma không cho biết trước chính xác chi phí của từng tác vụ.
2. **ZIP Figma có xung đột tên tệp trên Windows.** Hai cặp tệp chỉ khác chữ hoa/thường làm build nguyên bản thất bại; bản sao đổi tên tương thích đã build và mở được. Bằng chứng: `FM-03-build-log.txt`, `FM-04-build-sau-sua-tuong-thich.png`.
3. **Stitch đang ở trạng thái Beta và dùng hạn mức theo ngày.** Tính năng, mô hình hoặc quota có thể thay đổi; kết quả chỉ áp dụng tại ngày 19/10/2026. Bằng chứng: `ST-01-beta-quota.jpg`, `ST-02-model.png`.

## 7. Khuyến nghị

- **Nên dùng:** phác thảo nhanh giao diện và luồng cho dự án nhỏ, sau đó để con người đối chiếu yêu cầu và sửa lỗi.
- **Không nên dùng như sản phẩm hoàn thiện:** hệ thống có quy tắc nghiệp vụ, thanh toán hoặc dữ liệu nhạy cảm nếu chưa kiểm thử thủ công và rà soát mã/nội dung bên thứ ba.
- Trước khi nộp hoặc trình bày, mở thử mọi liên kết và tệp trên máy/tài khoản khác; nếu không mở được, dùng video quay màn hình làm phương án dự phòng.

## 8. Nội dung bàn giao cho slide

### Slide “Công cụ”

- **Figma Make – Đã chạy:** Education plan, 3.000 credit/tháng, còn 2.066 credit sau khi dùng; đã tiêu hao 934 credit, reset 01/11.
- **Google Stitch – Đã chạy:** Beta, 400 credit/ngày, đã dùng 56; mô hình Balanced – Gemini 3.8 Flash.
- **Theo tài liệu:** Figma Make tạo ứng dụng web/prototype tương tác; Stitch tạo thiết kế và luồng trên canvas.

### Slide “Cách bàn giao”

- **Stitch – Đã chạy:** bật chia sẻ cho người có link; đã nhận HTML, PNG và DESIGN.md.
- **Figma – Đã chạy:** đã nhận ZIP mã nguồn; ZIP build được sau khi sửa hai xung đột tên tệp trên Windows. **Theo tài liệu:** chia sẻ preview và chép preview thành layer.

## 9. Danh sách nguồn

| Mã | Nguồn chính thức | Ngày đọc |
|---|---|---|
| F1 | https://help.figma.com/hc/en-us/articles/31304412302231-Explore-Figma-Make | 19/10/2026 |
| F2 | https://help.figma.com/hc/en-us/articles/31722591905559-Figma-Make-FAQs | 19/10/2026 |
| F3 | https://help.figma.com/hc/en-us/articles/33459875669015-How-AI-credits-work | 19/10/2026 |
| F4 | https://help.figma.com/hc/en-us/articles/31304548273047-Preview-a-functional-prototype-or-web-app | 19/10/2026 |
| F5 | https://help.figma.com/hc/en-us/articles/33649966245783-Edit-the-code-of-a-functional-prototype-or-web-app | 19/10/2026 |
| F6 | https://help.figma.com/hc/en-us/articles/35060759685015 | 19/10/2026 |
| F7 | https://www.figma.com/legal/ai-terms/ | 19/10/2026 |
| G1 | https://blog.google/innovation-and-ai/models-and-research/google-labs/stitch-ai-ui-design/ | 19/10/2026 |
| G2 | https://stitch.withgoogle.com/ | 19/10/2026 |
| G3 | https://stitch.withgoogle.com/docs/design-md/overview/ | 19/10/2026 |
| G4 | https://stitch.withgoogle.com/docs/mcp/setup/ | 19/10/2026 |
| G5 | https://github.com/google-labs-code/stitch-sdk | 19/10/2026 |
| G6 | https://policies.google.com/terms | 19/10/2026 |
