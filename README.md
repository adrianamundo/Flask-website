

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/flask-dashboard-atlantis-dark.git
$ cd Flask-website
$
$ # Virtualenv modules installation Windows
$ venv\Scripts\activate
$
$
$ # Install modules in Windows
$ pip3 install -r requirements.txt or python3 -m pip install -r requirements.txt

$
$ # Set the FLASK_APP environment variable
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ (Windows) set FLASK_ENV=development
$ (Powershell) $env:FLASK_ENV = "development"
$
$ # Start the application (development mode)
$ flask run --port=5000
$
$ # Access the dashboard in browser: http://127.0.0.1:5000/
```
