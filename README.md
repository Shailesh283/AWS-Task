# AWS Task 1 - Windows EC2 Setup

## 📌 Objective

To create a Windows EC2 instance on AWS, connect to it using Remote Desktop (RDP), and retrieve system information.

---

## 🚀 Steps Performed

### 1. AWS Login

* Logged into AWS Console using root user credentials.

### 2. EC2 Instance Creation

* Navigated to EC2 Dashboard
* Clicked on **Launch Instance**
* Selected **Microsoft Windows Server 2019/2022 Base**
* Chose instance type: **t2.micro (Free Tier)**
* Created a new key pair (.pem file)
* Allowed **RDP (Port 3389)** in security group
* Launched the instance

---

### 3. Connecting to Windows VM

* Waited for instance status to become **Running**
* Clicked on **Connect → RDP Client**
* Decrypted password using key pair
* Opened Remote Desktop Connection (`mstsc`)
* Entered Public IP
* Logged in using:

  * Username: **Administrator**
  * Password: (Decrypted from AWS)

---

### 4. Executing Command

* Opened Command Prompt (CMD)
* Ran the following command:

```
systeminfo
```

* Retrieved system details like OS version, RAM, CPU, etc.

---

## 📸 Screenshots

* EC2 Instance Running
* Windows VM Desktop
* CMD with systeminfo output

---

## ⚠️ Important Note

* Instance was stopped after completion to avoid charges.

---

## ✅ Conclusion

Successfully created and accessed a Windows EC2 instance and executed system commands using RDP.

---
