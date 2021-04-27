1. Git branch
Branch là dùng để phân nhánh và branch đã phân nhánh sẽ không ảnh hưởng đến branch khác nên có thể tiến hành nhiều thay đổi đồng thời trong cùng 1 repository.
- git branch  <branchname> : Tạo branch 
- git branch : Liệt kê branch ở local 
- git branch -r : Liệt kê branch trên git server 
- git branch -a : Liệt kê toàn bộ branch
2. Git checkout vs git switch
Chuyển sang nhánh được chỉ định 
- git checkout [<option>] <branch>
- git switch <branch>
3. Pull/merge request
4. Git fetch
Cập nhập sự thay đổi thông tin của remote repository so với local repository 
- git fetch <name remote>
5. Git merge
Kết hợp sự thay đổi của các commit kể từ lúc tách nhánh của nhánh hiện tại vào nhánh tách ra trước đó 
- git merge destination_branch_name 
destination_branh_name: là tên nhánh bạn muốn merge vào nhánh hiện tại
6. Git pull 
git pull = git fetch + merge 
- git pull destination_branch_name 

*Review from Đỗ Ngọc Anh (Trưởng nhóm):
Bài tóm tắt của bạn khá đầy đủ, trình bày rõ ràng.
