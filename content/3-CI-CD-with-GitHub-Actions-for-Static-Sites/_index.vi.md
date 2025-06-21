+++
title = "CI/CD với GitHub Actions cho các trang tĩnh"
date = 2025
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

Phần này giới thiệu cách thiết lập **pipeline CI/CD** sử dụng **GitHub Actions** để tự động xây dựng và triển khai các trang web tĩnh (ví dụ: Hugo) mỗi khi mã nguồn được đẩy lên kho lưu trữ. Điều này đảm bảo:

* Tích hợp liên tục (xây dựng trên mỗi lần commit)

* Triển khai liên tục (tự động xuất bản các thay đổi)

* Tính nhất quán và giảm công việc thủ công