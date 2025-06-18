A simple polls django application 

Welcome to my first Django project—a simple Polls App where users can vote on different polls and view results in real time. 
Features
 ✅ Create and manage polls 
✅ Vote on poll questions 
✅ View poll results dynamically 
✅ Admin panel for managing questions & choices 
✅ Built with Django and uses MySQL as the database 
Installation & Setup 
Follow these steps to get the app running:
Clone the Repository git clone https://github.com/MuwaEric/polls.git 
cd django-polls

Set Up a Virtual Environment 
python -m venv 
env source env/bin/activate (Mac/Linux) 
env\Scripts\activate (Windows)

Install django pip install django

Run Migrations python manage.py migrate

Start the Development Server python manage.py runserver

Now, open http://127.0.0.1:8000/polls/ in your browser to test the app! Usage

Navigate to /admin to add polls and choices.
Visit /polls to view available polls and vote. 
Project Structure 
django-polls/ 
│── polls/  # Main app (models, views, templates) 
│── manage.py # Django management script
Technologies Used
Django (Web framework)
SQL (Database)
HTML/CSS (Templates)

