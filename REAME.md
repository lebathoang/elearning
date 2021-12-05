echo "# elearning" >> README.md
# Khởi tạo git (lần đầu)
git init
# Thêm file vào hàng chờ
git add README.md
# Log nội dung thay đôi
git commit -m "first commit"
# Xác định nhánh nào
git branch -M main
# Xác định repo github (lần đầu)
git remote add origin https://github.com/lebathoang/elearning.git
# Đẩy code
git push -u origin main