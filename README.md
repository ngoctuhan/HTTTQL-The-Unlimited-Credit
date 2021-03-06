# HTTTQL-The-Unlimited-Credit

HỆ THỐNG QUẢN QUẢN TRỊ QUAN HỆ KHÁCH HÀNG VÀ QUẢN LÝ NHÂN VIÊN TRONG CÔNG TY TÀI CHÍNH 
THE UNLIMITED
Trong tài liệu này bao gồm:
1.	Bản mô tả hệ thống tổng quát 
2.	Thuộc nhóm đề tài
3.	Các module chính cần xây dựng
4.	Công nghệ sử dụng
Tài liệu mục đích học tập
Phần 1: Mô tả hệ thống
	Bối cảnh: Trong các công ty tài chính như homecredit … việc phân phối, quản lý khách hàng giúp cho việc tìm kiếm, phát hiện khách hàng tiềm năng giúp nâng cao lợi nhuận công ty. 
Các vấn đề cần giải quyết:
+ Trong công ty tài chính có nhiều chi nhánh rải rác khắp các vùng trên cả nước, mỗi nơi có nhiều phòng giao dịch khác nhau. Nên cần quản lý các phòng giao dịch, nhân viên và các hợp đồng tại các phòng giao dịch đó một cách tự động.
+ Trong công ty tài chính việc phân khúc khách hàng nhiều yếu tố, giúp truy xuất độ tín nhiệm khách hàng để cung cấp thêm các dịch vụ và ưu đãi, hoặc ngược lại là nhắc nhở khoản nợ tài chính.
+ Trong các công ty tài chính cần có công cụ giúp thống kê các hợp đồng, định giá hợp đồng theo từng tháng quý, đánh giá tỉ suất sinh lợi.
+ Các công ty tài chính cần hợp đồng với các đại ý kinh doanh cần quản lý các hợp đồng hợp tác giữa các đối tác như thegioididong, fpt, media mart…
Vì vậy cấp thiết cần có hệ thống thông tin quản lý với thông tin phân tán tại các miền và giải quyết các vấn đề cơ bản trên.
Phần 2: Phân loại đề tài
+ Xác định tính đúng đắn đề tài là sự kết hợp của marketing + quản trị quan hệ khách hàng + quản lý tri thức.
Phần 3: Các tính năng chính xây dựng trong hệ thống
•	Đối với khách hàng (5 modules)
+ Tạo hồ sơ khách hàng với khoản vay mặc định tối đa 10 tr không thế chấp, 50 tr với thế chấp.
+ Theo dõi lộ trình thanh toán trong hợp đồng theo các giai đoạn (tháng, quý).
+ Thông báo ưu đãi, nhắc nhở thanh toán (qua email).
+ Thanh toán theo kì hạn (mở rộng).
+ Xem, thanh toán hợp đồng của người khác. 
+ Tạo phòng giao dịch 
•	Đối với nhân viên tại các phòng giao dịch (4 modules)
+ Tạo lập hồ sơ mới với các khoản vay mới của khách hàng.
+ Thêm hồ sơ khách hàng mới mở tài khoản tín dụng.
+ Quản lý thông tin cá nhân: lương, ngày đi làm trong tháng, hệ số lương, thưởng, điểm uy tín ….
+ Xem và xuất báo cáo thống kê phòng giao dịch theo tháng, quý và năm.
•	Đối với bộ phận kế toán công ty (2 modules)
+ Xem, xuất báo cáo thống kê các giao dịch, hợp đồng của toàn công ty, của các phòng giao dịch.
+ Tạo bảng lương, hệ số thưởng.
•	Đối với bộ phận quản lý nhân sự (3 modules)
+ Xem, và kế hoạch toàn bộ nhân sự tại các phòng ban, tạo danh bạ cơ quan.
+ Cung cấp tài khoản cho các nhân viên tại phòng giao dịch
+ Đánh giá nhân viên, xét thưởng. 
•	Đối với bộ phận kế hoạch và đầu tư (2 modules)
+ Phân khúc khách hàng, thống kê khách hàng, phân khúc khách hàng theo các mục.
+ Quản lý hợp tác với các đối tác sử dụng dịch vụ tài chính như thegioididong, mediamart, trananh, phongvu…
Phần 4: Công nghệ sử dụng
Hệ thống triển khai thành web application.
	+ Công nghệ web: Front-end: html5, css, bootstrap, js jquerry. Back-end: servelet, spring boot, python flasks (thiết kê api quản lý tri thức).
	 + Cơ sở dữ liệu: SQL server để phân tán dữ liệu, MongoDB nếu cần.
	+ Hệ Recommend Systems: lọc cộng tác.
	+ Java Core. 
	+  Môi trường phát triển: TomCat Server. 
  	+ IDE: netbeans, esclip


Phần 5: Timeline cơ bản (dự tính trước cho bản quản lý dự án).
STT	Tên nội dung	Thời gian thực hiện	Dư tính thời gian hoàn thành
1	Tài liệu quản lý dự án.		
2	Phân tích thiết kế.	12/04/2020	7 ngày
3	Front-end.	13/04/2020	14 ngày
4	Thiết kế cơ sở dữ liệu và nạp dữ liệu mẫu.		5 ngày
5	Back-end.		20-30 ngày
6	Tổng hợp test thử, fix tính tăng.		7 ngày
7	Tổng		53 - 63 ngày







