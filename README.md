# Làm quen với Git  
## Một vài lệnh cơ bản trong Git  
1. **Lệnh cấu hình Git**  
``$ git config --global user.name "DCTTu"``  
``$ git config --global user.email "tudoan.dev@gmail.com"``  
2.  **Lệnh Git init**  
Tạo một kho lưu trữ cục bộ  
``$ git init``  
3. **Lệnh Git clone**  
Tạo bản sao của kho lưu trữ từ một URL hiện có  
``$ git clone https://github.com/DCTTu/hello-world.git``  
4. **Lệnh Git status**  
Hiển thị trạng thái của thư mục làm việc và vùng origin. Xem những thay đổi nào đã được thực hiện, những thay đổi nào chưa và những file nào không được Git theo dõi  
``$ git status``  
5. **Lệnh Git add**  
Thêm một hoặc nhiều tệp vào branch  
``$ git add data_1.txt``  
6. **Lệnh Git commit**  
Ghi lại hoặc chụp nhanh mọi thay đổi của các file trong lịch sử thay đổi bằng một tin nhắn  
``$ git commit -m "Thêm data_1.txt"``  
7.  **Lệnh Git push**  
Tải nội dung của kho lưu trữ cục bộ lên kho lưu trữ từ xa  
``$ git push origin main``  
8. **Lệnh Git pull**   
Tìm nạp và kết hợp các thay đổi trên máy chủ từ xa vào thư mục cục bộ  
``$ git pull https://github.com/DCTTu/hello-world.git``  
9. **Lệnh Git branch**  
Liệt kê tất cả các nhánh có sẵn trong kho lưu trữ  
``$ git branch``  
10. **Lệnh Git merge**
Hợp nhất nhánh được chỉ định vào nhánh hiện tại  
``$ git merge BranchName``  
11. **Lệnh Git log**  
Kiểm tra lịch sử commit  
``$ git log``  
