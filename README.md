# Frontend Mentor - News homepage solution

Đây là lời giải của tôi cho thử thách xây dựng trang chủ tin tức từ Frontend Mentor. Dự án này tập trung vào việc xử lý bố cục đáp ứng (Responsive) và các tương tác người dùng cơ bản.

## Overview

### The challenge

Người dùng có thể thực hiện các thao tác sau:
- Xem bố cục tối ưu tùy theo kích thước màn hình thiết bị.
- Thấy trạng thái hover và focus cho các phần tử tương tác như nút, liên kết và tiêu đề bài viết.
- Sử dụng menu điều hướng dạng thanh bên (Sidebar) trên thiết bị di động thông qua nút bấm.

### Links

- **Solution URL**: [Thêm link GitHub của bạn tại đây]
- **Live Site URL**: [Thêm link trang web đã chạy của bạn tại đây]

## My process

### Built with

Dự án này được xây dựng bằng các công cụ sau:
- **Semantic HTML5 markup**: Sử dụng các thẻ ngữ nghĩa để cấu trúc trang web.
- **CSS Grid**: Sử dụng để chia bố cục chính với 3 cột trên Desktop.
- **Flexbox**: Dùng để căn chỉnh các phần tử bên trong menu và danh sách bài viết.
- **Vanilla JavaScript**: Dùng để xử lý logic đóng/mở Mobile Menu.
- **Mobile-first workflow**: Ưu tiên thiết kế cho điện thoại trước khi mở rộng lên màn hình lớn.

### What I learned

Trong quá trình làm việc, tôi đã học được những kỹ thuật quan trọng sau:

- **Quản lý Grid Layout**: Cách điều chỉnh vị trí các khối nội dung khác nhau giữa Desktop và Mobile bằng thuộc tính `grid-template-columns` và `grid-row`.
- **Hiệu ứng Animation**: Tạo hiệu ứng gạch chân (underline) mượt mà cho menu bằng `@keyframes`.
- **Logic Mobile Menu**: Sử dụng sự kiện `change` trên thẻ `<input type="checkbox">` để điều khiển hiển thị danh sách Menu thay vì chỉ dùng nút bấm thông thường.

**Note**: Việc sử dụng `position: sticky` cho phần `header` giúp người dùng luôn tiếp cận được menu khi cuộn trang.

### Code Snippets

Đoạn mã JavaScript mà tôi tâm đắc nhất để xử lý Menu:

```javascript
checkbox.addEventListener('change', function() {
    if (this.checked) {
        navPageMobile.classList.add('active');
    } else {
        navPageMobile.classList.remove('active');
    }
});
```

## Author

- Website - [Hứa Minh Thiện](https://www.your-site.com)
- Frontend Mentor - [@HuaMinhThien](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

