pingo-exercise
==============
Bài tập của lớp Rails cơ bản

#####Quy ước
-----------------
- Mỗi người tạo 1 repository tren github
- Tạo 1 branch trên repository vừa tạo ra
- Tên branch là tên học viên viết thường, không dấu, cách nhau bởi dấu "-" (ex: học viên Nguyễn Văn A sẽ tạo branch nguyen-van-a)
- Tạo 1 pull request khi hoàn thành bài tập, gửi link tới email của giáo viên hướng dẫn, thời gian update pull-request được xem là thời gian nộp bài
- Bài tập phải nộp trước 23h:59 ngày 9-12-2014

#####Yêu cầu
---------------------
- Viết một ứng dụng quản lý cửa hàng bán giày, mỗi đôi giày thuộc về 1 hoặc nhiều loại, do 1 công ty sản xuất, có thông tin mô tả, giá bán và hình minh họa
  - ứng dụng gồm 2 roles: admin và user
  - layout của mỗi role được lấy trong thư mục templates/ của repository này
  - user không được cập nhật/xóa thông tin sản phẩm
  - ứng dụng phải có predefined data(loại giầy, công ty sản xuất, một số đôi giày mẫu)
- Admin
  - admin được phép thay đổi/xóa sản phẩm
  - xem report sản phẩm: số lần khách hàng xem sản phẩm, san pham duoc sap xep theo ten san pham
  - admin co the active/deactive 1 category nao do
- User
  - xem tat ca san pham, co phan trang
  - xem nhung doi giay thuoc mot loai nao do
  - danh gia san pham(them comment)
