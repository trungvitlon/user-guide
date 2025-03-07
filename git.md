# Git Function 
git clone 
-
> Sao chép 1 repository từ xa về máy chủ (local)
```
git clone <URL>
```
git init
-
> Khởi tạo 1 repository trong máy chủ 
```
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
2. Thêm tất cả (**Dùng nhiều**)
```bash
git add .
```
3. Thêm từng thay đổi cụ thể 
```
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
```
git status
```
git branch 
> Quản lý các nhánh trong repo
1. Tạo nhánh mới

