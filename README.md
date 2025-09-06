# 🍲 RasoiHub

RasoiHub is a **simple Django + Tailwind CSS** based web application for managing and exploring recipes.  
It is designed with a **modern UI** using **Tailwind CSS** and a **powerful backend** using **Django**.

---

## 🚀 Features

- 🧑‍🍳 **Recipe Management** – Add, update, delete, and view recipes
- 🎨 **Tailwind-Powered UI** – Fully responsive, modern, and fast
- 🔍 **Search Functionality** – Quickly find recipes by name or ingredients
- 🖼️ **Image Uploads** – Add dish images with ease
- 📱 **Responsive Design** – Works smoothly on mobile & desktop
- ⚡ **Optimized Performance** – Lightweight and fast-loading pages

---

## 🛠️ Tech Stack

### **Frontend**
- **Tailwind CSS** → For modern, responsive, and clean UI
- **DaisyUI / Flowbite** *(if used)* → Prebuilt components for faster development
- **HTML5 / Jinja Templates** → Django templating system

### **Backend**
- **Django 5+** → Core backend framework
- **SQLite** *(default)* or **PostgreSQL** *(optional)*
- **Python 3.12+**

### **Tools & Dependencies**
- **Django** → Web framework
- **Tailwind CSS** → Styling framework
- **Django-Tailwind** → Tailwind integration with Django
- **Pillow** → For image uploads *(optional)*
- **Crispy Forms** *(optional)* → Better form styling

---

## 📦 Installation & Setup

Follow these steps to set up **RasoiHub** locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sanij0579/RasoiHub.git
cd RasoiHub

## 📦 Installation & Setup

Follow these steps to set up **RasoiHub** locally:

### 1️⃣ Clone the Repository

git clone https://github.com/sanij0579/RasoiHub.git
cd RasoiHub


2️⃣ Create a Virtual Environment
python3 -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Apply Database Migrations
python manage.py migrate

🧑‍💻 Usage
	•	Open the website in your browser.
	•	Browse through recipes or add new ones.
	•	Use the search feature to find dishes quickly.
	•	Admins can manage all recipes via Django Admin Panel at
http://127.0.0.1:8000/admin/

📧 Contact

For any queries or suggestions:

Author: Sani Jain
GitHub: @sanij0579

