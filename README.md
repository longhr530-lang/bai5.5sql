# bai5.5sql
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Hải Long
- **Mã số sinh viên:** 24810320154
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình.Net
- **Tên bài tập:** Lập trình C# / Windows Forms với sql

---
#Kết Quả Thực Hành

Giao diện chính
<img width="969" height="696" alt="image" src="https://github.com/user-attachments/assets/bd6f02d7-141e-4099-8e7a-30bd31e13606" />


Giao diện phần quản lí/cảnh báo tồn kho
<img width="965" height="692" alt="image" src="https://github.com/user-attachments/assets/5ea4d18e-d8d3-48a8-a544-de442d8644e7" />


Lỗi khi nhập dữ liệu kho khi chưa có mặt hàng nào
<img width="968" height="695" alt="image" src="https://github.com/user-attachments/assets/6ec627ca-deeb-4cc1-afb3-70dc0b807101" />


Thêm các mặt hàng vào phiếu
<img width="973" height="690" alt="image" src="https://github.com/user-attachments/assets/af7e54a0-1ae8-4800-a1cf-9cf9ee189e4b" />


Xác nhận lưu trữ mặt hàng vào phiếu
<img width="964" height="689" alt="image" src="https://github.com/user-attachments/assets/b39a02b2-38da-4886-86cf-41ca02debb8c" />


HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
Khởi tạo CSDL:

Mở file Database.sql có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
Chạy toàn bộ script (Execute) để tự động tạo CSDL InventoryDB cùng các bảng và dữ liệu mẫu.
Cấu hình chuỗi kết nối:

Mở file Dbhelper.cs.
Kiểm tra và đổi lại Data Source cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới (localdb)\MSSQLLocalDB).
Chạy chương trình:

Nhấn F5 (hoặc nút Start) trên Visual Studio để chạy hệ thống.
