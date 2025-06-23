+++
title = "Create React App and Configure Amplify"
date = 2025
weight = 1
chapter = false
pre = "<b>3.1. </b>"
+++

1. Install **AWS Amplify CLI**
`npm install -g @aws-amplify/cli`
![1](../../images/3/1.png)

2. Create React app
`npx create-react-app amplify-react-app`
![2](../../images/3/2.png)

3. **Open** folder React just created
![3](../../images/3/3.png)

4. **Configure** Amplify
`amplify configure`
![4](../../images/3/4.png)

3. **Choose** your region. **Enter** after that
![5](../../images/3/5.png)

4. **Enter** your User name. **Click Next**
![6](../../images/3/6.png)

5. **Select** Attach policies directly and Check AdministratorAccess. **Click Next**
![7](../../images/3/7.png)

6. **Select** User just created
![8](../../images/3/8.png)

7. **Create access key**
![9](../../images/3/9.png)

8. **Select Other. Click Next**
![10](../../images/3/10.png)

9. **Enter** Description tag value. **Click Create access key**
![11](../../images/3/11.png)

10. **Copy** Access key and Secret access key
![12](../../images/3/12.png)

11. **Paste** it into the command line in VS Code
![13](../../images/3/13.png)

12. **Enter** your Users just created
![14](../../images/3/14.png)

13. Initialize Amplify in the project `amplify init`
![15](../../images/3/15.png)

14. Enter **Y (Yes)**. Choose **Prefer not to answer**
![16](../../images/3/16.png)

15. Enter `amplifyreactapp`
![17](../../images/3/17.png)

16. **Yes** and Select **AWS profile**
![18](../../images/3/18.png)

17. We have a folder **amplify** and an **aws-exports.js** file
![19](../../images/3/19.png)


