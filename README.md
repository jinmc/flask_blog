# flask_blog

 made from https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

 also will be hosted in http://jimchong.pythonanywhere.com/
 using venv virtual environment with Python 3.6 and venv

 Inside wsgi file
```
import sys
 The "/home/jimchong" below specifies your home
 directory -- the rest should be the directory you uploaded your Flask
 code to underneath the home directory.  So if you just ran
 "git clone git@github.com/myusername/myproject.git"
 ...or uploaded files to the directory "myproject", then you should
 specify "/home/jimchong/myproject"
path = '/home/jimchong/deploy'
if path not in sys.path:
    sys.path.append(path)
from microblog import app as application
```

<p> Installed Applications</p>
pip install flask-wtf (web forms)<br>
pip install flask-migrate (db)<br>
pip install flask-sqlalchemy (db)<br>
pip install flask-login <br>
pip install flask-mail (email) <br>
pip install pyjwt (json web token for secure token)<br>
pip install flask-bootstrap (css)<br>
pip install flask-moment (date and time js library) <br>
</p>

Flask Shell Commands
<ul>
<li>flask db init</li>
<li>flask db migrate -m "create table something"</li>
<li>flask db upgrade</li>

</ul>
