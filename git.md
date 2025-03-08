# Git Function 
git clone 
-
> Sao chép 1 repository từ xa về máy chủ (local)
```bash
git clone <URL>
```
git init
-
> Khởi tạo 1 repository trong máy chủ 
```bash
git init
```
git add
-
> Thêm tệp hoặc thay đổi vào vùng nhớ tạm (staging area) trước khi commit 
1. Thêm file, folder
```bash
git add <file>
git add <folder>/
```
2. Thêm tất cả
```bash
git add .
```
3. Thêm từng thay đổi cụ thể 
```bash
git add -p
```
git mv
-
> Dùng để di chuyển hoặc đổi tên tệp, thư mục
1. Đổi tên
```bash
git mv <new file/folder> <new file/folder>
```
2. Di chuyển tệp vào thư mục
```bash 
git mv <file> <folder>
```
git log
-
> Xem lịch sử commit trong repo
```bash
git log
```
git status 
-
> Kiểm tra trạng thái của repo
```bash
git status
```
git branch 
> Quản lý các nhánh trong repo
1. Tạo nhánh mới
```bash
git branch main
```
2. Đổi tên nhánh
```bash
git branch -m main master 
```
3. Xóa nhánh
```bash
git branch -d main
```
4. Liệt kê các nhánh
```bash
git branch -r -a
```
git checkout
-
> Dùng để chuyển đổi sang nhánh khác, khôi phục file, kiểm tra trạng thái commit
1. Chuyển sang nhánh khác 
```bash
git checkout main
```
2. Tạo và chuyển sang nhánh mới 
```bash
git checkout -b main
```
git commit
-
> Lưu thay đổi trong kho lưu trữ cục bộ (local)
```bash
git commit -m 'add message'
```






