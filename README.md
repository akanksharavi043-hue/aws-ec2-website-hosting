# 🚀 Hosting a Static Website on AWS EC2 (Amazon Linux + Apache)

This project demonstrates how I deployed a full static website template on an
AWS EC2 instance using **Amazon Linux** and the **Apache Web Server**.
This project demonstrates how I hosted two different static websites on an AWS EC2 instance:

1️⃣ My own custom static welcome page (written manually in HTML)
2️⃣ A professional template website (2095_level) downloaded and hosted using Apache

This was my first hands-on experience with cloud computing, Linux commands,
Apache setup, and security group configuration.

---

## 🟢 Features
- Hosted a static website on Amazon EC2
- Configured Apache web server on Amazon Linux
- Worked with Linux file system, permissions, and services
- Managed HTML/CSS/JS assets inside `/var/www/html`
- Troubleshot common EC2 and Apache issues
- Used security groups to enable HTTP access

---

## 🟦 Tech Stack
- **AWS EC2 (Amazon Linux 2023)**
- **Apache HTTP Server**
- **Linux (bash commands)**
- HTML, CSS, JavaScript

---
#code for the static welcome page 
---
**##template URL used** : https://www.tooplate.com/download/2095_level
---
## 📁 Project Structure
/var/www/html/
|-- index.html
|-- css/
|-- js/
|-- img/
|-- slick/
|-- fonts/

🧩 Debugging & Problem Solving
🔹 Issue: Public IP didn’t load website

✔ Restarted Apache
✔ Allowed HTTP (port 80) in security group
✔ Ensured instance was running

🔹 Issue: Website worked only with /index.html

✔ Cause: browser cache
✔ Solution: manually open
http://<public-ip>/index.html

📚 What I Learned

-Basics of web hosting on AWS EC2
-Linux directory navigation
-Apache installation & configuration
-Security groups (inbound rules)
-Debugging server issues
-Deploying static websites


🧑‍💻 Author
Akanksha Ravi

Feel free to explore or recreate the setup!
***END***

## 📁 Project Structure

