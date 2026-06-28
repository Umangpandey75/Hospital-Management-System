<!-- ═══════════ ANIMATED HEADER ═══════════ -->

# 🏥 Hospital Management System

<div align="center">
<!-- ═══════════ TYPING ANIMATION ═══════════ -->

<br/>

<!-- ═══════════ BADGES ═══════════ -->
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
&nbsp;
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
&nbsp;
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

<br/>

![Repo Size](https://img.shields.io/github/repo-size/Umangpandey75/Hospital-Management-System?style=flat-square&color=6AD3F7&label=Repo+Size)
&nbsp;
![Last Commit](https://img.shields.io/github/last-commit/Umangpandey75/Hospital-Management-System?style=flat-square&color=58A6FF&label=Last+Commit)
&nbsp;
![License](https://img.shields.io/github/license/Umangpandey75/Hospital-Management-System?style=flat-square&color=27AE60)
&nbsp;
![Stars](https://img.shields.io/github/stars/Umangpandey75/Hospital-Management-System?style=social)
&nbsp;
![Forks](https://img.shields.io/github/forks/Umangpandey75/Hospital-Management-System?style=social)

</div>

---

## 🌊 What is Hospital Management System?

**Hospital Management System** is a robust and scalable web application built with PHP and MySQL, designed to automate and streamline the day-to-day operations of a hospital. It provides dedicated modules for administrators, doctors, nurses, and patients, ensuring smooth workflows and efficient healthcare management.

Whether you're managing appointments, handling patient records, or overseeing hospital staff — this system has you covered.

> *"Streamline Healthcare. Manage Efficiently. — The digital backbone of modern hospitals."*

### ✨ Core Philosophy
- 🎯 **Efficiency first** — intuitive dashboards tailored for different roles
- ⚡ **Reliability** — robust data management with secure access controls
- 🔌 **Extensibility** — easily customizable for different healthcare environments

---

## 🚀 Features

<div align="center">

| Feature | Description | Status |
|---------|-------------|--------|
| 👨‍💼 **Admin Module** | Manage departments, staff, users, accounts, and reports | ✅ Active |
| 🧑‍⚕️ **Doctor Module** | Manage patient records, appointments, and prescriptions | ✅ Active |
| 🩺 **Nurse Module** | Handle patient accounts and personal profile management | ✅ Active |
| 🤒 **Patient Module** | View appointments, doctor lists, and personal prescriptions | ✅ Active |
| 📊 **Dashboard Interface** | Beautiful and clean UI for monitoring hospital activities | ✅ Active |
| 🔒 **Role-Based Access** | Secure login system tailored for specific user roles | ✅ Active |

</div>

---

## 🛠️ Tech Stack

<div align="center">

### 🧠 Backend & Database
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=for-the-badge&logo=codeigniter&logoColor=white)

### 🌐 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🔧 Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 🗂️ Project Structure

```
📦 Hospital-Management-System/
├── 📁 application/        ← Application logic (Controllers, Models, Views)
├── 📁 system/             ← Core framework files
├── 📁 css/ & js/          ← Frontend styling and scripts
├── 📁 images/ & uploads/  ← Media and uploaded assets
├── 📄 index.php           ← Main entry point
└── 📄 hospital.sql        ← Database schema
```

---

## ⚙️ Architecture Overview

```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "background":         "#0a0e1a",
    "primaryColor":       "#1a1a2e",
    "primaryTextColor":   "#6AD3F7",
    "primaryBorderColor": "#58A6FF",
    "lineColor":          "#58A6FF",
    "secondaryColor":     "#16213e",
    "tertiaryColor":      "#0f3460",
    "fontFamily":         "Fira Code, monospace"
  }
}}%%
flowchart LR
    A["👥 User (Admin/Doctor/Patient)"] --> B["🌐 Web Interface\n(HTML/CSS/JS)"]
    B --> C{"⚙️ Application Logic\n(PHP / application folder)"}
    C --> D["🗄️ Database\n(MySQL / hospital.sql)"]
    D --> C
    C --> E["📊 Action/Response\n(Dashboards/Reports)"]
    E --> B
```

---

## 🚦 Quick Start

### Prerequisites

```bash
# Make sure you have a local server environment installed (like XAMPP, WAMP, or MAMP)
# PHP Version: 7.x or higher recommended
# MySQL Server
```

### 🖥️ Installation Setup

```bash
# 1. Clone the repository into your server's root directory (e.g., htdocs for XAMPP)
git clone https://github.com/Umangpandey75/Hospital-Management-System.git

# 2. Start Apache and MySQL services in your local server control panel.

# 3. Create a new database in phpMyAdmin named `hospital` (or your preferred name).

# 4. Import the provided `hospital.sql` file into your newly created database.

# 5. Open your browser and navigate to the project
http://localhost/Hospital-Management-System
```

---

## 🎮 How to Use

<div align="center">

```
  Step 1             Step 2              Step 3              Step 4
     🌐                 🔐                  📊                  📋
Open Browser  →  Select User Role  →  Login to Dash  →  Manage Hospital
```

</div>

### 👥 User Modules Breakdown

| Role | Key Capabilities |
|------|------------------|
| **Admin** | Full system oversight, manage all users, departments, transactions & reports |
| **Doctor** | Manage patient profiles, update prescriptions, and handle appointments |
| **Nurse** | Assist in managing patient accounts and updates |
| **Patient** | View doctor availability, book appointments, check prescriptions |

---

## 📸 Interface Preview

<div align="center">

📸 <b>Explore More Screenshots</b><br>
<a href="https://drive.google.com/open?id=1MzCn77LxilevsqaCCaRMESF63wTxnLPr">
View Complete Gallery →
</a>

</div>
---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Here's how you can help:

```bash
# 1. Fork the repository on GitHub
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit your changes
git commit -m '✨ Add AmazingFeature'

# 4. Push to the branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request 🎉
```

### 💡 Ideas for Contribution
- [ ] 📱 Implement a fully responsive mobile-first UI
- [ ] 💳 Add payment gateway integration for transactions
- [ ] 📧 Implement email/SMS notifications for appointments
- [ ] 📈 Enhance data visualization with interactive charts
- [ ] 🔐 Upgrade authentication to support OAuth or Two-Factor Auth

---

## 📜 License

Distributed under the **MIT License**. See `license.txt` for more information.

---

## 👨‍💻 Author

<div align="center">

### **Umang Pandey**
*Python Developer · Data Analyst · ML Engineer*

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:umangpandey.co@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/umang-pandey-01b486273)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Umangpandey75)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-6AD3F7?style=for-the-badge&logo=vercel&logoColor=black)](https://umangpandey.vercel.app)

*"Query the data. Build the insight. Ship the WOW. ✨"*

</div>

---

## ⭐ Show Your Support

If the **Hospital Management System** helped you, please give it a ⭐ — it means the world!

<div align="center">

[![Star this repo](https://img.shields.io/badge/⭐_Star_this_repo-FFD700?style=for-the-badge)](https://github.com/Umangpandey75/Hospital-Management-System/stargazers)
&nbsp;
[![Fork this repo](https://img.shields.io/badge/🍴_Fork_it-58A6FF?style=for-the-badge)](https://github.com/Umangpandey75/Hospital-Management-System/fork)
&nbsp;
[![Share on Twitter](https://img.shields.io/badge/Share_on_Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=Check+out+the+Hospital+Management+System+by+%40Umangpandey75!+%F0%9F%8F%A5%F0%9F%92%BB&url=https://github.com/Umangpandey75/Hospital-Management-System)

</div>
---
<!-- ═══════════ FOOTER WAVE ═══════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,40:16213e,70:1a1a2e,100:0d1117&height=120&section=footer" width="100%"/>

<div align="center">

*Made with ❤️ by [Umang Pandey](https://github.com/Umangpandey75) · © 2026 Hospital Management System*

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Umangpandey75.Hospital-Management-System&left_color=1F6FEB&right_color=6AD3F7&left_text=Visitors)
</div>
