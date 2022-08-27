# terms
repository(repo) => thư mục
branch  => cành , nhánh nhỏ
# commands
- git init : làm dự  án chuyển thành git (repo)
- git status : cho biết được trạng thái của dự án
- git add : chuẩn bị lưu lại thời điểm hiện tại của dự án
- git add . là lưu tạm thời lại tất cả các file của dự án
- git reset : hủy lưu file 
- git commit -m "initial commit" : lưu lại và chi biết tên tại thời điểm bắt đầu repo
- git log : xem lại lịch sử commit
- git log --oneline : xem lại commit một các thu gọn
- git checkout (id-git..oneline) : trở lại thời điểm bạn đầu
- git checkout master : qoay lại hiện tại
-git branch : mặc định master
-git checkout -b (tên branch) : tạo branch mới
- git merge dev : tổng hợp branch của dev sang master 