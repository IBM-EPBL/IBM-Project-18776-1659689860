FROM python:3.7

WORKDIR /app

COPY . .
RUN pip3 install django
RUN pip3 install -r requirements.txt

CMD [ "python3", "manage.py", "runserver", "0.0.0.0:8080" ]

