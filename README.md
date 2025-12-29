## Cấu trúc thư mục
- src: Thư mục chứa mã nguồn
  + assets: các file hình ảnh, logo, icon cố định của UI
  + components: Chứa các component có thể tái sử dụng ở nhiều chỗ, các component cùng loại được nhóm lại thành các folder (ví dụ: button, card, menu,...)
  + hooks: các file custom hook 
  + layouts: các layout component. (ví dụ: tạo layout gồm header và footer để bọc bên ngoài cùng của các trang home, dashboard, inner-blog,...)
  + lib: dữ liệu cần có khi tải về và sử dụng các thư viện bên ngoài
  + pages: Nơi chứa code của riêng các page, trong mỗi page folder sẽ lại có một folder component sử dụng riêng cho page đó
  + router: chứa file config cho react route
