# 🚀 NVĐ Portfolio — Nguyễn Việt Đức

## 📁 Cấu trúc thư mục

```
nvd-portfolio/
├── index.html              ← File web chính
├── favicon.ico             ← Icon tab trình duyệt (tự thêm)
├── cv/
│   └── cv.pdf              ← CV của bạn (đặt vào đây)
└── images/
    ├── avatar/
    │   └── avatar.jpg      ← Ảnh đại diện hero (đã có)
    ├── gallery/
    │   ├── photo_1.jpg     ← Ảnh gallery (thay bằng ảnh thật)
    │   ├── photo_2.jpg
    │   ├── photo_3.jpg
    │   ├── photo_4.jpg
    │   ├── photo_5.jpg
    │   └── photo_6.jpg
    └── projects/
        ├── project1.jpg    ← Ảnh dự án 1
        └── project2.jpg    ← Ảnh dự án 2
```

---

## 📸 Cách thêm / đổi ảnh

### Đổi ảnh đại diện (hero)
1. Bỏ ảnh vào `images/avatar/`
2. Đặt tên `avatar.jpg` (hoặc đổi tên trong `index.html` dòng có `#char-sprite`)

### Thêm ảnh gallery
1. Bỏ ảnh `.jpg` / `.png` vào `images/gallery/`
2. Mở `index.html`, tìm `<!-- ═══════════ GALLERY ═══════════ -->`
3. Thêm block sau vào trong `<div class="gallery-grid">`:
```html
<div class="gallery-item" onclick="openLightbox(this)">
  <img src="images/gallery/TÊN_FILE.jpg" alt="Mô tả" loading="lazy"/>
  <div class="gallery-overlay"><span>Xem ảnh</span></div>
</div>
```

### Đổi ảnh dự án
- Thay file trong `images/projects/project1.jpg` và `project2.jpg`

### Thêm CV
- Đặt file PDF vào `cv/cv.pdf`

---

## 🌐 Deploy lên GitHub Pages

1. Tạo repo GitHub (VD: `username.github.io` hoặc `portfolio`)
2. Push toàn bộ thư mục lên repo
3. Vào repo → **Settings** → **Pages**
4. Source: chọn **main branch** → **/ (root)**
5. Save → web live sau ~1 phút tại `https://username.github.io`

---

## ✏️ Chỉnh thông tin cá nhân

Tìm và sửa trong `index.html`:
- **Tên / tagline**: tìm `NGUYỄN VIỆT ĐỨC`
- **Email**: tìm `nguyenvietduc@email.com`
- **Zalo / Facebook / Instagram**: tìm `social-link`
- **Stats số liệu**: tìm `stat-item`
- **Timeline**: tìm `timeline-item`
- **Dự án links**: tìm `project-links`

---

*Portfolio by Nguyễn Việt Đức — 2025*
