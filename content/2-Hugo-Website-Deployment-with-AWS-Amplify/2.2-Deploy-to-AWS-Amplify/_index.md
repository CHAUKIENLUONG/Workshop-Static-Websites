+++
title = "Deploy to AWS Amplify"
date = 2025
weight = 2
chapter = false
pre = "<b>2.2. </b>"
+++

On the AWS [Console](https://us-west-2.console.aws.amazon.com/console/home?nc2=h_ct&region=us-west-2&src=header-signin#):

1. Go to **AWS Amplify → Deploy an app**

![1](../../images/1/1.png)

![2](../../images/1/2.png)

2. Select **GitHub** as the source provider and authorize access

![3](../../images/1/3.png)

![4](../../images/1/4.png)

![5](../../images/1/5.png)

![6](../../images/1/6.png)


3. Choose your **repository** and the **branch** to deploy (e.g., main). CLick **Next**

![7](../../images/1/7.png)

4. Click **Next**

![8](../../images/1/8.png)

5. Click **Save and deploy**

![9](../../images/1/9.png)

{{%notice%}}
Amplify will attempt to auto-detect the Hugo project and generate a default build pipeline {{%/notice%}}

After a successful deployment, it will look like this.

![11](../../images/1/11.png)

6. Click on the link.

![10](../../images/1/10.png)

Your Hugo website has been successfully deployed.

![12](../../images/1/12.png)