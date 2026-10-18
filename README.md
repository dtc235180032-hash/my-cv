# My CV

CV cá nhân được xây dựng bằng HTML + Tailwind CSS - thiết kế hiện đại, tối giản, responsive.

## ✨ Tính năng

- **Responsive** - Hiển thị tốt trên mobile, tablet, desktop
- **Dark/Light mode** - Tự động theo hệ thống, có nút chuyển đổi
- **Print-ready** - In ra PDF đẹp (Ctrl+P)
- **Animations** - Fade-in, skill bar animations
- **Accessible** - Semantic HTML, ARIA labels
- **No build step** - Mở file `index.html` trực tiếp trong trình duyệt

## 🚀 Cách sử dụng

1. Mở `index.html` trong trình duyệt
2. Chỉnh sửa nội dung trong file HTML (tìm các phần trong ngoặc `[...]`)
3. Thay ảnh đại diện: thay thế SVG placeholder trong header
4. Deploy: Push lên GitHub Pages, Netlify, Vercel...

## 📝 Các phần cần điền

| Phần | Mô tả |
|------|-------|
| **Header** | Tên, chức danh, địa chỉ, email, phone, LinkedIn, GitHub, Portfolio |
| **Mục tiêu nghề nghiệp** | 2-3 câu tóm tắt kinh nghiệm & mục tiêu |
| **Kinh nghiệm** | Các vị trí cũ: công ty, thời gian, thành tựu (có số liệu), tech stack |
| **Học vấn** | Bằng cấp, trường, năm, GPA/xếp loại |
| **Kỹ năng** | Chia nhóm, có thanh progress bar (0-100%) |
| **Dự án** | Tên, mô tả, tech stack, link demo/code |
| **Chứng chỉ/Giải thưởng** | Tên, tổ chức cấp, năm |

## 🎨 Tùy biến màu sắc

Trong `<script>` tag của `tailwind.config`:
```js
colors: {
  primary: { 50: '#f0f9ff', ..., 950: '#082f49' }, // Màu chủ đạo (mặc định: xanh dương)
  neutral: { 50: '#fafafa', ..., 950: '#0a0a0a' }   // Màu trung tính
}
```

Thay đổi `primary` để đổi màu theme.

## 📄 Xuất PDF

1. Mở file trong Chrome/Edge
2. `Ctrl+P` (hoặc `Cmd+P` trên Mac)
3. Destination: **Save as PDF**
4. More options → **Background graphics** ✓
5. Margins: **None** hoặc **Minimum**
6. Save

## 📁 Cấu trúc

```
my-cv/
├── index.html    # File chính (đơn lẻ, self-contained)
└── README.md     # File này
```

## 🛠️ Tech Stack

- HTML5 semantic
- Tailwind CSS (via CDN)
- Inter font (Google Fonts)
- Vanilla JS (theme toggle, animations)
- SVG icons (inline, no external deps)