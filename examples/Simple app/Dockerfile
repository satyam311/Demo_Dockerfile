FROM ubuntu:latest

#set the working directory in the image 
WORKDIR /app

# Copy the file from the host file system to image file system 

COPY . /app

# Install the neccesary packages into the image file system

RUN apt-get update && apt-get Install -y python3-pip

# Set the environment variables 
ENV NAME world

CMD [ "python3" , "app.py" ]



