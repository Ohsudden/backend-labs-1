FROM python:3.9
WORKDIR /flask-app
COPY requirements.txt /flask-app
RUN pip3 install --upgrade pip -r requirements.txt
COPY . /flask-app
EXPOSE 5000