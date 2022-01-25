# init a base image (Alpine is small Linux distro)
FROM python:3.8-alpine
# define the present working directory
WORKDIR /app
# copy the contents into the working dir
ADD . /app
# run pip to install the dependencies of the flask app
RUN pip install -r requirements.txt
#RUN easy_install requirements.txt
# define the command to start the container
CMD ["python","flaskApp.py"]
