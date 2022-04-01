FROM python:3.8
WORKDIR /django/
# EXPOSE 8000
COPY . .
RUN pip install -r requirements.txt
CMD ["python", "manage.py", "runserver", "0.0.0.0:8080"]


