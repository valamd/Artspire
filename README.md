# Artspire
# 🎨 Artspire - Online Art Auction Website 🎨

Artspire is a Django-based web application for art auctions. Artists can showcase their artworks, and buyers can bid on them in real-time. The platform provides login systems for buyers, sellers, and admin, and includes features like bidding, user authentication, and artwork management.

---

## 🚀 Features

- 👤 Buyer, Seller, and Admin login
- 🖼️ Artwork posting by sellers
- 💰 Bidding system for buyers
- 🔐 Secure authentication
- 📥 Admin dashboard to manage users and artworks
- 📧 Contact page
- 📱 Responsive front-end design using Bootstrap

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Backend:** Django (Python)
- **Database:** SQLite (default Django DB)
- **Other:** Django Templates, Static and Media file handling

---

## 📁 Project Structure
ARTSPIRE_Project_Django/<br>
│
├── 🧭 artspire/ # 🔧 Main Django project configuration<br>
│ ├── 📄 init.py<br>
│ ├── ⚙️ settings.py # Project settings<br>
│ ├── 🌐 urls.py # URL routing<br>
│ └── 🚀 wsgi.py / asgi.py # Deployment entry points<br>
│<br>
├── 🎨 home/ # 🧠 Main app for art auction logic<br>
│ ├── 🛠️ admin.py<br>
│ ├── 🧬 models.py # Models for users, artworks, bids<br>
│ ├── 🧾 views.py # Core view logic<br>
│ └── 🖼️ templates/ # HTML Templates<br>
│ ├── 🧩 base.html<br>
│ ├── 🏠 index.html<br>
│ ├── 🔐 login.html<br>
│ ├── 📝 register.html<br>
│ ├── 🧑‍🎨 sellerlogin.html<br>
│ ├── 🛒 buyerlogin.html<br>
│ ├── 💰 bid.html<br>
│ └── 🔍 detail.html<br>
│<br>
├── 📦 static/ # 🎨 CSS, JS, Images<br>
│ └── 🖼️ images/ # Gallery images<br>
│<br>
│
└── ⚙️ manage.py # Django management script<br>

## 🖼️ Screenshots

- 🏠 **Home Page**
![Screenshot (351)](https://github.com/user-attachments/assets/d28bb84d-5b5f-4fb4-8a21-2abbcdb70808)

- 🧑‍💼 **Login Page**
![Screenshot (352)](https://github.com/user-attachments/assets/d0d87fa2-5067-4b1e-9ad4-603d1b25f32d)

