Simple Flask Login Example
Create and activate virtualenv: python -m venv venv source venv/bin/activate # or venv\Scripts\activate on Windows

Install: pip install -r requirements.txt

Run: export FLASK_APP=app.py flask run

Open http://127.0.0.1:5000/

This app supports:

/register/ to create users
/login/?next=/dashboard/ to login and redirect to the 'next' path
/dashboard/ protected page 
