# Lấy Báo cáo tài chính vào HTKK

**Bước 1.** Trước hết nên tạo 1 thư mục chứa dữ liệu thuế như Thue200 \(hoặc Thue133\). Trong thư mục thuế tạo thư mục theo từng năm \(nếu có nhiều công ty khác nhau thì nên tạo mỗi công ty 1 thư mục\)

**Bước 2.** Vào HTKK, chọn TT200 \(hoặc TT133-B01a\), nhớ bỏ dấu tích LCTTGT. Bấm nút Kết xuất XML

Nếu có thông báo

![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/3.png)

Thì nhập số 1 vào 1 dòng tài sản \(1. Tiền\) và số 1 vào 1 dòng nguồn vốn \(- Cổ phiếu phổ thông\)

Sau đó bấm nút Kết xuất XML. Chọn nơi lưu là thư mục thuế của năm với tên là TT200.xml

\(đây là file nền đã có thông tin doanh nghiệp\). Mỗi công ty đều Kết xuất XML như thế.

**Bước 3.** Chạy phần mềm kế toán, vào báo cáo tài chính, bấm nút “Ghi ra Excel” cho từng báo cáo và cũng lưu vào thư mục thuế \(nhớ đặt tên theo từng báo cáo cho dễ nhớ\)

**Bước 4.** Menu “Tiện ích” -&gt; “Xuất XML, chuyển Excel vào phần mềm”

Nếu là TT133 thì chọn 2. Thông tư 133-B01a. Khi đó sẽ có thêm “File cân đối tài khoản”

![](https://phanmemnhatnam.com/wp-content/uploads/2018/03/3-1.png)

**Bước 5.** Bấm nút \(…\) ở “Nơi lưu file XML gốc” và chọn vào file TT200.xml của công ty cần chuyển.

Tương tự bấm nút \(…\) chọn các file BCTC Excel

**Bước 6.** Sau khi chọn xong bấm “Thực hiện”

**Bước 7.** Sau khi “Thực hiện” xong sẽ tạo ra file XML trong thư mục và có tên như “File cân đối kế toán”. Vào HTKK và bấm nút “Nhập từ XML”.



