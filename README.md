# Trang Web Profile Cá Nhân

Đây là template trang web profile cá nhân được thiết kế theo mẫu trang web học thuật chuyên nghiệp.

## 📁 Cấu Trúc File

```
PROFILE/
├── index.html       # File HTML chính
├── style.css        # File CSS cho giao diện
└── README.md        # Hướng dẫn sử dụng
```

## 🚀 Cách Sử Dụng

### 1. Mở File trong Trình Duyệt

Chỉ cần double-click vào file `index.html` để mở trang web trong trình duyệt của bạn.

### 2. Tùy Chỉnh Thông Tin Cá Nhân

Mở file `index.html` và thay đổi các thông tin sau:

#### Thông Tin Header:
- **Ảnh đại diện**: Thay thế `https://via.placeholder.com/200` bằng đường dẫn ảnh của bạn
- **Tên**: Thay "Your Full Name" bằng tên của bạn
- **Chức danh**: Thay "AI Researcher / Software Engineer" bằng chức danh của bạn
- **Địa điểm**: Cập nhật địa điểm của bạn
- **Liên kết mạng xã hội**: Thêm links đến email, ResearchGate, LinkedIn, Github, Google Scholar của bạn

#### Biography:
Viết lại phần giới thiệu về bản thân, bao gồm:
- Vị trí công việc hiện tại
- Bằng cấp và trường học
- Lĩnh vực nghiên cứu và sở thích
- Mục tiêu nghiên cứu hiện tại

#### News:
Thêm các tin tức mới nhất về thành tích, bài báo được chấp nhận, giải thưởng, v.v.

#### Publications:
Liệt kê các công trình xuất bản của bạn, bao gồm:
- **Conferences**: Các bài báo hội nghị
- **Journals**: Các bài báo tạp chí
- **Preprints**: Các bản thảo đang xem xét

#### Honors and Awards:
Liệt kê các giải thưởng và danh hiệu của bạn theo thứ tự thời gian ngược

#### Educations:
Thêm thông tin về học vấn của bạn (bằng cấp, trường, thời gian)

#### Experiences:
Liệt kê kinh nghiệm làm việc và nghiên cứu của bạn

## 🎨 Tùy Chỉnh Giao Diện

### Thay Đổi Màu Sắc

Mở file `style.css` và sửa các biến CSS trong phần `:root`:

```css
:root {
    --primary-color: #2c3e50;      /* Màu chính */
    --secondary-color: #3498db;    /* Màu phụ */
    --text-color: #333;            /* Màu chữ */
    --light-text: #666;            /* Màu chữ nhạt */
    --bg-color: #fff;              /* Màu nền */
    --light-bg: #f8f9fa;           /* Màu nền nhạt */
}
```

### Thay Đổi Font Chữ

Trong file `style.css`, tìm dòng:
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
```

Và thay thế bằng font chữ bạn muốn.

## 📱 Responsive Design

Trang web đã được tối ưu cho các thiết bị:
- 💻 Desktop
- 📱 Mobile
- 📱 Tablet

## 🌐 Đưa Trang Web Lên Internet

### Cách 1: GitHub Pages (Miễn Phí)

1. Tạo repository mới trên GitHub
2. Upload các file lên repository
3. Vào Settings → Pages
4. Chọn branch main và folder root
5. Lưu và đợi vài phút
6. Trang web của bạn sẽ có địa chỉ: `https://username.github.io/repository-name`

### Cách 2: Netlify (Miễn Phí)

1. Truy cập [Netlify](https://www.netlify.com/)
2. Kéo thả folder PROFILE vào Netlify
3. Trang web sẽ được deploy tự động

### Cách 3: Vercel (Miễn Phí)

1. Truy cập [Vercel](https://vercel.com/)
2. Import project từ GitHub hoặc upload trực tiếp
3. Deploy tự động

## 💡 Gợi Ý Nâng Cao

### Thêm Ảnh Đại Diện:
1. Chuẩn bị ảnh của bạn (ảnh vuông, tối thiểu 400x400px)
2. Đặt ảnh vào folder PROFILE, ví dụ: `profile.jpg`
3. Trong `index.html`, thay:
   ```html
   <img src="https://via.placeholder.com/200" alt="Profile Photo">
   ```
   Thành:
   ```html
   <img src="profile.jpg" alt="Your Name">
   ```

### Thêm Google Analytics:
Thêm code tracking của Google Analytics vào trước thẻ `</head>` trong file `index.html`

### Thêm Favicon:
1. Tạo file favicon.ico
2. Thêm vào `<head>`:
   ```html
   <link rel="icon" href="favicon.ico" type="image/x-icon">
   ```

## 📝 Checklist Trước Khi Publish

- [ ] Đã thay thế tất cả placeholder text
- [ ] Đã thêm ảnh đại diện
- [ ] Đã cập nhật tất cả links mạng xã hội
- [ ] Đã kiểm tra trên mobile và desktop
- [ ] Đã kiểm tra tất cả các liên kết
- [ ] Đã cập nhật thông tin liên hệ
- [ ] Đã thêm favicon (tùy chọn)

## 🆘 Hỗ Trợ

Nếu bạn gặp vấn đề hoặc cần hỗ trợ, hãy:
1. Kiểm tra lại cú pháp HTML/CSS
2. Kiểm tra Console trong trình duyệt (F12)
3. Đảm bảo tất cả file đều trong cùng folder

## 📄 License

Template này được cung cấp miễn phí để sử dụng cho mục đích cá nhân và thương mại.

---

**Chúc bạn thành công với trang web profile của mình! 🎉**
