
# Bai luyen ngay 1 - Nhap mon CNTT

**BÀI LUYỆN TẬP – NGÀY 1**

**NHẬP MÔN CÔNG NGHỆ THÔNG TIN**

**ÔN TẬP HACKATHON 01**

**[Thứ Ba, 20/10/2026]**

************************

4. Yêu cầu:
4.1 
Phần A: **Tổ chức thư mục bằng GUI (ôn Mục 4.1)**
Bảng tên tiêu chuẩn snake_case: 
1.  `Logo Trung Tam.PN` ---> logo_trung_tam.png
2.  `Anh Lop Hoc.JPG` ---> anh_lop_hoc.jpg  
3.  `Lich Hoc.txt` ---> lich_hoc.txt
4.  `Hoc Vien Khoa 3.xlsx` ---> hoc_vien_khoa_3.xlsx
5.  `Access.log` ---> access.log

4.2
**B1. Hiển thị đường dẫn tuyệt đối:**
+ pwd

**B2. Liệt kê nội dung bao gồm file ẩn:**
+ ls -a 

**B3. Di chuyển tài liệu và file media vào các thư mục tương ứng:**
+ mv lich_hoc.txt docs
+ mv logo_trung_tam.png media
+ mv anh_lop_hoc.jpg media

**B4. Sao chép logo từ media sang archive:**
+ cp media/logo_trung_tam.png archive/

**B5. Xóa 2 file .tmp (mỗi file 1 lệnh):**
+ rm temp_202.tmp

**B6. Vào logs bằng đường dẫn tương đối, liệt kê rồi quay lại:**
+ cd logs
+ ls
+ cd ..

**B7. Di chuyển vào docs, sao chép ảnh từ media sang archive, quay lại gốc:**
+ cp ../media/anh_lop_hoc.jpg ../archive/
+ cd ..

**B8. Liệt kê toàn bộ dự án đệ quy bao gồm file ẩn:**
+ ls -aR