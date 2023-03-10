FROM python:3.8

WORKDIR /usr/src/backend

COPY ./requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD python manage.py migrate