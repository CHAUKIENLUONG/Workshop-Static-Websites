+++
title = "Thêm Cognito vào dự án, Triển khai lên AWS và Cấu hình nút đăng xuất cho người dùng"
date = 2025
weight = 2
chapter = false
pre = "<b>3.2. </b>"
+++

1. Thêm tính năng xác thực (Cognito)  
`amplify add auth`  
![20](../../../images/3/20.png)

2. **Chọn** **Cấu hình mặc định, Email, không, Tôi đã xong**  
![21](../../../images/3/21.png)

3. Triển khai tài nguyên lên AWS  
`amplify push`  
![22](../../../images/3/22.png)

4. Sau khi triển khai, chúng ta có đoạn mã sau  
![23](../../../images/3/23.png)

5. Cấu hình nút đăng xuất (signOut) cho người dùng  
![24](../../../images/3/24.png)

6. Chạy dự án và xem kết quả  
![25](../../../images/3/25.png)
![26](../../../images/3/26.png)
![27](../../../images/3/27.png)
![28](../../../images/3/28.png)