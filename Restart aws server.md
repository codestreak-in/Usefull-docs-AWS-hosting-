Steps here: 

copy and paste this in terminal 

0.  python manage.py migrate
   

2.  sudo systemctl restart gunicorn


3.  sudo systemctl daemon-reload


4.  sudo systemctl restart gunicorn.socket gunicorn.service


5.  sudo nginx -t && sudo systemctl restart nginx
