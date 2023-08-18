FROM python:3.11


WORKDIR /app


COPY . .


RUN pip install --no-cache-dir -r requirements.txt


# Run the application.
CMD python3 manage.py runserver 0.0.0.0:8000
