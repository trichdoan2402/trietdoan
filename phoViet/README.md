# Phở Việt

Website tĩnh giới thiệu món phở, xây dựng bằng HTML5 và CSS3 cho bài tập lập trình web.

Website đã triển khai: **https://trichdoan2402.github.io/trietdoan/**  
Mã nguồn trên GitHub: **https://github.com/trichdoan2402/trietdoan/tree/main/phoViet**

## Các trang

| Tệp | Nội dung |
| --- | --- |
| `index.html` | Trang chủ và giới thiệu chung |
| `cau-chuyen.html` | Câu chuyện và nét gần gũi của phở |
| `cac-loai-pho.html` | Phở bò, phở gà, phở chay |
| `thuong-thuc.html` | Gợi ý cách thưởng thức |
| `nguyen-lieu.html` | Các nhóm nguyên liệu và lưu ý an toàn |
| `cong-thuc.html` | Công thức tham khảo theo từng bước |
| `thu-vien.html` | Thư viện ảnh và thông tin nguồn |
| `lien-he.html` | Thông tin liên hệ và biểu mẫu minh họa |

Mở `index.html` trong trình duyệt để xem website. Các trang, ảnh và CSS đều dùng đường dẫn tương đối, phù hợp khi triển khai bằng GitHub Pages.

## Cấu trúc

```text
.
├── index.html
├── cau-chuyen.html
├── cac-loai-pho.html
├── thuong-thuc.html
├── nguyen-lieu.html
├── cong-thuc.html
├── thu-vien.html
├── lien-he.html
├── css/
│   └── style.css
├── images/
│   ├── chan-nuoc-dung.jpg
│   ├── pho-bo.jpg
│   ├── pho-ga.jpg
│   └── pho-chay.jpg
├── lienket.txt
└── README.md
```

## Nguồn nội dung và hình ảnh

- Toàn bộ phần chữ được biên soạn riêng cho website; không sao chép văn bản từ nguồn bên ngoài.
- Bốn ảnh trong `images/` được tạo bằng công cụ tạo ảnh của OpenAI cho dự án này, không lấy từ website bên ngoài.
- Ảnh được tạo bằng công cụ tích hợp `image_gen` với các mô tả: (1) tô phở bò Việt Nam trên bàn gỗ, rau thơm, chanh, ớt, ánh sáng buổi sáng; (2) thao tác chan nước dùng vào tô phở trong gian bếp Việt; (3) tô phở gà với thịt gà, hành và nước dùng vàng trong; (4) tô phở chay với nấm, đậu hũ và rau xanh. Cả bốn ảnh được yêu cầu theo phong cách chụp món ăn tự nhiên, bố cục ngang, không có chữ, logo hoặc watermark.
- Các ảnh được chuyển sang JPEG để giảm dung lượng tải trang.

## Triển khai lên GitHub Pages

Mã nguồn website nằm trong repository `trichdoan2402/trietdoan`, thư mục `phoViet/` trên nhánh `main`. GitHub Pages dùng workflow trong `.github/workflows/pages.yml` để xuất bản thư mục này. Website gồm tám trang HTML, một tệp CSS dùng chung và bốn ảnh minh họa.

Để cập nhật website: chỉnh sửa các tệp tương ứng trong `phoViet/`, commit và đẩy lên nhánh `main`. Workflow sẽ triển khai lại từ thư mục đó.

Hướng dẫn triển khai được đối chiếu với [tài liệu GitHub Pages chính thức](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

