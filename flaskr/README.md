export FLASK_APP=flaskr.py
export FLASK_ENV=development
flask run
 * Running on http://127.0.0.1:5000/
 
 
If you are on Windows, the environment variable syntax depends on command line interpreter. On Command Prompt:

C:\path\to\app>set FLASK_APP=flaskr.py
And on PowerShell:

PS C:\path\to\app> $env:FLASK_APP = "hello.py"
Alternatively you can use python -m flask:

$ export FLASK_APP=hello.py
$ python -m flask run
 * Running on http://127.0.0.1:5000/