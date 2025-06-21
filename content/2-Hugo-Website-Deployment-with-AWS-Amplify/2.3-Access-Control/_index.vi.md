+++
title = "Kiểm Soát Truy Cập"
date = 2025
weight = 3
chapter = false
pre = "<b>2.3. </b>"
+++

AWS Amplify cung cấp các **tính năng kiểm soát truy cập** tích hợp sẵn, cho phép bạn giới hạn quyền truy cập vào trang web đã triển khai. Điều này đặc biệt hữu ích cho:

* Môi trường nội bộ/thử nghiệm

* Khách hàng xem trước trước khi phát hành công khai

* Các bản demo được bảo vệ bằng mật khẩu

1. Truy cập vào **Amplify Console**

2. Mở ứng dụng của bạn và chọn tab “**Access control**”. Nhấn **Manage access**

![13](../../../images/1/13.png)

3. Chọn một nhánh (ví dụ: main, dev hoặc staging)

4. Thiết lập quyền truy cập "**Restricted - password required**". Đặt **tên đăng nhập/mật khẩu và lưu lại**

![14](../../../images/1/14.png)

Sau khi hoàn tất thiết lập, tải lại trang web đã triển khai — một cửa sổ popup như sau sẽ xuất hiện.

![15](../../../images/1/15.png)