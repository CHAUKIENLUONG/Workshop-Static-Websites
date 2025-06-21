+++
title = "Access key và Policy"
date = 2025
weight = 4
chapter = false
pre = "<b>3.4. </b>"
+++

Chọn **Security credentials** (Thông tin xác thực bảo mật)

![50](../../../images/2/50.png)

Cuộn xuống phần Access keys, nhấn Create access key (Tạo access key)

![20](../../../images/2/20.png)

Chọn **Other** và nhấn **Next**

![21](../../../images/2/21.png)

Nhập **Decription tag value** (Giá trị thẻ mô tả), nhấn **Create access key** (Tạo access key)

![22](../../../images/2/22.png)

Vào S3 bucket của bạn và sao chép tên bucket

![24](../../../images/2/24.png)

Vào phần Settings của repository GitHub, cuộn xuống Secrets and variables → Actions, sau đó nhấn New repository secret (Tạo secret mới)

![19](../../../images/2/19.png)

Nhập **Tên** `AWS_S3_BUCKET`

Dán tên bucket S3 vào trường secret

Nhấn **Add Secret** (Thêm Secret)

![25](../../../images/2/25.png)

Nhập **Tên** `AWS_ACCESS_KEY_ID`

Sao chép **Access Key** và dán vào trường secret

Nhấn **Add Secret**

![23](../../../images/2/23.png)

![26](../../../images/2/26.png)

Nhập **Tên** `AWS_SECRET_ACCESS_KEY`

Sao chép **Secret Access Key** và dán vào trường secret

Nhấn **Add Secret**

![27](../../../images/2/27.png)

![28](../../../images/2/28.png)

Trong **S3 Bucket** chọn Permissions (Quyền truy cập)

Cuộn xuống **Bucket Policy**, **Nhấn Edit**, Nhấn **Policy Generator**

![29](../../../images/2/29.png)

![30](../../../images/2/30.png)

Chọn **S3 Bucket Policy**

![31](../../../images/2/31.png)

Vào **IAM Users** sao chép **ARN**

Dán vào trường Principal

Chọn All Actions ('*')

Vào **Bucket S3** chọn **Properties**

Sao chép **ARN** và dán vào trường **Amazon Resource Name (ARN)**

![32](../../../images/2/32.png)

![33](../../../images/2/33.png)

![34](../../../images/2/34.png)

Nhấn **Add Statement**

Nhấn **Generate Policy**

![35](../../../images/2/35.png)

Sao chép đoạn **Json** này

![36](../../../images/2/36.png)

Vào tab **Permissions** của S3 bucket, cuộn xuống **Bucket policy**, nhấn **Edit**, và dán toàn bộ policy vào trường **Policy**

Nhấn **Save changes** (Lưu thay đổi)

![37](../../../images/2/37.png)

![38](../../../images/2/38.png)











