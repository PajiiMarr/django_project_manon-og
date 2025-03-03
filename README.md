Task Manager

A simple Django-based Task Manager for creating, editing, and deleting tasks with due dates.

Features
- Add, update, and delete tasks.  
- Track task statuses (Upcoming, Due Today, Overdue).  
- Responsive design with Bootstrap.  

Setup
git clone https://github.com/PajiiMarr/django_project_manon-og.git
cd django_project_manon-og
pipenv shell
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Access at [http://127.0.0.1:8000](http://127.0.0.1:8000).

Usage
1. View all tasks on the homepage.  
2. Click Add to create a task.  
3. Click Edit to modify a task.  
4. Click Delete to remove a task.  
