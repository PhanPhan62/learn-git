# git clone
# git add origin (Đường dẫn đến )
# git checkout (Di chuyển giữa các branch)
  - Th1: Khi chưa tồn tại branch chỉ định, dùng câu lệnh:
    `git checkout -b (name-new-branch)`
  - Th2: Đã có branch, dùng câu lệnh:
    `git checkout (name-branch)`
# git status (HIển thị trạng thái (vd: các file thay đổi, file thêm vào,...))
# git add . (Đưa các đóng gói file)
# git commit --amend (Kiểm tra các file thay đổi trong branch) :wq(Để out terminal amend )
# git commit -m "..." (Dùng để commit gợi nhớ nhiệm vụ)
  - TH1: Tạo commit mới 
    `git commit -m "(name-commit)"`
    `git push origin (name-branch)`
  - TH2: Đã có commit và chỉnh sửa
    `git add .`
    `git commit --amend`
    `:wq`
    `git push origin (name-branch) -f`
# git remote -v (Điều khiển origin)
