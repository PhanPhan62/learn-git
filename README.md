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
# git remote -v (hiển thị toàn bộ origin)
  - Muốn xoá remote
    `git remote rm origin`
  - Add remote
    `git remote add origin (url-remote)`
# git rebase (Lấy toàn bộ code được merge vào nhánh chính)
  `git rebase (main_branch)`
# git branch -D (name_branch) (Xoá branch)
# git branch (Hiển thị tất cả branch)
# khôi phục branch đã xoá
  `git checkout -b restore_(name_deleted_branch)` or `git checkout -b (name_deleted_branch) (code_branch)`
# git reflog (Check log)
# git log -- online (Như git reflog tuy nhiên clear hơn. (recoment))
# git log -- online -n(number_row) (Log ra số dòng chỉ định)

[Hướng_dẫn_học_git](https://www.youtube.com/watch?v=-VmX40r5ARI&t=151s)
