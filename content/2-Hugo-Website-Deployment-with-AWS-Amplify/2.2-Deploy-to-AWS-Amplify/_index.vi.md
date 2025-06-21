+++
title = "Triển khai lên AWS Amplify"
date = 2025
weight = 2
chapter = false
pre = "<b>2.2. </b>"
+++

Trên [Bảng điều khiển AWS](https://us-west-2.console.aws.amazon.com/console/home?nc2=h_ct&region=us-west-2&src=header-signin#):

1. Vào **AWS Amplify → Deploy an app**

![1](../../../images/1/1.png)

![2](../../../images/1/2.png)

2. Chọn **GitHub** làm nguồn và cấp quyền truy cập

![3](../../../images/1/3.png)

![4](../../../images/1/4.png)

![5](../../../images/1/5.png)

![6](../../../images/1/6.png)


3. Chọn **repository** và **branch** bạn muốn triển khai (ví dụ: main). Nhấn **Next**

![7](../../../images/1/7.png)

4. Nhấn **Next**

![8](../../../images/1/8.png)

5. Nhấn **Save and deploy**

![9](../../../images/1/9.png)

{{%notice%}}
Amplify sẽ tự động phát hiện dự án Hugo và tạo pipeline build mặc định {{%/notice%}}

Sau khi triển khai thành công, giao diện sẽ như sau.

![11](../../../images/1/11.png)

6. Nhấn vào đường link.

![10](../../../images/1/10.png)

Website Hugo của bạn đã được triển khai thành công.

![12](../../../images/1/12.png)