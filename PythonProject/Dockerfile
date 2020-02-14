FROM python:3.6

# Create app directory
WORKDIR /myapp

# Install app dependencies
COPY flaskweb/requirements.txt ./

RUN pip install -r requirements.txt

# Bundle app source
COPY flaskweb /myapp

EXPOSE 5000
CMD [ "python", "app.py" ]