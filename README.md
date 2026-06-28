# Ha Minh Hieu - Personal Profile Website

Trang web profile cá nhân với thiết kế hiện đại, có **Light/Dark Mode Toggle** 🌓

## ✨ Tính Năng Mới

### 🌓 Light/Dark Mode Toggle
- **Nút toggle** ở góc trên phải để chuyển đổi theme
- Tự động lưu preference vào browser
- Animation mượt mà khi chuyển đổi
- Icon thay đổi: 🌙 (moon) cho light mode, ☀️ (sun) cho dark mode

### 📐 Layout Mới
- **Sidebar trái**: Tên, ảnh, tiểu sử, social links, navigation
- **Main content phải**: Chi tiết về About, Research, News, Publications, Honors
- Responsive: Tự động điều chỉnh trên mobile

### 🎨 Thiết Kế
- **Light Mode**: Nền trắng, chữ đen, sang trọng
- **Dark Mode**: Nền tối, chữ sáng, dễ nhìn ban đêm
- **Accent Color**: Xanh dương (#3b82f6) cho cả 2 theme
- Modern UI với shadows, borders, hover effects

## 📁 Cấu Trúc

```
PROFILE/
├── index.html       # HTML với sidebar layout
├── style.css        # CSS với light/dark theme
├── script.js        # JavaScript cho theme toggle
├── cv.pdf           # CV của bạn
└── README.md        # File này
```

## 🚀 Cách Sử Dụng

### 1. Cập Nhật Thông Tin

Mở `index.html`:

#### Sidebar (Dòng 17-60):
- **Ảnh**: Dòng 18
- **Tên**: Dòng 23 - `Ha Minh Hieu`
- **Chức danh**: Dòng 24
- **Địa điểm**: Dòng 25
- **Bio**: Dòng 29-30
- **Social links**: Dòng 34-40

#### Main Content:
- **About**: Dòng 67-71
- **Research Interest**: Dòng 75-82
- **News**: Dòng 87-92
- **Publications**: Dòng 97-144
- **Honors**: Dòng 147-154

### 2. Thêm Ảnh Đại Diện

1. Đặt ảnh vào folder PROFILE, đặt tên `profile.jpg`
2. Trong `index.html` dòng 18:
   ```html
   <img src="profile.jpg" alt="Ha Minh Hieu" class="profile-image">
   ```

### 3. Thêm CV

**Option 1**: Đặt file PDF tên `cv.pdf` vào folder
**Option 2**: Đổi link trong navigation (dòng 55)

## 🎨 Tùy Chỉnh Theme

Mở `style.css`:

### Light Mode Colors (Dòng 10-18):
```css
:root {
    --bg-primary: #ffffff;        /* Nền chính */
    --text-primary: #2c3e50;      /* Chữ chính */
    --accent-color: #3b82f6;      /* Màu accent */
}
```

### Dark Mode Colors (Dòng 20-29):
```css
[data-theme="dark"] {
    --bg-primary: #0f0f1e;        /* Nền tối */
    --text-primary: #e8e8e8;      /* Chữ sáng */
    --accent-color: #3b82f6;      /* Màu accent */
}
```

## 🌐 Deploy

### GitHub Pages đã được setup!

- **Repository**: https://github.com/langkhachhoha/Profile
- **Website**: https://langkhachhoha.github.io/Profile/

### Để bật Pages:

1. Vào: https://github.com/langkhachhoha/Profile/settings/pages
2. **Source**: Chọn "GitHub Actions"
3. Đợi 1-2 phút

## 📱 Responsive

- **Desktop (>1024px)**: Sidebar 300px trái, content phải
- **Tablet (768-1024px)**: Sidebar 250px
- **Mobile (<768px)**: Sidebar trên, content dưới

## 🔄 Cập Nhật

```bash
git add .
git commit -m "Update profile"
git push
```

## ✨ Highlights

- ✅ **Light/Dark Mode Toggle** với icon thay đổi
- ✅ **Sidebar Layout** với tên và info bên trái
- ✅ **Smooth Animations** khi toggle theme
- ✅ **Auto-save Theme** preference vào localStorage
- ✅ **Responsive Design** hoàn toàn
- ✅ **Active Navigation** highlight khi scroll
- ✅ **Modern UI** với shadows và hover effects

## 🎯 Theme Toggle

**Cách dùng**:
1. Bấm nút ở góc trên phải
2. Theme tự động chuyển đổi
3. Preference được lưu tự động
4. Lần sau vào lại sẽ nhớ theme đã chọn

**Icon**:
- 🌙 Moon icon = Light mode (bấm để chuyển sang Dark)
- ☀️ Sun icon = Dark mode (bấm để chuyển sang Light)

---

**Trang web hiện đại với Light/Dark Mode! 🌓✨**
