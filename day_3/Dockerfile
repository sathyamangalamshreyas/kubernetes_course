FROM python:3.10-slim

WORKDIR /app

ADD app.py app.py

RUN pip install flask

EXPOSE 5000

CMD [ "python", "/app/app.py" ]

# This is not recommended as it opens a shell and then executes the app.py command
# CMD python app.py
