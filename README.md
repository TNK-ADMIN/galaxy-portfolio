# 🌌 Galaxy Portfolio - Landing Page Cá Nhân

Một landing page hiện đại với theme galaxy đẹp mắt và responsive để giới thiệu thông tin cá nhân, được thiết kế với nhiều hiệu ứng vũ trụ và tối ưu cho cả điện thoại và máy tính.

## ✨ Tính năng thực tế

### 🎨 Thiết kế & Giao diện
- **Responsive Design**: Tối ưu cho mọi thiết bị (mobile, tablet, desktop)
- **Modern UI/UX**: Giao diện hiện đại với gradient và glassmorphism effects
- **Smooth Animations**: Nhiều hiệu ứng mượt mà và chuyên nghiệp
- **Interactive Elements**: Các phần tử tương tác với hover effects và 3D transforms
- **Galaxy Theme**: Background với hình ảnh vũ trụ và hiệu ứng sao động

### 🎯 Các phần chính
1. **Hero Section**: Giới thiệu bản thân với floating tech icons và parallax scrolling
2. **About Section**: Thông tin chi tiết với thống kê động (counter animation)
3. **Skills Section**: Hiển thị kỹ năng với progress bars animated
4. **Projects Section**: Showcase các dự án với hover effects và overlay
5. **Contact Section**: Form liên hệ và thông tin liên lạc với social links

### 🎪 Hiệu ứng đặc biệt đã implement
- **Parallax Scrolling**: Hiệu ứng cuộn parallax cho hero section
- **Floating Particles**: Hệ thống hạt bay lơ lửng với animation 3D
- **Cosmic Dust**: Hiệu ứng bụi vũ trụ tạo không gian động
- **Typing Animation**: Hiệu ứng gõ chữ cho tiêu đề hero
- **Counter Animation**: Đếm số động cho thống kê trong about section
- **Ripple Effect**: Hiệu ứng gợn sóng khi click buttons
- **Custom Cursor**: Con trỏ chuột tùy chỉnh với 3D rotation
- **Scroll Animations**: Hiệu ứng xuất hiện khi cuộn trang (Intersection Observer)
- **3D Transforms**: Nhiều hiệu ứng 3D cho cards, buttons, và elements
- **Loading Screen**: Màn hình loading với spinner
- **Scroll to Top**: Nút cuộn lên đầu trang với 3D effects
- **Notification System**: Hệ thống thông báo cho form submission

### 📱 Responsive Features
- **Mobile Navigation**: Menu hamburger cho mobile với smooth transitions
- **Touch Friendly**: Tối ưu cho cảm ứng
- **Flexible Grid**: Layout linh hoạt cho mọi kích thước màn hình
- **Optimized Images**: Sử dụng Unsplash images với responsive sizing

## 🛠️ Công nghệ sử dụng

### Frontend Technologies
- **HTML5**: Cấu trúc semantic và accessible
- **CSS3**: 
  - Flexbox & Grid Layout
  - CSS Animations & Transitions với 3D transforms
  - Media Queries cho responsive design
  - CSS Variables cho theming
  - Backdrop Filter cho glassmorphism effects
  - Complex background gradients và image overlays
- **JavaScript (ES6+)**:
  - Intersection Observer API cho scroll animations
  - Smooth Scrolling navigation
  - Event Listeners với throttling cho performance
  - DOM Manipulation
  - Custom particle system
  - Form validation và notification system
  - Performance optimization với requestAnimationFrame

### External Libraries
- **Font Awesome 6.0.0**: Icons cho UI elements
- **Google Fonts (Poppins)**: Typography
- **Unsplash Images**: Background và content images

## 📁 Cấu trúc file

```
├── index.html          # File HTML chính (332 lines)
├── style.css           # File CSS với responsive design (1171 lines)
├── script.js           # File JavaScript với tương tác (593 lines)
└── README.md           # Hướng dẫn sử dụng
```

## 🚀 Cách sử dụng

