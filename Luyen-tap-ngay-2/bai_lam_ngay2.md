# Bai luyen ngay 2 - Nhap mon CNTT
### BÀI LUYỆN TẬP – NGÀY 2
### NHẬP MÔN CÔNG NGHỆ THÔNG TIN
### ÔN TẬP HACKATHON 01
**[Thứ Tư, 21/10/2026]**
********************


**Bài 1. Lọc log thủ công (ôn Mục 4.3)**
_ Lệnh chuẩn theo yêu cầu:
`cat logs/access.log` | grep "ERROR" > logs/error_report.txt.

**Bài 2. Đếm bằng pipeline (ôn Mục 4.6)**
_ `macOS: cat logs/access.log | grep "WARNING" | wc -l ( Đếm số chứa dòng "WARNING")`
_ `macOS: cat logs/payment.log | grep "ERROR" | wc -l  ( Đếm số chứa dòng "ERROR")`

**Bài 3. Hoàn thiện script có khung sẵn (ôn Mục 4.5)**

``echo "Dang loc canh bao thanh toan..."
echo "CANH BAO THANH TOAN " > logs/warning_report.txt
cat logs/payment.log | grep "WARNING" >> logs/warning_report.txt
 
 echo "Hoan thanh."``

**Bài 4. Báo cáo tổng hợp (ôn Mục 4.7 – thử thách)**
1. Dùng lệnh `echo "=== TONG HOP ACCESS LOG ===" > logs/tong_hop_ngay2.txt`
2. Để trích dẫn và lọc ra lỗi ERROR, dùng lệnh `cat logs/access.log | grep "ERROR" >> logs/tong_hop_ngay2.txt`
3. Để trích dẫn và lọc ra lỗi WARNING, dùng lệnh `cat logs/payment.log | grep "WARNING" >> logs/tong_hop_ngay2.txt`

**Bài 5: Câu hỏi ngắn**
a. Lệnh > : Dùng để ghi đè hoặc tạo 1 file mới và sẽ xoá hết dữ liệu trước đó của file.
   Lệnh >> : Dùng để ghi nối tiếp nội dung và vẫn giữ được dữ liệu, nội dung của file 
b.  Nếu dùng > thay cho >> thì các dư liệu vừa tạo như tiêu đề === TONG HOP ACCESS LOG === sẽ bị xoá sạch và chỉ còn lại các dòng lỗi ERROR.
c. 