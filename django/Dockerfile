FROM python:3.10
ENV PYTHONUNBUFFERED=1
RUN pip install --upgrade pip
RUN mkdir app
COPY ./requirements.txt ./requirements.txt
RUN pip install -r requirements.txt
COPY . /app/
WORKDIR /app
USER root
# RUN python manage.py collectstatic
