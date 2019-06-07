# Tạo dữ liệu mới

## **TẠO DỮ LIỆU MỚI:**

* Ta chuột phải vào biểu tượng kế toán ngoài desktop -&gt; chọn open file location -&gt; chọn restore
* Hoặc nếu quý khách thường xuyên phải tạo hay phục hồi dữ liệu thì có thể send to "restore" ra desktop để tiện thao tác
* Kích đúp vào biểu tượng restore -&gt; chọn kiểu tệp

![](../.gitbook/assets/tm1.png)



* Sẽ có 2 kiểu định dạng chứa dữ liệu: 1 là kiểu nén file.rar, 2 là kiểu file.bak \(hình ảnh minh họa\). dữ liệu ở định dạng nào thì ta chọn đối chiếu đến đó.
* Thông thường trong bộ cài đặt kế toán chúng tôi có để file ketoan.rar để tạo dữ liệu mới, quý khách chọn ketoan.rar _\(nếu không có file ketoan.rar, tải về theo đường link sau:_ [_https://phanmemnhatnam.com/tai-ve_](https://phanmemnhatnam.com/tai-ve/) _\)_
* Đặt tên cho dữ liệu
* Sau khi ấn thực hiện và hệ thống chạy xong. Ta thoát ra và vào chương trình
* Ta đăng nhập với tên người sử dụng: 99; pass: khong mot \( "khong" dấu cách chữ "mot"\)![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/3-3.png)
* Chọn Thay đổi tên đơn vị -&gt; Sửa -&gt; điền thông tin công ty
* Chọn Từ điển dữ liệu kế toán -&gt; bấm sửa -&gt; lôi dữ liệu ra.
* Nếu dữ liệu theo TT133, vào Hệ thống -&gt; Thay đổi các tham số của hệ thống -&gt; Search ở ô Diễn giải cần tìm là DNN -&gt; Thay giá trị SX ở cột giá trị thành DNN -&gt; thoát

## **PHỤC HỒI DỮ LIỆU CŨ**

#### 1. Có 2 kiểu dữ liệu cũ

### **1.1. Kiểu thứ nhất: dữ liệu đã được backup thành file.rar hoặc file.bak**

Quý khách xem hướng dẫn tại link sau: [https://docs.phanmemnhatnam.com/huong-dan-su-dung-1/phuc-hoi-du-lieu-cu](https://docs.phanmemnhatnam.com/huong-dan-su-dung-1/phuc-hoi-du-lieu-cu)

### **1.2. Kiểu thứ hai: dữ liệu được lưu trữ trong dưới dạng file gốc .mdf hoặc .data**

* Đối với kiểu dữ liệu gốc lưu ở dạng .mdf, ta vào Enterprise manager

![](../.gitbook/assets/tm3.png)

* Chọn \(+\) cho đến khi thấy Databases -&gt; chuột phải -&gt; all Tasks -&gt; Attach Database

![](../.gitbook/assets/tm4.png)

* Chọn \[...\] \(bên cạnh nút Verify\) để chọn file nguồn chứa dữ liệu -&gt; chọn các file lưu dưới dạng .mdf hoặc .data -&gt; ok

![](../.gitbook/assets/tm5.png)

* Vào Người sử dụng: 99; pass: "khong mot" \( không cách một \) -&gt; để lôi dữ liệu ra \(thao tác giống phần trên\)
