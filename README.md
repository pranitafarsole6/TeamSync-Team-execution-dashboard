# 🚀 TeamSync

**TeamSync** is a collaborative task and project management web application built using Django. It helps teams efficiently organize tasks, track progress, and manage projects in one place.

---

## 📌 Features

* User Authentication (Login/Register)
* Task Management (Create, Update, Delete tasks)
* Project Management
* Reports & Progress Tracking
* Team Collaboration
* Clean and simple UI

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (default Django DB)
* **Tools:** VS Code, Git, GitHub

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/teamsync.git
cd teamsync
```

---

### 2️⃣ Create virtual environment

```bash
python -m venv venv
```

---

### 3️⃣ Activate virtual environment

#### Windows:

```bash
venv\Scripts\activate
```

#### Mac/Linux:

```bash
source venv/bin/activate
```

---

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 5️⃣ Apply migrations

```bash
python manage.py migrate
```

---

### 6️⃣ Run the development server

```bash
python manage.py runserver
```

---

### 7️⃣ Open in browser

Go to:

```
http://127.0.0.1:8000/
```

---

## 👤 Admin Access (Optional)

To access admin panel:

```bash
python manage.py createsuperuser
```

Then visit:

```
http://127.0.0.1:8000/admin
```

---

## 📁 Project Structure (Simplified)

```
TeamSync/
│── manage.py
│── requirements.txt
│
├── djangoProject/   # Main settings
├── users/           # User management
├── task_manager/    # Task logic
├── reports/         # Reports module
├── templates/       # HTML files
├── static/          # CSS, JS, images
```

---

## 🎯 Use Case

TeamSync is designed for:

* Students working on group projects
* Teams managing tasks collaboratively
* Hackathons and productivity tools

---

## Future Improvements

* Notifications system
* Calendar integration
* AI-based task suggestions
* Deployment on cloud

---

## Author

**Pranita Farsole**
Developed as part of a learning project / hackathon.

---

## Contributing

Feel free to fork this repository and improve the project. Contributions are always welcome!

---

## 📄 License

This project is open-source and available under the MIT License.

---
