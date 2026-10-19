# MetricsHub layout strategy

Navbar là bố cục một chiều: các nhóm nội dung cần tự giãn theo độ dài văn bản, nên dùng Flexbox với `flex-wrap` và khoảng cách `gap`. Dashboard là bố cục hai chiều: widget phải chiếm chính xác nhiều hàng/cột và tạo hình Bento Box, nên CSS Grid phù hợp hơn với `grid-column` và `grid-row`. Pricing chỉ là ba cột chuẩn, cần responsive nhanh, nên dùng Bootstrap `row` và `col-12 col-md-4`; các cột xếp dọc trên mobile và chia đều từ breakpoint `md`.
