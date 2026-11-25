# WD-Lab03 – HTML & CSS Management Applications

Môn Thiết kế Web · Bài thực hành WD-Lab03
Sinh viên: **Hồ Việt Thuận Phú** · MSSV: **24110098**

Cả hai ứng dụng chỉ dùng **HTML5 + CSS**, không dùng JavaScript, framework hay backend. Mở file `index.html` bằng trình duyệt là chạy được ngay, không cần mạng (trừ các link Netflix/YouTube bên ngoài).

## Cấu trúc thư mục

| Thư mục | Phần | Nội dung |
|---|---|---|
| `SoundNest_Offline/` | **Phần 1** – Cá nhân hóa ứng dụng mẫu | Cá nhân hóa từ **MelodyBox** (WDLab03 Instruction – Phần B): playlist nhạc band theo trạng thái cuối ngày, tông cam vàng. |
| `CineVault/` | **Phần 2** – Ứng dụng quản lý tự chọn | **CineVault** – thư viện phim cá nhân: 29 phim, 9 thể loại, mục Phim sắp chiếu, bảng dữ liệu, form đề xuất phim. |

```
WBLab03/
├── SoundNest_Offline/      # Phần 1
│   ├── index.html
│   ├── styles.css
│   ├── form-result.html
│   └── assets/             # covers/ (ảnh bìa), audio/ (file .wav)
├── CineVault/              # Phần 2
│   ├── index.html
│   ├── styles.css
│   ├── form-result.html
│   └── assets/posters/     # poster .jpg (f01–f29, u01–u14)
└── README.md
```

## Cách chạy

1. Clone repo hoặc tải ZIP (nút **Code → Download ZIP**).
2. Mở `SoundNest_Offline/index.html` hoặc `CineVault/index.html` bằng Chrome/Edge.
3. Thử form: điền đủ trường bắt buộc rồi gửi → chuyển sang `form-result.html` (trang xác nhận tĩnh, dữ liệu **không** được lưu).

## Kỹ thuật chính

- HTML5 semantic: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- Form: `label/for/id/name`, `required`, `select`, `radio`, `checkbox`, `textarea`, `action="form-result.html"`
- CSS: biến `:root`, Flexbox, Grid (`auto-fill`, `minmax`), `position` (sticky/absolute/fixed), media query
- Tương tác không JS: lọc bằng `:checked`, popup chi tiết bằng `:target`, `<details>`, `<audio controls>`

## Ghi chú bản quyền

Ảnh bìa, poster phim và file nhạc thuộc bản quyền của nghệ sĩ, nhà sản xuất và nhà phát hành, chỉ dùng cho mục đích học tập. Nguồn được ghi trong báo cáo.
