pingo-exercise
==============
Bài tập của lớp Rails cơ bản

#####Quy ước
-----------------
- Mỗi người tạo 1 repository tren github
- Tạo 1 branch trên repository vừa tạo ra
- Tên branch là tên học viên viết thường, không dấu, cách nhau bởi dấu "-" (ex: học viên Nguyễn Văn A sẽ tạo branch nguyen-van-a)
- Tạo 1 pull request khi hoàn thành bài tập, gửi link tới email của giáo viên hướng dẫn, thời gian update pull-request được xem là thời gian nộp bài
- Comment(nếu có) và điểm sẽ được update trên pull request
- Bài tập phải nộp trước 23h:59:59 ngày 9-12-2014

#####Yêu cầu
---------------------
- Viết một ứng dụng quản lý cửa hàng bán giày, mỗi đôi giày thuộc về 1 hoặc nhiều loại, do 1 công ty sản xuất, có thông tin mô tả, giá bán và hình minh họa
  - ứng dụng gồm 2 roles: admin và user
  - layout của mỗi role được lấy trong thư mục templates/ của repository này
  - user không được cập nhật/xóa thông tin sản phẩm
  - ứng dụng phải có pre-defined data(loại giầy, công ty sản xuất, một số đôi giày mẫu), hình minh hoạ của pre-defined data có thể để trống
- Admin
  - admin được phép thay đổi/xóa sản phẩm
  - thêm/xoá/sửa sp phải kiểm tra tính hợp lệ
  - xem report sản phẩm: gồm có số lần khách hàng xem sản phẩm, sản phẩm được xếp theo tên nhà sản xuất, sau đó theo tên sp
  - admin có thể active/deactive 1 công ty sản xuất nào đó.
- User
  - trang chủ:
    - hiển thị những sản phẩm được xem nhiều nhất trên 1 row 
    - phần còn lại hiển thị tất cả sản phẩm, có phân trang, sắp xếp theo giá sản phẩm từ cao xuống thấp.
  - có thể xem những sản phẩm thuộc một loại nào đó khi click vào link loại giày
  - có thể đánh giá sản phẩm(thêm comment) ở trang chi tiết sản phẩm

----------
Duong Van Long