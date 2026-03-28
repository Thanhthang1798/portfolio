# Portfolio — Thắng Nguyễn

Trang portfolio tĩnh (HTML + Bootstrap + Alpine.js). Có thể host miễn phí qua **GitHub Pages**.

## Đưa lên GitHub

1. Tạo repository mới trên GitHub (**không** tick “Add a README” để tránh conflict).
2. Trong thư mục project, chạy (thay `USER` và `REPO`):

```bash
git remote add origin https://github.com/USER/REPO.git
git branch -M main
git push -u origin main
```

## Bật GitHub Pages

1. Vào repo trên GitHub → **Settings** → **Pages**.
2. **Build and deployment**: Source = **Deploy from a branch**.
3. Branch = **main**, folder = **/ (root)** → Save.
4. Sau vài phút, site có dạng: `https://USER.github.io/REPO/` (hoặc URL GitHub hiển thị trong Pages).

## Gắn vào “GitHub profile”

- **Cách 1:** Trong repo đặc biệt `github.com/USER/USER`, sửa README profile và thêm dòng kiểu:  
  `[Portfolio](https://USER.github.io/REPO/)`
- **Cách 2:** Ở trang GitHub → **Settings** → **Public profile** → **Social accounts** / bio → dán link Pages.

## Ảnh đại diện

File: `image/avatar.jpg` — thay bằng ảnh của bạn (giữ tên hoặc cập nhật `src` trong `index.html`).
