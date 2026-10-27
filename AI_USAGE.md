# AI Usage Log

## 1. Công cụ AI

- **Tên công cụ:** ChatGPT
- **Đường dẫn:** https://chatgpt.com/

## 2. Mục đích sử dụng

Em sử dụng ChatGPT để tham khảo ý tưởng cải tiến giao diện website thương mại điện tử, hỗ trợ viết và chỉnh sửa HTML/CSS, giải thích các kiến thức đã học và rà soát mã nguồn.

Em không sử dụng kết quả AI một cách máy móc mà đối chiếu với mã nguồn và kiểm tra giao diện trước khi áp dụng.

## 3. Các prompt đã sử dụng

### Prompt 1 – Đề xuất giao diện

Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3.

Tôi muốn cải tiến khu vực thẻ sản phẩm trong danh sách sản phẩm của website Shopee Việt Nam. Tôi muốn khách hàng dễ nhận biết giá khuyến mãi, giá gốc và mức giảm giá; đồng thời nút thao tác cần dễ nhìn và bố cục cần phù hợp với điện thoại.

Hãy đề xuất bố cục giao diện, các thành phần HTML cần sử dụng, cách tổ chức CSS, cách hiển thị trên máy tính và điện thoại, cùng những điểm cần kiểm tra về khả năng sử dụng. Trước tiên, hãy giải thích phương án thiết kế, chưa tạo mã nguồn.

### Prompt 2 – Tạo mã nguồn

Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3.

Yêu cầu có tiêu đề và khu vực sản phẩm; tối thiểu 4 sản phẩm mẫu; mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác; thể hiện giá gốc, giá khuyến mãi và tỷ lệ giảm giá. Bố cục cần phù hợp với máy tính và điện thoại, CSS được tách thành file riêng, không sử dụng backend hoặc cơ sở dữ liệu.

Hãy giải thích cách chạy website và những phần cần kiểm tra.

### Prompt 3 – Kiểm tra kiến thức HTML5 và CSS3

Dựa trên mã HTML/CSS của website, hãy giải thích các thẻ HTML ngữ nghĩa, sự khác nhau giữa `margin` và `padding`, cách sử dụng Flexbox và CSS Grid, tác dụng của thuộc tính `alt` và ảnh hưởng khi xóa `display: grid`.

### Prompt 4 – Cải thiện mã CSS

Hãy xem xét mã CSS của website và đề xuất cách làm cho mã nguồn gọn gàng, dễ bảo trì hơn. Chú ý các quy tắc bị khai báo trùng lặp và cách hiển thị hình ảnh sản phẩm. Giải thích những điểm cần kiểm tra sau khi chỉnh sửa.

### Prompt 5 – Kiểm tra README

Tôi đang hoàn thiện README.md cho bài tập cá nhân Buổi 2 của môn Phát triển ứng dụng TMĐT.

Bài tập tiếp tục phát triển website từ Buổi 1. Tôi đã thực hành HTML5, CSS selector, Box Model và Flexbox hoặc CSS Grid ở mức cơ bản.

Hãy đề xuất cấu trúc README ngắn gọn gồm:
1. Giới thiệu bài tập.
2. Website tham khảo và khu vực đã cải tiến.
3. Những kỹ thuật HTML5/CSS3 đã thực hành.
4. Hướng dẫn chạy website.
5. Những thay đổi tôi đã thực hiện.
6. Công cụ AI đã sử dụng và cách tôi kiểm tra kết quả.
7. Đường dẫn repository và website nếu đã triển khai.

Không tự bịa thông tin về dự án. Sử dụng chỗ trống cho các thông tin tôi chưa cung cấp.

## 4. Kết quả AI đề xuất

AI gợi ý cách tổ chức thẻ sản phẩm bằng HTML, sử dụng CSS để làm nổi bật giá khuyến mãi, giá gốc và thông tin giảm giá. AI cũng hỗ trợ giải thích cách sử dụng Flexbox, CSS Grid, Box Model, media queries và thuộc tính `alt`.

Trong quá trình hoàn thiện bài tập, AI còn gợi ý kiểm tra các quy tắc CSS trùng lặp để mã nguồn dễ đọc và dễ chỉnh sửa hơn.

## 5. Kiểm tra và điều chỉnh

Sau khi tham khảo AI, em cần đối chiếu các gợi ý với mã nguồn hiện tại và kiểm tra giao diện trên trình duyệt.

Các nội dung cần kiểm tra gồm:

- Hình ảnh sản phẩm có hiển thị đúng và sử dụng đường dẫn phù hợp không.
- Tên, giá và thông tin sản phẩm có bị che khuất hoặc tràn khỏi khung không.
- Các thẻ sản phẩm có được sắp xếp đúng theo bố cục Grid không.
- Giao diện có phù hợp với màn hình máy tính và điện thoại không.
- Các quy tắc CSS trùng lặp có thể được gộp lại mà không làm thay đổi giao diện ngoài ý muốn không.

### Ghi nhận kết quả kiểm tra thực tế

- **Kích thước màn hình đã thử:** Màn hình máy tính và màn hình điện thoại bằng Chrome DevTools.
- **Vấn đề phát hiện:** Một số quy tắc CSS được khai báo trùng lặp, có thể gây khó khăn khi chỉnh sửa và ảnh hưởng đến cách hiển thị giao diện.
- **Điều chỉnh đã thực hiện:** Kiểm tra và gộp các quy tắc CSS trùng lặp của `.product-image`, đồng thời rà soát cách sử dụng `object-fit: cover` để hình ảnh phù hợp với khung sản phẩm.
- **Kết quả sau khi sửa:** Mã CSS gọn gàng và dễ quản lý hơn. Em cần kiểm tra lại hình ảnh và bố cục trên máy tính, điện thoại để đảm bảo giao diện hiển thị đúng sau khi chỉnh sửa.

## 6. Những kiến thức em hiểu sau khi thực hiện

- Các thẻ HTML ngữ nghĩa giúp tổ chức nội dung website rõ ràng hơn.
- `margin` tạo khoảng cách bên ngoài phần tử, còn `padding` tạo khoảng cách bên trong.
- Flexbox hỗ trợ căn chỉnh các thành phần theo một chiều.
- CSS Grid giúp sắp xếp sản phẩm thành hàng và cột.
- Media queries giúp điều chỉnh giao diện theo kích thước màn hình.
- Thuộc tính `alt` cung cấp mô tả thay thế cho hình ảnh.
- `object-fit: cover` giúp hình ảnh lấp đầy khung nhưng có thể cắt một phần ảnh.
- CSS cần được kiểm tra sau khi chỉnh sửa vì các quy tắc có thể ảnh hưởng lẫn nhau.

## 7. Kết luận

Qua bài tập, em hiểu rõ hơn cách kết hợp HTML5 và CSS3 để xây dựng giao diện website thương mại điện tử. ChatGPT giúp em tham khảo ý tưởng và giải thích kiến thức, nhưng em vẫn cần tự kiểm tra mã nguồn và giao diện để quyết định cách áp dụng phù hợp.

