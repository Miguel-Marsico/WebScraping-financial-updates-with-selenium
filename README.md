<h1>
    WebScraping - Financial Updates with Selenium 📈
</h1>

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/e294bd58-bb1c-4f3a-9d16-dde9d1dde450)
![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/dd436653-338a-45a1-aeb2-c33411ea8f69)

 ## 📋 Topics
<div>
 • <a href="#-about">About</a> </br>
 • <a href="#-tools">Tools</a> </br>
 • <a href="#-how-to-execute-the-project">How to execute the project</a> </br>    
 • <a href="#-license">License</a></br>
</div>

## 📗 About

This project is an automation in **Selenium** that performs **WebScraping** of financial data on the internet and sends it by **e-mail**, running in the **background**.

## 🔧 Tools

### 👩‍💻 **Language** ([Pyhton](https://www.python.org))

- [Selenium](https://www.selenium.dev/documentation/)
- [Smtplib](https://docs.python.org/3/library/smtplib.html)
- [Email](https://docs.python.org/3/library/email.html#module-email)

### 🛠️ **Utilities** ([PostgreSQL](https://www.postgresql.org/docs/))

- Compilers: **[Pycharm Community](https://www.jetbrains.com/pt-br/pycharm/)** 

## ▶ How to execute the project

### Create a venv:

1 - Navigate to the directory where you want to create the virtual environment:
```bash
 cd /path/to/your/project
```
2 - Create virtual environment:
```bash
 python3 -m venv name
```
3 - Activate the virtual environment:
```bash
 name\Scripts\activate
```

### Installing libraries:

```bash
 pip install selenium
```

### 💡 SmtpLib and Email are native Python packages

### Library import:
```bash
 from selenium import webdriver
 from selenium.webdriver.chrome.options import Options
 from selenium.webdriver.common.by import By
 imdport smtplib
 from email.mime.text import MIMEText
 from email.mime.multipart import MIMEMultipart
```

### Gmail configuration 📨

If you enter your common password when entering your email details, the **code will not work**. You must actually use another password that will be generated by **Google**.

1 - Go to "Manage your Google account"

<br>

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/85998236-064b-492e-ae5d-eb21def9912d)
<br>

2- Go to the "Security" tab and "Two-Step Verification". It is mandatory that this feature is enabled on your account.

<br>

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/220cae17-7668-4931-bde0-9bcd766d9cde)

<br>

3- Go to "App passwords" and create a new app and copy your generated password
<br>

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/090e110a-08f5-4c8f-a35a-1e0f887f2056)

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/7db99b28-fcf0-488b-b606-4ff141330521)

![image](https://github.com/Miguel-Marsico/Financial-updates-with-selenium/assets/158609724/62cf8111-4391-4a78-a704-16711a571e92)

### 💡 It will **impossible** to view an APP's password again, it only appears once when creating it

<br>

## 📜 License

### This project is under the MIT license. 
<br>
Developed by Miguel Marsico 👋🏻