1. **Tải xuống** tất cả các file
2. **Mở file** `index.html` trong trình duyệt web
3. **Tùy chỉnh** thông tin cá nhân trong file HTML:
   - Thay đổi tên, nghề nghiệp (dòng 39-41)
   - Cập nhật thông tin liên hệ (dòng 271, 280, 289)
   - Thêm/sửa các dự án (section #projects)
   - Thay đổi hình ảnh (cập nhật URL trong src attributes)
   - Cập nhật social media links (dòng 293-296)

## 🎨 Tùy chỉnh

### Thay đổi màu sắc
Trong file `style.css`, tìm và thay đổi các màu chính:
```css
/* Màu chính */
--primary-blue: #78b3ff;
--primary-pink: #ff77c6;
--primary-cyan: #78dbff;

/* Background colors */
background: #0a0a0a; /* Dark background */
```

### Thêm/sửa nội dung
1. **Thông tin cá nhân**: Sửa trong section `#about` (dòng 70-110)
2. **Kỹ năng**: Thêm/sửa trong section `#skills` (dòng 112-188)
3. **Dự án**: Cập nhật trong section `#projects` (dòng 190-254)
4. **Liên hệ**: Sửa thông tin trong section `#contact` (dòng 256-318)

### Thay đổi hình ảnh
Thay thế các URL Unsplash bằng hình ảnh thực:
```html
<!-- Profile image -->
<img src="your-profile-image.jpg" alt="Profile" class="profile-img">

<!-- Background images -->
background: url('your-background-image.jpg')
```

### Tùy chỉnh animations
Trong file `script.js`, bạn có thể điều chỉnh:
- Tốc độ typing animation (dòng 264)
- Số lượng floating particles (dòng 119)
- Tốc độ counter animation (dòng 337)

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## 🎯 Tối ưu hóa Performance

- **Throttled Scroll Events**: Sử dụng throttling cho scroll events (16ms = ~60fps)
- **Intersection Observer**: Hiệu quả cho scroll animations
- **RequestAnimationFrame**: Cho smooth animations
- **CSS Transforms**: Sử dụng GPU acceleration
- **Lazy Loading**: Images được tối ưu với responsive sizing

## 🌟 Tính năng nâng cao đã implement

### JavaScript Features
- **Particle System**: Tạo floating particles và cosmic dust
- **Custom Cursor**: Con trỏ tùy chỉnh với 3D rotation
- **Form Validation**: Kiểm tra form với notification system
- **Scroll to Top**: Nút cuộn với 3D effects
- **Loading Screen**: Màn hình loading tự động
- **Ripple Effects**: Hiệu ứng gợn sóng cho buttons
- **Counter Animation**: Đếm số động cho statistics
- **Typing Effect**: Hiệu ứng gõ chữ cho hero title

### CSS Features
- **3D Transforms**: RotateX, RotateY, Scale effects
- **Backdrop Filter**: Glassmorphism effects
- **Complex Gradients**: Multi-layer background effects
- **Keyframe Animations**: 15+ custom animations
- **CSS Grid & Flexbox**: Modern layout techniques

## 🔧 Browser Support

- Chrome 60+ (full support)
- Firefox 55+ (full support)
- Safari 12+ (full support)
- Edge 79+ (full support)

## 📊 Code Statistics

- **Total Lines**: ~2,096 lines
- **HTML**: 332 lines
- **CSS**: 1,171 lines  
- **JavaScript**: 593 lines
- **Features**: 20+ interactive features
- **Animations**: 15+ keyframe animations

## 🚀 Performance Features

- **Smooth 60fps animations** với throttled scroll events
- **GPU-accelerated transforms** cho 3D effects
- **Optimized particle system** với performance controls
- **Lazy loading** cho images
- **Minimal DOM manipulation** với efficient selectors

## 📄 License

Dự án này được tạo ra cho mục đích học tập và sử dụng cá nhân.

---

**Tác giả**: Landing Page được tạo với ❤️ và nhiều hiệu ứng đẹp mắt!

**Phiên bản**: 1.0.0

**Cập nhật lần cuối**: 2024

**Tính năng đặc biệt**: 
- ✅ 3D transforms và effects
- ✅ Particle system với cosmic dust
- ✅ Custom cursor với mouse tracking
- ✅ Advanced scroll animations
- ✅ Form validation với notifications
- ✅ Performance optimized code