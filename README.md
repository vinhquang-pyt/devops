# devops
1.	Git
LOCAL
-	Cài đặt Git
-   Git --version #kiểm tra phiên bản git
-   Git init #tạo repo dự án
-	Git config --global user.name “username” #cấu hình username tài khoản git
-	Git config --global user.email “email” #cấu hình email tài khoản git
-	Git config user.name #kiểm tra username đã cấu hình
-	Git config user.email #kiểm tra email đã cấu hình
-	Git config --list #các thông tin cấu hình git
-   Git push "link repo" "branch" #đẩy repo lên github
-	Git remote add origin “link repo” #tạo alias cho link repo
-   Git push "alias link repo" branch #đấy repo với alias đã tạo
-	Git pull #repo dự án về
-	Git branch -M main #cấu hình nhánh mặc định
-	Git status #trạng thái dự án
-	Git add . #lưu toàn bộ file vào vùng chuẩn bị(staging area)
-	Git add "file cần lưu" #lưu file chỉ định vào vùng chuẩn bị
-	Git reset #xóa toàn bộ file tại vùng chuẩn bị(staging area)
-	Git commit -m “ghi chú cần thiết” #áp dụng tất cả các thay đổi local repo
-	Git log #hiển thị các phiên bản commit đầy đủ thông tin
-	Git log --oneline #hiển thị các phiên bản commit rút gọn
-   Git checkout "ID" #trở về các phiên bản commit đã chọn
-   Git checkout "branch" #phiên bản mới nhất, chuyển đổi giữa các branch
-   Git branch #kiểm tra các branch(cành) hiện có
-   Git branch -b "tên branch" #tạo branch(cành) mới
-   Git merge "tên branch" #tổng hợp các branch với nhau
-   Git branch -d "tên branch" #xóa branch


