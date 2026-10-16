# AI Usage Log

## 1. Công cụ AI
- **Tên công cụ:** ChatGPT
- **URL:** https://chatgpt.com/

## 2. Mục đích sử dụng
- Hỗ trợ xác định vấn đề trong cách hiển thị thẻ sản phẩm.
- Đề xuất bố cục và các thành phần HTML cần thiết.
- Hỗ trợ tạo khung mã HTML5 và CSS3.
- Giải thích responsive design và cách kiểm tra giao diện.

## 3. Prompt đã sử dụng

### Prompt 1 – Đề xuất giao diện
Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3.

Tôi muốn cải tiến khu vực thẻ sản phẩm trong danh sách sản phẩm của website Shopee Việt Nam. Tôi muốn khách hàng dễ nhận biết giá khuyến mãi, giá gốc và mức giảm giá; đồng thời nút thao tác cần dễ nhìn và bố cục cần phù hợp với điện thoại.

Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam.

Hãy đề xuất:
1. Bố cục giao diện.
2. Các thành phần HTML cần sử dụng.
3. Cách tổ chức CSS.
4. Cách hiển thị trên máy tính và điện thoại.
5. Những điểm cần kiểm tra về khả năng sử dụng.

Trước tiên, hãy giải thích phương án thiết kế, chưa tạo mã nguồn.

### Prompt 2 – Tạo mã nguồn
Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3.

Yêu cầu:
- Có tiêu đề và khu vực sản phẩm.
- Có tối thiểu 4 sản phẩm mẫu.
- Mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác.
- Thể hiện rõ giá gốc, giá khuyến mãi và tỷ lệ giảm giá.
- Bố cục phù hợp với màn hình máy tính và điện thoại.
- Mã HTML có cấu trúc rõ ràng.
- CSS được tách thành file riêng.
- Không sử dụng backend hoặc cơ sở dữ liệu.
- Không đưa thư viện hoặc thành phần không cần thiết vào dự án.

Giải thích cách chạy trang web và những phần cần kiểm tra.

## 4. Kết quả AI đề xuất
AI gợi ý sử dụng thẻ sản phẩm gồm hình ảnh, tên, giá khuyến mãi, giá gốc, nhãn giảm giá và nút thao tác. Giá khuyến mãi được làm nổi bật bằng màu sắc và cỡ chữ; giá gốc được hiển thị nhỏ hơn, màu xám và gạch ngang. CSS Grid được dùng để sắp xếp các thẻ sản phẩm, kết hợp media queries để điều chỉnh bố cục theo kích thước màn hình.

## 5. Kiểm tra và điều chỉnh
Sau khi mở trang bằng Chrome, cần kiểm tra:
- Tất cả hình ảnh có hiển thị đúng hay không.
- Tên và giá sản phẩm có bị tràn hoặc che khuất không.
- Giá khuyến mãi và giá gốc có dễ phân biệt không.
- Nút thao tác có dễ nhìn và dễ bấm trên điện thoại không.
- Bố cục có xuất hiện thanh cuộn ngang ngoài ý muốn không.
- Giao diện ở màn hình máy tính, máy tính bảng và điện thoại.

**Ghi lại sau khi tự kiểm tra:**  
- Kích thước màn hình đã thử: [điền kích thước thực tế].  
- Vấn đề tự phát hiện: [ghi vấn đề thực tế, nếu có].  
- Điều chỉnh đã thực hiện: [ghi phần đã sửa trong HTML/CSS].  
- Kết quả sau khi sửa: [ghi kết quả kiểm tra thực tế].

Không nên điền các nội dung trên theo suy đoán; cần kiểm tra trang web trước khi nộp.

## 6. Phần tôi hiểu và có thể giải thích
- `header`, `main`, `section`, `article` và `footer` giúp tổ chức nội dung HTML theo từng khu vực.
- `img` hiển thị hình ảnh; thuộc tính `alt` mô tả hình ảnh để hỗ trợ khả năng tiếp cận.
- `class` cho phép CSS chọn và định dạng các thành phần.
- `display: grid` và `grid-template-columns` sắp xếp sản phẩm thành các cột.
- `@media` điều chỉnh bố cục theo chiều rộng màn hình.
- `object-fit: contain` giữ toàn bộ hình minh họa nằm trong khung mà không bị cắt.
- `:hover` và `:focus-visible` giúp thể hiện trạng thái tương tác của nút.
- HTML/CSS hiện chỉ dựng giao diện. Nút “Xem sản phẩm” chưa có chức năng chuyển trang hoặc xử lý mua hàng vì bài tập không yêu cầu JavaScript hay backend.
