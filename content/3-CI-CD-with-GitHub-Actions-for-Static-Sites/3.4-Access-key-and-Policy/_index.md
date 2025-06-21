+++
title = "Access key and Policy"
date = 2025
weight = 4
chapter = false
pre = "<b>3.4. </b>"
+++

Select **Security credentials**

![50](../../images/2/50.png)

Scroll down to Access keys, Click Create access key

![20](../../images/2/20.png)

Select **Other** and Click **Next**

![21](../../images/2/21.png)

Enter **Decription tag value**, Click **Create access key**

![22](../../images/2/22.png)

Go to your S3 bucket and copy the bucket name

![24](../../images/2/24.png)

Go to the Settings of your GitHub repository, scroll down to Secrets and variables → Actions, then click New repository secret

![19](../../images/2/19.png)

Enter **Name** `AWS_S3_BUCKET`

Paste the S3 bucket name into the secret field

Click **Add Secret**

![25](../../images/2/25.png)

Enter **Name** `AWS_ACCESS_KEY_ID`

Copy the **Access Key** and paste it into the secret field

Click **Add Secret**

![23](../../images/2/23.png)

![26](../../images/2/26.png)

Enter **Name** `AWS_SECRET_ACCESS_KEY`

Copy the **Secret Access Key** and paste it into the secret field

Click **Add Secret**

![27](../../images/2/27.png)

![28](../../images/2/28.png)

In **S3 Bucket** Select Permissions

Scroll down **Bucket Policy**, **Click Edit**, Click **Policy Generator**

![29](../../images/2/29.png)

![30](../../images/2/30.png)

Select **S3 Bucket Policy**

![31](../../images/2/31.png)

Go to **IAM Users** copy **ARN**

Paste it into Principal

Check All Actions ('*')

Go to **Bucket S3** Select **Properties**

Copy **ARN** and Paste it into **Amazon Resource Name (ARN)**

![32](../../images/2/32.png)

![33](../../images/2/33.png)

![34](../../images/2/34.png)

Click **Add Statement**

Click **Generate Policy**

![35](../../images/2/35.png)

Copy this **Json**

![36](../../images/2/36.png)

Go to the **Permissions** tab of your S3 bucket, scroll down to **Bucket policy**, click **Edit**, and paste the entire policy into the **Policy** field

Click **Save changes**

![37](../../images/2/37.png)

![38](../../images/2/38.png)











