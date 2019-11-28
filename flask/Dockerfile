#Use python container image
FROM python:3.7.2-stretch

#setup working dir to app
WORKDIR /app

#copy current directory contents into container .app
ADD . /app

#install dependencies
RUN pip install -r requirements.txt

#run command to start uWSGI server
CMD ["uwsgi", "app.ini"]