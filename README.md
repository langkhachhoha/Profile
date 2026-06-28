# Ha Hieu - Personal Profile Website 🌙

Trang web profile cá nhân với thiết kế **Dark Theme** sang trọng, giống layout của https://daotranbk.github.io/

## 🎨 Dark Theme Design

- **Background**: Tối (#0f0f1e) 
- **Text**: Sáng (#e8e8e8)
- **Accent Color**: Hồng (#e94560)
- **Link Color**: Xanh (#3b82f6)
- **Modern & Professional**: Shadows, borders, và hover effects tinh tế

## 📁 Cấu Trúc File

```
PROFILE/
├── index.html          # File HTML chính
├── style.css           # File CSS Dark Theme
├── script.js           # JavaScript
├── cv.pdf              # File CV của bạn (cần thêm)
└── README.md           # File này
```

## 🚀 Thêm CV của bạn

**Option 1: Upload PDF trực tiếp** (Khuyên dùng)
1. Export CV của bạn ra file PDF
2. Đổi tên thành `cv.pdf`
3. Copy vào folder PROFILE
4. Commit và push lên GitHub

**Option 2: Link CV từ nơi khác**
Mở `index.html` dòng 20, thay đổi:
```html
<li><a href="YOUR_CV_LINK" target="_blank">CV</a></li>
```

## 📝 Cập Nhật Thông Tin

Mở `index.html` và thay đổi:
- **Ảnh**: Dòng 33
- **Tên**: Dòng 36
- **Chức danh**: Dòng 38
- **Social links**: Dòng 40-45
- **Biography**: Dòng 54-58
- **News**: Dòng 64-70
- **Publications**: Dòng 77-101
- **Honors**: Dòng 108-121
- **Experiences**: Dòng 135-140

## 🎨 Tùy Chỉnh Màu

Mở `style.css` dòng 8-21 để đổi màu:

```css
:root {
    --highlight-color: #e94560;  /* Màu highlight */
    --link-color: #3b82f6;       /* Màu link */
    --text-color: #e8e8e8;       /* Màu chữ */
}
```

## 🌐 Deploy Lên GitHub Pages

1. Vào: https://github.com/langkhachhoha/Profile/settings/pages
2. **Source**: Chọn "**GitHub Actions**"
3. Trang web online tại: https://langkhachhoha.github.io/Profile/

## 🔄 Cập Nhật

```bash
git add .
git commit -m "Update profile"
git push
```

## ✨ Tính Năng

- ✅ Dark Theme đẹp mắt
- ✅ CV link download/view
- ✅ Responsive design
- ✅ Icon đầy đủ
- ✅ Smooth scrolling

---

**Trang web Dark Theme của bạn! 🌙✨**
