---
# ============================================================
# FILE MẪU — không hiển thị trên site vì có `published: false`.
# Cách thêm publication mới:
#   1. Copy file này thành _publications/<năm>/<năm>-<ten-ngan>.md
#   2. Xoá dòng `published: false`
#   3. Điền các trường bên dưới
# ============================================================
published:      false

title:          "Tiêu đề bài báo"
date:           2026-01-05 00:01:00 +0700   # dùng để sắp xếp, mới nhất lên đầu
selected:       true                        # true = hiện ở mục "Selected Publications" trang chủ
pub:            "Tên hội nghị / tạp chí"    # vd: "International Conference on Machine Learning (ICML)"
pub_date:       "2026"                      # năm hiển thị trên badge

# Các trường tuỳ chọn:
# pub_pre:      "Submitted to "             # chữ đứng trước tên hội nghị
# pub_post:     "Under review."             # chữ đứng sau
# pub_last:     ' <span class="badge badge-pill badge-publication badge-success">Oral</span>'
# semantic_scholar_id: <id>                 # để tự động lấy số lượt trích dẫn
# cover:        /assets/images/covers/cover1.jpg   # ảnh minh hoạ, bỏ qua nếu không có

abstract: >-
  Tóm tắt 1-2 câu (TLDR), không nên dán abstract đầy đủ vì quá dài.
  Hỗ trợ LaTeX: $a = b + c$.

authors:                                    # tên phải khớp key trong _data/authors.yml
- Tên Của Bạn
- Đồng Tác Giả

links:
  Paper: https://arxiv.org/abs/xxxx.xxxxx
  Code: https://github.com/sieutrstd-pixel/xxx
---
