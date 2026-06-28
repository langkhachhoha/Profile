# Ha Hieu - Personal Profile Website

Trang web profile cá nhân với thiết kế gọn gàng, chuyên nghiệp theo phong cách academic portfolio.

## 🎨 Thiết Kế

- **Layout**: Sidebar bên trái với navigation, content area bên phải
- **Style**: Clean, minimalist, professional
- **Responsive**: Tự động điều chỉnh trên mobile, tablet, desktop
- **Sections**: About me, Research Interests, News, Publications, Experience

## 📁 Cấu Trúc File

```
PROFILE/
├── index.html          # File HTML chính
├── style.css           # File CSS cho giao diện
├── script.js           # JavaScript cho navigation
├── README.md           # File này
└── DEPLOY_GUIDE.md     # Hướng dẫn deploy
```

## 🚀 Cách Sử Dụng

### 1. Xem Local

Mở file `index.html` trong trình duyệt để xem trang web.

### 2. Cập Nhật Thông Tin Cá Nhân

Mở file `index.html` và thay đổi các thông tin sau:

#### Sidebar:
- **Ảnh đại diện**: Dòng 17, thay `https://via.placeholder.com/200` bằng đường dẫn ảnh của bạn
- **Tên**: Dòng 18, thay "Ha Hieu"
- **Chức danh**: Dòng 19, thay "Software Engineer"
- **Địa điểm**: Dòng 26
- **Social links**: Dòng 28-31

#### About Me Section (Dòng 54-64):
Viết giới thiệu về bản thân, học vấn, kinh nghiệm.

#### Research Interests Section (Dòng 67-86):
Liệt kê các lĩnh vực nghiên cứu hoặc chuyên môn của bạn.

#### News Section (Dòng 89-107):
Thêm các tin tức, thành tích, giải thưởng mới nhất.

#### Publications Section (Dòng 110-155):
Thêm các bài báo, công trình xuất bản của bạn.

#### Experience Section (Dòng 158-190):
Liệt kê kinh nghiệm làm việc của bạn.

### 3. Thêm Ảnh Đại Diện

1. Chuẩn bị ảnh của bạn (ảnh vuông, tối thiểu 400x400px)
2. Đổi tên ảnh thành `profile.jpg` hoặc `profile.png`
3. Copy ảnh vào folder PROFILE
4. Trong `index.html`, dòng 17, thay:
   ```html
   <img src="https://via.placeholder.com/200" alt="Ha Hieu" class="profile-image">
   ```
   Thành:
   ```html
   <img src="profile.jpg" alt="Ha Hieu" class="profile-image">
   ```

## 🎨 Tùy Chỉnh Màu Sắc

Mở file `style.css` và sửa các biến trong phần `:root` (dòng 9-17):

```css
:root {
    --primary-color: #2c3e50;      /* Màu chữ chính */
    --secondary-color: #3498db;    /* Màu highlight (xanh) */
    --text-color: #333;            /* Màu chữ thường */
    --light-text: #666;            /* Màu chữ nhạt */
    --border-color: #e1e4e8;       /* Màu viền */
    --bg-color: #fff;              /* Màu nền chính */
    --sidebar-bg: #f8f9fa;         /* Màu nền sidebar */
}
```

## 🌐 Deploy Lên GitHub Pages

### Trang web đã được push lên GitHub!

- **Repository**: https://github.com/langkhachhoha/Profile
- **Trang web sẽ online tại**: https://langkhachhoha.github.io/Profile/

### Để bật GitHub Pages:

1. Vào: https://github.com/langkhachhoha/Profile/settings/pages
2. Trong **"Build and deployment"**:
   - **Source**: Chọn "GitHub Actions"
3. Đợi 1-2 phút
4. Trang web sẽ online!

**Hoặc xem hướng dẫn chi tiết trong file `DEPLOY_GUIDE.md`**

## 📱 Responsive Design

Trang web tự động điều chỉnh trên:
- 💻 Desktop: Sidebar bên trái, content bên phải
- 📱 Tablet: Sidebar nhỏ hơn
- 📱 Mobile: Sidebar chuyển lên trên, content xuống dưới

## ✨ Tính Năng

- ✅ Sidebar navigation với highlight active section
- ✅ Smooth scrolling giữa các section
- ✅ Clean, minimalist design
- ✅ Professional academic portfolio style
- ✅ Fully responsive
- ✅ Easy to customize

## 🔄 Cập Nhật Trang Web

Sau khi chỉnh sửa nội dung, chạy các lệnh sau để cập nhật lên GitHub:

```bash
git add .
git commit -m "Update profile content"
git push
```

Đợi 1-2 phút, trang web sẽ tự động cập nhật!

## 📝 Checklist

- [ ] Đã thay đổi tên và chức danh
- [ ] Đã thêm ảnh đại diện
- [ ] Đã cập nhật phần About Me
- [ ] Đã điền Research Interests / Skills
- [ ] Đã thêm News / Achievements
- [ ] Đã thêm Publications / Projects
- [ ] Đã thêm Experience
- [ ] Đã cập nhật social links
- [ ] Đã bật GitHub Pages
- [ ] Đã kiểm tra trên mobile

## 🆘 Hỗ Trợ

Nếu cần thay đổi thêm:
- Thêm/bớt sections
- Đổi màu sắc
- Thay đổi layout
- Thêm tính năng mới

Hãy cho tôi biết!

---

**Trang web của bạn đang online tại: https://langkhachhoha.github.io/Profile/**

Chúc bạn thành công! 🚀
