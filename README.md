# Ha Hieu - Personal Profile Website

Trang web profile cá nhân với layout giống hệt https://daotranbk.github.io/

## 📐 Layout

- **Navigation bar**: Ngang ở trên cùng với các links
- **Header**: Ảnh tròn bên trái, tên và thông tin bên phải
- **Content sections**: Biography, News, Publications, Honors and Awards, Educations, Experiences
- **Footer**: Đơn giản với đường kẻ ngang

## 📁 Cấu Trúc File

```
PROFILE/
├── index.html          # File HTML chính
├── style.css           # File CSS cho giao diện
├── script.js           # JavaScript cho navigation
├── README.md           # File này
└── DEPLOY_GUIDE.md     # Hướng dẫn deploy
```

## 🎯 Cập Nhật Thông Tin

### 1. Header (Dòng 34-49)

Thay đổi:
- **Ảnh**: Dòng 35 - `<img src="https://via.placeholder.com/200"` → thay bằng đường dẫn ảnh của bạn
- **Tên**: Dòng 39 - `<h1 class="profile-name">Ha Hieu</h1>`
- **Chức danh**: Dòng 41 - `<li>Software Engineer / AI Researcher</li>`
- **Địa điểm**: Dòng 42 - `<li>Hanoi, Vietnam</li>`
- **Social links**: Dòng 43-48

### 2. Biography (Dòng 54-59)

Viết lại phần giới thiệu về bản thân:
- Vị trí hiện tại
- Học vấn
- Lĩnh vực quan tâm
- Mục tiêu nghiên cứu

### 3. News (Dòng 62-70)

Format:
```html
<li><em>2025.07</em>: 🏆 <strong>Giải thưởng</strong> tại <strong>Hội nghị</strong> (<em>rank A</em>)!!</li>
```

### 4. Publications (Dòng 73-103)

Có 3 subsections:
- **Conferences** (Dòng 76-82)
- **Journals** (Dòng 84-91)
- **Preprints** (Dòng 93-98)

Format:
```html
<li>Paper Title, by <strong>Ha Hieu</strong>, Co-Author, Conference (<em>Abbreviation 2025</em>)</li>
```

### 5. Honors and Awards (Dòng 106-121)

Format:
```html
<li><em>2025</em>: <strong>Giải thưởng</strong> - Tên hội nghị/tổ chức</li>
```

### 6. Educations (Dòng 124-128)

Format:
```html
<li><em>2022.01 - 2023.10</em>: Bằng cấp tại Trường đại học.</li>
```

### 7. Experiences (Dòng 131-137)

Format:
```html
<li><em>2022.09 - present</em>: Vị trí tại Công ty</li>
```

## 📸 Thêm Ảnh Đại Diện

### Cách 1: Dùng ảnh local
1. Đặt ảnh của bạn (ảnh vuông, tối thiểu 400x400px) vào folder PROFILE
2. Đặt tên: `profile.jpg` hoặc `profile.png`
3. Trong `index.html` dòng 35, thay:
   ```html
   <img src="profile.jpg" alt="Ha Hieu" class="profile-photo">
   ```

### Cách 2: Dùng link online
Upload ảnh lên GitHub hoặc dịch vụ khác, rồi dùng link trực tiếp.

## 🎨 Tùy Chỉnh Màu Sắc

Mở `style.css` và sửa dòng 9-17:

```css
:root {
    --primary-color: #2c3e50;      /* Màu tiêu đề */
    --text-color: #333;            /* Màu chữ */
    --light-text: #666;            /* Màu chữ nhạt */
    --bg-color: #fff;              /* Màu nền */
    --link-color: #0366d6;         /* Màu link */
    --link-hover: #0056b3;         /* Màu link khi hover */
}
```

## 🌐 Deploy Lên GitHub Pages

### Trang web đã được push lên GitHub!

- **Repository**: https://github.com/langkhachhoha/Profile
- **Trang web sẽ online tại**: https://langkhachhoha.github.io/Profile/

### Để bật GitHub Pages:

**Option 1: GitHub Actions (Đã setup sẵn)**
1. Vào: https://github.com/langkhachhoha/Profile/settings/pages
2. Trong **"Source"**: Chọn "**GitHub Actions**"
3. Vào tab Actions: https://github.com/langkhachhoha/Profile/actions
4. Đợi workflow chạy xong (màu xanh ✅)
5. Trang web sẽ online!

**Option 2: Deploy from branch**
1. Vào: https://github.com/langkhachhoha/Profile/settings/pages
2. Trong **"Source"**: Chọn "Deploy from a branch"
3. **Branch**: Chọn `main`
4. **Folder**: Chọn `/ (root)`
5. Click **Save**
6. Đợi 1-2 phút

## 🔄 Cập Nhật Trang Web

Sau khi chỉnh sửa nội dung:

```bash
git add .
git commit -m "Update profile information"
git push
```

Đợi 1-2 phút, trang web tự động cập nhật!

## 📱 Responsive Design

- 💻 **Desktop**: Layout đầy đủ với ảnh bên trái, thông tin bên phải
- 📱 **Tablet**: Giảm kích thước, layout vẫn ngang
- 📱 **Mobile**: Ảnh và thông tin xếp dọc, navigation menu dọc

## ✅ Checklist

- [ ] Đã thay đổi tên và chức danh
- [ ] Đã thêm ảnh đại diện
- [ ] Đã cập nhật Biography
- [ ] Đã thêm News
- [ ] Đã thêm Publications (Conferences, Journals, Preprints)
- [ ] Đã thêm Honors and Awards
- [ ] Đã thêm Educations
- [ ] Đã thêm Experiences
- [ ] Đã cập nhật social links
- [ ] Đã bật GitHub Pages
- [ ] Đã kiểm tra trên mobile

## 🔗 Links

- **GitHub Repository**: https://github.com/langkhachhoha/Profile
- **Website**: https://langkhachhoha.github.io/Profile/ (sau khi bật Pages)
- **Template based on**: https://daotranbk.github.io/

---

**Chúc bạn thành công! 🚀**
