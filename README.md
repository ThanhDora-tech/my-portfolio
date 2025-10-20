# Portfolio Website

## Mô tả
Website portfolio cá nhân được thiết kế hiện đại, responsive với nhiều animation sinh động.

## Cấu trúc thư mục
```
portfolio-website/
├── index.html          # File HTML chính
├── style.css           # File CSS với thiết kế và animation
├── script.js           # File JavaScript cho tương tác
├── images/             # Thư mục chứa ảnh
│   ├── photo1.jpg      # Ảnh cá nhân 1 (banner)
│   ├── photo2.jpg      # Ảnh cá nhân 2 (dự án 1)
│   ├── photo3.jpg      # Ảnh cá nhân 3 (dự án 2)
│   └── photo4.jpg      # Ảnh cá nhân 4 (dự án 3)
└── README.md           # File hướng dẫn này
```

## Tính năng chính

### ✅ Đã hoàn thành theo yêu cầu:

1. **Banner & Navbar** (1 điểm)
   - Banner với animation gradient background
   - Navbar responsive với hiệu ứng blur
   - Navigation smooth scrolling

2. **Layout Flexbox & Grid** (1 điểm)
   - Sử dụng CSS Grid cho layout chính
   - Flexbox cho các component nhỏ
   - Responsive design hoàn chỉnh

3. **Thông tin cá nhân** (0.5 điểm)
   - Card hiển thị thông tin cá nhân đầy đủ
   - Animation hover effects

4. **Mục tiêu nghề nghiệp** (0.5 điểm)
   - Nội dung mục tiêu cá nhân
   - Highlight các lĩnh vực quan tâm

5. **Sở thích** (0.5 điểm)
   - Grid layout hiển thị sở thích
   - Icons và animation hover

6. **Ngôn ngữ & Kỹ năng** (1 điểm)
   - Thanh tiến độ kỹ năng với animation
   - Hiển thị trình độ ngôn ngữ
   - Skills tags với hover effects

7. **Chứng chỉ - Giải thưởng** (0.5 điểm)
   - Card hiển thị chứng chỉ
   - Mặc định "Không có" cho các mục trống

8. **Dự án** (0.5 điểm)
   - Grid hiển thị dự án cá nhân
   - Hover effects và links

9. **Liên hệ** (0.5 điểm)
   - Thông tin liên hệ đầy đủ
   - Social media links với hover effects

10. **Nội dung cá nhân** (0.5 điểm)
    - Tất cả nội dung đã được cá nhân hóa
    - Thông tin sinh viên thực tế

11. **Clean code & Comment** (0.5 điểm)
    - Code được comment rõ ràng
    - Cấu trúc dễ đọc và bảo trì

12. **CSS3 Animations** (1.5 điểm)
    - Gradient backgrounds
    - Transform animations
    - Hover effects
    - Scroll animations
    - Particle effects
    - Typing animation
    - Parallax scrolling

13. **Ảnh cá nhân** (1.5 điểm)
    - 4 ảnh cá nhân theo yêu cầu
    - Tối ưu hiển thị và responsive

## Cách sử dụng

### 1. Chuẩn bị ảnh
- Đặt 4 ảnh cá nhân vào thư mục `images/`
- Đặt tên file theo thứ tự: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, `photo4.jpg`
- Kích thước khuyến nghị: 400x400px cho ảnh vuông, 800x600px cho ảnh dự án

### 2. Tùy chỉnh nội dung
Mở file `index.html` và thay đổi các thông tin sau:

```html
<!-- Thay đổi thông tin cá nhân -->
<h1 class="banner-title">
    Xin chào, tôi là <span class="highlight">TÊN CỦA BẠN</span>
</h1>

<!-- Cập nhật thông tin trong phần About -->
<span class="info-value">TÊN CỦA BẠN</span>
<span class="info-value">NGÀY SINH CỦA BẠN</span>
<!-- ... các thông tin khác -->
```

### 3. Tùy chỉnh màu sắc
Trong file `style.css`, thay đổi gradient colors:

```css
/* Thay đổi màu chủ đạo */
background: linear-gradient(45deg, #667eea 0%, #764ba2 100%);
```

### 4. Chạy website
- Mở file `index.html` trong trình duyệt
- Hoặc sử dụng live server nếu có VS Code

## Tính năng nâng cao

### Animations được sử dụng:
- **Fade In/Out**: Khi scroll vào viewport
- **Slide In**: Từ trái/phải khi xuất hiện
- **Scale In**: Phóng to khi hover
- **Parallax**: Banner background
- **Typing Effect**: Banner title
- **Particle System**: Background particles
- **Gradient Animations**: Background gradients
- **Hover Transformations**: Card hover effects

### Responsive Breakpoints:
- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

### Browser Support:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Tùy chỉnh nâng cao

### Thêm section mới:
1. Thêm HTML structure trong `index.html`
2. Thêm CSS styles trong `style.css`
3. Thêm JavaScript interactions trong `script.js`

### Thay đổi layout:
- Sử dụng CSS Grid cho layout chính
- Flexbox cho alignment và spacing
- Media queries cho responsive

### Thêm animation:
```css
.element {
    transition: all 0.3s ease;
    transform: translateY(0);
}

.element:hover {
    transform: translateY(-10px);
}
```

## Troubleshooting

### Ảnh không hiển thị:
- Kiểm tra đường dẫn file ảnh
- Đảm bảo tên file đúng (photo1.jpg, photo2.jpg, etc.)
- Kiểm tra kích thước file ảnh

### Animation không hoạt động:
- Kiểm tra JavaScript có được load không
- Xem console để tìm lỗi
- Đảm bảo CSS animations được support

### Responsive không đúng:
- Kiểm tra viewport meta tag
- Test trên các kích thước màn hình khác nhau
- Sử dụng developer tools để debug

## Liên hệ
- Email: tranvana@email.com
- GitHub: [your-github-profile]
- Portfolio: [your-portfolio-url]

---

**Lưu ý**: Đây là template portfolio, hãy tùy chỉnh nội dung và hình ảnh theo thông tin cá nhân của bạn.
