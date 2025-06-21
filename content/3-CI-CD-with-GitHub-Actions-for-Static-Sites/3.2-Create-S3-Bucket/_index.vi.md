+++
title = "Tạo S3 Bucket"
date = 2025
weight = 2
chapter = false
pre = "<b>3.2. </b>"
+++

1. Truy cập [AWS Console](https://us-east-1.console.aws.amazon.com/console/home?nc2=h_ct&src=header-signin&region=us-east-1)

2. Tìm kiếm **S3**

3. **Tạo Bucket**

![1](../../../images/2/1.png)

4. **Nhập** tên Bucket

![2](../../../images/2/2.png)

5. Nhấn **Tạo Bucket**

![3](../../../images/2/3.png)

6. **Chọn** bucket vừa tạo

![4](../../../images/2/4.png)

7. **Chọn Properties (Thuộc tính)**

![5](../../../images/2/5.png)

8. **Kéo xuống** phần Static website hosting. **Nhấn Chỉnh sửa (Edit)**

![6](../../../images/2/6.png)

9. **Chọn Bật (Enable)**, **Nhập tên file Html**

![7](../../../images/2/7.png)

10. Quay lại và **Chọn Quyền (Permissions)**

![8](../../../images/2/8.png)

11. **Kéo xuống** phần Block public access (bucket settings), **Nhấn Chỉnh sửa (Edit)**

![9](../../../images/2/9.png)

12. **Bỏ chọn Block all public access** và **Lưu thay đổi (Save changes)**

![10](../../../images/2/10.png)

13. **Nhập Confirm** và nhấn Xác nhận (Confirm)

![11](../../../images/2/11.png)

14. Quay lại và kéo xuống phần **Object Ownership**. **Nhấn Chỉnh sửa (Edit)**

![12](../../../images/2/12.png)

15. Chọn:

    1. **Bật ACLs (ACLs enabled)**
    2. **Chọn Tôi xác nhận rằng ACLs sẽ được khôi phục**
    3. **Nhấn Lưu thay đổi (Save changes)**

![13](../../../images/2/13.png)


