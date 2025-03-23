# Template Practice

A practice project to explore and implement Django templates with proper usage of static files, including CSS, JS, and images. This repository is intended for learning and experimenting with Django's template system.

## 🔍 Project Overview
This project demonstrates how to structure a Django project with:

Correct usage of static files (CSS, JS, images).
Proper template inheritance (base and child templates).
Inline styles and background images using Django's static tag.

## 📂 Project Structure

template_practice/
│
├── templates/
│   ├── base.html
│   ├── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── img/
│       └── sp_photo.jpg
│
├── manage.py
├── README.md



## 🚀 Key Features
Implements Django's static file handling.
Demonstrates the use of background images with static tags.
Uses template inheritance for better structure.

## ⚙️ How to Run Locally
Clone the repository:
git clone https://github.com/farzamasadian/template_practice.git
cd template_practice
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Run the Django development server:
python manage.py runserver
Open in browser:
Navigate to http://127.0.0.1:8000/.

## 🔧 Common Issues
Static files not loading?
Ensure you have {% load static %} at the top of your HTML file.
Try running python manage.py collectstatic if in production.

## 🏗️ Future Improvements
Add more complex template structures.
Experiment with form handling and dynamic content.
Deploy the project to Render or Railway for online access.

## 📫 Contributing
Feel free to fork this repository and submit a pull request with suggestions or improvements!

## 📜 License
This project is for educational purposes — feel free to use or modify it.
