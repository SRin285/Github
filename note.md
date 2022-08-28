# terms
repository(repo) => thư mục
branch  => cành , nhánh nhỏ
conflict ==> xung đột 
# commands
- git init : làm dự  án chuyển thành git (repo)
- git status : cho biết được trạng thái của dự án
- git add : chuẩn bị lưu lại thời điểm hiện tại của dự án
- git add . là lưu tạm thời lại tất cả các file của dự án
- git reset : hủy lưu file 
- git commit -m "initial commit" : lưu lại và chi biết tên tại thời điểm bắt đầu repo
- git log : xem lại lịch sử commit
- git log --oneline : xem lại commit một các thu gọn
- git checkout (id-git..oneline)          : trở lại thời điểm bạn đầu

- git checkout master : qoay lại hiện tại
-git branch : mặc định master
-git checkout -b (tên branch name) : tạo branch mới 
- git branch : đi vào nhánh hiện tại
branch dev :
 -git checkout (tên branch "master") : chuyển branch dev sang thành branch "master"
branch master : 
- git merge (tên branch : "dev") : tổng hợp branch của dev sang master 
- git branch -D (tên branch : "dev") : xóa branch đó 
conflect : xung đột
- git commit : tổng hợp , giải quyết 1 conflict