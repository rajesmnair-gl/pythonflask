# using python as base image
FROM python:3.9-slim

# setting the workspace
WORKDIR /app

# copy app.py to container
COPY app.py /app

#install flask
RUN pip install flask

# define env variable
ENV FLASK_APP=app.py

# run app.py on startup
CMD ["python","app.py"]

#expose 4000 host : 5000 container port
EXPOSE 5000
