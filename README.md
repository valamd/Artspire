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
ARTSPIRE_Project_Dajngo/
│
├── artspire/ # Main Django project configuration
│ ├── init.py
│ ├── settings.py # Project settings
│ ├── urls.py # URL routing
│ └── wsgi.py / asgi.py
│
├── home/ # Main app for art auction logic
│ ├── admin.py
│ ├── models.py # Models for users, artworks, bids
│ ├── views.py # Core view logic
│ └── templates/ # HTML Templates
│ ├── base.html
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ ├── sellerlogin.html
│ ├── buyerlogin.html
│ ├── bid.html
│ └── detail.html
│
├── static/ # CSS, JS, Images
│ └── images/ # Gallery images
│
├── screenshot/ # Screenshots for documentation
│ ├── ss1.png
│ ├── ss2.png
│ ├── ss3.png
│ └── lastss.png
│
└── manage.py # Django management script

**ScreenShot:**

**Home**:

![Screenshot (351)](https://github.com/user-attachments/assets/ea489020-e078-4ab5-8d07-ab896b37ade5)

**Login**:
![Screenshot (352)](https://github.com/user-attachments/assets/fa9ef294-d23a-4305-84ae-b9ecd42e7e3c)

