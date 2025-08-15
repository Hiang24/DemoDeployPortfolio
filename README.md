# Portfolio Website

Một portfolio website hiện đại được tạo bằng HTML, CSS và JavaScript với tone màu cam và trắng.

## 🎨 Tính năng

- **Thiết kế responsive** - Tương thích với mọi thiết bị
- **Tone màu cam và trắng** - Thiết kế ấm áp và chuyên nghiệp
- **Animations mượt mà** - Hiệu ứng chuyển động đẹp mắt
- **Navigation cố định** - Menu điều hướng luôn hiển thị
- **Smooth scrolling** - Cuộn trang mượt mà
- **Mobile menu** - Menu hamburger cho thiết bị di động
- **Form liên hệ** - Form gửi tin nhắn với validation
- **Skill bars** - Hiển thị mức độ kỹ năng với animation
- **Project showcase** - Trưng bày các dự án
- **Social links** - Liên kết mạng xã hội

## 📁 Cấu trúc file

```
Portfolio/
├── index.html          # File HTML chính
├── styles.css          # File CSS với thiết kế
├── script.js           # File JavaScript với tương tác
└── README.md           # Hướng dẫn sử dụng
```

## 🚀 Cách sử dụng

1. **Mở file `index.html`** trong trình duyệt web
2. Hoặc sử dụng live server để chạy local:

   ```bash
   # Nếu có Python
   python -m http.server 8000

   # Nếu có Node.js
   npx live-server
   ```

## 🎯 Các section chính

### 1. Hero Section

- Giới thiệu bản thân
- Call-to-action buttons
- Avatar với animation float

### 2. About Section

- Thông tin về bản thân
- Thống kê (kinh nghiệm, dự án, khách hàng)
- Avatar với animation pulse

### 3. Skills Section

- Hiển thị các kỹ năng với icon
- Progress bars với animation
- Hover effects

### 4. Projects Section

- Showcase các dự án
- Technology tags
- Links đến demo và code

### 5. Contact Section

- Thông tin liên hệ
- Form gửi tin nhắn
- Social media links

## 🎨 Tùy chỉnh

### Thay đổi màu sắc

Chỉnh sửa các biến CSS trong file `styles.css`:

```css
:root {
  --primary-color: #ff6b35; /* Màu cam chính */
  --primary-dark: #e55a2b; /* Màu cam đậm */
  --primary-light: #ff8c5a; /* Màu cam nhạt */
  --secondary-color: #ffffff; /* Màu trắng */
  /* ... */
}
```

### Thay đổi nội dung

- Cập nhật thông tin cá nhân trong `index.html`
- Thay đổi các dự án trong section Projects
- Cập nhật thông tin liên hệ

### Thêm dự án mới

Thêm vào section Projects:

```html
<div class="project-card">
  <div class="project-image">
    <i class="fas fa-[icon-name]"></i>
  </div>
  <div class="project-content">
    <h3>Tên dự án</h3>
    <p>Mô tả dự án</p>
    <div class="project-tech">
      <span>React</span>
      <span>Node.js</span>
    </div>
    <div class="project-links">
      <a href="#" class="btn btn-small">Live Demo</a>
      <a href="#" class="btn btn-small btn-outline">Code</a>
    </div>
  </div>
</div>
```

## 📱 Responsive Design

Website được thiết kế responsive với các breakpoints:

- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🎭 Animations

- **Float animation** cho hero avatar
- **Pulse animation** cho about avatar
- **Fade-in-up** cho các elements
- **Skill bar animation** khi scroll
- **Counter animation** cho statistics
- **Typing effect** cho hero title
- **Ripple effect** cho buttons

## 🔧 JavaScript Features

- Mobile menu toggle
- Smooth scrolling
- Active navigation highlighting
- Form validation
- Notification system
- Parallax effects
- Intersection Observer animations

## 📧 Form Contact

Form liên hệ bao gồm:

- Validation email
- Required fields check
- Success/error notifications
- Auto-reset sau khi gửi

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📝 License

MIT License - Tự do sử dụng và chỉnh sửa.

## 🤝 Contributing

Nếu bạn muốn đóng góp:

1. Fork project
2. Tạo feature branch
3. Commit changes
4. Push to branch
5. Tạo Pull Request

---

**Tạo bởi với ❤️ và ☕**
