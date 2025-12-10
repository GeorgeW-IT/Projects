# Active Directory Home Lab

## 📌 Overview
This project demonstrates how I set up a small Active Directory environment in a virtual lab to learn user management, group policies, and Windows domain networking.

The lab includes:
- 1x Domain Controller (Windows Server)
- 1x Windows 10/11 Client
- DNS + DHCP (optional)
- Organisational Units (OUs), Groups, and Users
- Basic Group Policy Objects (GPOs)

---

## 🖥️ Lab Environment
**Platform:** Microsoft Azure 

**VM OS:** Windows Server 2022 

**VM Specs:** Windows 10/11 Pro  

**Network:** Internal network within VM

---

## ⚙️ Steps Performed

### **1️⃣ Installed Windows Server**
- Configured hostname  
- Set static IP  
- Installed roles:  
  - Active Directory Domain Services  
  - DNS Server  

### **2️⃣ Promoted Server to Domain Controller**
- Created new forest: `yourdomain.local`

### **3️⃣ Created Organisational Units**
- _Users_  
- _Admins_  
- _Computers_  
- _Groups_  

### **4️⃣ Created Test Users & Groups**
- Example:
  - `Alice.User`
  - `Bob.Admin`
  - Security groups for permissions

### **5️⃣ Joined Windows Client to Domain**
- Connected via System → Domain Join  
- Verified login with domain accounts  

### **6️⃣ Applied Basic Group Policies**
Examples:
- Force password policy  
- Disable Control Panel  
- Desktop wallpaper  
- Software restriction policy  

---

## 📸 Screenshots
_Add your screenshots here:_
