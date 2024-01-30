git init: biến dự án thành repository(kiểu thư mục)
git status: kiểu hiện thị trạng thái của dự án
git add .(tên file): sẽ 'chuẩn bị lưu' file chỉ định
git reset: reset nếu đã add rồi
git commit: tiến hành lưu file chính thức
git commit -m 'ghi chú con mẹ gì cũng được' (bắt buộc ghi để phân biệt)
git log: thời điểm bây đã commit, ai commit, khi nào
git log --oneline: i chang git log mà nó gọn hơn
git checkout <id commit>:trở lại thời điểm commit tùy ý
git checkout master: trở lại thời điểm hiện tại hoặc master branch

git branch: show ra cái cây m đang làm việc
git checkout -b {branch name}: tạo 1 branch mới để m code
git merge {branch name}: merge lại cái branch với master
git branch -d {branch name}: xóa branch

conflict thì khi giải quyết xong thì m phải 'add . 'và 'commit lại'

remote : là github
Local : là máy đang sử dụng
--Liên kết với github
\*PUSH LÊN
B1: tạo reponsitory mới(tên giống dưới local)
B2: copy đường dẫn
sau đó thì:
git push <đường dẫn> <tên branch hiện tại>
--thay thế đường dẫn:
git remote add origin <đường dẫn> -> biến đường dẫn thành 1 cái tên bây muốn

\*DOWN VỀ:
B1: lấy đường hướng dẫn
B2: git clone <đường hướng dẫn>

khi mà down về rồi commit lại thì chỉ cần push là được, đéo cần đường dẫn nữa

--tạo branch ở loacal rồi push lên remote
git push -u origin <tên branch>(dùng lần đầu, lần sau thì git push bth)

--tạo branch ở remote rồi down về local
git fetch origin
git checkout -b <tên branch> origin/<tên branch>

nếu muốn merge thì xài pull trên github
--khi merge xong trên github mà muốn cái master ở máy nó cập nhật lại thì quay về master và xài git pull

--.gitinore thì nó sẽ đéo ghi cái file mà m để vô file này

# Terms

Repository : thư mục dự án
