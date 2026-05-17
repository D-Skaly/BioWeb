# BioWeb - Neon Tech Personal Bio (Vietnam)

Trang bio cá nhân chuyên nghiệp phong cách **neon/tech**, tối ưu cho thị trường Việt Nam và deploy nhanh lên Vercel.

## Nâng cấp giao diện

- Sử dụng **Tailwind CSS CDN** để tăng tốc style system.
- Sử dụng **AOS** cho scroll animation.
- Sử dụng **GSAP** cho entrance animation.
- Sử dụng **Font Awesome** cho icon.
- Tạo hiệu ứng nền **starfield neon** bằng Canvas API.

## Chạy local

```bash
python3 -m http.server 8080
```

Mở: `http://localhost:8080`

## Deploy lên Vercel

1. Push repo lên GitHub.
2. Vào Vercel → Add New Project.
3. Import repo và deploy static site.
4. Vercel sẽ dùng `vercel.json` để routing clean URL.

## Tùy chỉnh nhanh

- Nội dung profile: `index.html`
- Màu neon/layout: `styles.css`
- Liên kết social/contact: cập nhật trong section `#contact`
