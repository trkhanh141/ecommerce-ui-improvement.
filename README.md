
# TEELAB – E-commerce UI Improvement

## 1. Giới thiệu dự án

Dự án được thực hiện trong khuôn khổ học phần **Phát triển ứng dụng Web/Thương mại điện tử**, với mục tiêu khảo sát và đề xuất cải tiến giao diện người dùng cho website thương mại điện tử.

Website được lựa chọn để nghiên cứu là [TEELAB](https://teelab.vn/), một thương hiệu thời trang kinh doanh trực tuyến tại Việt Nam.

Dựa trên quá trình khảo sát giao diện website, dự án tập trung cải tiến khu vực **Product Card (thẻ sản phẩm)** trong trang danh mục sản phẩm nhằm nâng cao khả năng hiển thị thông tin, cải thiện trải nghiệm tìm kiếm và hỗ trợ khách hàng tiếp cận sản phẩm thuận tiện hơn.

## 2. Mục tiêu cải tiến

- Tổ chức lại bố cục thông tin trên thẻ sản phẩm.
- Làm nổi bật hình ảnh, tên sản phẩm và giá bán.
- Phân biệt rõ giá gốc, giá khuyến mãi và tỷ lệ giảm giá.
- Bổ sung nút thao tác giúp người dùng dễ dàng tiếp cận thông tin sản phẩm.
- Tối ưu khả năng hiển thị trên máy tính, máy tính bảng và điện thoại.

## 3. Công nghệ sử dụng

| Công nghệ | Mục đích |
|---|---|
| HTML5 | Xây dựng cấu trúc và nội dung trang web |
| CSS3 | Thiết kế giao diện, bố cục và hiệu ứng |
| Google Fonts | Sử dụng phông chữ Be Vietnam Pro |
| Unsplash | Cung cấp hình ảnh minh họa sản phẩm |

## 4. Cấu trúc dự án

```text
ecommerce-ui-improvement/
│
├── index.html       # Cấu trúc trang web
├── style.css        # Định dạng giao diện
├── README.md        # Giới thiệu dự án
├── AI_USAGE.md      # Tài liệu sử dụng AI
└── images/          # Thư mục lưu hình ảnh (nếu sử dụng)
```

## 5. Các nội dung đã triển khai

### 5.1. Header
- Hiển thị logo TEELAB.
- Xây dựng thanh điều hướng.
- Bổ sung biểu tượng tìm kiếm và giỏ hàng.

### 5.2. Khu vực giới thiệu sản phẩm
- Hiển thị tiêu đề và mô tả ngắn.
- Bổ sung đường dẫn điều hướng (breadcrumb).
- Trình bày số lượng sản phẩm minh họa.

### 5.3. Product Card
Mỗi thẻ sản phẩm bao gồm:
- Hình ảnh sản phẩm.
- Tên sản phẩm.
- Giá bán hiện tại.
- Giá gốc được gạch ngang.
- Nhãn hiển thị tỷ lệ giảm giá.
- Nút xem sản phẩm.

### 5.4. Responsive Design
Giao diện được thiết kế thích ứng với nhiều kích thước màn hình:
- Desktop: 4 cột sản phẩm.
- Tablet: 3 cột sản phẩm.
- Mobile: 2 cột sản phẩm.

## 6. Hướng dẫn sử dụng

**Cách 1: Chạy trực tiếp trên máy tính**

1. Tải hoặc clone repository về máy.
2. Mở thư mục dự án.
3. Mở file `index.html` bằng trình duyệt web.

**Cách 2: Sử dụng Visual Studio Code**

1. Mở thư mục dự án bằng Visual Studio Code.
2. Mở file `index.html`.
3. Chạy trang web bằng trình duyệt hoặc tiện ích Live Server.

## 7. Hỗ trợ từ AI

Trong quá trình thực hiện, ChatGPT được sử dụng để hỗ trợ:
- Phân tích và đề xuất phương án cải tiến giao diện.
- Xây dựng cấu trúc HTML.
- Viết và điều chỉnh mã CSS.
- Hỗ trợ giải thích các thành phần trong mã nguồn.

Chi tiết quá trình sử dụng AI được trình bày trong file [AI_USAGE.md](AI_USAGE.md).

## 8. Phạm vi và lưu ý

Đây là sản phẩm mô phỏng giao diện nhằm minh họa phương án cải tiến Product Card, không phải phiên bản chính thức của website TEELAB.

Thông tin sản phẩm, giá bán và hình ảnh trong giao diện có tính chất minh họa. Các nút thao tác chưa được kết nối với hệ thống quản lý sản phẩm, thanh toán hoặc giỏ hàng thực tế.

---

**Course:** Phát triển ứng dụng Web/Thương mại điện tử  
**Project:** TEELAB E-commerce UI Improvement  
**Technologies:** HTML5, CSS3
