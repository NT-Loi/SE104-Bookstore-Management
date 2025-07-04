# SE104 - 📚 Bookstore Management

## INTRODUCTION
This is a full-stack **Bookstore Management Web Application** built with **React.js** for the frontend and **Django** for the backend. The system allows bookstore staff to manage books, customers, sales invoices, inventory, and monthly debt reports efficiently.

> 🏫 This project is the final assignment for the _"Introduction to Software Engineering"_ course (SE104.P22), carried out by the group $16^{th}$ under the supervision of **Mrs. Do Thi Thanh Tuyen**.

---

### MEMBER
|#|Full Name|Student ID|
|:-:|:-:|:-:|
|1|[Trịnh Trân Trân](https://github.com/trantranuit)|23521624|
|2|[Phạm Thị Ngọc Bích](https://github.com/bingbleene)|23520148|
|3|[Ngô Phạm Phương Uyên](https://github.com/uyenuit)|23521762|
|4|[Nguyễn Thị Minh Phú](https://github.com/ntmphu)|23521186|
|5|[Nguyễn Thắng Lợi](https://github.com/NT-Loi)|23520872|

## 🛠 Tech Stack

### Frontend
- [React.js](https://reactjs.org/)
- [Axios](https://www.npmjs.com/package/axios)

### Backend
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [JWT Authentication](https://www.npmjs.com/package/axios)

### Database
- [SQLite](https://sqlite.org/)

---

## ✨ Key Features

- ✅ Book Management (Add, Edit, Delete, View)
- 👥 Customer Database
- 🧾 Invoice & Payment Processing
- 📦 Monthly Inventory Reports
- 💰 Customer Debt Reports
- 🔐 User Authentication & Role-based Authorization
- 📊 Clean UI with Interactive Dashboard

---

## 🚀 Getting Started

### 🔧 Prerequisites
- Node.js (v16+)
- Python (v3.10+)
- npm

```sh
# Clone the repo
git clone https://github.com/NT-Loi/SE104-Bookstore-Management.git
cd SE104-Bookstore-Management
```

### ⚙️ Backend Setup (Django)

```sh
cd backend
# Create virtual environment
python -m venv .venv
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create superuser
python manage.py createsuperuser

# Run server
python manage.py runserver
```
The backend will run at http://127.0.0.1:8000/

### 🌐 Frontend Setup (React.js)

```sh
cd ../frontend

# Install dependencies
npm install

# Run development server
npm start
```
The frontend will run at http://localhost:3000/

### 🔐 Logging In
After starting the frontend (http://localhost:3000/), you can log in using the account you created during the backend setup and be redirected to the main interface of the bookstore system.

![Login](assets/login.jpeg)
![Homepage](assets/homepage.jpeg)

### 🔑 User Roles and Permission Configuration

When a user logs in for the first time, their account is granted the **Admin** role by default, which provides full access to the system.

#### ⚙️ As an Admin, you can:
- Navigate to the **"Phân Quyền"** section to:
  - Add/Update user profiles
  - Enable or disable visibility of specific pages (e.g., **"Trang Chủ"**, **"Tra Cứu Sách"**, **"Thêm Sách"**, **"Nhập Sách"**, etc.) for each role

#### User Profiles Interface
![User Profiles](assets/user-profiles.jpeg)

#### 📋 Permissions Configuration Interface

![Permissions Configuration](assets/role.jpeg)

> ✅ After updating permissions, each user group's accessible menu and pages will automatically adjust according to their assigned role.

## 📜 License
This project is for academic purposes only. Contact the authors for reuse permissions.