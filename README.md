win_explorer_java

Họ và tên: Phạm Thị Kim Anh


Lớp: 17IT2


Mã SV: 17IY040

Đề 6: 


- Thực hiện giao diện Window Explorer


- Thực hiện chức năng xóa tệp tin (File)


Link video: https://www.youtube.com/watch?v=WDeMeMz1MeI&t=5s

-----------------------------------------------------------------------------------------------------------------------------------
HƯỚNG DẪN CHẠY CODE:


1. Tải project từ Github


2. Mở cmd


3. Dùng lện cd chuyển đến thư mục chứa source code


VD: cd F:\KIM ANH\JAVA\thigiuaki\src


4. Biên dịch bằng lệnh javac


  javac thigiuaki\BTGK.java
  
  
5. Chạy bằng lệnh java


 java thigiuaki.BTGK
-----------------------------------------------------------------------------------------------------------------------------------
HƯỚNG DẪN SỬ DỤNG


- Mở các thư mục bằng cách doubleclick vào thư mục ở JTree


- Thực hiện các chức năng bằng các button ở gần cuối


- Chức năng chính: Xóa File


    + Kích chuột vào file muốn xóa
    
    
    + Nhấn nút Delete
    
    
    + Xuất hiện hộp thoại, nhấn OK để xác nhận xóa file, nhấn No để hủy thao tác
    
    
- Chức năng làm thêm: Mở file và đặt lại tên


    + Open: Chọn file cần mở, nhấn nút Open
    
    
    + Rename:
    
    
      ~ Chọn file muốn đổi tên
      
      
      ~ Nhấn nút Rename
      
      
      ~ Gõ tên mới vào textfield trên hộp thoại mới xuất hiện. Nhấn OK để hoàn thành đổi tên, nhấn Cancel để hủy thao tác
------------------------------------------------------------------------------------------------------------------------------------
BIÊN DỊCH CÁC DÒNG LỆNH:
- private void renameFile(): Dùng để đổi tên file


- private void deleteFile() : Dùng để xóa file


- private void setFileDetails(File file): hiển thị thông tin chi tiết về folder/file 


- public Container getGui(): Hiển thị các thành phần 


- public void showRootFile(): Hiển thị các tệp lên jtree và jtable từ lớp FileTableModel.


- private void showErrorMessage(): Hàm dùng để hiển thị tin nhắn báo lỗi


- private void setTableData(final File[] files): Dùng để cài đặt dự liệu cho table


- private void setColumnWidth(int column, int width): Dùng để cài đặt kích cỡ cho table


- private void showChildren(final DefaultMutableTreeNode node): Hiển thị các cành con của Tree


