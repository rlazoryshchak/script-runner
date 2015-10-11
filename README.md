# flask-mongo-login

###Install:
  * cd script-runner
  * mkdir env
  * virtualenv env
  * source env/bin/activate
  * pip install -r requirements.txt 

######Set a mongodb host into MONGO_HOST variable in models.py after that create new user:

  * python create_user.py username password role

######This command will create credentials adm/pass

  * python app.py
  
######Navigate in browser http://0.0.0.0:5000/login

