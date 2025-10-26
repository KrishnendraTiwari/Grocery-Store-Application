# 🛒 Grocery Store Management System

A **full-stack web application** built using **Flask (Python)** and **MySQL** to manage grocery store operations including inventory, orders, customers, and reporting — all from a modern, responsive admin panel.

![Application Screenshot](homepage.JPG)

---

## 🏗️ Architecture Overview

This system follows a **3-tier architecture** using modern web technologies:

| Layer | Technology Stack |
|--------|------------------|
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap 5, Chart.js |
| **Backend** | Python (Flask Framework) |
| **Database** | MySQL |

---

## ✨ Key Features Added

### 🎯 Admin Panel Features
- 🔐 Secure Authentication with Flask-Login  
- 📊 Dashboard with statistics & visual charts  
- 📦 Product Management (CRUD operations)  
- 🛒 Order Management with detailed breakdowns  
- 👥 Customer Management System  
- ⚙️ UOM (Unit of Measurement) Management  
- 📱 Fully Responsive Design using Bootstrap 5  

### 🎨 UI/UX Improvements
- Modern gradient-based design  
- Interactive charts via Chart.js  
- Smooth animations & transitions  
- Professional dark color scheme  
- Icon integration using Font Awesome  

### 🔧 Technical Enhancements
- RESTful API endpoints for modular structure  
- MySQL database integration  
- Server-side & form validation with error handling  
- Password hashing & session management  
- Real-time data updates  

### 📱 Responsive Design
- Mobile-friendly dashboard  
- Adaptive layouts for tablets & phones  
- Touch-friendly interface elements  

---

## ⚙️ Installation Guide

### 📋 Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **MySQL 5.7+**
- **pip** (Python package manager)

---

### 🧩 Step-by-Step Setup

#### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd python_projects_grocery_webapp
```

#### 2️⃣ Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

#### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

#### 4️⃣ Configure Database
```bash
pip install mysql-connector-python
mysql -u root -p -e "CREATE DATABASE grocery_store;"
```

#### 5️⃣ Setup Environment Variables
```bash
cp .env.example .env
# Edit .env with your database credentials
```

#### 6️⃣ Run the Application
```bash
python app.py
```

Access the app at 👉 [http://localhost:5000](http://localhost:5000)

---

## 🗂️ Project Structure

```plaintext
grocery_webapp/
├── app.py              # Main Flask app entry point
├── models/             # Database models
├── templates/          # HTML templates
├── static/             # CSS, JS, and image files
├── utils/              # Helper functions
└── config/             # Configurations & environment settings
```

---

## 🧪 Running Tests
```bash
python -m pytest tests/
```

---

## 📋 Enhancement Tasks

### 🎯 Priority 1: Product Module
- Add **Edit Product** functionality (with validation)
- Create **UOM Management System**
  - Backend API for UOM CRUD  
  - Frontend dropdown integration  

### 🎯 Priority 2: Orders Module
- **Validation:**  
  - Customer name (required)  
  - Item details (name, quantity, price)  
- **Real-Time Totals:** Fix grand total updates dynamically  
- **Order Details View:**  
  - “View” button with modal  
  - Itemized breakdown & print-friendly format  

---

## 🤝 Contributing

1. **Fork** the repository  
2. **Create a branch**  
   ```bash
   git checkout -b feature/improvement
   ```
3. **Commit changes**
   ```bash
   git commit -am "Add new feature"
   ```
4. **Push to your branch**
   ```bash
   git push origin feature/improvement
   ```
5. **Create a Pull Request**

---

## 📞 Support

If you encounter issues:
- 🧩 Create a GitHub issue  
- 📘 Check documentation & previous issues  
- 💬 Discuss improvements with contributors  

---

## ❤️ Built With
- [Python Flask](https://flask.palletsprojects.com/)
- [MySQL](https://www.mysql.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)

---

### 📸 Sample Dashboard Data (homepage.JPG)
| Date | Order No. | Customer | Total |
|------|------------|-----------|--------|
| Wed, 11 Nov 2020 | 1 | Dhaval | ₹530.00 |
| Wed, 11 Nov 2020 | 2 | Farzana | ₹410.00 |
| Sun, 15 Nov 2020 | 15 | Sheila | ₹200.00 |
| Sun, 15 Nov 2020 | 16 | — | ₹80.00 |
| **Total** | — | — | **₹5300.00** |

---

### ✅ Summary of Improvements
- Clean, modern **README layout** with emojis & structure  
- Added **professional formatting** & setup guide  
- Clear **priority-based task management**  
- Developer-friendly **contribution steps**  
- **Maintainable** and **production-ready documentation**

---

**Built with 💚 using Flask & MySQL**
