# Profile Tiến - Website cá nhân

Website profile cá nhân với hero 3D, các section giới thiệu, dự án, kỹ năng và mạng xã hội.

## Cấu trúc file

```
profile-tinh-an/
├── index.html          # Trang chủ profile
├── japanese.html       # Trang học tiếng Nhật
└── backend/            # Backend Node.js (để phát triển sau)
    ├── server.js
    ├── package.json
    └── README.md
```

## Tính năng hiện tại

- Hero 3D với hiệu ứng parallax
- Top menu điều hướng
- Section "Về mình", "Điều nhỏ", "Hôm nay", "Kỹ năng", "Dự án", "Mạng XH"
- Gấu bông 3D tương tác
- Đổi sáng/tối (theme switcher)
- Music player nền
- Modal cánh cửa bí mật

## Chạy local

Mở trực tiếp `index.html` trong trình duyệt, hoặc dùng một static server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

Truy cập `http://localhost:8000`.
