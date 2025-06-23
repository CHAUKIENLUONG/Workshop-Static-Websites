+++
title = "Tạo ứng dụng React và cấu hình Amplify"
date = 2025
weight = 1
chapter = false
pre = "<b>3.1. </b>"
+++

1. Cài đặt **AWS Amplify CLI**
`npm install -g @aws-amplify/cli`
![1](../../../images/3/1.png)

2. Tạo ứng dụng React
`npx create-react-app amplify-react-app`
![2](../../../images/3/2.png)

3. **Mở** thư mục React vừa tạo
![3](../../../images/3/3.png)

4. **Cấu hình** Amplify
`amplify configure`
![4](../../../images/3/4.png)

5. **Chọn** khu vực (region) của bạn. **Nhấn Enter** sau đó
![5](../../../images/3/5.png)

6. **Nhập** tên người dùng. **Nhấn Tiếp theo**
![6](../../../images/3/6.png)

7. **Chọn** Attach policies directly và đánh dấu AdministratorAccess. **Nhấn Tiếp theo**
![7](../../../images/3/7.png)

8. **Chọn** người dùng vừa tạo
![8](../../../images/3/8.png)

9. **Tạo** access key
![9](../../../images/3/9.png)

10. **Chọn Other. Nhấn Tiếp theo**
![10](../../../images/3/10.png)

11. **Nhập** giá trị thẻ mô tả (Description tag). **Nhấn Tạo access key**
![11](../../../images/3/11.png)

12. **Sao chép** Access key và Secret access key
![12](../../../images/3/12.png)

13. **Dán** vào dòng lệnh trong VS Code
![13](../../../images/3/13.png)

14. **Nhập** người dùng vừa tạo
![14](../../../images/3/14.png)

15. Khởi tạo Amplify trong dự án `amplify init`
![15](../../../images/3/15.png)

16. Nhập **Y (Yes)**. Chọn **Prefer not to answer**
![16](../../../images/3/16.png)

17. Nhập `amplifyreactapp`
![17](../../../images/3/17.png)

18. **Chọn Yes** và chọn **AWS profile**
![18](../../../images/3/18.png)

19. Chúng ta sẽ có một thư mục **amplify** và một file **aws-exports.js**
![19](../../../images/3/19.png)


