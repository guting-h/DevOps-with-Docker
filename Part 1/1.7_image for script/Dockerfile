# Start from the ubuntu image
FROM ubuntu:20.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the hello.sh file from this location to /usr/src/app/ creating /usr/src/app/website.sh
COPY website.sh .

# Grants execution permissions during the build.
RUN chmod +x website.sh

RUN apt-get -y update
RUN apt-get -y install curl

# docker run runs ./hello.sh
CMD ./website.sh