# Lab 2:
![image2](image2.png)
---
This lab contains a SQL injection vulnerability in the login function.

To solve the lab, perform a SQL injection attack that logs in to the application as the **administrator** user. 
## lab walkthrough:
![image3](image3.png)
---
![image4](image4.png)
---
- as we can see here the login page, username is **administrator** and we dont know the password, i tried **test** as a password:
![image5](image5.png)
---
- lets try put this on the password: **' OR 1=1 --**
**username:administrator**
**password:' OR 1=1 --**
![image6](image6.png)
---

CONGRATS!!
--- 
and there is another way, put this in the username: **administrator'--**
