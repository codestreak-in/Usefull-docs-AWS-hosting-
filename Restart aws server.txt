Steps here: 

copy and paste this in terminal 

1.  sudo systemctl restart gunicorn


2.  sudo systemctl daemon-reload


3.  sudo systemctl restart gunicorn.socket gunicorn.service


4.  sudo nginx -t && sudo systemctl restart nginx