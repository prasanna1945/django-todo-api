# django-todo-api
📝 Todo API with Django REST Framework
A simple RESTful API built using Django and Django REST Framework (DRF) to perform CRUD operations (Create, Read, Update, Delete) on a Todo list.

📌 Features
✅ Create a new todo (POST /api/todos/)

📄 View all todos (GET /api/todos/)

🔍 View a specific todo (GET /api/todos/<id>/)

✏️ Update a todo (PUT /api/todos/<id>/)

❌ Delete a todo (DELETE /api/todos/<id>/)

🛠️ Tech Stack
Python

Django

Django REST Framework (DRF)

🚀 Setup Instructions
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/django-todo-api.git
cd django-todo-api
2. Create and activate a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
3. Install dependencies
bash

pip install django djangorestframework

4. Apply migrations
bash

python manage.py makemigrations

python manage.py migrate

5. Run the server
bash

python manage.py runserver
Visit the API in your browser: http://127.0.0.1:8000/api/todos/

📬 API Endpoints
Method	Endpoint	Description
GET	/api/todos/	List all todos
POST	/api/todos/	Create a new todo
GET	/api/todos/<id>/	Get todo by ID
PUT	/api/todos/<id>/	Update todo by ID
DELETE	/api/todos/<id>/	Delete todo by ID

🔧 Example POST Request
json
Copy
Edit
{
  "title": "Learn Django",
  "description": "Build REST APIs using DRF",
  "completed": false
}

✅ Future Improvements
Add user authentication

Add pagination and filtering

Add Swagger or Redoc documentation

Create a frontend with React or HTML

