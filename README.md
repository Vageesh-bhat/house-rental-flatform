# 🏠 House Rental Platform

## 🚀 Introduction

Welcome to the **House Rental Platform**!  
A modern, user-friendly web app designed to make renting homes easier for everyone. Landlords can list their properties, and tenants can browse, search, and apply for rental houses—all in one convenient place. Built using PHP, MySQL, and XAMPP, the platform streamlines the rental process with a sleek interface and powerful features.  

🌟 Whether you're a landlord or a tenant, this platform has you covered!

---

## 🛠️ Tech Stack

- **Backend:** PHP + MySQL
- **Frontend:** JavaScript, CSS, HTML
- **Database:** MySQL
- **Local Server:** XAMPP
- **Other:** Hack (minor usage)

---

## 📁 Folder Structure

```
house-rental-flatform/
├── assets/
│   ├── css/
│   ├── images/
│   └── js/
├── config/
│   └── db.php
├── landlord/
│   ├── add_property.php
│   ├── dashboard.php
│   └── ... 
├── tenant/
│   ├── browse.php
│   ├── apply.php
│   └── ...
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── ...
├── index.php
├── login.php
├── register.php
├── README.md
└── ...
```
> *Tip: Adjust folder names/files above to match your actual setup!*

---

## 🤖 How to Run

### Prerequisites

- 🖥️ **XAMPP** ([Download](https://www.apachefriends.org/index.html))
- 🌐 **Web Browser** (Chrome, Firefox, etc.)

### Steps

1. **Clone the Repo**
   ```sh
   git clone https://github.com/Vageesh-bhat/house-rental-flatform.git
   ```

2. **Move Project to XAMPP's `htdocs`**
   - Windows: `C:\xampp\htdocs\house-rental-flatform`
   - Linux/Mac: `/opt/lampp/htdocs/house-rental-flatform`

3. **Start XAMPP**
   - Open XAMPP Control Panel
   - Start **Apache** & **MySQL**

4. **Set Up the Database**
   - Go to [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a new database (e.g., `house_rental_db`)
   - Import the provided SQL file if available

5. **Configure DB Connection**
   - Edit `config/db.php` and update your host, username, password, and database name.

6. **Launch the App**
   - Visit: [http://localhost/project/house_rental/index.php?page=home](http://localhost/project/house_rental/index.php?page=home) in your browser 🎉

---

## ✨ Features

| Landlords 🧑‍💼 | Tenants 🧑‍💻 |
| ------------- | ------------ |
| List properties | Browse houses |
| Manage listings | Search + filter |
| View applications | Apply for rentals |

🔒 Secure login & registration for all users!

---

## 💡 Contributing

We 💖 contributions!  
Open an issue to suggest improvements, or submit a pull request. For major changes, please discuss first.

---

## 📜 License

MIT License

---

> ⚡ **Ready to get started?**  
> Clone the repo, fire up XAMPP, and dive into the world of hassle-free house rentals!