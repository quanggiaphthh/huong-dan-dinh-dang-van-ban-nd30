# 11. Hệ thống quản lý tài liệu điện tử

> Phụ lục VI — Nghị định 30/2020/NĐ-CP.

## Phần I. Yêu cầu hệ thống

### I. Nguyên tắc xây dựng

1. Quản lý văn bản và hồ sơ điện tử đúng quy định
2. An toàn, an ninh thông tin mạng theo pháp luật
3. Phân quyền truy cập cho cá nhân
4. Xác thực, tin cậy của tài liệu, dữ liệu lưu hành
5. Cho phép kiểm chứng, xác minh, đáp ứng yêu cầu nghiệp vụ khi được yêu cầu

### II. Yêu cầu chung khi thiết kế

1. Đủ quy trình và kỹ thuật quản lý văn bản điện tử, lập–quản lý hồ sơ điện tử và **dữ liệu đặc tả**
2. Tích hợp, liên thông, chia sẻ với hệ thống khác
3. Hệ thống hóa văn bản, hồ sơ; thống kê lượt truy cập
4. Xác thực, tin cậy, toàn vẹn; truy cập và sử dụng được
5. Lưu trữ theo thời hạn bảo quản
6. Phù hợp Khung kiến trúc Chính phủ điện tử Việt Nam
7. Dễ tiếp cận, dễ dùng
8. Ký số, kiểm tra, xác thực chữ ký số theo pháp luật

> **Dữ liệu đặc tả:** thông tin mô tả nội dung, định dạng, ngữ cảnh, cấu trúc, yếu tố cấu thành; liên hệ với văn bản/hồ sơ khác; thông tin chữ ký số; lịch sử hình thành, sử dụng và đặc tính khác phục vụ quản lý, tìm kiếm, sử dụng.

### III. Yêu cầu chức năng (tóm lược)

| Nhóm | Năng lực bắt buộc |
| --- | --- |
| Tạo lập & theo dõi văn bản | Tạo mới, chuyển định dạng, đính kèm, mã định danh văn bản đi, mức độ khẩn, tự cấp số đi/số đến theo năm, bên nhận báo đã nhận, tự cập nhật trường thông tin (xem Phần II), cảnh báo trùng mã hoặc trùng bộ ba *số + ký hiệu + tên cơ quan*, thông báo văn bản mới / tình trạng nhận, thống kê–đôn đốc, phân phối–theo dõi hạn, lãnh đạo sửa/chuyển lại dự thảo, bên gửi xem tình trạng xử lý bên nhận |
| Kết nối, liên thông | Liên thông Hệ thống quản lý tài liệu điện tử và Hệ thống lưu trữ lịch sử (cơ quan thuộc nguồn nộp lưu); chạy trên thiết bị di động khi bảo đảm ATTT; tích hợp hệ thống chuyên dụng tại cơ quan |
| An ninh | Đủ cấp độ ATTT; phân quyền từng hồ sơ/văn bản; cảnh báo đổi quyền đến khi người có thẩm quyền xác nhận |
| Lập & quản lý hồ sơ | Danh mục hồ sơ; mã hồ sơ + tự đánh STT văn bản trong hồ sơ; liên kết cùng mã; liên kết trường Danh mục với toàn bộ tài liệu; thống kê hồ sơ theo tài khoản; gán một văn bản cho nhiều hồ sơ **không nhân bản**; kết xuất PDF + XML theo trình tự thời gian |
| Bảo quản & lưu trữ | Lưu toàn bộ quá trình giải quyết (ý kiến chỉ đạo, dự thảo, góp ý, phê duyệt nội dung, phê duyệt thể thức, lịch sử xem, tác động khác); tự báo hồ sơ đến hạn nộp lưu **trước 30 ngày**; nộp lưu Lưu trữ cơ quan / Lưu trữ lịch sử; toàn vẹn, không thay đổi; truy cập theo thời hạn; di chuyển và đổi định dạng khi đổi công nghệ; sao lưu định kỳ/đột xuất và phục hồi |
| Thống kê, tìm kiếm, sử dụng | Thống kê số hồ sơ/văn bản và lượt truy cập; thống kê truy cập hệ thống; cấp–kiểm soát quyền hồ sơ lưu trữ; tìm mọi trường + nội dung; chọn cột hiển thị; lưu truy vấn; sắp thứ tự kết quả; xuất .doc/.docx/.pdf; tải/in; đánh dấu bản in từ Hệ thống; lưu lịch sử dùng |
| Dữ liệu đặc tả | Lưu theo thời hạn bảo quản; hiển thị đủ khi được quyền; nhập bổ sung; lưu dữ liệu kiểm soát an ninh; cố định liên kết văn bản/hồ sơ với mọi yếu tố đặc tả |
| Thu hồi văn bản | Đóng băng văn bản đi + đặc tả khi có lệnh thu hồi; hủy văn bản đến + đặc tả khi lệnh từ cơ quan phát hành; lưu đặc tả quá trình thu hồi |

### IV. Quản trị hệ thống

Người quản trị được: tạo nhóm tài liệu/hồ sơ theo cấp độ thông tin; phân quyền; truy cập hồ sơ và đặc tả theo quy định; đổi quyền khi đổi quy định hoặc đổi vị trí công tác; phục hồi dữ liệu khi lỗi và thông báo kết quả; khóa/đóng băng tập hợp để ngăn di chuyển, xóa, sửa khi có yêu cầu thẩm quyền.

