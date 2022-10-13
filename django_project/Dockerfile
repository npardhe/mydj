FROM python

RUN pip install django==4.1.2
COPY . .

RUN python manage.py migrate
EXPOSE 8080
CMD ["python","manage.py","runserver","0.0.0.0:8080"]