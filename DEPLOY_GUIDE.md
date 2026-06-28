# 🚀 Hướng Dẫn Deploy Trang Web Lên GitHub Pages

## Bước 1: Tạo Repository trên GitHub

### 1.1. Đăng nhập vào GitHub
- Truy cập: https://github.com
- Đăng nhập vào tài khoản của bạn

### 1.2. Tạo Repository Mới
1. Click nút **"+"** ở góc trên bên phải → chọn **"New repository"**
2. Điền thông tin:
   - **Repository name**: `profile` (hoặc tên bạn thích, ví dụ: `my-portfolio`, `personal-website`)
   - **Description**: "My personal profile website"
   - Chọn **Public** (để dùng GitHub Pages miễn phí)
   - **KHÔNG** tick vào "Add a README file"
   - **KHÔNG** tick vào "Add .gitignore"
   - Click **"Create repository"**

3. Sau khi tạo xong, bạn sẽ thấy một trang với hướng dẫn. **GHI CHÚ LẠI** URL repository của bạn, nó sẽ có dạng:
   ```
   https://github.com/[username]/profile.git
   ```

---

## Bước 2: Khởi Tạo Git và Push Code (Chạy Commands)

Mở Terminal trong thư mục PROFILE này và chạy các lệnh sau:

### 2.1. Khởi tạo Git repository
```bash
git init
```

### 2.2. Thêm tất cả files
```bash
git add .
```

### 2.3. Tạo commit đầu tiên
```bash
git commit -m "Initial commit: Add personal profile website"
```

### 2.4. Đổi tên branch sang main (nếu cần)
```bash
git branch -M main
```

### 2.5. Kết nối với GitHub repository
**QUAN TRỌNG**: Thay `[username]` bằng username GitHub của bạn và `profile` bằng tên repository bạn đã tạo

```bash
git remote add origin https://github.com/[username]/profile.git
```

Ví dụ:
```bash
git remote add origin https://github.com/minhhieu/profile.git
```

### 2.6. Push code lên GitHub
```bash
git push -u origin main
```

**Lưu ý**: Nếu lần đầu push, bạn có thể cần nhập username và password (hoặc Personal Access Token) của GitHub.

---

## Bước 3: Cấu Hình GitHub Pages

### 3.1. Vào Settings của Repository
1. Truy cập repository của bạn trên GitHub
2. Click tab **"Settings"** (ở menu trên cùng)

### 3.2. Bật GitHub Pages
1. Ở sidebar bên trái, tìm và click **"Pages"**
2. Trong phần **"Source"**:
   - **Branch**: Chọn `main`
   - **Folder**: Chọn `/ (root)`
   - Click **"Save"**

### 3.3. Đợi Deploy
- GitHub sẽ tự động build và deploy trang web của bạn
- Quá trình này mất khoảng 1-3 phút
- Sau khi xong, bạn sẽ thấy thông báo màu xanh với link trang web:
  ```
  Your site is live at https://[username].github.io/profile/
  ```

### 3.4. Truy Cập Trang Web
- Click vào link hoặc copy paste vào trình duyệt
- Trang web profile của bạn đã online! 🎉

---

## 🔄 Cập Nhật Trang Web Sau Này

Khi bạn muốn thay đổi nội dung trang web:

### Cách 1: Qua Terminal
```bash
# 1. Lưu thay đổi
git add .

# 2. Tạo commit với mô tả thay đổi
git commit -m "Update biography section"

# 3. Push lên GitHub
git push
```

Sau 1-2 phút, trang web sẽ tự động cập nhật!

### Cách 2: Qua GitHub Web Interface
1. Vào repository trên GitHub
2. Click vào file muốn sửa (ví dụ: `index.html`)
3. Click icon bút chì (Edit)
4. Sửa nội dung
5. Kéo xuống, điền commit message
6. Click "Commit changes"

---

## 🎯 Custom Domain (Tùy chọn)

Nếu bạn có tên miền riêng (ví dụ: `yourname.com`):

1. Vào Settings → Pages của repository
2. Trong phần **"Custom domain"**, nhập domain của bạn
3. Cấu hình DNS records tại nhà cung cấp domain:
   ```
   Type: CNAME
   Name: www
   Value: [username].github.io
   ```
4. Đợi 24h để DNS cập nhật

---

## ❗ Xử Lý Lỗi Thường Gặp

### Lỗi: "Permission denied"
- Bạn cần tạo Personal Access Token:
  1. GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
  2. Generate new token → Chọn scope `repo`
  3. Copy token
  4. Khi push, dùng token thay cho password

### Lỗi: "Repository not found"
- Kiểm tra lại URL repository có đúng không
- Kiểm tra bạn đã tạo repository trên GitHub chưa

### Lỗi: "Failed to push"
- Thử: `git pull origin main --rebase` rồi push lại

### Trang web không hiển thị đúng
- Đợi 5-10 phút
- Kiểm tra file `index.html` có đúng tên không (phải là chữ thường)
- Clear cache trình duyệt (Ctrl + F5)

---

## 📋 Checklist

- [ ] Đã tạo repository trên GitHub
- [ ] Đã chạy `git init` trong folder PROFILE
- [ ] Đã chạy `git add .` và `git commit`
- [ ] Đã kết nối với GitHub remote
- [ ] Đã push code lên GitHub
- [ ] Đã bật GitHub Pages trong Settings
- [ ] Đã kiểm tra trang web hoạt động

---

## 🆘 Cần Trợ Giúp?

Nếu gặp vấn đề, hãy:
1. Kiểm tra lại từng bước
2. Đọc thông báo lỗi cẩn thận
3. Google thông báo lỗi (thường có giải pháp)
4. Hoặc hỏi tôi, tôi sẽ giúp bạn!

---

**Chúc bạn deploy thành công! 🚀**
