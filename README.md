# Diet Dash 🍽️

**Diet Dash** is a nutrition-focused web application that helps users discover meals aligned with their fitness goals. Instead of enforcing strict pre-made diet plans, it provides a curated collection of goal-oriented meals — giving you the flexibility to create your own diet.

Whether your goal is weight loss, muscle building, weight gaining, or balanced health, Diet Dash makes it easy to explore suitable meal options with complete nutritional details.

---

## 🌟 Key Highlights
- 🎯 **Goal-Oriented Meal Suggestions** – Browse meals for weight loss, muscle building, weight gaining, or balanced health  
- 📊 **Detailed Nutrition Info** – Calories, protein, carbs, and fats for each meal  
- ⚖️ **Health Tools** – Built-in BMI calculator  
- ⚡ **Dynamic Database** – Meals served from a MySQL database via Django backend  

---

## 🛠️ Technology Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Django (Python)  
  - `MainInterface-Backend/` – Core backend with meal logic and APIs  
  - `loginbackend/` – Optional login/authentication backend  
- **Database:** MySQL  

---

## 📁 Folder Structure
```bash
Diet-Dash-main/
│── frontend/                   # User interface files
│── loginbackend/                # Optional login/auth backend
│── MainInterface-Backend/       
│   ├── diet/                    # Core Django app for meals
│   ├── maininterfacebackend/    # Django project settings & URLs
│   ├── venv/                    # Virtual environment
│── manage.py                    # Django management script
│── myenv/                       # Another virtual environment (local only)
```
---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Prathamporwal/Diet-Dash.git
```

### 2️⃣ Activate Virtual Environment

```bash
& D:/dietdash/Diet-Dash-main/MainInterface-Backend/venv/Scripts/Activate.ps1
```

### 3️⃣ Configure Database

Edit settings.py in maininterfacebackend/ to match your MySQL setup.

### 4️⃣ Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the Server

```bash
python manage.py runserver
```

---

## 🙌 Contributions

Want to enhance Diet Dash? Fork the repo, create a branch, and submit a pull request.

This project was collaboratively developed by Pratham Porwal and [@Pratham-punjabi](https://github.com/pratham-punjabi).

---

## 📬 Contact

-**Developer**: *Pratham Porwal*
-📧 **Email**: *prathamporwal2@gmail.com*
-🔗 **LinkedIn**: www.linkedin.com/in/pratham-porwal-2682872bb
