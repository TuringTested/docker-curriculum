# specify base image
FROM python:3

# set a directory for the app
WORKDIR /usr/src/app

# copy all the files to the container
COPY . .

# install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# define the port number the container should expose (5000 here b/c that's where our flask app runs)
EXPOSE 5000

# command for running the app
CMD ["python", "./app.py"]
