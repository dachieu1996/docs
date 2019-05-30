# Phục hồi dữ liệu cũ

### Phục hồi dữ liệu có 2 kiểu:

### **Kiểu thứ nhất: Phục hồi dữ liệu ghi đè lên dữ liệu cũ.**

Bước 1: Vào nút Windown trên thanh taskbar -&gt; Microsoft SQL server -&gt; Service manager -&gt; ấn nút STOP để tạm dừng SQL

![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/3-2.png)

Bước 2: Vào thư mục chứa dữ liệu gốc tên thư mục là Dulieuketoan, thường sẽ ở ổ D:\Dulieuketoan, xóa file tên\_dữ\_liệu.data \(hoặc tên\_dữ\_liệu.mdf\) và tên\_dữ\_liệu.log

Bước 3: Bật Start/Continue của Service Manager lên để chạy tiếp SQL

Bước 4: Vào C:\Program Files \(x86\)\Ketoan -&gt; chọn Restore \(nếu phải phục hồi nhiều lần chuột phải vào Restore -&gt; send to desktop\)

Kích vào Restore -&gt; chọn file nguồn dữ liệu -&gt; đặt tên dữ liệu -&gt; bấm thực hiện -&gt; Xong

![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/5.png)

### **Kiểu thứ hai: Phục hồi dữ liệu đặt tên mới.**

Bước 1: Vào C:\Program Files \(x86\)\Ketoan -&gt; chọn Restore \(nếu phải phục hồi nhiều lần chuột phải vào Restore -&gt; send to desktop\)

**Kích vào Restore -&gt; chọn file nguồn dữ liệu -&gt; đặt tên dữ liệu -&gt; bấm thực hiện \(giống với bước 4 ở trên\)**

Bước 2: Đăng nhập vào chương trình: user: 99

pass: khong mot \(chữ "khong" dấu cách chữ "mot"\)

![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/3-3.png)

Bước 3: Chọn hệ thống -&gt; 8. Từ điển dữ liệu kế toán -&gt; pass: khong mot -&gt; chọn Sửa -&gt; lấy dữ liệu ra -&gt; Thoát -&gt; lưu thay đổi -&gt; Xong

