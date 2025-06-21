+++
title = "Chuẩn bị"
date = 2025
weight = 1
chapter = false
pre = "<b>2.1. </b>"
+++

### Yêu cầu trước

* Một tài khoản AWS có quyền truy cập AWS Amplify

* Một tài khoản GitHub

* Đã cài đặt Hugo và Git trên máy tính

  * [Hugo Theme](https://gohugo.io/)

  * [Git](https://git-scm.com/downloads)

* Một trình soạn thảo mã nguồn (ví dụ: VS Code)

  * [Visual Studio Code](https://code.visualstudio.com/download)

### Thiết lập dự án

* Sử dụng một dự án Hugo có sẵn hoặc tạo mới nếu cần.

* Đảm bảo dự án có cấu trúc hợp lệ, bao gồm thư mục public để chứa kết quả build.

* Đẩy toàn bộ mã nguồn lên một repository GitHub (trên nhánh main hoặc master).

### Đẩy lên GitHub

* Tạo một repository mới trên GitHub

* Khởi tạo Git và đẩy dự án Hugo của bạn lên GitHub:

        git init
        git remote add origin https://github.com/<ten-nguoi-dung>/<ten-repo>.git
        git add .
        git commit -m "Khởi tạo dự án"
        git push -u origin main