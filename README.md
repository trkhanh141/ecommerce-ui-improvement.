
# TEELAB – E-COMMERCE WEBSITE UI

**Bài tập cá nhân Buổi 2 – Phát triển ứng dụng WEB/TMĐT**

## 1. Giới thiệu dự án

Dự án xây dựng và cải tiến giao diện website thương mại điện tử mô phỏng website thời trang TEELAB, sử dụng HTML5 và CSS3.

Bài tập được phát triển tiếp nối từ mã nguồn Buổi 1, tập trung vào việc hoàn thiện cấu trúc giao diện, tổ chức danh sách sản phẩm và cải thiện trải nghiệm hiển thị trên các kích thước màn hình khác nhau.

Thông qua bài tập, người thực hiện vận dụng các kiến thức về HTML5 Semantic, CSS Selector, Box Model, Flexbox, CSS Grid và các hiệu ứng tương tác cơ bản.

| Nội dung | Thông tin |
|---|---|
| Tên dự án | TEELAB – E-commerce Website UI |
| Học phần | Phát triển ứng dụng WEB/TMĐT |
| Giảng viên | TS. Nguyễn Mạnh Tuấn |
| Website tham khảo | [TEELAB](https://teelab.vn/) |
| Ngôn ngữ | HTML5, CSS3 |
| Công cụ phát triển | Visual Studio Code |
| Trình duyệt kiểm tra | Google Chrome |

## 2. Website tham khảo và khu vực thực hiện

Website tham khảo: [https://teelab.vn/](https://teelab.vn/)

Dự án tập trung mô phỏng và cải tiến giao diện danh sách sản phẩm thời trang, bao gồm các khu vực:

- **Header:** Logo, thanh điều hướng và các biểu tượng chức năng.
- **Page Introduction:** Đường dẫn điều hướng, tiêu đề và phần giới thiệu bộ sưu tập.
- **Product Section:** Danh sách bốn sản phẩm thời trang, hình ảnh, giá bán, giá gốc và mức giảm giá.
- **Footer:** Thông tin thương hiệu và liên hệ.

Dự án tập trung vào giao diện tĩnh, chưa triển khai các chức năng xử lý dữ liệu, thanh toán hoặc quản lý giỏ hàng.

## 3. Công nghệ và kỹ thuật sử dụng

### 3.1. HTML5

Sử dụng HTML5 để xây dựng cấu trúc và nội dung website.

Các phần tử semantic được sử dụng:

- `header`: Khu vực đầu trang.
- `nav`: Thanh điều hướng.
- `main`: Nội dung chính.
- `section`: Phân chia các khu vực nội dung.
- `article`: Đại diện cho từng thẻ sản phẩm.
- `footer`: Khu vực cuối trang.

Các phần tử bổ trợ gồm `h1`, `h2`, `h3`, `p`, `a`, `img`, `span` và `del` nhằm tổ chức tiêu đề, nội dung, liên kết, hình ảnh và thông tin giá sản phẩm.

Thuộc tính `alt` được sử dụng để cung cấp nội dung mô tả thay thế cho hình ảnh, hỗ trợ khả năng tiếp cận của website.

### 3.2. CSS3 Selector và Box Model

Sử dụng các loại CSS Selector:

- Element Selector.
- Class Selector.
- Descendant Selector.

Vận dụng Box Model thông qua các thuộc tính:

- `margin`: Khoảng cách bên ngoài phần tử.
- `padding`: Khoảng cách bên trong phần tử.
- `border`: Đường viền phần tử.
- `box-sizing`: Kiểm soát cách tính kích thước phần tử.

### 3.3. Flexbox

Sử dụng Flexbox tại khu vực `.product-info` để sắp xếp thông tin sản phẩm theo chiều dọc.

Các thuộc tính được sử dụng:

- `display: flex`
- `flex-direction: column`
- `justify-content`
- `align-items`
- `gap`
- `flex`

### 3.4. CSS Grid

Sử dụng CSS Grid tại `.product-grid` để tổ chức danh sách sản phẩm thành các cột.

Bố cục được điều chỉnh theo kích thước màn hình:

| Kích thước màn hình | Số cột sản phẩm |
|---|---:|
| Trên 1024 px | 4 cột |
| Từ 769 px đến 1024 px | 3 cột |
| Từ 768 px trở xuống | 2 cột |

### 3.5. Hover, Focus và Transition

Bổ sung các hiệu ứng tương tác:

- Thẻ sản phẩm có hiệu ứng nâng nhẹ khi di chuột.
- Hình ảnh sản phẩm phóng to nhẹ khi hover.
- Liên kết và nút sản phẩm thay đổi màu khi hover.
- Sử dụng `transition` để tạo chuyển động mượt mà.
- Sử dụng `:focus-visible` để thể hiện trạng thái focus khi điều hướng bằng bàn phím.

### 3.6. Responsive Design

Sử dụng Media Queries để điều chỉnh giao diện theo các kích thước màn hình khác nhau.

Các kích thước được lựa chọn để kiểm tra gồm:

- 1366 px.
- 768 px.
- 390 px.

## 4. Cấu trúc thư mục

```text
ecommerce-ui-improvement/
│
├── css/
│   └── style.css
│
├── images/
│
├── index.html
├── README.md
└── AI_USAGE.md
```

| Tệp/thư mục | Chức năng |
|---|---|
| `index.html` | Chứa cấu trúc và nội dung giao diện website |
| `css/style.css` | Chứa các quy tắc định dạng và bố cục giao diện |
| `images/` | Lưu trữ hình ảnh sử dụng trong dự án nếu có |
| `README.md` | Giới thiệu và hướng dẫn sử dụng dự án |
| `AI_USAGE.md` | Ghi nhận quá trình sử dụng công cụ AI |

## 5. Hướng dẫn chạy website

**Yêu cầu:** Máy tính có trình duyệt web và Visual Studio Code.

Các bước thực hiện:

1. Clone repository về máy tính:

   ```bash
   git clone https://github.com/trkhanh141/ecommerce-ui-improvement.git
   ```

2. Mở thư mục dự án bằng Visual Studio Code.
3. Kiểm tra cấu trúc thư mục và đường dẫn liên kết CSS trong `index.html`.
4. Mở tệp `index.html` bằng trình duyệt hoặc sử dụng tiện ích Live Server.
5. Kiểm tra giao diện website trên trình duyệt.

Đường dẫn CSS được sử dụng:

```html
<link rel="stylesheet" href="css/style.css">
```

## 6. Những thay đổi và cải tiến trong Buổi 2

Dự án tiếp tục kế thừa mã nguồn Buổi 1 và thực hiện các nội dung sau:

| STT | Nội dung | Kết quả triển khai |
|---:|---|---|
| 1 | Hoàn thiện cấu trúc HTML5 | Sử dụng các phần tử semantic để tổ chức giao diện |
| 2 | CSS Selector | Áp dụng Element, Class và Descendant Selector |
| 3 | Box Model | Điều chỉnh margin, padding, border và kích thước phần tử |
| 4 | Flexbox | Sắp xếp thông tin bên trong thẻ sản phẩm |
| 5 | CSS Grid | Tổ chức danh sách sản phẩm theo dạng lưới |
| 6 | Hover và Focus | Bổ sung hiệu ứng tương tác và trạng thái focus |
| 7 | Responsive | Điều chỉnh bố cục theo các kích thước màn hình |
| 8 | Kiểm tra và cải tiến | Bổ sung thuộc tính alt cho hình ảnh sản phẩm |

## 7. Kiểm thử giao diện

Website được kiểm tra trên trình duyệt Google Chrome, kết hợp Chrome DevTools để quan sát bố cục tại các kích thước màn hình khác nhau.

### 7.1. Bảng kiểm thử

| STT | Nội dung kiểm tra | Kết quả | Ghi chú |
|---:|---|---|---|
| 1 | Trang HTML mở được | Đạt | Website truy cập được trên trình duyệt |
| 2 | CSS được áp dụng | Đạt | Giao diện hiển thị theo định dạng CSS |
| 3 | Hình ảnh hiển thị đúng | Đạt | Hình ảnh sản phẩm được hiển thị |
| 4 | Liên kết hoạt động | Đạt | Kiểm tra các liên kết trên giao diện |
| 5 | Bố cục không bị tràn nghiêm trọng | Đạt | Kiểm tra các kích thước màn hình |
| 6 | Hover và Focus hoạt động | Đạt | Kiểm tra hiệu ứng chuột và bàn phím |
| 7 | Đã tự sửa ít nhất một vấn đề | Đạt | Bổ sung thuộc tính alt cho hình ảnh sản phẩm |

### 7.2. Vấn đề phát hiện và cách khắc phục

Trong quá trình rà soát mã nguồn HTML, em tập trung kiểm tra các thẻ hình ảnh sản phẩm và nhận thấy cần bổ sung nội dung mô tả thay thế để hình ảnh có thông tin rõ ràng hơn đối với người dùng sử dụng công cụ hỗ trợ đọc màn hình.

- **Vấn đề phát hiện:** Một số thẻ hình ảnh cần được bổ sung nội dung mô tả thay thế phù hợp với sản phẩm.
- **Nguyên nhân:** Thuộc tính `alt` chưa được sử dụng đầy đủ hoặc nội dung mô tả hình ảnh chưa được thể hiện rõ ràng trong mã nguồn.
- **Cách khắc phục:** Bổ sung thuộc tính `alt` vào các thẻ `<img>` trong `index.html`, sử dụng nội dung mô tả tương ứng với từng sản phẩm.
- **Kết quả sau khi sửa:** Các hình ảnh sản phẩm có nội dung mô tả thay thế rõ ràng hơn. Thay đổi không ảnh hưởng đến bố cục hiển thị thông thường của website.

Ví dụ:

```html
<img
    src="..."
    alt="Áo thun oversized graphic màu trắng"
    loading="lazy"
>
```

Thông qua thay đổi này, em hiểu rõ hơn vai trò của thuộc tính `alt` trong HTML5 và tầm quan trọng của việc tự rà soát, điều chỉnh mã nguồn thay vì chỉ áp dụng nguyên trạng các đề xuất từ công cụ AI.

## 8. Sử dụng công cụ AI

**Công cụ hỗ trợ:** ChatGPT.

Công cụ AI được sử dụng trong quá trình tìm hiểu và triển khai HTML5, CSS3, CSS Selector, Box Model, Flexbox, CSS Grid, hiệu ứng hover/focus và hỗ trợ phân tích lỗi giao diện.

AI đóng vai trò công cụ tham khảo và hỗ trợ kỹ thuật. Các đề xuất được đối chiếu với cấu trúc HTML, CSS hiện có và yêu cầu bài tập trước khi áp dụng. Người thực hiện trực tiếp rà soát mã nguồn, lựa chọn những nội dung phù hợp, điều chỉnh mã và kiểm tra kết quả trên trình duyệt.

Các prompt tiêu biểu, mục đích sử dụng và nội dung điều chỉnh được ghi nhận trong tệp `AI_USAGE.md`.

## 9. Repository và website triển khai

- **GitHub Repository:** [ecommerce-ui-improvement](https://github.com/trkhanh141/ecommerce-ui-improvement)
- **Website:** [TEELAB – E-commerce Website UI](https://trkhanh141.github.io/ecommerce-ui-improvement/)

---

**Lưu ý:** Đây là bài tập thực hành giao diện website tĩnh bằng HTML5 và CSS3. Các chức năng tìm kiếm, lọc sản phẩm, sắp xếp giá và giỏ hàng sẽ được xem xét triển khai trong các buổi thực hành tiếp theo.
