-Tên đề tài: Hệ thống giảng dạy trực tuyến TDTU Classroom

-Thành viên nhóm: 
	Nguyễn Anh Huy - 51900652
	Bùi Ngọc Khai Tâm - 51900772
	Nguyễn Phước Du Phương - 51303379
	Trần Phú Trí - 51303192

Các bước setup
Bước 1: copy toàn bộ folder dự án "Classroom" vào thư mục XAMPP/htdocs/
Bước 2: Khởi động  XAMP và tiến hành khởi động Apache cùng MySQL
Bước 3: import database: database.sql nằm trong folder source code lên php admin
BƯớc 4: Tiến hành truy cập vào dự án bằng cách khởi động trình duyệt, bằng lệnh localhost cùng với port của xampp và nhập đường dẫn vào source code.


Ghi chú công việc:
1_Giao diện GUI và database(phpmysql): Trí ,Phương ,Huy ,Tâm

2_Chức năng:
	Đăng kí, đăng nhập: Phương,Tâm
	Khôi phục lại mật khẩu: Phương,Huy,Tâm
	Tính năng giới hạn thời gian khôi phục mật khẩu: Tâm
	Admin phân quyền cho người dùng bất kì:Huy
	Thêm lớp học: Huy, Tâm
	Xóa lớp học:Huy, Tâm 
	Sửa lớp học:
	Tìm kiếm lớp học: 
	Học viên tham gia vào lớp học bằng mã lớp học: Huy, Tâm
	Học viên thấy được danh sách lớp học đã tham gia: Huy, Tâm
	Giáo viên xem danh sách Học viên: Huy, Tâm, Phương
	Giáo viên thêm/loại Học viên khỏi lớp học: Huy, Tâm , Trí
	Giáo viên đăng tin tức, tài liệu, hình ảnh lên lớp học: Huy, Tâm
	Giáo viên sửa tin tức, tài liệu, hình ảnh:
	Học viên coi tin tức, download tài liệu, hình ảnh:
	Học viên, Giáo viên comment vào tin tức:
	Giáo viên xóa comment:
	Giáo viên tạo assignment:
	Responsive Web Design: Huy, Tâm.
	Tính năng thông báo bằng email: Huy, Tâm
	Tính năng mã hóa mật khẩu người dùng: Phương, Tâm.

3_Lưu Ý
Để chức năng gửi mail hoạt động tốt nhất có thể ADMIN hãy đổi email mặc định thành
email cá nhân, trường hợp vẫn không hoạt dộng thì hãy truy cập đường link sau
https://myaccount.google.com/lesssecureapps thao tác như hướng dẫn rồi chạy lại.

Cụ thể ở file send_mail.php, ADMIN hãy thực hiện đổi các biến sau:
$mail->Username = 'email cá nhân'; 
$mail->Password = 'mật khẩu email';
