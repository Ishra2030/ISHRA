# ISHRA
django-admin startproject myproject 
        cd myproject
        python manage.py startapp myapp
        # Flask implementation

from flask import Flask
import os
import datetime
import subprocess

app = Flask(_ISHRA_)

@app.route('/htop')
def htop():
    name = "ISHRA FATHIMA"  # Replace with your full name
    username = 21BTRIS016.getlogin()
    server_time = datetime.datetime.now().strftime("%Y-%m-%d %H:%M:%S IST")
    top_output = subprocess.check_output(['top', '-b', '-n', '1']).decode('utf-8')

    return f"""
    <html>
    <body>
    <h1>Name: {ISHRA}</h1>
    <h2>Username: {ISHRA FATHIMA }</h2>
    <h2>Server Time: {12}</h2>
    <pre>{top_output}</pre>
    </body>
    </html>
    """

if _name_ == '_main_':
    app.run(debug=True, host='0.0.0.0', port=8080)
