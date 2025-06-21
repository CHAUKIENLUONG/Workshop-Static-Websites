+++
title = "Access Control"
date = 2025
weight = 3
chapter = false
pre = "<b>2.3. </b>"
+++

AWS Amplify provides built-in **access control features** that allow you to restrict access to your deployed site. This is especially useful for:

* Internal/staging environments

* Client reviews before public release

* Password-protected demos

1. Go to the **Amplify Console**

2. Open your app and select the “**Access control**” tab. CLick **Manage access**

![13](../../images/1/13.png)

3. Choose a branch (e.g., main, dev, or staging)

4. Set the access settings "**Retricted - password required**". Define **username/password and save**

![14](../../images/1/14.png)

After completing the setup, reload the deployed website — a popup like this will appear.

![15](../../images/1/15.png)