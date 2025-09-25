 lab02
Phân tích yêu cầu &amp; Thiết kế Use Case

dự án: bán hàng online
Use Case diagram 

Use Case Description
Use Case 1: Đăng nhập
Actor: Khách hàng
Mô tả: Khách hàng nhập tài khoản và mật khẩu để đăng nhập vào hệ thống
điều kiện đầu : Khách hàng đã có tài khoản hợp lệ
điều kiện cuối: Hệ thống xác thực và cho phép truy cập
Luồng chính:
Khách hàng chọn chức năng đăng nhập
Hệ thống hiển thị form đăng nhập
Khách hàng nhập tên đăng nhập và mật khẩu
Hệ thống kiểm tra thông tin
Nếu đúng → truy cập thành công
Ngoại lệ:
Sai mật khẩu → Thông báo lỗi
Tài khoản không tồn tại → Yêu cầu đăng ký
Use Case 2: Thanh toán
Actor: Khách hàng
Mô tả: Khách hàng thực hiện thanh toán cho đơn hàng trong giỏ
Tiền điều kiện: Khách hàng đã đăng nhập và có sản phẩm trong giỏ hàng
Hậu điều kiện: Đơn hàng được tạo và lưu trong hệ thống
Luồng chính:
Khách hàng chọn giỏ hàng
Hệ thống hiển thị danh sách sản phẩm
Khách hàng nhấn “Thanh toán"
Hệ thống yêu cầu nhập thông tin giao hàng
Khách hàng nhập thông tin và xác nhận
Hệ thống lưu đơn hàng và chuyển trạng thái “Chờ xử lý”
Ngoại lệ:
Nếu giỏ hàng trống → không thể thanh toán
Nếu thông tin giao hàng không hợp lệ → yêu cầu nhập lạ
