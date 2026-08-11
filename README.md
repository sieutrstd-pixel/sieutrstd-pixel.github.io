# sieutrstd-pixel.github.io

Trang cá nhân học thuật, chạy bằng Jekyll trên GitHub Pages.
Site: https://sieutrstd-pixel.github.io/

## Sửa nội dung ở đâu

| Muốn đổi gì | Sửa file nào |
| --- | --- |
| Tên, chức danh, email, mạng xã hội, bio, học vấn, kinh nghiệm, giải thưởng | `_data/profile.yml` |
| Ảnh chân dung | `assets/images/photos/portrait.jpg` |
| Danh sách tác giả (in đậm tên mình, link tới trang người khác) | `_data/authors.yml` |
| Các mục hiện trên trang chủ, chữ ở footer | `_data/display.yml` |
| Menu điều hướng | `_data/navigation.yml` |
| Thêm bài báo | tạo file mới trong `_publications/<năm>/`, xem mẫu `_publications/2026/_TEMPLATE.md` |
| Thêm tin tức | tạo file mới trong `_news/`, xem mẫu `_news/_TEMPLATE.md` |

Các file `_TEMPLATE.md` có `published: false` nên không hiển thị trên site — chúng chỉ để tham khảo format.

## Chạy thử ở máy

Cần Ruby + Bundler ([RubyInstaller for Windows](https://rubyinstaller.org/), chọn bản có Devkit):

```bash
bundle install
```

```bash
bundle exec jekyll serve
```

Rồi mở http://localhost:4000

## Deploy

Push lên nhánh `main` của repo `sieutrstd-pixel.github.io`, sau đó bật GitHub Pages trong
Settings → Pages → Source: `Deploy from a branch` → `main` / `(root)`.

## Credit

Dựa trên template [academic-homepage](https://github.com/luost26/academic-homepage) của Shitong Luo (MIT License).
