# Importing the base image.
# In our example, we want to import the python image (from DockerHub).
# So, we write 'python' for the image name and 'latest' for the version.
FROM python:latest

# We must import the 'server.py' and 'index.html' file, in order to launch our python code.
# 'server.py' is the name of the file on the host.
# '/server/' is the path where to put the file on the image.
ADD multiconn-server.py /server/


# Define '/server/' as base directory (where all commands will be executed).
WORKDIR /server/
