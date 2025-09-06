# 🍲 RasoiHub

RasoiHub is a **simple Django-based web application** designed to manage recipes, explore dishes, and provide a smooth cooking experience.  
This project demonstrates the use of **Django** for backend development with a clean and structured setup.

---

## 🚀 Features

- 🧑‍🍳 **Recipe Management** – Add, update, delete, and view recipes  
- 🔍 **Search Functionality** – Quickly find recipes by name or ingredients  
- 🖼️ **Image Support** – Upload and display dish images  
- 👤 **User-Friendly Interface** – Clean and simple UI  
- ⚡ **Fast & Lightweight** – Uses Django’s powerful framework  

---

## 🛠️ Tech Stack

- **Backend:** Django 5+
- **Frontend:** HTML, CSS,  Tailwind (if used)
- **Database:** SQLite (default) 
- **Language:** Python 3.12+
- **Tools & Dependencies:**
  - Django
  - Pillow *(if image upload is used)*
  - Django Crispy Forms *(if used)*
  - Other dependencies listed in `requirements.txt`

---

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

