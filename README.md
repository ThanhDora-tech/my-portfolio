# 🚀 Portfolio Space Theme - Đào Quốc Thanh

## 📋 Tổng quan dự án
Portfolio cá nhân với theme không gian hiện đại, được thiết kế responsive và sử dụng CSS-only animations.

## 🎨 Design System

### Color Scheme
- **Primary Colors**: 
  - `#00bfff` (Deep Sky Blue) - Màu chủ đạo
  - `#00ffff` (Cyan) - Màu accent
  - `#0080ff` (Dodger Blue) - Màu phụ
- **Background**: Radial gradient từ `#1b2735` → `#090a0f`
- **Text**: `#ffffff` (White) cho primary text, `#a0d8ff` (Light Blue) cho secondary text

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

## 📁 Cấu trúc file

```
portfolio/
├── index.html          # File HTML chính
├── style.css           # File CSS với space theme
├── Image/              # Thư mục chứa ảnh cá nhân
│   ├── ảnh 1.jpg      # Ảnh banner
│   ├── ảnh 2.jpg      # Ảnh About Me
│   ├── ảnh 3.jpg      # Ảnh Skills
│   └── ảnh 4.jpg      # Ảnh Projects
└── README.md           # File hướng dẫn này
```

## 🎯 Các sections chính

### 1. **Navigation Bar**
- Fixed position với glass morphism effect
- Responsive mobile menu
- Smooth scroll navigation

### 2. **Banner Section**
- Hero section với thông tin giới thiệu
- Ảnh cá nhân với glow effects
- Call-to-action buttons

### 3. **About Section**
- Thông tin cá nhân chi tiết
- Mục tiêu nghề nghiệp
- Sở thích cá nhân

### 4. **Skills Section**
- Ngôn ngữ (Tiếng Việt, Tiếng Anh)
- Kỹ năng lập trình (HTML, CSS, JavaScript, Java, MySQL)
- Kỹ năng khác (Git, Figma, Teamwork, etc.)

### 5. **Certificates Section**
- Chứng chỉ và giải thưởng (hiện tại: "Không có")

### 6. **Projects Section**
- 3 dự án chính:
  - Website Portfolio
  - Website Lớp học trực tuyến
  - Phần mềm Quản lý Bảo dưỡng Xe điện

### 7. **Contact Section**
- Thông tin liên hệ
- Social media links (Facebook, Instagram, GitHub)

## 🎭 Animation System

### Keyframe Animations
- `twinkle` - Nhấp nháy sao
- `nebulaFloat` - Chuyển động tinh vân
- `spaceGlow` - Hiệu ứng phát sáng
- `spacePulse` - Nhịp đập không gian
- `cardFloat` - Cards bay lơ lửng
- `skillsGlow` - Skills phát sáng
- `projectBounce` - Projects nhảy
- `socialBounce` - Social links nhảy

### Hover Effects
- Scale, rotate, translateY transforms
- Box-shadow và border-color changes
- Smooth transitions với cubic-bezier easing

## 📱 Responsive Design

### Breakpoints
- **Desktop**: > 768px
- **Tablet**: ≤ 768px
- **Mobile**: ≤ 480px

### Mobile Optimizations
- Hamburger menu
- Reduced font sizes
- Optimized spacing
- Touch-friendly interactions

## 🛠️ Technical Features

### CSS Features
- CSS Grid & Flexbox layouts
- CSS Custom Properties (variables)
- Backdrop-filter cho glass morphism
- CSS-only animations và transitions
- Smooth scroll behavior

### Performance
- Optimized images
- Efficient CSS selectors
- Minimal dependencies (chỉ Font Awesome & Google Fonts)

## 🎨 Customization

### Thay đổi màu sắc
Chỉnh sửa các biến màu trong `style.css`:
```css
/* Primary colors */
#00bfff  /* Deep Sky Blue */
#00ffff  /* Cyan */
#0080ff  /* Dodger Blue */

/* Background */
#1b2735 → #090a0f  /* Radial gradient */
```

### Thêm sections mới
1. Thêm HTML structure trong `index.html`
2. Thêm CSS styling trong `style.css`
3. Thêm responsive breakpoints nếu cần

## 🚀 Deployment

1. Upload tất cả files lên web server
2. Đảm bảo thư mục `Image/` có đủ 4 ảnh
3. Test responsive trên các thiết bị khác nhau

## 📞 Liên hệ

- **Email**: thanhdq1647@ut.edu.vn
- **Phone**: 0385433474
- **Facebook**: [Đào Quốc Thanh](https://www.facebook.com/aoquocthanh.841561)
- **GitHub**: [ThanhDora-tech](https://github.com/ThanhDora-tech)
- **Instagram**: [_thanh.hh](https://www.instagram.com/_thanh.hh/)

---

*Portfolio được thiết kế với ❤️ bởi Đào Quốc Thanh*
