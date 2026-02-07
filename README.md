# MotoElite - Premium Bike Marketplace

MotoElite is a high-end, full-stack web application for buying and selling motorcycles. Built with **Django**, it features a modern **Glassmorphism UI**, a robust **Customer Dashboard**, and a **Dynamic Admin Control Panel**.

## 🚀 Key Features

### 👤 Customer Features
- **Full Authentication:** Secure Signup, Login, and Logout functionality.
- **Personal Dashboard:** Manage your listings, track inquiries you've sent, and view messages received from potential buyers.
- **Dynamic Listings:** Post your bike for sale with details like mileage, year, and images.
- **Smart Communications:** Inquiries are linked directly to specific bikes for clear buyer-seller context.

### 🏠 Marketplace Features
- **Smart Inventory:** Live search and filtering by category (Sport, Cruiser, etc.) and price range.
- **Interactive Details:** High-quality detail pages for every bike listing.
- **Glassmorphism Design:** A premium, modern aesthetic using pure CSS.

### 🛡️ Administrative Features
- **Real-time Metrics:** Overview of live listings, pending reviews, and system status.
- **Data Management:** Centralized view of all active inventory and customer inquiries.
- **Dynamic Updates:** Total counts and recent activities update dynamically from the database.

## 🛠️ Tech Stack
- **Backend:** Python (Django 6.x)
- **Frontend:** HTML5, Modern CSS (Glassmorphism), Vanilla JavaScript
- **Database:** SQLite (Easily portable for local development)
- **API:** Django REST Framework (Integrated serializers)

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/MotoElite.git
   cd MotoElite
   ```

2. **Install Dependencies:**
   ```bash
   pip install django djangorestframework
   ```

3. **Database Setup:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Populate Sample Data (Optional):**
   ```bash
   # If you have the populate_data command configured
   python manage.py populate_data
   ```

5. **Run the Server:**
   ```bash
   python manage.py runserver
   ```
   Access the app at `http://127.0.0.1:8000/`

## 📂 Project Structure
```text
BikeSalePurchase/
├── core/               # Project settings and URL routing
├── marketplace/        # Main application logic (Views, Models, Serializers)
├── static/             # Global CSS, JS, and Images
├── templates/          # HTML Templates (Index, Inventory, Dashboard, etc.)
└── db.sqlite3          # Local database file
```

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---
*Created with ❤️ for motorcycle enthusiasts.*
<img width="1915" height="851" alt="Screenshot 2026-02-07 211301" src="https://github.com/user-attachments/assets/2fd9ff94-9c82-47ec-af3d-2d717fe7868e" />