Hệ thống cảnh báo xung đột và cho phép thiết lập kết nối liên thông.

### V. Thông tin đầu ra

1. Sổ đăng ký văn bản đến
2. Báo cáo tình hình giải quyết văn bản đến
3. Sổ đăng ký văn bản đi
4. Báo cáo tình hình giải quyết văn bản đi
5. Mục lục văn bản trong hồ sơ
6. Mục lục hồ sơ

---

## Phần II. Chuẩn thông tin đầu vào

Mã định danh cơ quan, tổ chức lập danh mục hồ sơ (`OrganId`) được **mặc định trong Hệ thống**.

> Trong Nghị định, một số chỗ in `Organld` / `Signerlnfo` — đây là lỗi chữ (`l`/`I`). Tên trường chuẩn dùng: **OrganId**, **SignerInfo**.

### I. Văn bản đi

| STT | Trường | Tên Anh | Kiểu | Độ dài |
| --- | --- | --- | --- | ---: |
| 1 | Mã hồ sơ | FileCode | *(nhóm)* | |
| 1.1 | Mã định danh cơ quan lập DMHS | OrganId | String | 13 |
| 1.2 | Năm hình thành hồ sơ | FileCatalog | Number | 4 |
| 1.3 | Số và ký hiệu hồ sơ | FileNotation | String | 20 |
| 2 | Số thứ tự văn bản trong hồ sơ | DocOrdinal | Number | 3 |
| 3 | Tên loại văn bản | TypeName | String | 100 |
| 4 | Số của văn bản | CodeNumber | String | 11 |
| 5 | Ký hiệu của văn bản | CodeNotation | String | 30 |
| 6 | Ngày, tháng, năm văn bản | IssuedDate | Date | 10 |
| 7 | Tên cơ quan ban hành | OrganName | String | 200 |
| 8 | Trích yếu nội dung | Subject | String | 500 |
| 9 | Ngôn ngữ | Language | String | 30 |
| 10 | Số trang | PageAmount | Number | 3 |
| 11 | Ghi chú | Description | String | 500 |
| 12 | Chức vụ, họ tên người ký | SignerInfo | *(nhóm)* | |
| 12.1 | Chức vụ người ký | Position | String | 100 |
| 12.2 | Họ và tên người ký | FullName | String | 50 |
| 13 | Nơi nhận | To | *(nhóm)* | |
| 13.1 | Mã định danh cơ quan nhận | OrganId | String | 13 |
| 13.2 | Tên cơ quan nhận | OrganName | String | 200 |
| 14 | Mức độ khẩn, độ mật | Priority | Number | 1 |
| 15 | Số lượng bản phát hành | IssuedAmount | Number | 3 |
| 16 | Hạn trả lời | DueDate | Date | 10 |

Tự động cập nhật các trường: **1.1, 1.2, 2, 4, 6, 10, 13.1**.

### II. Văn bản đến

Giống văn bản đi đến trường 11, sau đó:

| STT | Trường | Tên Anh | Kiểu | Độ dài |
| --- | --- | --- | --- | ---: |
| 12 | Ngày, tháng, năm đến | ArrivalDate | Date | 10 |
| 13 | Số đến | ArrivalNumber | Number | 10 |
| 14 | Chức vụ, họ tên người ký | SignerInfo | *(nhóm)* | |
| 14.1 | Chức vụ | Position | String | 100 |
| 14.2 | Họ và tên | FullName | String | 50 |
| 15 | Mức độ khẩn, độ mật | Priority | Number | 1 |
| 16 | Đơn vị hoặc người nhận | ToPlaces | String | 1000 |
| 17 | Ý kiến phân phối, chỉ đạo, trạng thái xử lý | TraceHeaderList | LongText | |
| 18 | Thời hạn giải quyết | DueDate | Date | 10 |

Tự động cập nhật: **1.1, 1.2, 2, 10, 12, 13**.

### III. Hồ sơ

| STT | Trường | Tên Anh | Kiểu | Độ dài |
| --- | --- | --- | --- | ---: |
| 1 | Mã hồ sơ | FileCode | *(nhóm)* | |
| 1.1 | Mã định danh cơ quan lập DMHS | OrganId | String | 13 |
| 1.2 | Năm hình thành hồ sơ | FileCatalog | Number | 4 |
| 1.3 | Số và ký hiệu hồ sơ | FileNotation | String | 20 |
| 2 | Tiêu đề hồ sơ | Title | String | 500 |
| 3 | Thời hạn bảo quản | Maintenance | String | 30 |
| 4 | Chế độ sử dụng | Rights | String | 30 |
| 5 | Người lập hồ sơ | Creator | String | 30 |
| 6 | Ngôn ngữ | Language | String | 50 |
| 7 | Thời gian bắt đầu | StartDate | Date | 10 |
| 8 | Thời gian kết thúc | EndDate | Date | 10 |
| 9 | Tổng số văn bản trong hồ sơ | DocTotal | Number | 4 |
| 10 | Tổng số trang của hồ sơ | PageTotal | Number | 4 |
| 11 | Ghi chú | Description | String | 500 |

Tự động cập nhật: **1.1, 1.2, 9, 10**.
