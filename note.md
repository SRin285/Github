# terms
Repository(repo) => thư mục
Branch  => cành , nhánh nhỏ
Conflict ==> xung đột 

Local ==> tất cả các tệp trên một máy tính
Remote ==> tệp ngoài local được hiểu là sever

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
  - git branch : mặc định master
  - git checkout -b (tên branch name) : tạo branch mới 
  - git branch : đi vào nhánh hiện tại
 
branch dev :
  - git checkout (tên branch "master") : chuyển branch dev sang thành branch "master"
branch master : 
  - git merge (tên branch : "dev") : tổng hợp branch của dev sang master 
  - git branch -D (tên branch : "dev") : xóa branch đó

 
=============================
conflect : xung đột
  - git commit : tổng hợp , giải quyết 1 conflict

local : 
  - git push : đẩy source lên repo của mình trên git
đẩy code từ local lên github ~~

" git add . 
  git commit -m 'note'
  git remote add origin  (link github)
  git push origin (tên branch) 

  vd git remote add origin https://github.com/SRin285/Github.git
     git push origin master
"

================================
lấy code trên github về local ~~

"
 create foder
 link foder : lấy link foder để chứa. 
 link : lấy đường link github (repo) của dự án có sẵn 

mở cd : 
  - cd (link foder)
  - git clone (link)
  - ls ==> kq : cho biết repo
  - cd kq : link vào repo
  - code . : mở code
  " push code "
  - git add . 
  - git commit -m 'nd'
  - git push
"

=================================
branch local : đẩy branch lên repo
"
   - git push -u origin  (tên branch) lần đầu 
   - git push : lần sau dùng git put bình thường
"
================================
lấy branch repo về local
"
   - tạo brach ở trên github
   vs-git base : 
   - git checkout master trở về master
   - git fetch origin
   - git checkout -b (tên branch) origin/tenbranch 
"
================================
tổng hợp branch (tên branch) sang master
"   
    - pull requests => new pull request => branch : master  compare : tên branch => merge

git base : 
   - git checkout master 
   - git pull 
"	


================================
Remote : che dấu file 
"    create folder : .gitignore {.file cần dấu}
git base : 
	- git add 
	- git commit -m 'remote gitignore'
	- git push
"
================================

fork 
   tác giả :
	linl : lấy link thư viện của tác giả 
   about : 
	dán link ==> fork
		( chỉnh sửa .... )
	==> commit changes
 
   share đến tác giả
	==> pull request ==> new pull request ==> create pull request 
	==> chờ tác giả đồng ý