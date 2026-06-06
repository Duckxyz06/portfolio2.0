# 🚀 NVĐ Portfolio — Nguyễn Việt Đức

## 📁 Cấu trúc thư mục

```
nvd-portfolio/
├── index.html
├── favicon.ico
├── cv/
│   └── cv.pdf                          ← Đặt CV vào đây
└── images/
    ├── avatar/
    │   └── avatar.jpg                  ← Ảnh đại diện hero
    ├── gallery/
    │   ├── manifest.json               ← DANH SÁCH ảnh gallery
    │   ├── anh_cua_toi.jpg             ← Ảnh bất kỳ
    │   └── IMG_2024.png                ← Tên file tuỳ ý
    └── projects/
        ├── manifest.json               ← DANH SÁCH dự án
        ├── project_web.jpg             ← Ảnh dự án
        └── automation.png
```

---

## 📸 Thêm ảnh GALLERY

**Bước 1** — Bỏ ảnh vào `images/gallery/`
Hỗ trợ: `.jpg` `.jpeg` `.png` `.webp` `.gif`

**Bước 2** — Mở `images/gallery/manifest.json`, thêm tên file:
```json
{
  "files": [
    "anh_di_choi.jpg",
    "IMG_0123.png",
    "su-kien-doan.webp"
  ]
}
```

**Bước 3** — Commit & push lên GitHub → web tự cập nhật ✅

---

## 🚀 Thêm DỰ ÁN mới

**Bước 1** — Bỏ ảnh screenshot vào `images/projects/`

**Bước 2** — Mở `images/projects/manifest.json`, thêm entry:
```json
{
  "projects": [
    {
      "image": "project_web.jpg",
      "title": "Tên dự án của tôi",
      "tags": ["Web Dev", "Supabase"],
      "problem": "Vấn đề cần giải quyết.",
      "solution": "Giải pháp đã thực hiện.",
      "result": "Kết quả đạt được.",
      "demo": "https://link-demo.com",
      "github": "https://github.com/..."
    }
  ]
}
```

> 💡 **Chỉ cần có `"image"` là đủ** — các trường khác đều tuỳ chọn.
> Không có `title` → tự đặt "Dự án #1", "Dự án #2"...
> Không có `demo`/`github` → không hiển thị nút link.

**Bước 3** — Commit & push → dự án mới xuất hiện trên web ✅

---

## 🌐 Deploy GitHub Pages (lần đầu)

1. Tạo repo mới trên GitHub
2. Push toàn bộ thư mục lên
3. Repo → **Settings** → **Pages** → Source: **main** / **root** → Save
4. Web live sau ~1 phút: `https://username.github.io/tên-repo`

---

## ✏️ Chỉnh thông tin cá nhân trong `index.html`

| Cần đổi | Tìm kiếm |
|---|---|
| Tên / tagline | `NGUYỄN VIỆT ĐỨC` |
| Email | `nguyenvietduc@email.com` |
| Zalo / FB / IG | `social-link` |
| Số liệu stats | `stat-item` |
| Timeline | `timeline-item` |

