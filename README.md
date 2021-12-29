# scheduling_system
scheduling system project
Django application using Django graphene that can be connected to PostgreSQL the application is for scheduling system that allows the user to create a reservable timing that others can book using it. 

# Step to setup Project
 1. git clone https://github.com/dipakgupta12/scheduling_system.git
 2. Install python and create a virtual environment 
      $ command: virtualenv -p python 3.6 "your environment name"
 3. Activate you environment
      $ command: source "your environment"/bin/activate/
 4. Change your current directory to project directory
 5. Install all requirements of this project 
      $ command: pip install -r requirements.txt
 6. Migrate models with your db
      $ commands: python manage.py makemigrations 
                  python manage.py migrate  
 7. Run your server
      $ command: Python manage.py runserver
 8. For localhost the url is : http://127.0.0.1:8000/dashboard/

